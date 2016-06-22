#### Test 721454317367600_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
,06-22 07:43:57.724  5387  5387 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
--------- beginning of system
06-22 07:43:57.934  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
06-22 07:43:57.934  1017  1030 D ActivityManager: com.samsung.android.app.watchmanagerstub, Starting
06-22 07:43:57.934  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:57.934  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:57.934  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:57.934  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:57.954  1017  1030 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5530 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
06-22 07:43:57.954  1017  1030 I ActivityManager: Killing 4936:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
06-22 07:43:57.954  5530  5530 E Zygote  : MountEmulatedStorage()
06-22 07:43:57.954  5530  5530 I libpersona: KNOX_SDCARD checking this for 10100
06-22 07:43:57.954  5530  5530 E Zygote  : v2
06-22 07:43:57.954  5530  5530 I libpersona: KNOX_SDCARD not a persona
06-22 07:43:57.954  5530  5530 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
06-22 07:43:57.954  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
06-22 07:43:57.954  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
06-22 07:43:57.954  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:57.954  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:43:57.954  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
06-22 07:43:57.964  5530  5530 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
06-22 07:43:57.964  1904  1904 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-22 07:43:57.964  1017  1795 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
06-22 07:43:57.964  5387  5387 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
06-22 07:43:57.964  1017  1795 D ActivityManager: com.google.android.gms, Starting
06-22 07:43:57.964  1017  1795 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
06-22 07:43:57.964  5530  5530 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-22 07:43:57.984  5530  5530 D TimaKeyStoreProvider: TimaSignature is unavailable
06-22 07:43:57.984  5530  5530 D ActivityThread: Added TimaKeyStore provider
06-22 07:43:58.024  5387  5529 W AccountFeatureHelper: Write apps_features disabled false
06-22 07:43:58.034  5530  5530 D PackageIntentReceiver: ACTION_PACKAGE_ADDED
06-22 07:43:58.034  5530  5530 D PackageIntentReceiver: Not GearManger package! 
06-22 07:43:58.034  1017  1291 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
06-22 07:43:58.034  1017  1291 D ActivityManager: com.samsung.helphub, Starting
06-22 07:43:58.044  1017  1291 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:58.044  1017  1291 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:58.044  1017  1291 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:58.044  1017  1291 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:58.054  5552  5552 E Zygote  : MountEmulatedStorage()
06-22 07:43:58.054  5552  5552 E Zygote  : v2
06-22 07:43:58.054  5552  5552 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
06-22 07:43:58.054  5552  5552 I libpersona: KNOX_SDCARD checking this for 1000
06-22 07:43:58.054  5552  5552 I libpersona: KNOX_SDCARD not a persona
06-22 07:43:58.054  1017  1291 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=5552 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
06-22 07:43:58.064  5552  5552 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
06-22 07:43:58.064  5552  5552 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-22 07:43:58.074  5552  5552 D TimaKeyStoreProvider: TimaSignature is unavailable
06-22 07:43:58.084  5552  5552 D ActivityThread: Added TimaKeyStore provider
06-22 07:43:58.124  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
06-22 07:43:58.124  1017  1030 D ActivityManager: com.samsung.android.app.mirrorlink, Starting
06-22 07:43:58.124  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:58.124  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:58.124  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:58.124  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:58.134  5568  5568 E Zygote  : MountEmulatedStorage()
06-22 07:43:58.134  5568  5568 E Zygote  : v2
06-22 07:43:58.134  5522  5522 D AndroidRuntime: 
06-22 07:43:58.134  5522  5522 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-22 07:43:58.134  1017  1030 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5568 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
06-22 07:43:58.134  5568  5568 I libpersona: KNOX_SDCARD checking this for 1000
06-22 07:43:58.134  5568  5568 I libpersona: KNOX_SDCARD not a persona
06-22 07:43:58.134  1017  1030 I ActivityManager: Killing 3966:com.google.android.talk/u0a104 (adj 15): empty #31
06-22 07:43:58.134  5568  5568 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
06-22 07:43:58.144  5522  5522 D AndroidRuntime: CheckJNI is OFF
06-22 07:43:58.144  5522  5522 D AndroidRuntime: readGMSProperty: start
06-22 07:43:58.144  5522  5522 D AndroidRuntime: readGMSProperty: already setted!!
06-22 07:43:58.144  5522  5522 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-22 07:43:58.144  5522  5522 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-22 07:43:58.144  5522  5522 D AndroidRuntime: readGMSProperty: end
06-22 07:43:58.144  5522  5522 D AndroidRuntime: addProductProperty: start
06-22 07:43:58.144  5568  5568 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
06-22 07:43:58.144  5568  5568 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-22 07:43:58.164  5568  5568 D TimaKeyStoreProvider: TimaSignature is unavailable
06-22 07:43:58.164  5568  5568 D ActivityThread: Added TimaKeyStore provider
06-22 07:43:58.164   314   314 I art     : Explicit concurrent mark sweep GC freed 8725(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 32.022ms
06-22 07:43:58.184   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 603us total 16.950ms
06-22 07:43:58.204   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 604us total 16.606ms
06-22 07:43:58.204  1017  1030 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
06-22 07:43:58.204  3720  5041 I Icing   : Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
06-22 07:43:58.204  1017  1030 I ActivityManager: Killing 5069:com.sec.android.widgetapp.digitalclock/u0a88 (adj 15): empty #31
06-22 07:43:58.204  5568  5583 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_ADDED
06-22 07:43:58.204  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:58.214  5568  5583 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
06-22 07:43:58.214  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:43:58.214  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
06-22 07:43:58.214  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
06-22 07:43:58.214  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
06-22 07:43:58.214  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:58.214  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:43:58.214  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
06-22 07:43:58.224  5568  5568 D AcmsService: Enter Oncreate
06-22 07:43:58.224  5568  5568 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
06-22 07:43:58.224  5568  5568 D AcmsService: creating AcmsCore
06-22 07:43:58.224  5568  5568 D AcmsCore: AcmsCore.getAcmsCore() - Enter
06-22 07:43:58.224  5568  5568 D AcmsCore: AcmsCore
06-22 07:43:58.224  5568  5568 D AcmsCore: init
06-22 07:43:58.224  5568  5568 D AcmsCore: Looper handler is not null
06-22 07:43:58.224  5568  5568 D AcmsCore: Post to AcmsCoreHandler
06-22 07:43:58.224  5568  5568 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
06-22 07:43:58.224  5568  5568 D AcmsServiceMonitor: Incrementing - Counter value: 1
06-22 07:43:58.224  5568  5568 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
06-22 07:43:58.224  5568  5584 D AcmsCertificateMngr: AcmsCertificateMngr
06-22 07:43:58.224  5568  5568 D AcmsService: onStartCommand
06-22 07:43:58.224  5568  5568 D AcmsService: Action: android.intent.action.PACKAGE_ADDED
06-22 07:43:58.224  5568  5568 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
06-22 07:43:58.224  5568  5568 D AcmsServiceMonitor: Incrementing - Counter value: 2
06-22 07:43:58.224  5568  5568 D AcmsService: Incremented Counter Value : onStartCommand
06-22 07:43:58.234  1017  2903 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
06-22 07:43:58.234  1017  2903 D ActivityManager: com.samsung.android.app.mirrorlink, Starting
06-22 07:43:58.234  5568  5568 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
06-22 07:43:58.254  5568  5584 D AcmsRevocationMngr: AcmsRevocationMngr
06-22 07:43:58.274  5568  5568 D AcmsService: Inside handle Intent
06-22 07:43:58.274  5568  5568 D AcmsService: App added - package name: com.test.thalitest
06-22 07:43:58.274  5568  5568 D AcmsCore: Post to AcmsCoreHandler
06-22 07:43:58.274  5568  5568 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
06-22 07:43:58.274  5568  5568 D AcmsServiceMonitor: Incrementing - Counter value: 3
06-22 07:43:58.274  5568  5568 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>2
06-22 07:43:58.274  5568  5568 D AcmsService: Decremented Counter Value : handleStartIntent
06-22 07:43:58.274  5568  5568 D AcmsServiceMonitor: Decrementing - Counter value: 2
06-22 07:43:58.274  5387  5387 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
06-22 07:43:58.284  3720  5041 I Icing   : Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
06-22 07:43:58.324  3720  5041 I Icing   : Indexing 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD from com.google.android.googlequicksearchbox
06-22 07:43:58.384  5522  5522 E AffinityControl: AffinityControl: registerfunction enter
06-22 07:43:58.384  3720  5041 I Icing   : Indexing done 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD
06-22 07:43:58.404  1017  2903 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
06-22 07:43:58.404  1017  2903 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:43:58.404  1017  2903 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:43:58.404  1017  2903 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
06-22 07:43:58.404  5522  5522 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-22 07:43:58.424  1017  1472 E PersonaManagerService: inState():  stateMachine is null !!
06-22 07:43:58.424  1017  1472 I PersonaManagerService: PersonaId don't exist
06-22 07:43:58.424  1017  1472 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
06-22 07:43:58.424  1017  1472 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
06-22 07:43:58.434  1017  1472 W ActivityManager: mDVFSHelper.acquire()
06-22 07:43:58.434  1017  1472 D FocusedStackFrame: Set to : 0
06-22 07:43:58.444  1017  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
06-22 07:43:58.444  1017  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
06-22 07:43:58.444  1017  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:58.444  1017  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:58.444  1017  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:58.444  1017  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:58.464  1017  1472 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5595 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
06-22 07:43:58.464  1017  1472 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
06-22 07:43:58.464  1017  1472 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
06-22 07:43:58.464  1017  1472 D InputDispatcher: Focused application set to: xxxx
06-22 07:43:58.464  1017  1472 D InputDispatcher: Focus left window: 1474
06-22 07:43:58.464  5522  5522 D AndroidRuntime: Shutting down VM
06-22 07:43:58.464  5595  5595 E Zygote  : MountEmulatedStorage()
06-22 07:43:58.464  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
06-22 07:43:58.464  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
06-22 07:43:58.464   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
06-22 07:43:58.464  5595  5595 E Zygote  : v2
06-22 07:43:58.464  5595  5595 I libpersona: KNOX_SDCARD checking this for 10155
06-22 07:43:58.464  5595  5595 I libpersona: KNOX_SDCARD not a persona
06-22 07:43:58.464  5595  5595 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
06-22 07:43:58.474  5595  5595 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
06-22 07:43:58.474  5595  5595 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
06-22 07:43:58.484  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
06-22 07:43:58.484  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
06-22 07:43:58.484  5595  5595 D TimaKeyStoreProvider: TimaSignature is unavailable
06-22 07:43:58.494  5595  5595 D ActivityThread: Added TimaKeyStore provider
06-22 07:43:58.494  1017  1291 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
06-22 07:43:58.494  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-22 07:43:58.514  1017  1291 D PersonaManager: isKioskContainerExistOnDevice
06-22 07:43:58.524  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
06-22 07:43:58.554   257  5061 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
06-22 07:43:58.554   257   816 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
06-22 07:43:58.564  1474  1474 V ActivityThread: updateVisibility : ActivityRecord{3ad596ef token=android.os.BinderProxy@28fa2d44 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
06-22 07:43:58.564  1474  1474 D Launcher: onTrimMemory. Level: 20
06-22 07:43:58.614  5595  5595 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
06-22 07:43:58.634  5595  5595 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4469-4471)
06-22 07:43:58.634  5595  5595 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-22 07:43:58.654  5595  5595 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a8fc67d}
06-22 07:43:58.654  5595  5595 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-22 07:43:58.654  5595  5595 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
06-22 07:43:58.674  5522  5522 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,06-22 07:43:58.684  5595  5595 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-22 07:43:58.684  5595  5595 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-22 07:43:58.694  5595  5595 E SysUtils: ApplicationContext is null in ApplicationStatus
06-22 07:43:58.704  5595  5612 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
06-22 07:43:58.704  5595  5595 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
06-22 07:43:58.704  5595  5595 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
06-22 07:43:58.704  5595  5595 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
06-22 07:43:58.714  5595  5595 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
06-22 07:43:58.714  5595  5595 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
06-22 07:43:58.714  5595  5595 I Adreno-EGL: Build Date: 04/06/15 Mon
06-22 07:43:58.714  5595  5595 I Adreno-EGL: Local Branch: 
06-22 07:43:58.714  5595  5595 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
06-22 07:43:58.714  5595  5595 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
06-22 07:43:58.714  5595  5595 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
06-22 07:43:58.784  5595  5623 D BluetoothAdapter: 397920876: getState() :  mService = null. Returning STATE_OFF
06-22 07:43:58.834  5595  5621 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
06-22 07:43:58.874  5595  5595 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-22 07:43:58.894  5595  5595 W AwContents: onDetachedFromWindow called when already detached. Ignoring
06-22 07:43:58.904  5595  5595 D PhoneWindow: *FMB* installDecor mIsFloating : false
06-22 07:43:58.904  5595  5595 D PhoneWindow: *FMB* installDecor flags : -2139027200
06-22 07:43:58.904  5595  5595 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
06-22 07:43:58.904   287   287 E SMD     : DCD OFF
06-22 07:43:58.914  5595  5595 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-22 07:43:58.914  5595  5595 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-22 07:43:58.954  5595  5634 D OpenGLRenderer: Render dirty regions requested: true
06-22 07:43:58.964  1017  1291 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
06-22 07:43:58.964  1017  1291 D KnoxTimeoutHandler: postActiveUserChange for user 0
06-22 07:43:58.964  1017  1291 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
06-22 07:43:58.964  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
06-22 07:43:58.964  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
06-22 07:43:58.974  5595  5595 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
06-22 07:43:58.974  5595  5595 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
06-22 07:43:58.984   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
06-22 07:43:59.004  1017  1029 D InputDispatcher: Focus entered window: 5595
06-22 07:43:59.004  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
06-22 07:43:59.004  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
06-22 07:43:59.004  5595  5595 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
06-22 07:43:59.004  5595  5634 I OpenGLRenderer: Initialized EGL, version 1.4
06-22 07:43:59.014  5595  5634 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
06-22 07:43:59.014  5595  5634 D OpenGLRenderer: Enabling debug mode 0
06-22 07:43:59.044  5595  5595 V ActivityThread: updateVisibility : ActivityRecord{acaa8a5 token=android.os.BinderProxy@17be960f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
06-22 07:43:59.064  1017  1478 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
06-22 07:43:59.064  1017  5637 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
06-22 07:43:59.064  1179  1179 I StatusBar: Icon Only
06-22 07:43:59.064  1179  1179 D PanelView: There is/are notification(s) 
06-22 07:43:59.074  1878  1878 I SamsungIME: getCurrentCandidateView
06-22 07:43:59.084  1017  1047 I ActivityManager: Displayed Component not be shown by security: +563ms (total +633ms)
06-22 07:43:59.084  1017  1047 W ActivityManager: mDVFSHelper.release()
06-22 07:43:59.084  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{32430d1c u0 com.test.thalitest/.MainActivity t23} time:94920
06-22 07:43:59.084  5595  5595 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
06-22 07:43:59.084  5595  5595 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@17be960f time:94927
06-22 07:43:59.094   257   453 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
06-22 07:43:59.094   257  5061 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
06-22 07:43:59.134  5595  5595 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5595
06-22 07:43:59.174  1878  1878 D SamsungIME: Dismiss ExpandCandiate
06-22 07:43:59.254  5595  5595 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
06-22 07:43:59.304  1878  1878 I SamsungIME: getDebugLevel  : 0x4f4c
06-22 07:43:59.334  1878  1878 I SamsungIME: getDebugLevel  : 0x4f4c
06-22 07:43:59.354  1878  1878 I SamsungIME: KeybaordView init() : load resources
06-22 07:43:59.364  5595  5638 D jxcore_app_log: JniHelper::setJavaVM(0xb83cc328), pthread_self() = -1198329200
06-22 07:43:59.374  1878  1878 I SamsungIME: getCurrentKeyboard
06-22 07:43:59.374  1878  1878 I SamsungIME: getTextKeyboard
,06-22 07:43:59.384  5595  5638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-22 07:43:59.384  5595  5638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-22 07:43:59.384  5595  5638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-22 07:43:59.384  5595  5638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-22 07:43:59.384  5595  5638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,06-22 07:43:59.384  5595  5638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31f00515 added. We now have 1 listener(s)
,06-22 07:43:59.384  5595  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,06-22 07:43:59.384  5595  5638 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,06-22 07:43:59.394  5595  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-22 07:43:59.394  5595  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-22 07:43:59.394  5595  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-22 07:43:59.394  5595  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-22 07:43:59.394  5595  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-22 07:43:59.394  5595  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
06-22 07:43:59.394  5595  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-22 07:43:59.394  5595  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-22 07:43:59.394  5595  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-22 07:43:59.394  5595  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-22 07:43:59.394  5595  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-22 07:43:59.394  5595  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-22 07:43:59.394  5595  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-22 07:43:59.394  5595  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b42bb8 added. We now have 1 listener(s)
,06-22 07:43:59.394  5595  5638 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-22 07:43:59.394  5595  5638 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-22 07:43:59.394  5595  5638 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,06-22 07:43:59.404  5595  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-22 07:43:59.404  5595  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,06-22 07:43:59.404  5595  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-22 07:43:59.404  1878  1878 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
06-22 07:43:59.404  5595  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,06-22 07:43:59.404  5595  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-22 07:43:59.404  5595  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,06-22 07:43:59.404  5595  5638 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:43:59.404  5595  5638 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-22 07:43:59.404  5595  5638 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-22 07:43:59.404  5595  5638 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-22 07:43:59.404  5595  5638 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-22 07:43:59.404  5595  5638 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-22 07:43:59.404  5595  5638 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-22 07:43:59.404  5595  5638 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-22 07:43:59.404  5595  5638 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-22 07:43:59.404  5595  5638 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-22 07:43:59.404  5595  5638 D io.jxcore.node.ConnectivityMonitor: start: OK
,06-22 07:43:59.404  5595  5638 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-22 07:43:59.444  5595  5595 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-22 07:43:59.894  1878  5643 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,06-22 07:43:59.984  1017  1096 V AlarmManager: waitForAlarm result :8
,06-22 07:43:59.994  1017  2648 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-22 07:43:59.994  5595  5645 W jxcore-log: Initializing JXcore engine
06-22 07:43:59.994  5595  5645 W jxcore-log: JXcore engine is ready
,06-22 07:44:00.054  1875  1875 E audit   : type=1400 msg=audit(1466574240.054:203): avc:  denied  { ioctl } for  pid=5645 comm="Thread-968" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,06-22 07:44:00.054  1875  1875 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
06-22 07:44:00.054  1875  1875 E audit   : type=1300 msg=audit(1466574240.054:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e2008f8 items=0 ppid=314 ppcomm=main pid=5645 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-968" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
06-22 07:44:00.054  1875  1875 E audit   : type=1320 msg=audit(1466574240.054:203): 
,06-22 07:44:00.054  1017  1096 V AlarmManager: waitForAlarm result :8
,06-22 07:44:00.064  5595  5645 W jxcore-log: Starting JXcore engine
,06-22 07:44:00.174  5595  5645 W jxcore-log: Platform android
06-22 07:44:00.174  5595  5645 W jxcore-log: 
06-22 07:44:00.174  5595  5645 W jxcore-log: Process ARCH arm
06-22 07:44:00.174  5595  5645 W jxcore-log: 
,06-22 07:44:00.254  1017  2635 D SSRM:n  : SIOP:: AP = 330,
,06-22 07:44:00.304  1017  1478 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-22 07:44:00.304  1017  1478 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,06-22 07:44:00.304  1017  1478 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
06-22 07:44:00.304  1017  1478 D BatteryService: stay LED for fully charged
,06-22 07:44:00.304  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-22 07:44:00.304  1017  1017 I MotionRecognitionService: Plugged
06-22 07:44:00.304  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,06-22 07:44:00.314  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-22 07:44:00.314  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
06-22 07:44:00.324  1407  1407 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
06-22 07:44:00.324  1407  1407 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-22 07:44:00.344  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-22 07:44:00.344  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-22 07:44:00.344  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-22 07:44:00.384  5595  5645 I jxcore-log: JXcore Cordova bridge is ready!
06-22 07:44:00.384  5595  5645 I jxcore-log: 
,06-22 07:44:00.384  5595  5645 W jxcore-log: JXcore engine is started
,06-22 07:44:00.384  5595  5638 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION,
,06-22 07:44:00.384  5595  5595 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,06-22 07:44:00.394  5595  5645 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
06-22 07:44:00.394  5595  5645 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,06-22 07:44:00.404  5595  5595 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,06-22 07:44:00.404  5595  5595 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,06-22 07:44:00.404  1017  1078 D FocusedStackFrame: Set to : 0
06-22 07:44:00.404  1017  1078 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
06-22 07:44:00.404  1017  1078 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
06-22 07:44:00.404  1017  1078 D InputDispatcher: Focused application set to: xxxx
06-22 07:44:00.404  1017  1078 D InputDispatcher: Focus left window: 5595
06-22 07:44:00.414  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
06-22 07:44:00.414  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
06-22 07:44:00.414  1017  1078 I ActivityManager: Killing 5100:com.sec.android.app.camera/u0a139 (adj 15): empty #31
06-22 07:44:00.424  5595  5595 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
06-22 07:44:00.424  5595  5595 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,06-22 07:44:00.424  5595  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
06-22 07:44:00.424  5595  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-22 07:44:00.424  5595  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-22 07:44:00.424  5595  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
06-22 07:44:00.424  5595  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31f00515 removed from the list
06-22 07:44:00.424  5595  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-22 07:44:00.424  5595  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b42bb8 removed from the list
06-22 07:44:00.424  5595  5595 D io.jxcore.node.ConnectivityMonitor: stop
06-22 07:44:00.424  5595  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,06-22 07:44:00.424  5595  5595 I io.jxcore.node.LifeCycleMonitor: stop: OK
,06-22 07:44:00.454   257   451 I SurfaceFlinger: id=13 Removed NainActivit (6/8),
06-22 07:44:00.454   257   451 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,06-22 07:44:00.464  1017  1478 W ActivityManager: mDVFSHelper.acquire()
,06-22 07:44:00.474  1017  1478 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,06-22 07:44:00.494  1474  1474 D Launcher: onRestart, Launcher: 978799993
,06-22 07:44:00.494  1474  1474 D Launcher: onStart, Launcher: 978799993
06-22 07:44:00.494  1474  1474 D Launcher.HomeView: onStart
06-22 07:44:00.494  1474  1474 D Launcher: onResume, Launcher: 978799993
06-22 07:44:00.494  1017  1029 D SettingsProvider: name = kids_home_mode
06-22 07:44:00.494  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-22 07:44:00.494  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-22 07:44:00.494  1017  1029 D SettingsProvider: selectionArgs: false
06-22 07:44:00.494  1017  1029 D SettingsProvider: selectionArgs: 10007
06-22 07:44:00.494  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-22 07:44:00.494  1017  1029 D SettingsProvider: ret = -1
06-22 07:44:00.494  1474  1474 D Launcher.HomeView: onResume
,06-22 07:44:00.504  1474  1474 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,06-22 07:44:00.504  1474  1474 D MenuAppsGridFragment: onResume
06-22 07:44:00.504  1474  1474 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
06-22 07:44:00.504  1474  1474 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
06-22 07:44:00.504  1474  1474 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,06-22 07:44:00.514  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,06-22 07:44:00.514  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,06-22 07:44:00.514  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,06-22 07:44:00.514  1017  1472 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=6, mSplitNum[2]=8, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=10
,06-22 07:44:00.514  1017  1472 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,06-22 07:44:00.514  1017  1472 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:00.514  1017  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:44:00.514  1017  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,06-22 07:44:00.524  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,06-22 07:44:00.524  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:44:00.524  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,06-22 07:44:00.524  4420  4420 D GalleryCacheReady: Receive : home resume
,06-22 07:44:00.524  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:00.524  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,06-22 07:44:00.524  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
06-22 07:44:00.524  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
06-22 07:44:00.524  1017  1042 D ActivityManager: com.sec.android.widgetapp.digitalclock, Starting
,06-22 07:44:00.524  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:00.524  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:00.524  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:00.524  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:00.544  5654  5654 E Zygote  : MountEmulatedStorage()
06-22 07:44:00.544  5654  5654 I libpersona: KNOX_SDCARD checking this for 10088
06-22 07:44:00.544  5654  5654 E Zygote  : v2
06-22 07:44:00.544  5654  5654 I libpersona: KNOX_SDCARD not a persona
,06-22 07:44:00.544  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:00.544  1017  1042 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=5654 uid=10088 gids={50088, 9997} abi=armeabi-v7a
06-22 07:44:00.544  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:44:00.544  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,06-22 07:44:00.554  5022  5022 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME,
06-22 07:44:00.554  5654  5654 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
06-22 07:44:00.554  5654  5654 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
06-22 07:44:00.554  1017  2903 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:00.554  1017  2903 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
06-22 07:44:00.554  1017  2903 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms,
06-22 07:44:00.554  5654  5654 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
06-22 07:44:00.554  5081  5081 D Mms/UIEventReceiver: ui event
,06-22 07:44:00.564  1017  2903 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:00.564  1017  2903 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:44:00.564  1017  2903 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,06-22 07:44:00.574  1017  1478 D ActivityManager: handle home activity for 0
06-22 07:44:00.574  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
06-22 07:44:00.574  1017  1478 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
06-22 07:44:00.574  1017  1478 D KnoxTimeoutHandler: post home show event for user 0
06-22 07:44:00.574  1017  1017 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
06-22 07:44:00.574  1017  1478 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
06-22 07:44:00.574  1017  1478 D KnoxTimeoutHandler: postActiveUserChange for user 0
06-22 07:44:00.574  1017  1017 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
06-22 07:44:00.574  1017  1478 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
06-22 07:44:00.574  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
06-22 07:44:00.574  1474  1474 D Launcher.HomeView: onPause
,06-22 07:44:00.574  1474  1474 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,06-22 07:44:00.584  1017  1246 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:00.584  1017  1246 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:44:00.584  1017  1246 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1474, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
06-22 07:44:00.584  1017  1246 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,06-22 07:44:00.584  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:00.584  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:44:00.584  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,06-22 07:44:00.584  2462  2462 D Recents_RecreateReceiver: onReceive by home
,06-22 07:44:00.594  5654  5654 D TimaKeyStoreProvider: TimaSignature is unavailable
06-22 07:44:00.594  5654  5654 D ActivityThread: Added TimaKeyStore provider
,06-22 07:44:00.594   257   257 I SurfaceFlinger: id=14 createSurf (720x1280),1 flag=4, Mauncher
,06-22 07:44:00.604  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-22 07:44:00.604  1017  1478 D InputDispatcher: Focus entered window: 1474
06-22 07:44:00.604  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-22 07:44:00.604  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
06-22 07:44:00.604  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
06-22 07:44:00.604  1474  1474 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
06-22 07:44:00.614  5654  5654 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-22 07:44:00.614  1474  1474 V ActivityThread: updateVisibility : ActivityRecord{3ad596ef token=android.os.BinderProxy@28fa2d44 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
06-22 07:44:00.614  1474  1474 D Launcher.HomeView: onStop
,06-22 07:44:00.614  1017  3132 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,06-22 07:44:00.624  5595  5595 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,06-22 07:44:00.624  1017  5670 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-22 07:44:00.624  1878  1878 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,06-22 07:44:00.634  1179  1179 I StatusBar: Icon Only
,06-22 07:44:00.634  1017  1588 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:00.634  1017  1588 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:44:00.634  1017  1588 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
06-22 07:44:00.634  1017  1588 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
06-22 07:44:00.634  1017  1588 D ActivityManager: com.sec.android.app.camera, Starting
,06-22 07:44:00.634  1179  1179 D PanelView: There is/are notification(s) 
06-22 07:44:00.634  1017  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:00.634  1017  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:00.634  1017  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:00.634  1017  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:00.644  1474  1474 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@28fa2d44 time:96487
,06-22 07:44:00.664  5672  5672 E Zygote  : MountEmulatedStorage()
,06-22 07:44:00.664  5672  5672 E Zygote  : v2
06-22 07:44:00.664  5672  5672 I libpersona: KNOX_SDCARD checking this for 10139
06-22 07:44:00.664  5672  5672 I libpersona: KNOX_SDCARD not a persona
,06-22 07:44:00.664  1017  1588 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=5672 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a,
06-22 07:44:00.664  5672  5672 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
06-22 07:44:00.664  1017  1588 I ActivityManager: Killing 5128:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,06-22 07:44:00.664  5672  5672 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
06-22 07:44:00.664  5672  5672 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:44:00.674  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{32d08ee6 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t22} time:96512
,06-22 07:44:00.674  1017  1047 W ActivityManager: mDVFSHelper.release()
,06-22 07:44:00.694  5672  5672 D TimaKeyStoreProvider: TimaSignature is unavailable
06-22 07:44:00.694  5672  5672 D ActivityThread: Added TimaKeyStore provider
,06-22 07:44:00.694  5650  5650 D AndroidRuntime: 
06-22 07:44:00.694  5650  5650 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,06-22 07:44:00.704  5650  5650 D AndroidRuntime: CheckJNI is OFF
,06-22 07:44:00.704  5650  5650 D AndroidRuntime: readGMSProperty: start
06-22 07:44:00.704  5650  5650 D AndroidRuntime: readGMSProperty: already setted!!
06-22 07:44:00.704  5650  5650 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-22 07:44:00.704  5650  5650 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-22 07:44:00.704  5650  5650 D AndroidRuntime: readGMSProperty: end
06-22 07:44:00.704  5650  5650 D AndroidRuntime: addProductProperty: start
,06-22 07:44:00.714  1017  1588 D PersonaManager: isKioskContainerExistOnDevice
,06-22 07:44:00.714  5672  5672 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
06-22 07:44:00.714  5672  5672 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
06-22 07:44:00.714  5672  5672 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
06-22 07:44:00.714  5672  5672 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
06-22 07:44:00.714  5672  5672 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,06-22 07:44:00.724  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,06-22 07:44:00.734  1017  1291 I splitIntent: Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,06-22 07:44:00.734  1017  1291 I ActivityManager: Killing 5143:com.wsomacp/u0a25 (adj 15): empty #31
,06-22 07:44:00.744  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:00.744  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:44:00.744  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,06-22 07:44:00.744  5022  5022 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,06-22 07:44:00.834  5650  5650 E AffinityControl: AffinityControl: registerfunction enter
,06-22 07:44:00.854  5650  5650 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,06-22 07:44:00.864  1017  1795 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
06-22 07:44:00.864  1017  1795 D PackageManager: START PACKAGE DELETE: observer{506156985}
06-22 07:44:00.864  1017  1795 D PackageManager: pkg{<packageName>}
06-22 07:44:00.864  1017  1795 D PackageManager: user{0}
06-22 07:44:00.864  1017  1795 D PackageManager: caller{2000}
06-22 07:44:00.864  1017  1795 D PackageManager: flags{2}
06-22 07:44:00.874  1017  1795 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
06-22 07:44:00.874  1017  1795 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
06-22 07:44:00.874  1017  1795 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-22 07:44:00.874  1017  1795 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,06-22 07:44:00.874  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
06-22 07:44:00.874  1017  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
06-22 07:44:00.874  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
06-22 07:44:00.874  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
06-22 07:44:00.874  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,06-22 07:44:00.874  1017  1057 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,06-22 07:44:00.874  1017  1042 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,06-22 07:44:00.874  1017  1042 I ActivityManager: Killing 5595:com.test.thalitest/u0a155 (adj 15): stop com.test.thalitest cause uninstall pkg
,06-22 07:44:00.974  1017  1057 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,06-22 07:44:00.984  1017  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,06-22 07:44:01.014  1017  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,06-22 07:44:01.024  1904  2092 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.,
,06-22 07:44:01.034  1878  1878 E SamsungIME: mOCRHelper is null
,06-22 07:44:01.034  1017  1125 V NetworkStats: removeUidsLocked() for UIDs [10155]
06-22 07:44:01.034  1017  1125 V NetworkStats: performPollLocked(flags=0x3)
,06-22 07:44:01.044  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
,06-22 07:44:01.044  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,06-22 07:44:01.044  3778  3778 I art     : Explicit concurrent mark sweep GC freed 21142(1177KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 6MB/11MB, paused 784us total 53.416ms
,06-22 07:44:01.064  1431  1431 D PersonaManager: isKioskContainerExistOnDevice
,06-22 07:44:01.064  1431  1431 D RegisteredServicesCache: empty dynamic service
,06-22 07:44:01.074  1017  1125 V NetworkStats: performPollLocked() took 32ms
,06-22 07:44:01.084  1431  1431 D RegisteredComponentCache: Collect Tech packages for Knox
,06-22 07:44:01.084  1431  1431 D PersonaManager: isKioskContainerExistOnDevice
,06-22 07:44:01.094  4254  4254 I art     : Explicit concurrent mark sweep GC freed 13133(721KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 652us total 95.940ms
,06-22 07:44:01.114  4835  4835 I art     : Explicit concurrent mark sweep GC freed 11679(777KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/11MB, paused 756us total 131.051ms
,06-22 07:44:01.154  3562  3562 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Jun 22 07:44:01 GMT+02:00 2016
,06-22 07:44:01.154  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,06-22 07:44:01.154  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,06-22 07:44:01.154  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,06-22 07:44:01.154  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:44:01.154  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,06-22 07:44:01.184  3562  3562 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,06-22 07:44:01.184  1017  1126 D NtpTrustedTime: forceRefresh() from cache miss
,06-22 07:44:01.184   277   958 D EnterpriseController: uids 1000
06-22 07:44:01.184   277   958 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
06-22 07:44:01.184   277   958 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,06-22 07:44:01.194   277   958 D EnterpriseController: uids 1000
06-22 07:44:01.194   277   958 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
06-22 07:44:01.194   277   958 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,06-22 07:44:01.194  1017  1126 D NtpTrustedTime: forceRefresh Fail.
,06-22 07:44:01.204  3562  3562 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,06-22 07:44:01.204  3562  3562 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,06-22 07:44:01.214  3562  3562 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,06-22 07:44:01.224  3562  5696 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,06-22 07:44:01.224  1017  1017 I art     : Explicit concurrent mark sweep GC freed 176929(11MB) AllocSpace objects, 12(1937KB) LOS objects, 33% free, 28MB/42MB, paused 2.986ms total 233.783ms
,06-22 07:44:01.224  3562  5696 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
,06-22 07:44:01.224  1017  1078 I art     : WaitForGcToComplete blocked for 44.785ms for cause Explicit
,06-22 07:44:01.244  3562  5696 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,06-22 07:44:01.254  3562  5696 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,06-22 07:44:01.324  5568  5584 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,06-22 07:44:01.344  5568  5584 I AcmsKeyStoreHelper: Key Store exist
,06-22 07:44:01.344  5568  5584 I AcmsKeyStoreHelper: Hence loading the keystore file
,06-22 07:44:01.394  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,06-22 07:44:01.394  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,06-22 07:44:01.394  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
06-22 07:44:01.394  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,06-22 07:44:01.394  1017  1017 D OTPFW   : OtpDbHelper::getInstance New instance created
,06-22 07:44:01.394  1017  1017 D OTPFW   : DBIntegrity::getInstance - New instance created
,06-22 07:44:01.404  3562  5696 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,06-22 07:44:01.424  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,06-22 07:44:01.424  1017  1078 I art     : Explicit concurrent mark sweep GC freed 18403(1128KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 7.553ms total 195.527ms
06-22 07:44:01.424  1017  1078 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
06-22 07:44:01.424  1017  1078 D SecContentProvider2: mCursor = null
,06-22 07:44:01.424  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
06-22 07:44:01.424  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
06-22 07:44:01.424  1017  1057 I art     : WaitForGcToComplete blocked for 421.548ms for cause Explicit
06-22 07:44:01.424  3562  5696 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
06-22 07:44:01.424  1017  3132 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
06-22 07:44:01.424  1017  3132 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
06-22 07:44:01.424  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
06-22 07:44:01.424  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
06-22 07:44:01.424  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
06-22 07:44:01.424  1017  1017 V EnterpriseBillingPolicy: uID is 10155
06-22 07:44:01.424  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
06-22 07:44:01.424  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
06-22 07:44:01.424  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
06-22 07:44:01.424  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
06-22 07:44:01.424  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
06-22 07:44:01.424  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
06-22 07:44:01.424  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,06-22 07:44:01.434  1017  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
06-22 07:44:01.434  1017  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
06-22 07:44:01.434  1017  1041 W TextServicesManagerService: no available spell checker services found
,06-22 07:44:01.444  1017  3132 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
06-22 07:44:01.444  1017  3132 D ActivityManager: com.sec.esdk.elm, Starting
,06-22 07:44:01.444  1017  3132 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:01.444  3562  5696 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,06-22 07:44:01.444  1017  3132 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:01.444  1017  3132 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:01.444  1017  3132 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:01.444  5568  5584 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
06-22 07:44:01.444  5568  5584 I AcmsCertificateMngr: getKeyStoreForApplication success 
06-22 07:44:01.444  5568  5584 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
06-22 07:44:01.444  5568  5584 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
06-22 07:44:01.444  5568  5584 D AcmsServiceMonitor: Decrementing - Counter value: 1
06-22 07:44:01.444  5568  5584 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,06-22 07:44:01.444  5568  5584 D AcmsCore: This is NOT a valid MirrorLink app
06-22 07:44:01.444  5568  5584 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
06-22 07:44:01.444  5568  5584 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
06-22 07:44:01.444  5568  5584 D AcmsServiceMonitor: Decrementing - Counter value: 0
06-22 07:44:01.444  5568  5584 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,06-22 07:44:01.454  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-22 07:44:01.454  5699  5699 I libpersona: KNOX_SDCARD checking this for 10094
06-22 07:44:01.454  5699  5699 E Zygote  : MountEmulatedStorage()
06-22 07:44:01.454  5699  5699 I libpersona: KNOX_SDCARD not a persona
06-22 07:44:01.454  5699  5699 E Zygote  : v2
,06-22 07:44:01.454  5699  5699 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,06-22 07:44:01.464  5699  5699 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,06-22 07:44:01.464  5699  5699 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:44:01.464  1017  3132 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5699 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
06-22 07:44:01.464  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:44:01.474  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:44:01.474  4420  4420 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,06-22 07:44:01.474  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
06-22 07:44:01.474  1017  1042 D ActivityManager: com.sec.android.app.themechooser, Starting
06-22 07:44:01.484  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:01.484  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:01.484  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:01.484  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:01.484  5699  5699 D TimaKeyStoreProvider: TimaSignature is unavailable
06-22 07:44:01.484  5699  5699 D ActivityThread: Added TimaKeyStore provider
06-22 07:44:01.494  5715  5715 E Zygote  : MountEmulatedStorage()
06-22 07:44:01.494  5715  5715 I libpersona: KNOX_SDCARD checking this for 10149
06-22 07:44:01.494  5715  5715 E Zygote  : v2
06-22 07:44:01.494  5715  5715 I libpersona: KNOX_SDCARD not a persona
06-22 07:44:01.494  5715  5715 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
06-22 07:44:01.504  1017  1042 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=5715 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-22 07:44:01.494  5715  5715 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
06-22 07:44:01.504  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
06-22 07:44:01.504  5715  5715 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-22 07:44:01.504  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
06-22 07:44:01.504  1017  1017 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
06-22 07:44:01.504  1017  1017 V EnterpriseBillingPolicy: uID is 10155
06-22 07:44:01.504  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
06-22 07:44:01.504  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
06-22 07:44:01.504  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
06-22 07:44:01.504  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
06-22 07:44:01.504  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
06-22 07:44:01.504  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
06-22 07:44:01.504  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,06-22 07:44:01.514  5568  5568 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
06-22 07:44:01.514  5568  5568 D AcmsService: Enter onDestroy
06-22 07:44:01.514  5568  5568 I AcmsService: cleanUp(): inside service clean up
06-22 07:44:01.514  5568  5568 D AcmsCore: AcmsCore: inside DeInit
06-22 07:44:01.514  5568  5568 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
06-22 07:44:01.514  5568  5568 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
06-22 07:44:01.514  5568  5568 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
06-22 07:44:01.514  5568  5568 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
06-22 07:44:01.514  5568  5568 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,06-22 07:44:01.514  5568  5568 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
06-22 07:44:01.514  5568  5568 D AcmsService: killing acms process
06-22 07:44:01.514  5568  5568 I Process : Sending signal. PID: 5568 SIG: 9
,06-22 07:44:01.514  3562  3562 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,06-22 07:44:01.524  5081  5081 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,06-22 07:44:01.524  5715  5715 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:44:01.524  5715  5715 D ActivityThread: Added TimaKeyStore provider
,06-22 07:44:01.534  1017  1291 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
06-22 07:44:01.534  1017  1291 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,06-22 07:44:01.534  1017  1291 W ActivityManager: userId = 0, bbcId = -10000
,06-22 07:44:01.534  1017  1291 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:44:01.534  1017  1291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,06-22 07:44:01.544  1017  2904 I TactileAssist: enable value -1
06-22 07:44:01.544  1017  2904 I TactileAssist: internal enable value -1
06-22 07:44:01.544  1017  2904 I TactileAssist: intensity value -1
06-22 07:44:01.544  1017  2904 I TactileAssist: saveAppList value true
,06-22 07:44:01.554  1017  2635 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,06-22 07:44:01.554  5081  5730 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
06-22 07:44:01.554  5081  5730 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,06-22 07:44:01.554  1017  2904 I TactileAssist: List of disabled apps :
,06-22 07:44:01.564  5699  5699 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,06-22 07:44:01.574  5699  5699 D elm:15183: ELMEngine.ELMEngine( context ).
,06-22 07:44:01.584  5699  5699 D elm:15183: MDMBridge.setEnterpriseBridge()
,06-22 07:44:01.584  1017  3132 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
06-22 07:44:01.584  1017  3132 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,06-22 07:44:01.584  1017  3132 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:01.584  1017  3132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:44:01.584  1017  3132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,06-22 07:44:01.584  5699  5699 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
06-22 07:44:01.594  4254  5713 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,06-22 07:44:01.594  5404  5404 D Compatibility: onReceive() it will make start service
,06-22 07:44:01.604  3165  3165 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,06-22 07:44:01.604  3165  3165 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
06-22 07:44:01.604  1017  1291 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
06-22 07:44:01.604  1017  1291 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,06-22 07:44:01.604  3165  3165 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
06-22 07:44:01.604  3165  3165 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
06-22 07:44:01.604  3165  3165 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
06-22 07:44:01.604  3165  3165 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
06-22 07:44:01.604  3165  3165 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
06-22 07:44:01.604  3165  3165 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-22 07:44:01.604  3165  3165 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-22 07:44:01.604  3165  3165 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
06-22 07:44:01.604  3165  3165 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-22 07:44:01.604  3165  3165 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-22 07:44:01.604  3165  3165 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
06-22 07:44:01.604  3165  3165 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,06-22 07:44:01.604  1017  1291 W ActivityManager: userId = 0, bbcId = -10000
,06-22 07:44:01.604  1017  1291 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:44:01.604  1017  1291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,06-22 07:44:01.604  5715  5715 D ThemeInfoUtil: getCurrentFestivalName is [null]
06-22 07:44:01.604  5715  5715 D ThemeInfoUtil: isCurrentFestival = false
,06-22 07:44:01.614  4254  4254 I art     : Explicit concurrent mark sweep GC freed 1019(49KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 1.451ms total 63.171ms
,06-22 07:44:01.614  5404  5732 D Compatibility: onHandleIntent()
,06-22 07:44:01.614  5404  5732 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10155, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
06-22 07:44:01.614  5699  5699 D elm:15183: ElmAgentService : onCreate()
,06-22 07:44:01.614  5699  5731 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,06-22 07:44:01.614  5699  5731 D elm:15183: MainReceiver.listeningToPackageRemoved()
06-22 07:44:01.614  5699  5731 D elm:15183: MDMBridge.getInstance()
06-22 07:44:01.614  5699  5731 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,06-22 07:44:01.624  5699  5731 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,06-22 07:44:01.624  5404  5732 D Compatibility: found: 2
06-22 07:44:01.624  5404  5732 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
06-22 07:44:01.624  5404  5732 D Compatibility: skipping ResolveInfo{1f784a40 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
06-22 07:44:01.624  5404  5732 D Compatibility: considering ResolveInfo{3a574d79 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
06-22 07:44:01.624  5404  5732 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,06-22 07:44:01.624  5287  5287 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,06-22 07:44:01.624  5404  5732 D Compatibility: enabling receiver ResolveInfo{155d0abe com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,06-22 07:44:01.624  1017  1246 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
06-22 07:44:01.624  1017  1246 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,06-22 07:44:01.624  1017  1246 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:01.624  1017  1246 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:44:01.624  1017  1246 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,06-22 07:44:01.634  1017  1478 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.sm, calleePkgName: com.sec.android.provider.badge
06-22 07:44:01.634  1017  1478 D ActivityManager: com.sec.android.provider.badge, Starting
06-22 07:44:01.634  5287  5287 I PCWCLIENTTRACE_PushUtil: sales region : global
06-22 07:44:01.634  5287  5287 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
06-22 07:44:01.634  5287  5287 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,06-22 07:44:01.634  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:01.634  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:01.634  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:01.634  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:01.634  5404  5732 D Compatibility: enabling receiver ResolveInfo{3ed7a71f com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,06-22 07:44:01.634  4835  5733 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,06-22 07:44:01.644  5735  5735 E Zygote  : MountEmulatedStorage()
06-22 07:44:01.644  5735  5735 E Zygote  : v2
06-22 07:44:01.644  5735  5735 I libpersona: KNOX_SDCARD checking this for 10072
,06-22 07:44:01.644  5404  5732 D Compatibility: enabling receiver ResolveInfo{17b7ca6c com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
06-22 07:44:01.644  5735  5735 I libpersona: KNOX_SDCARD not a persona
,06-22 07:44:01.644  5735  5735 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,06-22 07:44:01.654  5735  5735 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
06-22 07:44:01.654  1017  1478 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5735 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,06-22 07:44:01.654  5735  5735 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,06-22 07:44:01.654  1017  3132 I ActivityManager: Process ACMS.Process (pid 5568)(adj 0) has died(69,1152)
,06-22 07:44:01.664  5404  5732 D Compatibility: enabling receiver ResolveInfo{14764835 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,06-22 07:44:01.664  1017  1291 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
06-22 07:44:01.664  1017  1291 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,06-22 07:44:01.664  1017  1291 W ActivityManager: userId = 0, bbcId = -10000
,06-22 07:44:01.664  1017  1291 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:44:01.664  1017  1291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,06-22 07:44:01.674  5735  5735 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:44:01.674  5735  5735 D ActivityThread: Added TimaKeyStore provider
,06-22 07:44:01.674  5404  5732 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,06-22 07:44:01.684  1017  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,06-22 07:44:01.684  5699  5699 D elm:15183: ElmAgentService : onDestroy().
,06-22 07:44:01.694  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:44:01.694  5365  5365 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,06-22 07:44:01.694  5365  5365 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
06-22 07:44:01.694  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:44:01.694  5365  5365 I TapandpayWidget:Utils: Clear T&P info.
,06-22 07:44:01.704  5365  5365 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,06-22 07:44:01.704  1017  1796 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,06-22 07:44:01.704  1017  1796 D ActivityManager: com.samsung.android.intelligenceservice, Starting
,06-22 07:44:01.704  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:44:01.704  1017  1796 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:01.704  1017  1796 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:01.704  1017  1796 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:01.704  1017  1796 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:01.714  1017  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
06-22 07:44:01.714  1017  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-22 07:44:01.714  1017  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-22 07:44:01.714  5275  5275 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,06-22 07:44:01.714  5751  5751 E Zygote  : MountEmulatedStorage()
06-22 07:44:01.714  5751  5751 E Zygote  : v2
06-22 07:44:01.724  5751  5751 I libpersona: KNOX_SDCARD checking this for 10003
06-22 07:44:01.724  5751  5751 I libpersona: KNOX_SDCARD not a persona
,06-22 07:44:01.724  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:44:01.724  1017  1796 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5751 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,06-22 07:44:01.724  5751  5751 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,06-22 07:44:01.734  5751  5751 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
06-22 07:44:01.734  5735  5735 D BadgeProvider: onCreate
06-22 07:44:01.734  5735  5735 D BadgeProvider: DatabaseHelper
,06-22 07:44:01.734  5751  5751 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:44:01.744  1017  2904 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,06-22 07:44:01.744  1017  2904 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,06-22 07:44:01.744  1017  2904 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:01.744  1017  2904 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:44:01.744  1017  2904 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
06-22 07:44:01.744  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:44:01.764  5751  5751 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:44:01.764  5751  5751 D ActivityThread: Added TimaKeyStore provider
,06-22 07:44:01.774  1017  2903 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,06-22 07:44:01.774  1017  2903 D ActivityManager: com.sec.enterprise.knox.cloudmdm.smdms, Starting
,06-22 07:44:01.774  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-22 07:44:01.774  1017  2903 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:01.774  1017  2903 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:01.774  5735  5750 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
06-22 07:44:01.774  1017  2903 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:01.774  5735  5750 D BadgeProvider: sendNotify, [notify] : null
06-22 07:44:01.774  1017  2903 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:01.774  5735  5750 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
06-22 07:44:01.774  5735  5750 D BadgeProvider: update, [BadgeCount] : badgecount=0
06-22 07:44:01.774  5735  5750 D BadgeProvider: update, [UpdateCount] : 1
06-22 07:44:01.784  1474  1474 D Launcher.Model: reloadBadges entered.
,06-22 07:44:01.784  1017  1057 I art     : Explicit concurrent mark sweep GC freed 10853(706KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 5.855ms total 358.395ms
,06-22 07:44:01.794  5767  5767 E Zygote  : MountEmulatedStorage(),
06-22 07:44:01.794  5767  5767 E Zygote  : v2
06-22 07:44:01.794  5767  5767 I libpersona: KNOX_SDCARD checking this for 10160
06-22 07:44:01.794  5767  5767 I libpersona: KNOX_SDCARD not a persona
,06-22 07:44:01.794  5767  5767 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,06-22 07:44:01.794  1017  2903 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=5767 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a,
06-22 07:44:01.794  5767  5767 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,06-22 07:44:01.794  5767  5767 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,06-22 07:44:01.814  1017  1796 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-22 07:44:01.814  1017  1796 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,06-22 07:44:01.814  1017  1796 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:01.814  1017  1796 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:44:01.814  1017  1796 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-22 07:44:01.824  1017  2903 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
06-22 07:44:01.824  1017  2903 D ActivityManager: com.sec.spp.push, Starting
,06-22 07:44:01.824  1017  2903 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:01.824  1017  2903 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:01.824  1017  2903 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:01.824  1017  2903 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:01.824  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:44:01.834  5767  5767 D TimaKeyStoreProvider: TimaSignature is unavailable,
06-22 07:44:01.834  5767  5767 D ActivityThread: Added TimaKeyStore provider
,06-22 07:44:01.834  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,06-22 07:44:01.834  1017  1057 D PackageManager: delete codoeFile: 
,06-22 07:44:01.834  1017  1057 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
06-22 07:44:01.834  1017  1057 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,06-22 07:44:01.834  1017  1057 D PackageManager: result of delete: 1{506156985},
,06-22 07:44:01.844  5782  5782 E Zygote  : MountEmulatedStorage()
06-22 07:44:01.844  5782  5782 E Zygote  : v2
06-22 07:44:01.844  5782  5782 I libpersona: KNOX_SDCARD checking this for 10035
06-22 07:44:01.844  5782  5782 I libpersona: KNOX_SDCARD not a persona
,06-22 07:44:01.844  5782  5782 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
06-22 07:44:01.844  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:44:01.844  5782  5782 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,06-22 07:44:01.844  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-22 07:44:01.844  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
06-22 07:44:01.844  5650  5650 D AndroidRuntime: Shutting down VM
,06-22 07:44:01.844  5782  5782 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
06-22 07:44:01.844  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-22 07:44:01.844  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,06-22 07:44:01.854  1017  2903 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=5782 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-22 07:44:01.854  1017  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
06-22 07:44:01.854  1017  1057 D PackageManager: userId{-1}
06-22 07:44:01.854  1017  1057 D PackageManager: andCode{true}
,06-22 07:44:01.854  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:44:01.864  5751  5751 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,06-22 07:44:01.864  1017  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
,06-22 07:44:01.864  1017  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,06-22 07:44:01.874  1017  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,06-22 07:44:01.874  5767  5767 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,06-22 07:44:01.884  5782  5782 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:44:01.884  5782  5782 D ActivityThread: Added TimaKeyStore provider
,06-22 07:44:01.884  1017  1291 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-22 07:44:01.884  1017  1291 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,06-22 07:44:01.884  1017  1291 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:01.884  1017  1291 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:44:01.884  1017  1291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-22 07:44:01.894  4919  4919 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,06-22 07:44:01.894  1017  1246 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
06-22 07:44:01.894  1017  1246 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,06-22 07:44:01.904  5751  5751 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,06-22 07:44:01.904  5751  5751 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
06-22 07:44:01.904  5751  5751 D UserAnalysis: Create SecureDbHelper
,06-22 07:44:01.904  5767  5767 D [0]UMC:UMCContentProvider: @onCreate
,06-22 07:44:01.904   287   287 E SMD     : DCD OFF
,06-22 07:44:01.914  5751  5751 D IntelligenceServiceApplication: onCreate()
,06-22 07:44:01.914  5751  5751 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,06-22 07:44:01.914  5767  5767 D [0]UMC:Core: onCreate(): 
06-22 07:44:01.914  5767  5767 D [0]UMC:Core: @isManagedProfileUser
06-22 07:44:01.914  5767  5767 D [0]UMC:Core: userId: 0
,06-22 07:44:01.914  5767  5767 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
06-22 07:44:01.914  5767  5767 D [0]UMC:Core: userInfo.isManagedProfile() : false
,06-22 07:44:01.924  4835  5733 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 278 ms] updated apps [took 278 ms] 
,06-22 07:44:01.924  1017  2902 I ActivityManager: Killing 5172:com.google.android.gms:car/u0a12 (adj 15): empty #31
,06-22 07:44:01.934  1017  2902 I ActivityManager: Killing 4722:com.dropbox.android/u0a92 (adj 15): empty #31
,06-22 07:44:01.934  1017  1478 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,06-22 07:44:01.934  1017  1478 D ActivityManager: com.android.keychain, Starting
,06-22 07:44:01.934  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:01.934  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:01.934  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:01.934  1017  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:01.944  5751  5751 D IntelligenceServiceApplication: no applications having user consent for prediction
,06-22 07:44:01.944  5767  5767 D [0]UMC:DeviceInfo: USA==US==
,06-22 07:44:01.954  5797  5797 E Zygote  : MountEmulatedStorage()
,06-22 07:44:01.954  5797  5797 E Zygote  : v2
06-22 07:44:01.954  5797  5797 I libpersona: KNOX_SDCARD checking this for 1000
06-22 07:44:01.954  5797  5797 I libpersona: KNOX_SDCARD not a persona
,06-22 07:44:01.954  5797  5797 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,06-22 07:44:01.964  5797  5797 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
06-22 07:44:01.964  5797  5797 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:44:01.964  1017  1478 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5797 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
06-22 07:44:01.964  1017  1478 I ActivityManager: Killing 4860:com.google.android.partnersetup/u0a15 (adj 15): empty #31
06-22 07:44:01.964  1017  2902 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,06-22 07:44:01.974  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,06-22 07:44:01.984  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,06-22 07:44:01.994  5797  5797 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:44:01.994  5797  5797 D ActivityThread: Added TimaKeyStore provider
,06-22 07:44:02.024  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,06-22 07:44:02.024  5782  5813 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
06-22 07:44:02.024  5782  5813 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,06-22 07:44:02.024  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,06-22 07:44:02.034  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
,06-22 07:44:02.034  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,06-22 07:44:02.034  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
06-22 07:44:02.034  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,06-22 07:44:02.034  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
06-22 07:44:02.034  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
06-22 07:44:02.034  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
,06-22 07:44:02.034  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
06-22 07:44:02.034  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,06-22 07:44:02.034  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
06-22 07:44:02.034  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,06-22 07:44:02.034  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
06-22 07:44:02.034  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
06-22 07:44:02.034  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
,06-22 07:44:02.034  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
06-22 07:44:02.034  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
06-22 07:44:02.034  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,06-22 07:44:02.034  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
06-22 07:44:02.034  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
06-22 07:44:02.034  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
06-22 07:44:02.034  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
06-22 07:44:02.034  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,06-22 07:44:02.054  5494  5494 I SA      : [SUR] onReceive called
06-22 07:44:02.054  1017  1588 I ActivityManager: Killing 4953:com.google.android.apps.plus/u0a120 (adj 15): empty #31
06-22 07:44:02.054  5494  5494 I SA      : [SUR] Not SA Package.. finish
06-22 07:44:02.054  5782  5813 D SPPClientService: PushLog.txt file is not deleted.
06-22 07:44:02.054  5782  5813 D SPPClientService: PushLog.txt file is not deleted.
06-22 07:44:02.054  5782  5813 D SPPClientService: ============PushLog. stop!
06-22 07:44:02.054  5650  5650 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
06-22 07:44:02.064  5751  5751 D BluetoothAdapter: 1032659288: getState() :  mService = null. Returning STATE_OFF
,06-22 07:44:02.064  5751  5751 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,06-22 07:44:02.064  5767  5767 D USER_AGENT: UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US,
06-22 07:44:02.064  5797  5797 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,06-22 07:44:02.074  1017  2904 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
06-22 07:44:02.074  1017  2904 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,06-22 07:44:02.074  1017  2904 W ActivityManager: userId = 0, bbcId = -10000
,06-22 07:44:02.074  1017  2904 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:44:02.074  1017  2904 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,06-22 07:44:02.074  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,06-22 07:44:02.074  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
06-22 07:44:02.074  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
06-22 07:44:02.074  5751  5751 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
06-22 07:44:02.074  1017  1030 D ActivityManager: com.samsung.android.app.mirrorlink, Starting
,06-22 07:44:02.084  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.084  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.084  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.084  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:02.084  5767  5767 D [0]UMC:AdminManager: init - start
,06-22 07:44:02.094  5816  5816 E Zygote  : MountEmulatedStorage()
06-22 07:44:02.094  5816  5816 E Zygote  : v2
06-22 07:44:02.094  5816  5816 I libpersona: KNOX_SDCARD checking this for 1000
06-22 07:44:02.094  5816  5816 I libpersona: KNOX_SDCARD not a persona
,06-22 07:44:02.094  1017  1030 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5816 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,06-22 07:44:02.104  1017  3132 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
,06-22 07:44:02.104  5816  5816 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
06-22 07:44:02.104  1017  3132 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,06-22 07:44:02.104  1017  3132 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:02.104  1017  3132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:44:02.104  1017  3132 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
06-22 07:44:02.104  5816  5816 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
06-22 07:44:02.104  5816  5816 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:44:02.104  5767  5767 D [0]UMC:AdminManager: loadAdmins
06-22 07:44:02.104  1017  1472 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
06-22 07:44:02.104  1017  1472 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,06-22 07:44:02.104  1017  1472 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:02.104  1017  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:44:02.104  1017  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,06-22 07:44:02.124   314   314 I art     : Explicit concurrent mark sweep GC freed 8706(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.328ms total 22.651ms
06-22 07:44:02.124  5816  5816 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:44:02.124  5816  5816 D ActivityThread: Added TimaKeyStore provider
,06-22 07:44:02.124  5767  5767 D [0]UMC:AdminManager: init - end
06-22 07:44:02.124  1017  1030 I ActivityManager: Killing 5306:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,06-22 07:44:02.134  5767  5767 D GSLBManager: migrateStoredUrlFromOldPref
,06-22 07:44:02.144  5767  5767 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
,06-22 07:44:02.144  5767  5767 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,06-22 07:44:02.144  5767  5767 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,06-22 07:44:02.144  5767  5767 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
06-22 07:44:02.144  5767  5767 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
06-22 07:44:02.144  5767  5767 D [0]UMC:UMCAdmin: isContainer : 0
,06-22 07:44:02.154  4254  4254 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
06-22 07:44:02.154   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 26.928ms
06-22 07:44:02.154  1017  1030 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,06-22 07:44:02.154  5767  5767 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
06-22 07:44:02.154  5767  5767 D [0]UMC:UMCAdmin: isContainer : 0
06-22 07:44:02.154  5767  5767 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,06-22 07:44:02.154  1017  1478 D ActivityManager: startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
06-22 07:44:02.154  1017  1478 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,06-22 07:44:02.154  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
,06-22 07:44:02.154  1017  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:44:02.154  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,06-22 07:44:02.164  5767  5767 D [0]UMC:GuardService: @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
06-22 07:44:02.164  5767  5767 D [0]UMC:CoreReceiver: Intent : android.intent.action.PACKAGE_REMOVED
06-22 07:44:02.164  5767  5767 D [0]UMC:CoreReceiver: PackageName : com.test.thalitest
06-22 07:44:02.164  5767  5767 D [0]UMC:CoreReceiver: Intent Replacing : false
,06-22 07:44:02.164   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 16.963ms
,06-22 07:44:02.174  5767  5767 D [0]UMC:CoreReceiver: bulk enrolled package: null
,06-22 07:44:02.174  5767  5767 V [0]UMC:ProfileStorage: Enter loadList
06-22 07:44:02.174  5767  5767 D [0]UMC:CoreReceiver: handleAutoEnrollmentAndUMCAdminDeactivation
06-22 07:44:02.174  5767  5767 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,06-22 07:44:02.174  1017  3132 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
06-22 07:44:02.174  5767  5767 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
06-22 07:44:02.174  1017  3132 D ActivityManager: com.google.android.apps.plus, Starting
06-22 07:44:02.174  5767  5767 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
06-22 07:44:02.174  5767  5767 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
06-22 07:44:02.174  5767  5767 D [0]UMC:UMCAdmin: isContainer : 0
06-22 07:44:02.174  5735  5743 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
06-22 07:44:02.174  5735  5743 D BadgeProvider: sendNotify, [notify] : null
06-22 07:44:02.174  5735  5743 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
06-22 07:44:02.174  5735  5743 D BadgeProvider: update, [BadgeCount] : badgecount=0
06-22 07:44:02.174  1017  3132 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.174  5735  5743 D BadgeProvider: update, [UpdateCount] : 1
06-22 07:44:02.174  1017  3132 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.174  1017  3132 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.174  1017  3132 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:02.174  1017  1246 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
06-22 07:44:02.174  5767  5767 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
06-22 07:44:02.174  5767  5767 D [0]UMC:UMCAdmin: isContainer : 0
06-22 07:44:02.174  1474  1474 D Launcher.Model: reloadBadges entered.
,06-22 07:44:02.174  5767  5767 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
06-22 07:44:02.174  5816  5837 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
06-22 07:44:02.174  5767  5767 D [0]UMC:GuardService: @GuardService oncreate()
06-22 07:44:02.174  5767  5767 D [0]UMC:GuardService: @GuardService onStartCommand()
,06-22 07:44:02.174  5816  5837 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,06-22 07:44:02.204  5839  5839 E Zygote  : MountEmulatedStorage()
06-22 07:44:02.204  5839  5839 E Zygote  : v2
06-22 07:44:02.204  5839  5839 I libpersona: KNOX_SDCARD checking this for 10120
06-22 07:44:02.204  5839  5839 I libpersona: KNOX_SDCARD not a persona
,06-22 07:44:02.204  5839  5839 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,06-22 07:44:02.204  1017  3132 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5839 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,06-22 07:44:02.204  1017  3132 I ActivityManager: Killing 5337:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31,
06-22 07:44:02.204  5839  5839 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,06-22 07:44:02.204  1017  1478 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
06-22 07:44:02.204  5839  5839 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-22 07:44:02.204  1017  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,06-22 07:44:02.204  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:02.204  1017  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:44:02.204  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,06-22 07:44:02.214  5816  5816 D AcmsService: Enter Oncreate
,06-22 07:44:02.214  5816  5816 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
06-22 07:44:02.214  5816  5816 D AcmsService: creating AcmsCore
06-22 07:44:02.214  5816  5816 D AcmsCore: AcmsCore.getAcmsCore() - Enter
06-22 07:44:02.214  5816  5816 D AcmsCore: AcmsCore
,06-22 07:44:02.224  5816  5816 D AcmsCore: init
06-22 07:44:02.224  5816  5816 D AcmsCore: Looper handler is not null
06-22 07:44:02.224  5816  5816 D AcmsCore: Post to AcmsCoreHandler
06-22 07:44:02.224  5816  5816 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
06-22 07:44:02.224  5816  5816 D AcmsServiceMonitor: Incrementing - Counter value: 1
06-22 07:44:02.224  5816  5816 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
06-22 07:44:02.224  5816  5816 D AcmsService: onStartCommand
06-22 07:44:02.224  5816  5816 D AcmsService: Action: android.intent.action.PACKAGE_REMOVED
06-22 07:44:02.224  5816  5816 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
06-22 07:44:02.224  5816  5816 D AcmsServiceMonitor: Incrementing - Counter value: 2
06-22 07:44:02.224  5816  5816 D AcmsService: Incremented Counter Value : onStartCommand
,06-22 07:44:02.224  5816  5853 D AcmsCertificateMngr: AcmsCertificateMngr
,06-22 07:44:02.224  1017  1078 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
06-22 07:44:02.234  1017  1078 D ActivityManager: com.samsung.android.app.mirrorlink, Starting
,06-22 07:44:02.234  4980  4980 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(280): Wear auto uninstall disabled for package com.test.thalitest
06-22 07:44:02.234  5816  5816 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,06-22 07:44:02.234  5839  5839 D TimaKeyStoreProvider: TimaSignature is unavailable
06-22 07:44:02.234  5839  5839 D ActivityThread: Added TimaKeyStore provider
,06-22 07:44:02.244  5816  5853 D AcmsRevocationMngr: AcmsRevocationMngr
,06-22 07:44:02.244  5816  5816 W FileUtils: Failed to chmod(/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,06-22 07:44:02.254  1017  1796 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-22 07:44:02.254  1017  1796 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
,06-22 07:44:02.254  5839  5839 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-22 07:44:02.264  1017  1796 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:02.264  1017  1796 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:44:02.264  1017  1796 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-22 07:44:02.264  3720  5428 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest,
06-22 07:44:02.264  3720  5428 D AccountUtils: Clearing selected account for com.test.thalitest
,06-22 07:44:02.274  1904  1904 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
06-22 07:44:02.274  1904  1904 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,06-22 07:44:02.274  1904  1904 D AndroidRuntime: Shutting down VM
,06-22 07:44:02.274  5816  5816 D AcmsService: Inside handle Intent
06-22 07:44:02.274  5816  5816 D AcmsService: App removed - package name: com.test.thalitest
06-22 07:44:02.274  5816  5816 D AcmsCore: Post to AcmsCoreHandler
06-22 07:44:02.274  5816  5816 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
06-22 07:44:02.274  5816  5816 D AcmsServiceMonitor: Incrementing - Counter value: 3
06-22 07:44:02.274  5816  5816 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>5
06-22 07:44:02.274  5816  5816 D AcmsService: Decremented Counter Value : handleStartIntent
,06-22 07:44:02.274  5816  5816 D AcmsServiceMonitor: Decrementing - Counter value: 2
,06-22 07:44:02.284  3720  5428 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,06-22 07:44:02.284  1017  1795 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: com.google.android.location.util.PreferenceService
06-22 07:44:02.284  1017  1795 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,06-22 07:44:02.294  1017  1795 W ActivityManager: userId = 0, bbcId = -10000,
06-22 07:44:02.294  1017  1795 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:44:02.294  1017  1795 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-22 07:44:02.294  1017  1472 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-22 07:44:02.294  1017  1472 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,06-22 07:44:02.294  1017  1472 W ActivityManager: userId = 0, bbcId = -10000
,06-22 07:44:02.294  1017  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:44:02.294  1017  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-22 07:44:02.304  1904  1904 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTMQjrg3Gl8KHWNvbS5nb29nbGUuYW5kcm9pZC
06-22 07:44:02.304  1904  1904 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjcuMjMgKDI4Njc2MzctMDM2KRjUq-AR
06-22 07:44:02.304  1904  1904 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsKvgEQ
06-22 07:44:02.304  1904  1904 I GCore-Chimera-Crash: ==
06-22 07:44:02.304  1904  1904 I GCore-Chimera-Crash: GCore-Chimera-Crash
,06-22 07:44:02.304  1904  1904 E AndroidRuntime: FATAL EXCEPTION: main
06-22 07:44:02.304  1904  1904 E AndroidRuntime: Process: com.google.android.gms.persistent, PID: 1904
06-22 07:44:02.304  1904  1904 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-22 07:44:02.304  1904  1904 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3132)
06-22 07:44:02.304  1904  1904 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
06-22 07:44:02.304  1904  1904 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
06-22 07:44:02.304  1904  1904 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-22 07:44:02.304  1904  1904 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
06-22 07:44:02.304  1904  1904 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
06-22 07:44:02.304  1904  1904 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
06-22 07:44:02.304  1904  1904 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-22 07:44:02.304  1904  1904 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
06-22 07:44:02.304  1904  1904 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
06-22 07:44:02.304  1904  1904 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-22 07:44:02.304  1904  1904 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
06-22 07:44:02.304  1904  1904 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
06-22 07:44:02.304  1904  1904 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
06-22 07:44:02.304  1904  1904 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
06-22 07:44:02.304  1904  1904 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
06-22 07:44:02.304  1904  1904 E AndroidRuntime: 	at jvg.a(SourceFile:251)
06-22 07:44:02.304  1904  1904 E AndroidRuntime: 	at owj.a(SourceFile:310)
06-22 07:44:02.304  1904  1904 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageChimeraTracker.a(SourceFile:134)
06-22 07:44:02.304  1904  1904 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageChimeraTracker$GcmPackageChangeReceiver.onReceive(SourceFile:3382)
06-22 07:44:02.304  1904  1904 E AndroidRuntime: 	at com.google.android.chimera.container.BroadcastReceiverProxy.onReceive(SourceFile:110)
06-22 07:44:02.304  1904  1904 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
06-22 07:44:02.304  1904  1904 E AndroidRuntime: 	... 9 more
,06-22 07:44:02.304  1017  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
06-22 07:44:02.304  1017  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms.persistent
06-22 07:44:02.314  1017  1478 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:02.314  1017  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:44:02.314  1017  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
06-22 07:44:02.324  1017  1588 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
06-22 07:44:02.324  3720  5858 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
06-22 07:44:02.324  3720  5858 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
06-22 07:44:02.324  1017  1588 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:02.324  1017  1588 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:44:02.324  1017  1588 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
06-22 07:44:02.334  1904  1904 I Process : Sending signal. PID: 1904 SIG: 9
06-22 07:44:02.334  1017  5859 E DropBoxManagerService: Can't write: system_app_crash
06-22 07:44:02.334  1017  5859 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop169.tmp: open failed: EROFS (Read-only file system)
06-22 07:44:02.334  1017  5859 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-22 07:44:02.334  1017  5859 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-22 07:44:02.334  1017  5859 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-22 07:44:02.334  1017  5859 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
06-22 07:44:02.334  1017  5859 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
06-22 07:44:02.334  1017  5859 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15777)
06-22 07:44:02.334  1017  5859 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-22 07:44:02.334  1017  5859 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
06-22 07:44:02.334  1017  5859 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-22 07:44:02.334  1017  5859 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-22 07:44:02.334  1017  5859 E DropBoxManagerService: 	... 5 more
06-22 07:44:02.334  1017  2902 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
06-22 07:44:02.334  1017  2902 W ActivityManager: userId = 0, bbcId = -10000
,06-22 07:44:02.334  1017  2902 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:44:02.334  1017  2902 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-22 07:44:02.344  1017  1078 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-22 07:44:02.344  1017  1078 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.disconnect.FitCleanupService; callingUser = 0; userId(target) = 0
,06-22 07:44:02.344  1017  1078 W ActivityManager: userId = 0, bbcId = -10000
,06-22 07:44:02.344  1017  1078 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,06-22 07:44:02.344  1017  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-22 07:44:02.344  1017  1078 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!

```
