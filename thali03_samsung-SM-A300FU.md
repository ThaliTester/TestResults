#### Test 836273370459b7a_thali03_samsung-SM-A300FU Logs


```
--------- beginning of system
09-13 16:33:45.760  1020  1061 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
09-13 16:33:45.760  1020  1061 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
09-13 16:33:45.770  1020  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:45.770  1020  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:45.770  1020  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:45.770  1020  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
--------- beginning of main
09-13 16:33:45.780  6888  6888 E Zygote  : MountEmulatedStorage()
09-13 16:33:45.780  6888  6888 E Zygote  : v2
09-13 16:33:45.780  6888  6888 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 16:33:45.780  6888  6888 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 16:33:45.780  6888  6888 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 16:33:45.780  6888  6888 I libpersona: KNOX_SDCARD checking this for 10003
09-13 16:33:45.780  6888  6888 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:45.780  1020  1061 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6888 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-13 16:33:45.780  1020  1032 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
09-13 16:33:45.780  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:45.780  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:45.780  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:45.780  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:45.800  6897  6897 E Zygote  : MountEmulatedStorage()
09-13 16:33:45.800  6897  6897 E Zygote  : v2
09-13 16:33:45.800  6897  6897 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 16:33:45.800  6897  6897 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 16:33:45.800  6897  6897 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 16:33:45.800  6897  6897 I libpersona: KNOX_SDCARD checking this for 10023
09-13 16:33:45.800  6897  6897 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:45.800  1020  1032 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6897 uid=10023 gids={50023, 9997} abi=armeabi-v7a
09-13 16:33:45.810  6888  6888 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:33:45.810  6888  6888 D ActivityThread: Added TimaKeyStore provider
09-13 16:33:45.820  6717  6768 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-13 16:33:45.820  6717  6768 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 16:33:45.820  6717  6768 I GAv4    :   adb logcat -s GAv4
09-13 16:33:45.830  6897  6897 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:33:45.830  6897  6897 D ActivityThread: Added TimaKeyStore provider
09-13 16:33:45.840  1020  1348 I ActivityManager: Killing 6568:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
,09-13 16:33:45.860   284   284 E installd: system dir 0 : /system/app/
09-13 16:33:45.860   284   284 E installd: system dir 1 : /system/priv-app/
09-13 16:33:45.860   284   284 E installd: system dir 2 : /vendor/app/
09-13 16:33:45.860   284   284 E installd: system dir 3 : /oem/app/
09-13 16:33:45.870  6717  6768 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
09-13 16:33:45.870  1020  1754 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
09-13 16:33:45.880  1836  6711 W art     : Verification of void com.google.android.gms.games.broker.GameAgent.addGameBadgeOps(com.google.android.gms.common.internal.ClientContext, com.google.android.gms.games.server.api.MarketInstance, java.lang.String, java.util.ArrayList, int) took 139.840ms
09-13 16:33:45.880  1020  1061 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
09-13 16:33:45.890  6717  6768 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
09-13 16:33:45.910  1836  4504 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
09-13 16:33:45.930  6897  6897 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
09-13 16:33:45.950  6653  6850 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
09-13 16:33:45.950  6717  6768 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
09-13 16:33:45.970  6897  6897 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
09-13 16:33:45.970  6897  6897 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
09-13 16:33:45.980  6717  6924 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
09-13 16:33:45.980  6897  6897 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
09-13 16:33:45.990  6897  6897 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
09-13 16:33:45.990  6897  6897 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
09-13 16:33:45.990  6897  6897 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
09-13 16:33:46.000  6897  6897 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
09-13 16:33:46.000  6897  6897 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
09-13 16:33:46.000  6897  6897 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
09-13 16:33:46.000  6897  6897 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
09-13 16:33:46.000  6897  6897 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
09-13 16:33:46.000  6897  6897 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
09-13 16:33:46.000  6897  6897 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
09-13 16:33:46.080  1836  4504 D Icing   : Loaded CLD2 Version V2.0 - 20141016
09-13 16:33:46.100   288   288 E SMD     : DCD OFF
09-13 16:33:46.130  6925  6925 D AndroidRuntime: 
09-13 16:33:46.130  6925  6925 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-13 16:33:46.140  6925  6925 D AndroidRuntime: CheckJNI is OFF
09-13 16:33:46.140  6925  6925 D AndroidRuntime: readGMSProperty: start
09-13 16:33:46.140  6925  6925 D AndroidRuntime: readGMSProperty: already setted!!
09-13 16:33:46.140  6925  6925 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-13 16:33:46.140  6925  6925 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-13 16:33:46.140  6925  6925 D AndroidRuntime: readGMSProperty: end
09-13 16:33:46.140  6925  6925 D AndroidRuntime: addProductProperty: start
09-13 16:33:46.170  1836  4504 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
09-13 16:33:46.190  1020  3759 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:46.190  1020  3759 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-13 16:33:46.190  1020  3759 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:46.190  1020  3759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-13 16:33:46.190  1020  1750 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
09-13 16:33:46.190  1020  1750 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:46.190  1020  1750 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:46.190  1020  1750 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:46.190  1020  1750 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:46.200  6933  6933 E Zygote  : MountEmulatedStorage()
09-13 16:33:46.200  6933  6933 E Zygote  : v2
09-13 16:33:46.200  6933  6933 I libpersona: KNOX_SDCARD checking this for 1000
09-13 16:33:46.200  6933  6933 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:46.210  6933  6933 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 16:33:46.210  6933  6933 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 16:33:46.210  1020  1750 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=6933 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-13 16:33:46.210  1020  1750 I ActivityManager: Killing 6583:com.sec.spp.push/u0a32 (adj 15): empty #21
09-13 16:33:46.210  6933  6933 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 16:33:46.250  6933  6933 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:33:46.250  6933  6933 D ActivityThread: Added TimaKeyStore provider
09-13 16:33:46.280  6933  6933 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
09-13 16:33:46.280  6933  6933 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
09-13 16:33:46.280  1020  1348 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
09-13 16:33:46.280  1020  1348 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
09-13 16:33:46.280  1020  1348 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:46.280  1020  1348 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:33:46.280  1020  1348 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
09-13 16:33:46.280  1020  3771 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
09-13 16:33:46.290  6933  6933 I FilterInstaller: FilterPackageService : ACTION_CHANGED
09-13 16:33:46.300  6933  6956 E FilterInstaller: installFilters
09-13 16:33:46.300  6933  6956 E FilterInstaller: There is no requred permission
09-13 16:33:46.310  1020  1348 I ActivityManager: Killing 5385:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
09-13 16:33:46.310  1020  1020 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
09-13 16:33:46.310  1020  1020 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
09-13 16:33:46.320  6925  6925 E AffinityControl: AffinityControl: registerfunction enter
09-13 16:33:46.320  6717  6931 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-13 16:33:46.320  6717  6931 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-13 16:33:46.340  1020  1020 I BackgroundCompactionService: onStart. jobID=801
09-13 16:33:46.340  1020  1020 I BackgroundCompactionService: onStart done. jobID=801
09-13 16:33:46.340  1020  6957 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
09-13 16:33:46.340  1020  6957 I BackgroundCompactionService: compact_memory command done
09-13 16:33:46.340  6925  6925 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-13 16:33:46.370  1020  3770 E PersonaManagerService: inState():  stateMachine is null !!
09-13 16:33:46.370  1020  3770 I PersonaManagerService: PersonaId don't exist
09-13 16:33:46.370  1020  3770 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-13 16:33:46.380  1020  3770 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-13 16:33:46.390  6717  6931 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
09-13 16:33:46.400  1020  3770 W ActivityManager: mDVFSHelper.acquire()
09-13 16:33:46.410  1020  3770 D FocusedStackFrame: Set to : 0
09-13 16:33:46.420  1020  3770 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:46.420  1020  3770 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:46.420  1020  3770 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:46.420  1020  3770 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:46.420  1020  1051 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-13 16:33:46.420  1020  1051 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-13 16:33:46.440  6961  6961 E Zygote  : MountEmulatedStorage()
09-13 16:33:46.440  6961  6961 E Zygote  : v2
09-13 16:33:46.440  6961  6961 I libpersona: KNOX_SDCARD checking this for 10170
09-13 16:33:46.440  6961  6961 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:46.440  6961  6961 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 16:33:46.440  1020  1051 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-13 16:33:46.440  1020  1051 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-13 16:33:46.440   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
09-13 16:33:46.440  1020  3770 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6961 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-13 16:33:46.440  1020  3770 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-13 16:33:46.440  1020  3770 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-13 16:33:46.450  6961  6961 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 16:33:46.450  6961  6961 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-13 16:33:46.460  1020  3770 D InputDispatcher: Focused application set to: xxxx
09-13 16:33:46.460  1020  3770 D InputDispatcher: Focus left window: 1490
09-13 16:33:46.460  6925  6925 D AndroidRuntime: Shutting down VM
09-13 16:33:46.470  1020  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-13 16:33:46.470  1020  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
09-13 16:33:46.480  6717  6931 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-13 16:33:46.480  6717  6931 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@ee2048d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-13 16:33:46.480  6717  6931 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-13 16:33:46.490  6961  6961 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:33:46.490  6961  6961 D ActivityThread: Added TimaKeyStore provider
09-13 16:33:46.490  1020  4006 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-13 16:33:46.490  1020  1020 V ActivityManager: Display changed displayId=0
09-13 16:33:46.500  1020  1049 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-13 16:33:46.510  1020  4006 D PersonaManager: isKioskContainerExistOnDevice
09-13 16:33:46.520  1020  1020 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-13 16:33:46.540   258  1042 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
09-13 16:33:46.540   258   440 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
09-13 16:33:46.550  1490  1490 V ActivityThread: updateVisibility : ActivityRecord{1cd7f8f7 token=android.os.BinderProxy@125b8eb0 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-13 16:33:46.550  1490  1490 D Launcher: onTrimMemory. Level: 20
09-13 16:33:46.640  6961  6961 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
09-13 16:33:46.670  6925  6925 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-13 16:33:46.670  6961  6961 I cr.library_loader: Time to load native libraries: 5 ms (timestamps 5523-5528)
09-13 16:33:46.670  6961  6961 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-13 16:33:46.700  6961  6961 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {397c601f}
,09-13 16:33:46.700  6961  6961 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-13 16:33:46.710  6961  6961 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 16:33:46.750  6961  6961 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-13 16:33:46.750  6961  6961 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 16:33:46.760  6961  6961 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-13 16:33:46.770  1020  3771 I ActivityManager: Killing 6615:com.samsung.helphub/1000 (adj 15): empty #21
,09-13 16:33:46.790  6961  6961 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-13 16:33:46.790  6961  6961 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-13 16:33:46.790  6961  6961 I Adreno-EGL: Build Date: 04/06/15 Mon
09-13 16:33:46.790  6961  6961 I Adreno-EGL: Local Branch: 
09-13 16:33:46.790  6961  6961 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-13 16:33:46.790  6961  6961 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-13 16:33:46.790  6961  6961 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-13 16:33:46.860  6961  6961 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 16:33:46.880  6961  6961 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-13 16:33:46.880  6961  6961 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-13 16:33:46.890  6961  6961 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-13 16:33:46.890  6961  6961 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-13 16:33:47.000  6961  6961 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 16:33:47.010  6961  6961 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-13 16:33:47.020  1020  1046 W ActivityManager: Activity pause timeout for ActivityRecord{251a61ed u0 com.test.thalitest/.MainActivity t163}
,09-13 16:33:47.020  6961  6961 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-13 16:33:47.020  6961  6961 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-13 16:33:47.030  6961  6961 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-13 16:33:47.040  6961  6961 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 16:33:47.040  6961  6961 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 16:33:47.080  1020  1139 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 16:33:47.080  1020  1139 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4193, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-13 16:33:47.080  1020  1139 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-13 16:33:47.080  1020  1139 D BatteryService: stay LED for charging
,09-13 16:33:47.080  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 16:33:47.080  1020  1020 I MotionRecognitionService: Plugged
,09-13 16:33:47.080  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 16:33:47.090  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 16:33:47.090  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 16:33:47.090  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-13 16:33:47.090  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 16:33:47.100  3406  3406 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 16:33:47.100  3406  3517 D HeadsetStateMachine: Disconnected process message: 10
,09-13 16:33:47.110  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
,09-13 16:33:47.110  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-13 16:33:47.110  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 16:33:47.180  6961  7001 D OpenGLRenderer: Render dirty regions requested: true
,09-13 16:33:47.180  1020  4006 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-13 16:33:47.180  1020  4006 D KnoxTimeoutHandler: postActiveUserChange for user 0
,09-13 16:33:47.190  1020  4006 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-13 16:33:47.190  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-13 16:33:47.190  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
,09-13 16:33:47.190  6961  6988 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,09-13 16:33:47.190  6961  6961 V ActivityThread: updateVisibility : ActivityRecord{2dec59ff token=android.os.BinderProxy@702dda0 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-13 16:33:47.200  6961  6961 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,09-13 16:33:47.200  6961  6961 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-13 16:33:47.210   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,09-13 16:33:47.220  1020  1348 D InputDispatcher: Focus entered window: 6961
,09-13 16:33:47.220  1020  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-13 16:33:47.220  1020  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-13 16:33:47.230  6961  6961 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-13 16:33:47.230  6961  7001 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 16:33:47.230  6961  7001 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
09-13 16:33:47.230  6961  7001 D OpenGLRenderer: Enabling debug mode 0
,09-13 16:33:47.260  1020  1519 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-13 16:33:47.270  1177  1177 D PanelView: There is/are notification(s) 
,09-13 16:33:47.270  1020  7006 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 16:33:47.280  1020  1051 I ActivityManager: Displayed Component not be shown by security: +761ms (total +861ms)
09-13 16:33:47.280  1020  1051 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{251a61ed u0 com.test.thalitest/.MainActivity t163} time:96134
09-13 16:33:47.280  1020  1051 W ActivityManager: mDVFSHelper.release()
,09-13 16:33:47.280   258  1042 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,09-13 16:33:47.280   258   440 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,09-13 16:33:47.290  6961  6961 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,09-13 16:33:47.300  6961  6961 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@702dda0 time:96151
,09-13 16:33:47.320  1983  1983 I SamsungIME: getCurrentCandidateView
,09-13 16:33:47.330  6961  6961 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6961
,09-13 16:33:47.410  1983  1983 D SamsungIME: Dismiss ExpandCandiate
,09-13 16:33:47.440  6653  6653 I Mms/MmsApp:  start initViewCache mms
,09-13 16:33:47.440  6653  6653 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1837.819322
09-13 16:33:47.440  6653  6653 D Mms/ComposeMessageFragment: fillCache, easy = false
,09-13 16:33:47.520  6961  6961 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 16:33:47.620  1020  3759 I art     : Explicit concurrent mark sweep GC freed 143605(8MB) AllocSpace objects, 4(1864KB) LOS objects, 33% free, 23MB/34MB, paused 2.486ms total 171.380ms
,09-13 16:33:47.630  6961  7005 D jxcore_app_log: JniHelper::setJavaVM(0xb73f52b0), pthread_self() = -1214772736
,09-13 16:33:47.630  1983  1983 I SamsungIME: getDebugLevel  : 0x4f4c
,09-13 16:33:47.640  6961  7005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 16:33:47.640  6961  7005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 16:33:47.640  6961  7005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 16:33:47.640  6961  7005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 16:33:47.640  6961  7005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-13 16:33:47.640  6961  7005 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264642cd added. We now have 1 listener(s)
,09-13 16:33:47.640  6961  7005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,09-13 16:33:47.650  6961  7005 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-13 16:33:47.650  6961  7005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 16:33:47.650  6961  7005 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 16:33:47.650  6961  7005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 16:33:47.650  6961  7005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 16:33:47.650  6961  7005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 16:33:47.650  6961  7005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
09-13 16:33:47.650  6961  7005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 16:33:47.650  6961  7005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 16:33:47.650  6961  7005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 16:33:47.650  6961  7005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 16:33:47.650  6961  7005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 16:33:47.650  6961  7005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 16:33:47.650  6961  7005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 16:33:47.650  6961  7005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 16:33:47.650  6961  7005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 16:33:47.650  6961  7005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 16:33:47.650  6961  7005 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dd8eed0 added. We now have 1 listener(s)
,09-13 16:33:47.650  6961  7005 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 16:33:47.660  6961  7005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 16:33:47.660  6961  7005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-13 16:33:47.660  6961  7005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 16:33:47.660  6961  7005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 16:33:47.660  6961  7005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-13 16:33:47.660  6961  7005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:33:47.670  6961  7005 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,09-13 16:33:47.670  6961  7005 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-13 16:33:47.670  6961  7005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:33:47.670  6961  7005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:33:47.670  6961  7005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:33:47.670  6961  7005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:33:47.670  6961  7005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:33:47.670  6961  7005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:33:47.670  6961  7005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:33:47.670  6961  7005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:33:47.670  6961  7005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 16:33:47.670  6961  7005 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:33:47.680  6961  7005 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 16:33:47.680  6961  6961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:33:47.680  6961  6961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:33:47.720  1983  1983 I SamsungIME: getDebugLevel  : 0x4f4c
,09-13 16:33:47.720  6961  6961 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 16:33:47.730  1983  1983 I SamsungIME: KeybaordView init() : load resources
,09-13 16:33:47.790  1983  1983 I SamsungIME: getCurrentKeyboard
09-13 16:33:47.790  1983  1983 I SamsungIME: getTextKeyboard
,09-13 16:33:47.800  6653  6653 D AbsListView: Get MotionRecognitionManager
,09-13 16:33:47.800  1020  1139 D MotionRecognitionService:  ssp status : false
,09-13 16:33:47.810  6653  6653 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 362.475157
,09-13 16:33:47.850  1983  1983 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-13 16:33:47.890  6653  6653 D Mms/BubbleViewCache: fillCache bubble = 1
,09-13 16:33:48.290  6961  7017 W jxcore-log: Initializing JXcore engine
09-13 16:33:48.290  6961  7017 W jxcore-log: JXcore engine is ready
09-13 16:33:48.350  2016  2016 E audit   : type=1400 msg=audit(1473777228.350:205): avc:  denied  { ioctl } for  pid=7017 comm="Thread-1320" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-13 16:33:48.350  2016  2016 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
09-13 16:33:48.350  2016  2016 E audit   : type=1300 msg=audit(1473777228.350:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=b a1=5451 a2=3 a3=9f7fb8f8 items=0 ppid=304 ppcomm=main pid=7017 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1320" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-13 16:33:48.350  2016  2016 E audit   : type=1320 msg=audit(1473777228.350:205): 
09-13 16:33:48.360  6961  7017 W jxcore-log: Starting JXcore engine
09-13 16:33:48.470  6961  7017 W jxcore-log: Platform android
09-13 16:33:48.470  6961  7017 W jxcore-log: 
09-13 16:33:48.470  6961  7017 W jxcore-log: Process ARCH arm
09-13 16:33:48.470  6961  7017 W jxcore-log: 
09-13 16:33:48.670  6961  7017 I jxcore-log: JXcore Cordova bridge is ready!
09-13 16:33:48.670  6961  7017 I jxcore-log: 
09-13 16:33:48.670  6961  7017 W jxcore-log: JXcore engine is started
09-13 16:33:48.680  6961  7005 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-13 16:33:48.680  6961  6961 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-13 16:33:48.730   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8b4a7c8
09-13 16:33:48.730   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
09-13 16:33:48.730   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
09-13 16:33:48.730   272   356 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1196120776)
09-13 16:33:48.770   272   356 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
09-13 16:33:48.770   272   356 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
09-13 16:33:48.770   272   356 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1196120776) wakelock released: 1, error no: 0
09-13 16:33:48.770   272   356 I rmt_storage: 
09-13 16:33:48.770   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb8b4a7c8
,09-13 16:33:49.100   288   288 E SMD     : DCD OFF,
,09-13 16:33:49.600  6635  6684 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,09-13 16:33:49.610  6635  6684 I AcmsKeyStoreHelper: Key Store exist
,09-13 16:33:49.610  6635  6684 I AcmsKeyStoreHelper: Hence loading the keystore file
,09-13 16:33:49.670  6635  6684 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
09-13 16:33:49.670  6635  6684 I AcmsCertificateMngr: getKeyStoreForApplication success 
09-13 16:33:49.670  6635  6684 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
09-13 16:33:49.670  6635  6684 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 16:33:49.670  6635  6684 D AcmsServiceMonitor: Decrementing - Counter value: 1
09-13 16:33:49.670  6635  6684 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,09-13 16:33:49.670  6635  6684 D AcmsCore: This is NOT a valid MirrorLink app
09-13 16:33:49.670  6635  6684 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
09-13 16:33:49.670  6635  6684 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 16:33:49.670  6635  6684 D AcmsServiceMonitor: Decrementing - Counter value: 0
09-13 16:33:49.670  6635  6684 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,09-13 16:33:49.680  6635  6635 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,09-13 16:33:49.680  6635  6635 D AcmsService: Enter onDestroy
09-13 16:33:49.680  6635  6635 I AcmsService: cleanUp(): inside service clean up
,09-13 16:33:49.680  6635  6635 D AcmsCore: AcmsCore: inside DeInit
09-13 16:33:49.680  6635  6635 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
,09-13 16:33:49.680  6635  6635 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
,09-13 16:33:49.680  6635  6635 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
09-13 16:33:49.680  6635  6635 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
09-13 16:33:49.680  6635  6635 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,09-13 16:33:49.690  6635  6635 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
09-13 16:33:49.690  6635  6635 D AcmsService: killing acms process
,09-13 16:33:49.690  6635  6635 I Process : Sending signal. PID: 6635 SIG: 9
,09-13 16:33:49.730  1020  1139 I ActivityManager: Process ACMS.Process (pid 6635)(adj 0) has died(43,752)
,09-13 16:33:50.240  1020  3505 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 16:33:50.640  1663  1663 I ConfigService: onDestroy
,09-13 16:33:52.100   288   288 E SMD     : DCD OFF
,09-13 16:33:53.980  1020  3487 D SSRM:n  : SIOP:: AP = 410
,09-13 16:33:55.100   288   288 E SMD     : DCD OFF
,09-13 16:33:55.240  1020  3505 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 16:33:55.940  1020  1061 D PackageManager: [MSG] MCS_UNBIND
,09-13 16:33:55.940  1020  4006 I ActivityManager: Killing 6589:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,09-13 16:33:56.420  1020  1061 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-13 16:33:57.120  1020  1488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 16:33:57.130  1020  1488 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-13 16:33:57.130  1020  1488 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 16:33:57.130  1020  1488 D BatteryService: stay LED for charging
,09-13 16:33:57.130  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 16:33:57.130  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 16:33:57.130  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 16:33:57.130  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-13 16:33:57.140  1020  1020 I MotionRecognitionService: Plugged
09-13 16:33:57.140  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
09-13 16:33:57.140  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 16:33:57.150  3406  3406 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 16:33:57.150  3406  3517 D HeadsetStateMachine: Disconnected process message: 10
,09-13 16:33:57.160  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 16:33:57.160  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 16:33:57.160  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 16:33:58.110   288   288 E SMD     : DCD OFF
,09-13 16:33:59.060  1020  1311 E Watchdog: !@Sync 3
,09-13 16:33:59.990  1020  1099 V AlarmManager: waitForAlarm result :4
,09-13 16:33:59.990  1020  1099 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,09-13 16:33:59.990  1020  1099 V AlarmManager: waitForAlarm result :8
,09-13 16:34:00.130   316   316 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-13 16:34:00.140   316   316 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-13 16:34:00.220  6167  6280 D Finsky  : [1144] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,09-13 16:34:00.220  6167  6167 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,09-13 16:34:00.890  6961  7017 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 16:34:00.890  6961  7017 I jxcore-log: 
,09-13 16:34:00.890  6961  7017 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 16:34:00.890  6961  7017 I jxcore-log: 
,09-13 16:34:00.900  6961  7017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:34:00.900  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:34:00.900  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:34:00.900  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:34:00.900  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:34:00.900  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:34:00.900  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:34:00.900  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:34:00.900  6961  7017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:34:00.900  6961  7017 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 16:34:00.900  6961  7017 I jxcore-log: 
,09-13 16:34:00.910  6961  7017 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 16:34:00.910  6961  7017 I jxcore-log: 
,09-13 16:34:01.110   288   288 E SMD     : DCD OFF
,09-13 16:34:01.570  6961  7017 I jxcore-log: Unit Test app is loaded,
09-13 16:34:01.570  6961  7017 I jxcore-log: 
,09-13 16:34:01.570  6961  7017 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:01.570  6961  7017 I jxcore-log: 
,09-13 16:34:01.580  6961  6961 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-13 16:34:01.580  6961  7017 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 16:34:01.580  6961  7017 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38b69be9 added. We now have 2 listener(s)
,09-13 16:34:01.590  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-13 16:34:01.590  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:34:01.590  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 16:34:01.590  6961  7017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 16:34:01.590  6961  7017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@877906e added. We now have 2 listener(s)
09-13 16:34:01.590  6961  7017 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 16:34:01.590  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 16:34:01.590  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:01.590  6961  7017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:34:01.590  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:34:01.590  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:34:01.590  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:34:01.590  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:34:01.590  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:34:01.590  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:34:01.590  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:34:01.590  6961  7017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:34:01.600  6961  7017 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:34:01.600  6961  7017 D ExecuteNativeTests: Running unit tests
09-13 16:34:01.600  6961  7017 D BluetoothAdapter: enable()
,09-13 16:34:01.600  6961  6961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:01.600  6961  7017 D BluetoothAdapter: enable(): BT is already enabled..!
,09-13 16:34:01.600  6961  6961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:01.600  1020  1139 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-13 16:34:01.610  1020  1139 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-13 16:34:01.610  1020  1139 D SecContentProvider2: mCursor = null
,09-13 16:34:01.610  1020  1139 D WifiService: setWifiEnabled: true pid=6961, uid=10170
,09-13 16:34:01.610  1020  1139 W ActivityManager: Permission Denial: getCurrentUser() from pid=6961, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-13 16:34:01.610  1020  1139 W WifiService: Failed getting userId using ActivityManagerNative
09-13 16:34:01.610  1020  1139 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6961, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-13 16:34:01.610  1020  1139 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-13 16:34:01.610  1020  1139 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-13 16:34:01.610  1020  1139 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-13 16:34:01.610  1020  1139 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-13 16:34:01.610  1020  1139 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-13 16:34:01.610  1020  1139 D SettingsProvider: name = wifi_on
,09-13 16:34:01.620  6961  7017 I System.out: Running UT
,09-13 16:34:04.010  1020  3487 D SSRM:n  : SIOP:: AP = 380
,09-13 16:34:04.100  1020  1053 I PowerManagerService: [PWL] Off : 50s ago,
,09-13 16:34:04.110   288   288 E SMD     : DCD OFF
,09-13 16:34:05.140   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 16:34:06.140   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 16:34:07.120   288   288 E SMD     : DCD OFF
,09-13 16:34:07.140   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 16:34:07.180  1020  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 16:34:07.180  1020  1489 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 16:34:07.180  1020  1489 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 16:34:07.180  1020  1489 D BatteryService: stay LED for charging
09-13 16:34:07.180  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 16:34:07.180  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 16:34:07.190  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 16:34:07.190  1020  1020 I MotionRecognitionService: Plugged
09-13 16:34:07.190  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 16:34:07.190  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-13 16:34:07.190  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 16:34:07.200  3406  3406 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
09-13 16:34:07.200  3406  3517 D HeadsetStateMachine: Disconnected process message: 10
,09-13 16:34:07.210  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 16:34:07.210  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 16:34:07.210  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 16:34:08.140   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 16:34:09.140   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 16:34:10.010  6041  6041 D FactoryTest: Not factory mode,
,09-13 16:34:10.010  6041  6041 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-13 16:34:10.010  6041  6041 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-13 16:34:10.010  6041  6041 D MTPRx   : still no open session command from host, so toast,
,09-13 16:34:10.010  6041  6041 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
09-13 16:34:10.020  6041  6041 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,09-13 16:34:10.020  6041  6041 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:118871,
09-13 16:34:10.020  1020  1519 E PersonaManagerService: inState():  stateMachine is null !!
09-13 16:34:10.020  1020  1519 I PersonaManagerService: PersonaId don't exist,
09-13 16:34:10.020  1020  1519 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-13 16:34:10.020  1020  1519 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,09-13 16:34:10.030  1020  1519 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:34:10.030  1020  1519 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:34:10.030  1020  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-13 16:34:10.030  1020  1519 W ActivityManager: mDVFSHelper.acquire(),
,09-13 16:34:10.040  1020  1519 D PersonaManager: isKioskContainerExistOnDevice
,09-13 16:34:10.050  1020  1519 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-13 16:34:10.050  1020  1519 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-13 16:34:10.050  1020  1519 D InputDispatcher: Focused application set to: xxxx
09-13 16:34:10.050  1020  1519 D InputDispatcher: Focus left window: 6961
,09-13 16:34:10.050  6041  6041 E MTPRx   : started activity for popup
,09-13 16:34:10.060  1020  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-13 16:34:10.060  1020  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-13 16:34:10.080  6041  6041 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-13 16:34:10.080  6041  6041 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-13 16:34:10.080  6041  6041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-13 16:34:10.080  6041  6041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 16:34:10.080  6041  6041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 16:34:10.080  6041  6041 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-13 16:34:10.110  6041  6041 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-13 16:34:10.110  1020  1489 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-13 16:34:10.110  1020  1489 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-13 16:34:10.110  1020  1489 D InputDispatcher: Focused application set to: xxxx
,09-13 16:34:10.110  1020  1489 D InputDispatcher: Focus entered window: 6961
,09-13 16:34:10.110   288   288 E SMD     : DCD OFF,
,09-13 16:34:10.110  1020  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-13 16:34:10.120  1020  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-13 16:34:10.120  1020  1348 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-13 16:34:10.120  1020  1348 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@f79002c attribute=null, token = android.os.BinderProxy@2db35acd
,09-13 16:34:10.140   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-13 16:34:10.150  6041  6041 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-13 16:34:10.150  6041  6041 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-13 16:34:10.150  6041  6041 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-13 16:34:10.170  6961  6961 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-13 16:34:10.170  6961  6961 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-13 16:34:10.170  6961  6961 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-13 16:34:10.170  6961  6961 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-13 16:34:10.180  1020  1519 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-13 16:34:10.180  1020  1519 D KnoxTimeoutHandler: postActiveUserChange for user 0
,09-13 16:34:10.180  1020  1519 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-13 16:34:10.180  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-13 16:34:10.180  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
,09-13 16:34:10.190  6961  6961 D io.jxcore.node.LifeCycleMonitor: onActivityPaused,
09-13 16:34:10.190  6961  6961 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-13 16:34:10.190  6961  6961 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@702dda0 time:119048
09-13 16:34:10.190  6961  6961 V ActivityThread: updateVisibility : ActivityRecord{2dec59ff token=android.os.BinderProxy@702dda0 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-13 16:34:10.190  6961  6961 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1334ab9c Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3b647f9c, 16908290=android.view.AbsSavedState$1@3b647f9c}, android:focusedViewId=100}]}]
09-13 16:34:10.190  6961  6961 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-13 16:34:10.190  6961  6961 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 16:34:10.190  6961  6961 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-13 16:34:10.210  1020  1754 D PersonaManager: isKioskContainerExistOnDevice
,09-13 16:34:11.700  6961  7017 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 16:34:11.700  6961  7017 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@391507cc added. We now have 3 listener(s)
,09-13 16:34:11.700  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-13 16:34:11.700  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:34:11.700  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 16:34:11.700  6961  7017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 16:34:11.700  6961  7017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1caa15 added. We now have 3 listener(s)
09-13 16:34:11.700  6961  7017 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 16:34:11.700  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 16:34:11.710  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:11.710  6961  7017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:34:11.710  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:34:11.710  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:34:11.710  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:34:11.710  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:34:11.710  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:34:11.710  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:34:11.710  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:34:11.710  6961  7017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:34:11.710  6961  7017 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:34:11.710  6961  6961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:11.720  6961  6961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:11.720  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 16:34:11.720  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:34:11.720  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:34:11.720  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 16:34:11.720  6961  7017 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-13 16:34:11.720  6961  7017 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 16:34:11.720  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 16:34:11.720  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:34:11.720  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:34:11.720  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 16:34:11.720  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:11.720  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:11.720  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:34:11.720  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 16:34:11.720  6961  7017 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@391507cc removed from the list
09-13 16:34:11.720  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:11.720  6961  7017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1caa15 removed from the list
09-13 16:34:11.720  6961  7017 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:11.720  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:11.720  6961  7017 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-13 16:34:11.730  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:11.730  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:11.730  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:11.730  6961  7017 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@391507cc not in the list
09-13 16:34:11.730  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:11.730  6961  7017 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1caa15 not in the list
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:11.730  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:11.730  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 16:34:11.730  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:11.730  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:11.730  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:11.730  6961  7017 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@391507cc not in the list
09-13 16:34:11.730  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:11.730  6961  7017 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1caa15 not in the list
09-13 16:34:11.730  6961  7017 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:11.730  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:11.730  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:11.730  6961  7017 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 16:34:11.740  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:11.740  6961  7017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:34:11.740  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:34:11.740  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:34:11.740  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:34:11.740  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:34:11.740  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:34:11.740  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:34:11.740  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:34:11.740  6961  7017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:34:11.740  6961  7017 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:34:11.740  6961  7017 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-13 16:34:11.740  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-13 16:34:11.740  6961  7017 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:34:11.740  6961  7017 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:34:11.740  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:34:11.740  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:11.740  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 16:34:11.750  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:34:11.750  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:34:11.750  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:34:11.750  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:34:11.750  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:11.750  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:34:11.750  6961  6961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:34:11.750  6961  7017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 16:34:11.750  6961  6961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:34:11.750  6961  6961 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:34:11.760  6961  7030 D BluetoothSocket: bindListen(): myUserId = 0
09-13 16:34:11.760  6961  7030 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:34:11.760  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 16:34:11.760  6961  7030 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
09-13 16:34:11.760  6961  7030 D BluetoothSocket: bindListen(), new LocalSocket 
09-13 16:34:11.760  6961  7030 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-13 16:34:11.760  6961  7030 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d2ad291
09-13 16:34:11.760  6961  7030 D BluetoothSocket: channel: 6
09-13 16:34:11.760  6961  7030 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 16:34:11.770  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 16:34:11.770  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 16:34:11.770  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-13 16:34:11.770  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 08 EC A9 50 75 41
09-13 16:34:11.770  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:34:11.770  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:34:11.770  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 16:34:11.780  3406  3415 D BtGatt.GattService: registerClient() - UUID=5ba3fe85-a072-4522-8aec-fb168883fb88
,09-13 16:34:11.820  3406  3466 D BtGatt.GattService: onClientRegistered() - UUID=5ba3fe85-a072-4522-8aec-fb168883fb88, clientIf=6
,09-13 16:34:11.820  6961  6974 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 16:34:11.830  3406  3514 D BtGatt.AdvertiseManager: message : 0
,09-13 16:34:11.830  3406  3514 D BtGatt.AdvertiseManager: number of adv instance running0
,09-13 16:34:11.830  3406  3514 D BtGatt.AdvertiseManager: size of list is =0
,09-13 16:34:11.830  3406  3514 D BtGatt.AdvertiseManager: starting advertising
,09-13 16:34:11.830  3406  3514 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-13 16:34:11.840  3406  3466 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-13 16:34:11.840  3406  3514 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:34:11.840  3406  3466 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-13 16:34:11.840  3406  3514 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-13 16:34:11.850  3406  3514 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-13 16:34:11.850  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 16:34:11.850  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:34:11.850  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:34:11.850  6961  6961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:34:11.850  6961  7017 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 16:34:11.860  6961  6961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 16:34:11.860  6961  6961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 16:34:11.860  6961  6961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 16:34:11.860  6961  6961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-13 16:34:11.860  6961  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:34:11.860  6961  6961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:11.860  6961  6961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:12.360  6961  7017 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 16:34:12.360  6961  7017 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 16:34:12.360  6961  7017 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-13 16:34:12.360  6961  7017 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 16:34:12.360  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:34:12.360  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:34:12.360  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:34:12.360  6961  7017 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@ed9adf7, channel: 6, state: LISTENING
09-13 16:34:12.360  6961  7017 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@ed9adf7, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d2ad291, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@29ba8464mSocket: android.net.LocalSocket@221906cd impl:android.net.LocalSocketImpl@34488b82 fd:FileDescriptor[105]
09-13 16:34:12.360  6961  7017 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@221906cd impl:android.net.LocalSocketImpl@34488b82 fd:FileDescriptor[105]
09-13 16:34:12.360  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 16:34:12.360  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 16:34:12.360  6961  6961 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:34:12.360  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 16:34:12.360  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:34:12.360  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:34:12.360  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 16:34:12.360  6961  7030 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@ed9adf7, channel: 6, state: CLOSED
,09-13 16:34:12.360  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 16:34:12.360  6961  7030 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 16:34:12.360  6961  7030 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 16:34:12.360  6961  7030 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 16:34:12.360  6961  7017 D BluetoothLeScanner: could not find callback wrapper
,09-13 16:34:12.360  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:34:12.360  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 16:34:12.360  3406  3514 D BtGatt.AdvertiseManager: message : 1
09-13 16:34:12.360  3406  3514 D BtGatt.AdvertiseManager: stop advertise for client 6
09-13 16:34:12.360  3406  3514 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,09-13 16:34:12.370  3406  3514 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-13 16:34:12.370  3406  3466 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-13 16:34:12.370  3406  3466 D BtGatt.GattService: Client app is not null!
,09-13 16:34:12.370  3406  3415 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 16:34:12.370  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 16:34:12.380  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-13 16:34:12.380  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 16:34:12.380  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 16:34:12.380  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 16:34:12.380  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:12.380  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 16:34:12.380  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:34:12.380  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:34:12.380  6961  6961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 16:34:12.380  6961  6961 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:34:12.390  6961  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:12.390  6961  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:12.390  6961  6961 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:34:12.390  6961  6961 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-13 16:34:12.390  6961  6961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:34:12.390  6961  7017 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 16:34:12.390  6961  7017 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-13 16:34:12.390  6961  7017 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-13 16:34:12.390  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-13 16:34:12.390  6961  7017 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:34:12.390  6961  7017 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:34:12.390  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:34:12.390  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:12.390  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 16:34:12.390  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 16:34:12.390  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 16:34:12.390  6961  6961 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:34:12.390  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:34:12.390  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:34:12.390  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:12.390  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 16:34:12.400  6961  7017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:34:12.400  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
09-13 16:34:12.410  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 16:34:12.410  6961  7034 D BluetoothSocket: bindListen(): myUserId = 0
,09-13 16:34:12.410  6961  7034 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:34:12.410  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 16:34:12.410  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-13 16:34:12.410  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 08 EC A9 50 75 41,
09-13 16:34:12.410  6961  7034 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
,09-13 16:34:12.410  6961  7034 D BluetoothSocket: bindListen(), new LocalSocket 
09-13 16:34:12.410  6961  7034 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,09-13 16:34:12.410  6961  7034 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@33c42c9
09-13 16:34:12.410  6961  7034 D BluetoothSocket: channel: 6
09-13 16:34:12.410  6961  7034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 16:34:12.410  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:34:12.410  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:34:12.410  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 16:34:12.420  3406  3426 D BtGatt.GattService: registerClient() - UUID=b0463618-f4e4-45c2-9404-3cac69b3c0ce
,09-13 16:34:12.460  3406  3466 D BtGatt.GattService: onClientRegistered() - UUID=b0463618-f4e4-45c2-9404-3cac69b3c0ce, clientIf=6
,09-13 16:34:12.460  6961  6974 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 16:34:12.460  3406  3514 D BtGatt.AdvertiseManager: message : 0,
09-13 16:34:12.460  3406  3514 D BtGatt.AdvertiseManager: number of adv instance running0
,09-13 16:34:12.460  3406  3514 D BtGatt.AdvertiseManager: size of list is =0
09-13 16:34:12.460  3406  3514 D BtGatt.AdvertiseManager: starting advertising
,09-13 16:34:12.460  3406  3514 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-13 16:34:12.470  3406  3466 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,09-13 16:34:12.470  3406  3514 D BtGatt.AdvertiseManager: starting multi advertising,
,09-13 16:34:12.470  3406  3466 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
,09-13 16:34:12.470  3406  3514 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-13 16:34:12.470  3406  3514 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-13 16:34:12.480  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 16:34:12.480  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:34:12.480  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:34:12.480  6961  6961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:34:12.480  6961  6961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 16:34:12.480  6961  6961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-13 16:34:12.480  6961  6961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 16:34:12.480  6961  6961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 16:34:12.480  6961  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:34:12.490  6961  7017 I io.jxcore.node.ConnectionHelper: start: OK,
,09-13 16:34:12.490  6961  6961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:12.490  6961  6961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:12.490  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:12.490  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 16:34:12.490  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:34:12.490  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 16:34:12.490  6961  7017 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3cf264ef, channel: 6, state: LISTENING
,09-13 16:34:12.490  6961  7017 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3cf264ef, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@33c42c9, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@dcffbfcmSocket: android.net.LocalSocket@213d4285 impl:android.net.LocalSocketImpl@93808da fd:FileDescriptor[105]
,09-13 16:34:12.500  6961  7017 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@213d4285 impl:android.net.LocalSocketImpl@93808da fd:FileDescriptor[105]
,09-13 16:34:12.500  6961  7034 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3cf264ef, channel: 6, state: CLOSED
,09-13 16:34:12.500  6961  7034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 16:34:12.500  6961  7034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 16:34:12.500  6961  7034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 16:34:12.500  6961  6961 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:34:12.500  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 16:34:12.500  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:34:12.500  6961  7017 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@391507cc not in the list
09-13 16:34:12.500  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:12.500  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:34:12.500  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:34:12.500  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:34:12.500  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 16:34:12.500  6961  7017 D BluetoothLeScanner: could not find callback wrapper
09-13 16:34:12.500  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:34:12.500  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 16:34:12.500  6961  6961 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:34:12.500  3406  3514 D BtGatt.AdvertiseManager: message : 1
,09-13 16:34:12.500  3406  3514 D BtGatt.AdvertiseManager: stop advertise for client 6
,09-13 16:34:12.500  3406  3514 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,09-13 16:34:12.510  3406  3514 D BtGatt.AdvertiseManager: logClientsSet() - status: -1,
,09-13 16:34:12.510  3406  3466 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-13 16:34:12.510  3406  3466 D BtGatt.GattService: Client app is not null!
,09-13 16:34:12.510  3406  3426 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 16:34:12.510  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 16:34:12.510  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 16:34:12.510  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 16:34:12.510  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 16:34:12.510  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 16:34:12.520  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
09-13 16:34:12.520  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:34:12.520  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:34:12.520  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:34:12.530  6961  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:34:12.530  6961  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:12.530  6961  6961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:12.530  6961  7017 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1caa15 not in the list
09-13 16:34:12.530  6961  7017 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:34:12.530  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:12.530  6961  7017 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-13 16:34:12.530  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:12.540  6961  7017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:34:12.540  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:34:12.540  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:34:12.540  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:34:12.540  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:34:12.540  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:34:12.540  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:34:12.540  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:34:12.540  6961  7017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:34:12.540  6961  7017 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:34:12.540  6961  6961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:12.550  6961  7017 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-13 16:34:12.550  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-13 16:34:12.550  6961  7017 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:34:12.550  6961  7017 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:34:12.550  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:34:12.550  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:12.550  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 16:34:12.550  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 16:34:12.550  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:34:12.550  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:34:12.550  6961  6961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:34:12.550  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:34:12.550  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:12.550  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:34:12.550  6961  6961 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING,
,09-13 16:34:12.550  6961  7017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:34:12.560  6961  7039 D BluetoothSocket: bindListen(): myUserId = 0
,09-13 16:34:12.560  6961  7039 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:34:12.560  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:34:12.560  6961  7039 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
09-13 16:34:12.560  6961  7039 D BluetoothSocket: bindListen(), new LocalSocket 
09-13 16:34:12.560  6961  7039 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-13 16:34:12.560  6961  7039 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@209dd8a6
09-13 16:34:12.560  6961  7039 D BluetoothSocket: channel: 6
09-13 16:34:12.560  6961  7039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 16:34:12.560  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:34:12.560  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 16:34:12.560  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-13 16:34:12.560  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 08 EC A9 50 75 41
,09-13 16:34:12.560  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 16:34:12.570  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:34:12.570  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 16:34:12.570  3406  3512 D BtGatt.GattService: registerClient() - UUID=dbd7cb07-accb-458d-b3eb-73d9ddb81285
,09-13 16:34:12.620  3406  3466 D BtGatt.GattService: onClientRegistered() - UUID=dbd7cb07-accb-458d-b3eb-73d9ddb81285, clientIf=6
,09-13 16:34:12.620  6961  6975 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 16:34:12.620  3406  3514 D BtGatt.AdvertiseManager: message : 0
,09-13 16:34:12.620  3406  3514 D BtGatt.AdvertiseManager: number of adv instance running0
,09-13 16:34:12.620  3406  3514 D BtGatt.AdvertiseManager: size of list is =0
,09-13 16:34:12.620  3406  3514 D BtGatt.AdvertiseManager: starting advertising
,09-13 16:34:12.620  3406  3514 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-13 16:34:12.620  3406  3466 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-13 16:34:12.630  3406  3514 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:34:12.630  3406  3466 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-13 16:34:12.630  3406  3514 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-13 16:34:12.630  3406  3514 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-13 16:34:12.630  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 16:34:12.630  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:34:12.630  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:34:12.640  6961  6961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:34:12.640  6961  6961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 16:34:12.640  6961  6961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 16:34:12.640  6961  6961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 16:34:12.640  6961  6961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-13 16:34:12.640  6961  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:34:12.640  6961  6961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:12.640  6961  6961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:12.640  6961  7017 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 16:34:12.650  6961  7017 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 16:34:12.650  6961  7017 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 16:34:12.650  6961  7017 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-13 16:34:12.650  6961  7017 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 16:34:12.650  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:34:12.650  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:34:12.650  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:34:12.650  6961  7017 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@df9ce94, channel: 6, state: LISTENING
09-13 16:34:12.650  6961  7017 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@df9ce94, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@209dd8a6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2ac63d3dmSocket: android.net.LocalSocket@373ed932 impl:android.net.LocalSocketImpl@1a9be683 fd:FileDescriptor[105]
09-13 16:34:12.650  6961  7017 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@373ed932 impl:android.net.LocalSocketImpl@1a9be683 fd:FileDescriptor[105]
09-13 16:34:12.650  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 16:34:12.650  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:34:12.650  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 16:34:12.650  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:34:12.650  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:34:12.650  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:34:12.650  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 16:34:12.650  6961  7039 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@df9ce94, channel: 6, state: CLOSED
09-13 16:34:12.650  6961  7039 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 16:34:12.650  6961  7039 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:34:12.650  6961  7039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 16:34:12.650  6961  6961 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-13 16:34:12.650  6961  7017 D BluetoothLeScanner: could not find callback wrapper
09-13 16:34:12.650  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:34:12.650  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 16:34:12.650  3406  3514 D BtGatt.AdvertiseManager: message : 1
09-13 16:34:12.650  3406  3514 D BtGatt.AdvertiseManager: stop advertise for client 6
09-13 16:34:12.650  3406  3514 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
09-13 16:34:12.650  3406  3514 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-13 16:34:12.650  3406  3466 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-13 16:34:12.650  3406  3466 D BtGatt.GattService: Client app is not null!
,09-13 16:34:12.660  3406  3512 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 16:34:12.660  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 16:34:12.660  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-13 16:34:12.660  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 16:34:12.660  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-13 16:34:12.660  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 16:34:12.660  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:12.670  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 16:34:12.670  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:34:12.670  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:34:12.670  6961  6961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 16:34:12.670  6961  6961 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:34:12.670  6961  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:34:12.670  6961  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:34:12.670  6961  6961 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 16:34:12.670  6961  6961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:12.670  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:12.670  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:12.680  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:34:12.680  6961  7017 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@391507cc not in the list
,09-13 16:34:12.680  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:34:12.680  6961  7017 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1caa15 not in the list
09-13 16:34:12.680  6961  7017 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:34:12.680  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:12.680  6961  7017 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-13 16:34:12.680  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:12.680  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:12.680  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:12.680  6961  7017 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@391507cc not in the list
09-13 16:34:12.680  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:34:12.680  6961  7017 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1caa15 not in the list
,09-13 16:34:12.680  6961  7017 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:12.680  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:12.680  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:12.680  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming],
09-13 16:34:12.690  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-13 16:34:12.690  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:12.690  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:12.690  6961  7017 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@391507cc not in the list
09-13 16:34:12.690  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:12.690  6961  7017 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1caa15 not in the list
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:12.690  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:12.690  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-13 16:34:12.690  6961  7017 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-13 16:34:12.690  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:12.690  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:12.690  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:12.690  6961  7017 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@391507cc not in the list
,09-13 16:34:12.690  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:12.690  6961  7017 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1caa15 not in the list
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:34:12.690  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:12.690  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:12.690  6961  7017 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-13 16:34:12.690  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:12.690  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:12.690  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:12.690  6961  7017 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@391507cc not in the list
09-13 16:34:12.690  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:12.690  6961  7017 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1caa15 not in the list
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectivityMonitor: stop,
09-13 16:34:12.690  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:12.690  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:12.690  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 16:34:12.690  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 16:34:12.690  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:34:12.690  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 16:34:12.690  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:34:12.690  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:34:12.690  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 16:34:12.690  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:34:12.690  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 16:34:12.690  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:12.690  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:12.690  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:12.690  6961  7017 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@391507cc not in the list
09-13 16:34:12.690  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:12.690  6961  7017 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1caa15 not in the list
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:34:12.690  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:12.690  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:12.690  6961  7017 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:34:12.690  6961  7017 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 16:34:12.690  6961  7017 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:34:12.690  6961  7017 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210],
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 16:34:12.690  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 16:34:12.690  6961  7017 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 16:34:12.690  6961  7017 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 16:34:12.690  6961  7017 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,09-13 16:34:12.690  6961  7017 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:34:12.690  6961  7017 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 16:34:12.690  6961  7017 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 16:34:12.690  6961  7017 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:34:12.690  6961  7017 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 16:34:12.690  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-13 16:34:12.700  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-13 16:34:12.700  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 16:34:12.700  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 16:34:12.700  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 16:34:12.700  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 16:34:12.700  6961  7017 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 16:34:12.700  6961  7017 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:34:12.700  6961  7017 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-13 16:34:12.700  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:12.700  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:12.700  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:12.700  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 16:34:12.700  6961  7043 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1421)
09-13 16:34:12.700  6961  7017 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@391507cc not in the list
,09-13 16:34:12.700  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:12.700  6961  7017 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1caa15 not in the list
09-13 16:34:12.700  6961  7017 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:12.700  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:12.700  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:12.700  6961  7044 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1421
09-13 16:34:12.700  6961  7017 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-13 16:34:12.700  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:12.700  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:12.700  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:12.700  6961  7017 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@391507cc not in the list
09-13 16:34:12.700  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:12.700  6961  7017 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1caa15 not in the list
09-13 16:34:12.700  6961  7017 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:12.700  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:12.700  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:12.700  6961  7017 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 16:34:12.700  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:12.700  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:12.700  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:12.700  6961  7017 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@391507cc not in the list
09-13 16:34:12.700  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:12.700  6961  7017 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1caa15 not in the list
,09-13 16:34:12.700  6961  7017 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:12.700  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:12.700  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:12.700  6961  7017 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 16:34:12.700  6961  7017 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 16:34:12.700  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 16:34:12.700  6961  7017 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 16:34:12.700  6961  7017 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-13 16:34:12.700  6961  7017 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 16:34:12.700  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 16:34:12.700  6961  7017 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 16:34:12.700  6961  7017 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 16:34:12.700  6961  7017 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 16:34:12.700  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 16:34:12.700  6961  7017 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 16:34:12.700  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:12.700  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:12.700  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:12.700  6961  7017 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@391507cc not in the list
09-13 16:34:12.700  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:12.700  6961  7017 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1caa15 not in the list
09-13 16:34:12.700  6961  7017 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:34:12.700  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:12.700  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:12.700  6961  7017 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 16:34:12.710  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:12.710  6961  7043 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-13 16:34:12.710  6961  7043 D BluetoothSocket: connect(): myUserId = 0
09-13 16:34:12.710  6961  7043 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:34:12.710  3406  3512 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:34:12.710  6961  7043 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
,09-13 16:34:12.710  6961  7017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:34:12.710  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:34:12.710  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:34:12.710  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:34:12.710  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:34:12.710  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:34:12.710  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:34:12.710  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:34:12.720  6961  7017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:34:12.720  6961  7017 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:34:12.720  6961  7017 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
,09-13 16:34:12.720  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-13 16:34:12.720  6961  7017 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:34:12.720  6961  7017 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:34:12.720  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:34:12.720  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:12.720  6961  6961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:12.720  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 16:34:12.720  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:34:12.720  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:34:12.720  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 16:34:12.720  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:34:12.720  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:12.720  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 16:34:12.730  6961  6961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:34:12.730  6961  6961 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 16:34:12.730  6961  7017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:34:12.730  6961  7045 D BluetoothSocket: bindListen(): myUserId = 0
09-13 16:34:12.730  6961  7045 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:34:12.730  6961  7045 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[107]}
09-13 16:34:12.730  6961  7045 D BluetoothSocket: bindListen(), new LocalSocket 
09-13 16:34:12.730  6961  7045 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-13 16:34:12.730  6961  7045 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@232c67df
09-13 16:34:12.730  6961  7045 D BluetoothSocket: channel: 6
09-13 16:34:12.730  6961  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 16:34:12.730  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:34:12.730  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:34:12.740  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 16:34:12.740  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-13 16:34:12.740  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 08 EC A9 50 75 41
09-13 16:34:12.740  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:34:12.740  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:34:12.740  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 16:34:12.740  3406  3426 D BtGatt.GattService: registerClient() - UUID=8757f044-8362-4d37-b562-b0d434799450
,09-13 16:34:12.780  3406  3466 D BtGatt.GattService: onClientRegistered() - UUID=8757f044-8362-4d37-b562-b0d434799450, clientIf=6,
09-13 16:34:12.780  6961  6974 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
09-13 16:34:12.780  3406  3514 D BtGatt.AdvertiseManager: message : 0
,09-13 16:34:12.780  3406  3514 D BtGatt.AdvertiseManager: number of adv instance running0
09-13 16:34:12.780  3406  3514 D BtGatt.AdvertiseManager: size of list is =0
09-13 16:34:12.780  3406  3514 D BtGatt.AdvertiseManager: starting advertising,
09-13 16:34:12.780  3406  3514 D BtGatt.AdvertiseManager: isStandardAdvfalse,
,09-13 16:34:12.790  3406  3466 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
09-13 16:34:12.790  3406  3514 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:34:12.790  3406  3466 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
09-13 16:34:12.790  3406  3514 D BtGatt.AdvertiseManager: logClientsSet() - status: 0,
09-13 16:34:12.790  3406  3514 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-13 16:34:12.790  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING,
09-13 16:34:12.790  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:34:12.800  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:34:12.800  6961  6961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:34:12.800  6961  6961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 16:34:12.800  6961  6961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 16:34:12.800  6961  6961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 16:34:12.800  6961  6961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-13 16:34:12.800  6961  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:34:12.800  6961  6961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:12.800  6961  6961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:12.810  6961  7017 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 16:34:12.810  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:12.810  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:34:12.810  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:34:12.810  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:34:12.810  6961  7017 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@30acd6f5, channel: 6, state: LISTENING
09-13 16:34:12.810  6961  7017 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@30acd6f5, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@232c67df, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@19945c8amSocket: android.net.LocalSocket@3519a2fb impl:android.net.LocalSocketImpl@34b50f18 fd:FileDescriptor[107]
09-13 16:34:12.810  6961  7017 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3519a2fb impl:android.net.LocalSocketImpl@34b50f18 fd:FileDescriptor[107]
09-13 16:34:12.810  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 16:34:12.810  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:34:12.810  6961  7017 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@391507cc not in the list
09-13 16:34:12.810  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:12.810  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:34:12.810  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:34:12.810  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:34:12.810  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 16:34:12.810  6961  7045 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@30acd6f5, channel: 6, state: CLOSED
09-13 16:34:12.810  6961  7045 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 16:34:12.810  6961  7045 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:34:12.810  6961  7045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 16:34:12.810  6961  6961 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-13 16:34:12.810  6961  7017 D BluetoothLeScanner: could not find callback wrapper
09-13 16:34:12.810  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:34:12.810  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 16:34:12.810  3406  3514 D BtGatt.AdvertiseManager: message : 1
,09-13 16:34:12.810  3406  3514 D BtGatt.AdvertiseManager: stop advertise for client 6
,09-13 16:34:12.810  3406  3514 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,09-13 16:34:12.810  3406  3514 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-13 16:34:12.820  3406  3466 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-13 16:34:12.820  3406  3466 D BtGatt.GattService: Client app is not null!
,09-13 16:34:12.820  3406  3426 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 16:34:12.820  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 16:34:12.820  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 16:34:12.820  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 16:34:12.820  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 16:34:12.820  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 16:34:12.820  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:12.820  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 16:34:12.830  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:34:12.830  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:34:12.830  6961  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:34:12.830  6961  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:34:12.830  6961  6961 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:34:12.830  6961  6961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:34:12.830  6961  7017 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1caa15 not in the list
09-13 16:34:12.830  6961  7017 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:12.830  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:12.830  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:12.830  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:12.830  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:12.830  6961  7017 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@391507cc not in the list
09-13 16:34:12.830  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:12.830  6961  7017 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1caa15 not in the list
09-13 16:34:12.830  6961  7017 D io.jxcore.node.ConnectivityMonitor: stop,
09-13 16:34:12.830  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:12.830  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:12.840  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 16:34:12.840  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:12.840  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 16:34:12.840  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 16:34:12.840  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:34:12.840  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:34:12.840  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 16:34:12.840  6961  6961 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:34:12.840  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:12.840  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:34:12.840  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:34:12.840  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:34:12.840  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:12.840  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:34:12.840  6961  6961 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-13 16:34:12.840  6961  7017 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@391507cc not in the list
09-13 16:34:12.840  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:12.840  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:34:12.840  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:34:12.840  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:34:12.840  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:12.840  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:12.840  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:12.840  6961  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:12.840  6961  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:12.840  6961  6961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:34:12.840  6961  7017 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1caa15 not in the list
09-13 16:34:12.840  6961  7017 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:12.840  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:12.840  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:12.840  6961  7017 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-13 16:34:12.840  6961  7049 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:34:12.840  6961  7049 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:34:12.850  6961  7017 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 16:34:12.850  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 16:34:12.850  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:34:12.850  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:34:12.850  6961  6961 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 16:34:12.850  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:12.850  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:12.850  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:12.850  6961  7017 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@391507cc not in the list
09-13 16:34:12.850  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:12.850  6961  7017 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1caa15 not in the list
09-13 16:34:12.850  6961  7017 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:12.850  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:12.850  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:12.850  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:12.850  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:12.850  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:12.850  6961  7017 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@391507cc not in the list
09-13 16:34:12.850  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:12.850  6961  7017 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1caa15 not in the list
09-13 16:34:12.850  6961  7017 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:34:12.850  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:12.850  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:12.850  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:12.850  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:12.850  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:12.850  6961  7017 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@391507cc not in the list
,09-13 16:34:12.850  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:12.850  6961  7017 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1caa15 not in the list
09-13 16:34:12.850  6961  7017 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:12.850  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-13 16:34:12.850  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:12.850  6961  7017 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 16:34:12.850  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left,
09-13 16:34:12.850  6961  7017 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,09-13 16:34:12.850  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left,
09-13 16:34:12.850  6961  7017 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 16:34:12.850  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-13 16:34:12.850  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 16:34:12.850  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-13 16:34:12.860  6961  7017 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-13 16:34:12.860  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 16:34:12.860  6961  7017 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-13 16:34:12.860  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-13 16:34:12.860  6961  7017 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-13 16:34:12.860  6961  7017 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 16:34:12.860  6961  7017 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed,
09-13 16:34:12.860  6961  7017 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-13 16:34:12.860  6961  7017 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 16:34:12.860  6961  7017 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 16:34:12.860  6961  7017 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 16:34:12.860  6961  7017 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-13 16:34:12.860  6961  7050 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-13 16:34:12.860  6961  7050 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 16:34:12.870   278   978 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-13 16:34:12.870   278   978 D Netd    : getNetworkForDns: using netid 502 for uid 10170
,09-13 16:34:12.870  6961  7050 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-13 16:34:12.870  6961  7050 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-13 16:34:12.870  6961  7050 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:34:12.870  6961  7050 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:34:12.870  6961  7052 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-13 16:34:12.870  6961  7050 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-13 16:34:12.870  6961  7052 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:34:12.870  6961  7052 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:34:12.870  6961  7055 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1474, name: OutgoingSocketThread/Sender)
,09-13 16:34:12.870  6961  7052 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:34:12.880  6961  7052 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 16:34:12.880  6961  7056 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1475, name: OutgoingSocketThread/Receiver)
09-13 16:34:12.880  6961  7058 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1477, name: IncomingSocketThread/Receiver)
09-13 16:34:12.880  6961  7056 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1475, thread name: OutgoingSocketThread/Receiver)
09-13 16:34:12.880  6961  7056 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 16:34:12.880  6961  7058 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1477, thread name: IncomingSocketThread/Receiver)
09-13 16:34:12.880  6961  7056 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1475, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-13 16:34:12.880  6961  7058 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 16:34:12.880  6961  7058 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1477, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-13 16:34:12.880  6961  7057 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1476, name: IncomingSocketThread/Sender)
,09-13 16:34:13.030  1020  1046 W ActivityManager: mDVFSHelper.release(),
,09-13 16:34:13.110   288   288 E SMD     : DCD OFF,
,09-13 16:34:13.350  6961  6961 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,09-13 16:34:13.370  6961  7017 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-13 16:34:13.370  6961  7017 D io.jxcore.node.LifeCycleMonitor: onActivityResumed,
,09-13 16:34:13.370  6961  7017 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1334ab9c Bundle[{}],
09-13 16:34:13.370  6961  7017 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 16:34:13.370  6961  7017 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-13 16:34:13.370  6961  7017 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-13 16:34:13.380  6961  7017 D io.jxcore.node.LifeCycleMonitor: onActivityStopped,
09-13 16:34:13.380  6961  7017 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-13 16:34:13.380  6961  7017 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 16:34:13.380  6961  7059 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-13 16:34:13.380  6961  7059 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 16:34:13.890  6961  7059 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-13 16:34:13.890  6961  7059 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...,
09-13 16:34:13.890  6961  7059 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:34:13.890  6961  7059 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:34:13.890  6961  7061 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-13 16:34:13.890  6961  7061 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:34:13.890  6961  7061 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:34:13.890  6961  7059 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-13 16:34:13.890  6961  7063 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1488, name: OutgoingSocketThread/Sender)
09-13 16:34:13.890  6961  7061 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:34:13.890  6961  7061 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 16:34:13.890  6961  7064 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1489, name: OutgoingSocketThread/Receiver)
,09-13 16:34:13.890  6961  7064 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1489, thread name: OutgoingSocketThread/Receiver)
09-13 16:34:13.890  6961  7064 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 16:34:13.890  6961  7064 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1489, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-13 16:34:13.900  6961  7066 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1491, name: IncomingSocketThread/Receiver)
09-13 16:34:13.900  6961  7066 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1491, thread name: IncomingSocketThread/Receiver)
09-13 16:34:13.900  6961  7066 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 16:34:13.900  6961  7066 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1491, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192,
09-13 16:34:13.900  6961  7065 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1490, name: IncomingSocketThread/Sender)
,09-13 16:34:14.030  1020  3487 D SSRM:n  : SIOP:: AP = 340
,09-13 16:34:14.390  6961  7017 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1500),
09-13 16:34:14.390  6961  7017 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-13 16:34:14.390  6961  7017 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1501)
09-13 16:34:14.390  6961  7017 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 16:34:14.390  6961  7017 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a63b756 added. We now have 3 listener(s)
,09-13 16:34:14.400  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-13 16:34:14.400  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
,09-13 16:34:14.400  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 16:34:14.400  6961  7017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 16:34:14.400  6961  7017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d573d7 added. We now have 3 listener(s)
,09-13 16:34:14.400  6961  7017 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 16:34:14.400  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 16:34:14.410  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:34:14.410  6961  7017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:34:14.410  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:34:14.410  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:34:14.410  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:34:14.410  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:34:14.410  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:34:14.410  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:34:14.410  6961  7017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:34:14.410  6961  7017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:34:14.410  6961  7017 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:34:14.420  6961  6961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:14.420  6961  6961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:14.420  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:14.420  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:14.420  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:34:14.420  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-13 16:34:14.430  6961  7017 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a63b756 removed from the list
,09-13 16:34:14.430  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:14.430  6961  7017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d573d7 removed from the list
,09-13 16:34:14.430  6961  7017 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:14.430  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:14.430  6961  7017 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
,09-13 16:34:14.430  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,09-13 16:34:14.430  6961  7017 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:34:14.430  6961  7017 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-13 16:34:14.430  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections,
,09-13 16:34:14.430  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
09-13 16:34:14.430  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 16:34:14.430  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:34:14.430  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:34:14.440  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:34:14.440  6961  6961 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:34:14.440  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:34:14.440  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:14.440  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 16:34:14.440  6961  7017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:34:14.440  6961  7067 D BluetoothSocket: bindListen(): myUserId = 0
09-13 16:34:14.440  6961  7067 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:34:14.450  6961  7067 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[104]},
09-13 16:34:14.450  6961  7067 D BluetoothSocket: bindListen(), new LocalSocket 
09-13 16:34:14.450  6961  7067 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,09-13 16:34:14.450  6961  7067 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@efbf2e2
09-13 16:34:14.450  6961  7067 D BluetoothSocket: channel: 6
09-13 16:34:14.450  6961  7067 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 16:34:14.450  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:34:14.450  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:34:14.450  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 16:34:14.450  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-13 16:34:14.450  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 08 EC A9 50 75 41
,09-13 16:34:14.450  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 16:34:14.450  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:34:14.450  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 16:34:14.460  3406  3512 D BtGatt.GattService: registerClient() - UUID=77ea996f-c267-42ad-815e-da3678c539d8
,09-13 16:34:14.500  3406  3466 D BtGatt.GattService: onClientRegistered() - UUID=77ea996f-c267-42ad-815e-da3678c539d8, clientIf=6
,09-13 16:34:14.500  6961  6974 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 16:34:14.500  3406  3514 D BtGatt.AdvertiseManager: message : 0
,09-13 16:34:14.500  3406  3514 D BtGatt.AdvertiseManager: number of adv instance running0
,09-13 16:34:14.500  3406  3514 D BtGatt.AdvertiseManager: size of list is =0
,09-13 16:34:14.500  3406  3514 D BtGatt.AdvertiseManager: starting advertising
,09-13 16:34:14.500  3406  3514 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-13 16:34:14.510  3406  3466 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-13 16:34:14.510  3406  3514 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:34:14.510  3406  3466 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-13 16:34:14.510  3406  3514 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-13 16:34:14.510  3406  3514 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-13 16:34:14.510  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 16:34:14.520  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:34:14.520  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:34:14.520  6961  6961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:34:14.520  6961  6961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 16:34:14.520  6961  6961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-13 16:34:14.520  6961  6961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 16:34:14.520  6961  6961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 16:34:14.520  6961  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:34:14.530  6961  6961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:14.530  6961  6961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:15.030  6961  6961 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 16:34:15.030  6961  6961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-13 16:34:15.030  6961  6961 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:34:15.150   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 16:34:15.240  1020  3505 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-13 16:34:16.120   288   288 E SMD     : DCD OFF,
,09-13 16:34:16.150   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 16:34:17.140   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 16:34:17.230  1020  3770 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
09-13 16:34:17.230  1020  3770 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 16:34:17.230  1020  3770 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-13 16:34:17.230  1020  3770 D BatteryService: stay LED for charging
09-13 16:34:17.230  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 16:34:17.240  1020  1020 I MotionRecognitionService: Plugged
09-13 16:34:17.240  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 16:34:17.240  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 16:34:17.240  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 16:34:17.240  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-13 16:34:17.240  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 16:34:17.260  3406  3406 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 16:34:17.260  3406  3517 D HeadsetStateMachine: Disconnected process message: 10
,09-13 16:34:17.270  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 16:34:17.270  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 16:34:17.270  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 16:34:18.030  6961  7017 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything,
09-13 16:34:18.030  6961  7017 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 16:34:18.030  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:34:18.030  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 16:34:18.030  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:34:18.030  6961  7017 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@52a930, channel: 6, state: LISTENING
09-13 16:34:18.030  6961  7017 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@52a930, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@efbf2e2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1dded9a9mSocket: android.net.LocalSocket@1fea5b2e impl:android.net.LocalSocketImpl@322506cf fd:FileDescriptor[104]
,09-13 16:34:18.030  6961  7017 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1fea5b2e impl:android.net.LocalSocketImpl@322506cf fd:FileDescriptor[104]
09-13 16:34:18.030  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:34:18.030  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 16:34:18.030  6961  7067 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@52a930, channel: 6, state: CLOSED
09-13 16:34:18.030  6961  7067 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
09-13 16:34:18.030  6961  7067 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:34:18.030  6961  7067 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:34:18.030  6961  6961 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
09-13 16:34:18.030  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 16:34:18.030  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:34:18.030  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:34:18.030  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:34:18.030  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 16:34:18.030  6961  7017 D BluetoothLeScanner: could not find callback wrapper
09-13 16:34:18.030  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 16:34:18.030  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 16:34:18.030  3406  3514 D BtGatt.AdvertiseManager: message : 1
09-13 16:34:18.030  3406  3514 D BtGatt.AdvertiseManager: stop advertise for client 6
09-13 16:34:18.030  3406  3514 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
09-13 16:34:18.040  3406  3514 D BtGatt.AdvertiseManager: logClientsSet() - status: -1,
09-13 16:34:18.040  3406  3466 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-13 16:34:18.040  3406  3466 D BtGatt.GattService: Client app is not null!
09-13 16:34:18.040  3406  3415 D BtGatt.GattService: unregisterClient() - clientIf=6
09-13 16:34:18.040  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 16:34:18.040  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 16:34:18.040  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 16:34:18.040  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 16:34:18.040  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 16:34:18.050  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:34:18.050  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:34:18.050  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:34:18.050  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:18.050  6961  6961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
,09-13 16:34:18.050  6961  6961 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-13 16:34:18.050  6961  6961 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:34:18.050  6961  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:18.060  6961  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:34:18.060  6961  6961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:34:18.060  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:18.060  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:18.060  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:18.060  6961  7017 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a63b756 not in the list
09-13 16:34:18.060  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:18.060  6961  7017 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d573d7 not in the list
09-13 16:34:18.060  6961  7017 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:18.060  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:18.060  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:18.060  6961  7017 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:34:18.060  6961  7017 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:34:18.060  6961  7017 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 16:34:18.060  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 16:34:18.060  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:18.060  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 16:34:18.060  6961  7017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:34:18.070  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:34:18.070  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:34:18.070  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-13 16:34:18.080  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-13 16:34:18.080  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 16:34:18.080  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-13 16:34:18.080  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 16:34:18.080  3406  3415 D BtGatt.GattService: registerClient() - UUID=f1488311-741e-4917-8752-45afe96afced
,09-13 16:34:18.130  3406  3466 D BtGatt.GattService: onClientRegistered() - UUID=f1488311-741e-4917-8752-45afe96afced, clientIf=6
,09-13 16:34:18.130  6961  6975 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-13 16:34:18.130  3406  3426 D BtGatt.GattService: start scan with filters
,09-13 16:34:18.130  3406  3515 D BtGatt.ScanManager: handling starting scan
,09-13 16:34:18.130  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 16:34:18.130  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-13 16:34:18.130  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-13 16:34:18.130  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 16:34:18.140  3406  3515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f2d07be
,09-13 16:34:18.140  3406  3466 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-13 16:34:18.140  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 16:34:18.140  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:34:18.140  6961  6961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 16:34:18.140  3406  3466 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:34:18.140  3406  3515 D BtGatt.ScanManager: allow scan with filters
09-13 16:34:18.140  3406  3515 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-13 16:34:18.140  3406  3515 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-13 16:34:18.140   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 16:34:18.140  3406  3466 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-13 16:34:18.140  3406  3466 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:34:18.140  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:34:18.140  3406  3515 D BtGatt.ScanManager: Starting BLE batch scan
,09-13 16:34:18.140  3406  3515 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-13 16:34:18.150  3406  3466 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-13 16:34:18.150  3406  3466 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,09-13 16:34:18.150  3406  3466 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-13 16:34:18.150  3406  3466 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:34:18.650  6961  6961 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-13 16:34:18.650  6961  6961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 16:34:18.650  6961  6961 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:34:18.650  1020  1099 V AlarmManager: waitForAlarm result :4
,09-13 16:34:18.660  1020  1020 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,09-13 16:34:18.660  3406  3406 D BtGatt.ScanManager: awakened up at time 127514
,09-13 16:34:18.660  1020  1020 V AlarmManagerEXT: <AppSync3 Whitelist>
,09-13 16:34:18.660  1020  1020 V AlarmManagerEXT: (AppSync) ### 0 added ###
,09-13 16:34:18.670  3406  3406 D BtGatt.ScanManager: awakened up at time 127520
,09-13 16:34:18.670  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
09-13 16:34:18.670  1177  1177 D KeyguardUpdateMonitor: handleTimeUpdate
,09-13 16:34:18.670  3406  3515 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 16:34:18.680  3406  3466 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-13 16:34:18.680  3406  3466 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:34:18.680  1177  1177 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-13 16:34:18.690  1177  1177 D SecKeyguardClockView: HomeTimezone(): 1
,09-13 16:34:18.690  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 16:34:18.690  1177  1177 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,09-13 16:34:18.690  1177  1177 I KeyguardEffectViewController: *** don't update sliding image ***
,09-13 16:34:18.710  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 16:34:18.730  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 16:34:18.740  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 16:34:18.760  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 16:34:19.120   288   288 E SMD     : DCD OFF
,09-13 16:34:19.140   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 16:34:19.180  1020  1099 V AlarmManager: waitForAlarm result :4
,09-13 16:34:19.180  3406  3406 D BtGatt.ScanManager: awakened up at time 128038
,09-13 16:34:19.190  3406  3406 D BtGatt.ScanManager: awakened up at time 128042
,09-13 16:34:19.190  3406  3515 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 16:34:19.190  3406  3466 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-13 16:34:19.190  3406  3466 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:34:19.690  1020  1099 V AlarmManager: waitForAlarm result :4
,09-13 16:34:19.690  3406  3406 D BtGatt.ScanManager: awakened up at time 128549
,09-13 16:34:19.700  3406  3406 D BtGatt.ScanManager: awakened up at time 128552
,09-13 16:34:19.700  3406  3515 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 16:34:19.700  3406  3466 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-13 16:34:19.700  3406  3466 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:34:20.140   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-13 16:34:20.210  1020  1099 V AlarmManager: waitForAlarm result :4
,09-13 16:34:20.210  3406  3406 D BtGatt.ScanManager: awakened up at time 129063
,09-13 16:34:20.210  3406  3406 D BtGatt.ScanManager: awakened up at time 129065
,09-13 16:34:20.210  3406  3515 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 16:34:20.210  3406  3466 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-13 16:34:20.210  3406  3466 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:34:20.300  3406  3467 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-13 16:34:20.300  3406  3467 E bt-btif : DISCOVERY_COMP_EVT slot id:7, failed to find channle,                                       status:1, scn:0
,09-13 16:34:20.300  3406  3507 W bt-btif : invalid rfc slot id: 7
,09-13 16:34:20.300  6961  7043 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@241540eb, channel: -1, state: INIT
,09-13 16:34:20.300  6961  7043 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@241540eb, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@37966e48, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@145714e1mSocket: android.net.LocalSocket@3876a206 impl:android.net.LocalSocketImpl@68500c7 fd:FileDescriptor[106]
,09-13 16:34:20.300  6961  7043 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3876a206 impl:android.net.LocalSocketImpl@68500c7 fd:FileDescriptor[106]
,09-13 16:34:20.300  6961  7043 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1421),
,09-13 16:34:20.720  1020  1099 V AlarmManager: waitForAlarm result :4
,09-13 16:34:20.720  3406  3406 D BtGatt.ScanManager: awakened up at time 129572
,09-13 16:34:20.720  3406  3406 D BtGatt.ScanManager: awakened up at time 129575
,09-13 16:34:20.720  3406  3515 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 16:34:20.730  3406  3466 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-13 16:34:20.730  3406  3466 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:34:21.160  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:21.160  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:34:21.160  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:34:21.160  6961  7017 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a63b756 not in the list
,09-13 16:34:21.160  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:21.160  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 16:34:21.160  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 16:34:21.160  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 16:34:21.160  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 16:34:21.160  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 16:34:21.160  3406  3415 D BtGatt.GattService: stopScan() - queue size =1,
,09-13 16:34:21.160  3406  3515 D BtGatt.ScanManager: filter size is 1
,09-13 16:34:21.170  3406  3515 D BtGatt.ScanManager: delete FilterIndex - 3
,09-13 16:34:21.170  3406  3512 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 16:34:21.170  3406  3466 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-13 16:34:21.170  3406  3466 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 16:34:21.170  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:34:21.170  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 16:34:21.170  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 16:34:21.170  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 16:34:21.170  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 16:34:21.170  3406  3515 D BtGatt.ScanManager: stopping BLe Batch
,09-13 16:34:21.170  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:21.170  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
09-13 16:34:21.170  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:34:21.170  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:34:21.170  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:21.180  6961  7017 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d573d7 not in the list,
09-13 16:34:21.180  6961  7017 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:21.180  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,09-13 16:34:21.180  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:21.180  6961  7017 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
09-13 16:34:21.180  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
09-13 16:34:21.180  6961  7017 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:34:21.180  6961  7017 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:34:21.180  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:34:21.180  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:21.180  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 16:34:21.180  6961  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:21.180  6961  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:21.180  6961  6961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:21.180  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:34:21.180  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:34:21.180  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 16:34:21.180  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:34:21.180  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:21.180  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 16:34:21.180  6961  6961 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 16:34:21.190  3406  3466 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-13 16:34:21.190  3406  3466 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 16:34:21.190  3406  3515 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 16:34:21.190  6961  7017 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:34:21.190  6961  7075 D BluetoothSocket: bindListen(): myUserId = 0
09-13 16:34:21.190  6961  7075 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:34:21.190  3406  3466 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
,09-13 16:34:21.190  3406  3466 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:34:21.190  3406  3466 D BtGatt.GattService: current time is 130049310938
,09-13 16:34:21.200  3406  3466 D BtGatt.GattService: Batch record : [86, -31, -99, 30, -52, -57, 1, 0, -94, -40, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 36, -115, 113, 6, -73, -88, 58, 61, -48, 68, 1, 3, 2, -29, 20, 62, -74, -3, 19, 28, 6, 8, 116, 105, 115, 55, 48, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
,09-13 16:34:21.200  6961  7075 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[110]}
09-13 16:34:21.200  6961  7075 D BluetoothSocket: bindListen(), new LocalSocket 
09-13 16:34:21.200  6961  7075 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,09-13 16:34:21.200  6961  7075 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10cad892
,09-13 16:34:21.200  6961  7075 D BluetoothSocket: channel: 6
09-13 16:34:21.200  6961  7075 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 16:34:21.200  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:34:21.200  3406  3466 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 36, -115, 113, 6, -73, -88, 58, 61, -48, 68, 1, 3, 2, -29, 20, 62, -74, -3, 19, 6, 8, 116, 105, 115, 55, 48, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
,09-13 16:34:21.200  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:34:21.210  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 16:34:21.210  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-13 16:34:21.210  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 08 EC A9 50 75 41
,09-13 16:34:21.210  3406  3466 D ScanRecord: parseFromBytes
,09-13 16:34:21.210  3406  3466 D ScanRecord: first manudata for manu ID
,09-13 16:34:21.210  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 16:34:21.210  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 8, -20, -87, 80, 117, 65]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 16:34:21.210  6961  7017 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 16:34:21.210  3406  3512 D BtGatt.GattService: registerClient() - UUID=820a2b60-817c-4476-b1bb-cb674032ba8d
,09-13 16:34:21.260  3406  3466 D BtGatt.GattService: onClientRegistered() - UUID=820a2b60-817c-4476-b1bb-cb674032ba8d, clientIf=6
,09-13 16:34:21.260  6961  6975 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 16:34:21.260  3406  3514 D BtGatt.AdvertiseManager: message : 0
,09-13 16:34:21.260  3406  3514 D BtGatt.AdvertiseManager: number of adv instance running0
,09-13 16:34:21.260  3406  3514 D BtGatt.AdvertiseManager: size of list is =0
,09-13 16:34:21.260  3406  3514 D BtGatt.AdvertiseManager: starting advertising
,09-13 16:34:21.260  3406  3514 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-13 16:34:21.270  3406  3466 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-13 16:34:21.280  3406  3514 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:34:21.280  3406  3466 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-13 16:34:21.280  3406  3514 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-13 16:34:21.280  3406  3514 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-13 16:34:21.280  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 16:34:21.280  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:34:21.280  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:34:21.290  6961  6961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:34:21.290  6961  6961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 16:34:21.290  6961  6961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-13 16:34:21.290  6961  6961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 16:34:21.290  6961  6961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-13 16:34:21.290  6961  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:34:21.290  6961  6961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:21.290  6961  6961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:34:21.800  6961  6961 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 16:34:21.800  6961  6961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 16:34:21.800  6961  6961 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:34:22.120   288   288 E SMD     : DCD OFF
,09-13 16:34:24.050  1020  3487 D SSRM:n  : SIOP:: AP = 320,
,09-13 16:34:24.300  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:24.300  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:34:24.300  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...,
09-13 16:34:24.300  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:34:24.300  6961  7017 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2dbabe60, channel: 6, state: LISTENING
,09-13 16:34:24.300  6961  7017 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2dbabe60, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10cad892, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3cc47f19mSocket: android.net.LocalSocket@24b9ebde impl:android.net.LocalSocketImpl@14bb41bf fd:FileDescriptor[110]
09-13 16:34:24.300  6961  7017 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@24b9ebde impl:android.net.LocalSocketImpl@14bb41bf fd:FileDescriptor[110]
09-13 16:34:24.300  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:34:24.300  6961  7017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:34:24.300  6961  7075 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2dbabe60, channel: 6, state: CLOSED,
09-13 16:34:24.300  6961  7017 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a63b756 not in the list
09-13 16:34:24.300  6961  7075 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 16:34:24.300  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:24.300  6961  7075 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:34:24.300  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 16:34:24.300  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:34:24.300  6961  7075 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:34:24.300  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:34:24.300  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 16:34:24.300  6961  6961 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:34:24.300  6961  6961 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:34:24.300  6961  7017 D BluetoothLeScanner: could not find callback wrapper
09-13 16:34:24.300  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 16:34:24.300  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 16:34:24.300  3406  3514 D BtGatt.AdvertiseManager: message : 1
09-13 16:34:24.300  3406  3514 D BtGatt.AdvertiseManager: stop advertise for client 6
09-13 16:34:24.300  3406  3514 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
09-13 16:34:24.300  3406  3514 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-13 16:34:24.310  3406  3466 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
09-13 16:34:24.310  3406  3466 D BtGatt.GattService: Client app is not null!
,09-13 16:34:24.310  3406  3512 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 16:34:24.320  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 16:34:24.320  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-13 16:34:24.320  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 16:34:24.320  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-13 16:34:24.320  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 16:34:24.320  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:24.320  6961  7017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 16:34:24.320  6961  7017 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:34:24.320  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:24.330  6961  7017 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d573d7 not in the list
09-13 16:34:24.330  6961  7017 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:24.330  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:24.330  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:24.330  6961  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:24.330  6961  7017 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:24.330  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:24.330  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:24.330  6961  7017 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a63b756 not in the list
09-13 16:34:24.330  6961  7017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:24.330  6961  7017 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d573d7 not in the list
09-13 16:34:24.330  6961  7017 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:24.330  6961  7017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:24.330  6961  7017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:34:24.330  6961  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:24.330  6961  7017 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-13 16:34:24.330  6961  7017 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 16:34:24.330  6961  7017 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-13 16:34:24.330  6961  7017 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:34:24.330  6961  7017 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-13 16:34:24.330  6961  7017 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 16:34:24.330  6961  6961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:34:24.340  6961  7080 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1521, name: My test thread name)
,09-13 16:34:24.840  6961  6961 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,09-13 16:34:25.120   288   288 E SMD     : DCD OFF,
,09-13 16:34:26.340  6961  7017 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 1521
,09-13 16:34:26.340  6961  7017 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 1521, name: My test thread name)
,09-13 16:34:26.340  6961  7081 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1522, name: My test thread name)
09-13 16:34:26.340  6961  7081 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1522, thread name: My test thread name)
09-13 16:34:26.340  6961  7081 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1522, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-13 16:34:26.340  6961  7017 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:34:26.340  6961  7082 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1526, name: My test thread name)
09-13 16:34:26.340  6961  7082 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 1526, thread name: My test thread name): Test exception.
09-13 16:34:26.340  6961  7082 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1526, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-13 16:34:26.340  6961  7017 I jxcore-log: Total number of executed tests:  76
09-13 16:34:26.340  6961  7017 I jxcore-log: 
09-13 16:34:26.340  6961  7017 I jxcore-log: Number of passed tests:  76
09-13 16:34:26.340  6961  7017 I jxcore-log: 
,09-13 16:34:26.340  6961  7017 I jxcore-log: Number of failed tests:  0
09-13 16:34:26.340  6961  7017 I jxcore-log: 
,09-13 16:34:26.350  6961  7017 I jxcore-log: Number of ignored tests:  0
09-13 16:34:26.350  6961  7017 I jxcore-log: 
09-13 16:34:26.350  6961  7017 I jxcore-log: Total duration:  14646
09-13 16:34:26.350  6961  7017 I jxcore-log: 
09-13 16:34:26.350  6961  7017 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 16:34:26.350  6961  7017 I jxcore-log: 
09-13 16:34:26.350  6961  7017 I jxcore-log: My device name is: samsung-SM-A300FU
09-13 16:34:26.350  6961  7017 I jxcore-log: 
09-13 16:34:26.350  6961  7017 I jxcore-log: WARN testUtils: myNameCallback not set!
09-13 16:34:26.350  6961  7017 I jxcore-log: 
,09-13 16:34:26.360  6961  7017 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:26.360  6961  7017 I jxcore-log: 
09-13 16:34:26.360  6961  7017 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:26.360  6961  7017 I jxcore-log: 
09-13 16:34:26.360  6961  7017 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:26.360  6961  7017 I jxcore-log: 
09-13 16:34:26.370  6961  7017 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 16:34:26.370  6961  7017 I jxcore-log: 
09-13 16:34:26.370  6961  7017 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:26.370  6961  7017 I jxcore-log: 
09-13 16:34:26.370  6961  7017 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:26.370  6961  7017 I jxcore-log: 
09-13 16:34:26.370  6961  7017 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 16:34:26.370  6961  7017 I jxcore-log: 
09-13 16:34:26.370  6961  7017 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:26.370  6961  7017 I jxcore-log: 
09-13 16:34:26.380  6961  7017 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 16:34:26.380  6961  7017 I jxcore-log: 
09-13 16:34:26.380  6961  7017 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-13 16:34:26.380  6961  7017 I jxcore-log: 
09-13 16:34:26.380  6961  7017 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 16:34:26.380  6961  7017 I jxcore-log: 
09-13 16:34:26.380  6961  7017 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 16:34:26.380  6961  7017 I jxcore-log: 
,09-13 16:34:26.480  6961  7080 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1521, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154,
,09-13 16:34:26.640  7083  7083 D AndroidRuntime: ,
09-13 16:34:26.640  7083  7083 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-13 16:34:26.640  7083  7083 D AndroidRuntime: CheckJNI is OFF,
09-13 16:34:26.640  7083  7083 D AndroidRuntime: readGMSProperty: start
09-13 16:34:26.640  7083  7083 D AndroidRuntime: readGMSProperty: already setted!!
,09-13 16:34:26.640  7083  7083 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-13 16:34:26.640  7083  7083 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-13 16:34:26.640  7083  7083 D AndroidRuntime: readGMSProperty: end
09-13 16:34:26.640  7083  7083 D AndroidRuntime: addProductProperty: start
,09-13 16:34:26.760  7083  7083 E AffinityControl: AffinityControl: registerfunction enter,
,09-13 16:34:26.790  7083  7083 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,09-13 16:34:26.800  1020  1033 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
09-13 16:34:26.800  1020  1033 D PackageManager: START PACKAGE DELETE: observer{645264521}
09-13 16:34:26.800  1020  1033 D PackageManager: pkg{<packageName>}
09-13 16:34:26.800  1020  1033 D PackageManager: user{0}
09-13 16:34:26.800  1020  1033 D PackageManager: caller{2000}
09-13 16:34:26.800  1020  1033 D PackageManager: flags{2}
09-13 16:34:26.800  1020  1033 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-13 16:34:26.800  1020  1061 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,09-13 16:34:26.800  1020  1033 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-13 16:34:26.800  1020  1033 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-13 16:34:26.800  1020  1033 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-13 16:34:26.800  1020  1061 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-13 16:34:26.800  1020  1061 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1,
09-13 16:34:26.800  1020  1061 D ApplicationPolicy: getApplicationUninstallationEnabled
09-13 16:34:26.800  1020  1061 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-13 16:34:26.810  1020  1061 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,09-13 16:34:26.810  1020  1046 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,09-13 16:34:26.810  1020  1046 I ActivityManager: Killing 6961:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-13 16:34:26.810  1020  1046 I ActivityManager:   Force finishing activity ActivityRecord{251a61ed u0 com.test.thalitest/.MainActivity t163}
,09-13 16:34:26.820  1020  1046 D InputDispatcher: Focus left window: 6961
,09-13 16:34:26.820   258  1042 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,09-13 16:34:26.820   258   440 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,09-13 16:34:26.840  1020  1046 D InputDispatcher: Focused application released
,09-13 16:34:26.840  1020  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-13 16:34:26.840  1020  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-13 16:34:26.930  1020  1061 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,09-13 16:34:26.940  1020  1061 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-13 16:34:26.970  6167  6167 I art     : Explicit concurrent mark sweep GC freed 73(15KB) AllocSpace objects, 0(0B) LOS objects, 27% free, 5MB/7MB, paused 915us total 39.853ms
,09-13 16:34:26.980  2830  2830 I art     : Explicit concurrent mark sweep GC freed 16513(986KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 775us total 44.048ms
,09-13 16:34:26.980  6116  6116 I art     : Explicit concurrent mark sweep GC freed 11707(836KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/8MB, paused 772us total 47.624ms
,09-13 16:34:26.990  1020  1102 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 16:34:26.990  1983  1983 E SamsungIME: mOCRHelper is null
,09-13 16:34:26.990  1634  1891 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-13 16:34:27.010  6307  6307 I art     : Explicit concurrent mark sweep GC freed 12877(709KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 4MB/6MB, paused 642us total 75.880ms
,09-13 16:34:27.010  1446  1446 D PersonaManager: isKioskContainerExistOnDevice
,09-13 16:34:27.030  2813  2813 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Sep 13 16:34:27 GMT+02:00 2016
,09-13 16:34:27.030  1020  1126 V NetworkStats: removeUidsLocked() for UIDs [10170]
,09-13 16:34:27.040  1020  1126 V NetworkStats: performPollLocked(flags=0x3)
09-13 16:34:27.040  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 16:34:27.040  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 16:34:27.040  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-13 16:34:27.040  1020  1126 V NetworkStats: performPollLocked() took 6ms
09-13 16:34:27.040  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 16:34:27.050  1020  3770 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-13 16:34:27.050  1020  3770 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-13 16:34:27.050  1446  1446 D RegisteredServicesCache: empty dynamic service
,09-13 16:34:27.050  1020  3770 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:34:27.050  1020  3770 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:34:27.050  1020  3770 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-13 16:34:27.050  1020  1227 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-13 16:34:27.050  1020  1227 D SecContentProvider2: mCursor = null
,09-13 16:34:27.060  2813  2813 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-13 16:34:27.060  1020  1488 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
09-13 16:34:27.060  1020  1488 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-13 16:34:27.060  1020  1488 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-13 16:34:27.060  1020  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.060  1020  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.060  1020  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.060  1020  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:27.070  2813  2813 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-13 16:34:27.070  2813  2813 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-13 16:34:27.070  2813  2813 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-13 16:34:27.080  2813  7094 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-13 16:34:27.080  7095  7095 E Zygote  : MountEmulatedStorage(),
09-13 16:34:27.080  2813  7094 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,09-13 16:34:27.080  7095  7095 E Zygote  : v2
09-13 16:34:27.080  7095  7095 I libpersona: KNOX_SDCARD checking this for 10090
09-13 16:34:27.080  7095  7095 I libpersona: KNOX_SDCARD not a persona
,09-13 16:34:27.080  1020  1488 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7095 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,09-13 16:34:27.090  2813  7094 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,09-13 16:34:27.090  7095  7095 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:34:27.090  7095  7095 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:34:27.100  7095  7095 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 16:34:27.100  2813  7094 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-13 16:34:27.130  7095  7095 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:34:27.130  7095  7095 D ActivityThread: Added TimaKeyStore provider
,09-13 16:34:27.140  1446  1446 D RegisteredComponentCache: Collect Tech packages for Knox
,09-13 16:34:27.150  1446  1446 D PersonaManager: isKioskContainerExistOnDevice
,09-13 16:34:27.150  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 16:34:27.150  1020  1046 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-13 16:34:27.150  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 16:34:27.150  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:27.150  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.150  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:27.150  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:27.170  7110  7110 E Zygote  : MountEmulatedStorage(),
09-13 16:34:27.170  7110  7110 E Zygote  : v2
09-13 16:34:27.170  7110  7110 I libpersona: KNOX_SDCARD checking this for 10032
09-13 16:34:27.170  7110  7110 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 16:34:27.170  7110  7110 I libpersona: KNOX_SDCARD not a persona
09-13 16:34:27.170  7110  7110 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:34:27.170  7110  7110 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-13 16:34:27.180  1020  1046 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=7110 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 16:34:27.190  1020  1020 I art     : Explicit concurrent mark sweep GC freed 33149(2MB) AllocSpace objects, 24(384KB) LOS objects, 33% free, 23MB/35MB, paused 4.276ms total 250.638ms
,09-13 16:34:27.190  1020  1061 I art     : WaitForGcToComplete blocked for 167.801ms for cause Explicit
,09-13 16:34:27.200  1020  1046 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,09-13 16:34:27.200  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:27.200  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.200  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.200  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:27.210  7124  7124 E Zygote  : MountEmulatedStorage()
09-13 16:34:27.210  7124  7124 E Zygote  : v2
09-13 16:34:27.210  7124  7124 I libpersona: KNOX_SDCARD checking this for 10098
09-13 16:34:27.210  7124  7124 I libpersona: KNOX_SDCARD not a persona
,09-13 16:34:27.210  7124  7124 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:34:27.220  7124  7124 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:34:27.220  7124  7124 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 16:34:27.220  2813  7094 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-13 16:34:27.220  1020  1046 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7124 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-13 16:34:27.230  7110  7110 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:34:27.230  7110  7110 D ActivityThread: Added TimaKeyStore provider
,09-13 16:34:27.230  7095  7095 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,09-13 16:34:27.240  7095  7095 D elm:15121: ELMEngine.ELMEngine( context ).
,09-13 16:34:27.240  1020  1033 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-13 16:34:27.240  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-13 16:34:27.240  7095  7095 D elm:15121: MDMBridge.setEnterpriseBridge()
,09-13 16:34:27.240  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:34:27.240  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:34:27.240  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-13 16:34:27.250  1020  1750 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
09-13 16:34:27.250  1020  1750 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-13 16:34:27.250  1020  1750 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:34:27.250  1020  1750 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:34:27.250  1020  1750 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-13 16:34:27.250  1020  1489 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-13 16:34:27.250  1020  1489 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-13 16:34:27.260  1020  1489 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:34:27.260  1020  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 16:34:27.260  1020  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
09-13 16:34:27.260  7095  7095 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-13 16:34:27.270  7095  7095 D elm:15121: ElmAgentService : onCreate()
,09-13 16:34:27.270  1020  1020 D RCPManagerService: PackageReceiver onReceive()
09-13 16:34:27.270  1020  1020 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
09-13 16:34:27.280  7095  7136 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
09-13 16:34:27.280  7095  7136 D elm:15121: MainReceiver.listeningToPackageRemoved()
09-13 16:34:27.280  7095  7136 D elm:15121: MDMBridge.getInstance()
09-13 16:34:27.280  7095  7136 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
09-13 16:34:27.280  2813  7094 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
09-13 16:34:27.280  2813  7094 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
09-13 16:34:27.280  1020  3773 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-13 16:34:27.280  1020  3773 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:27.280  1020  3773 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:27.290  1020  1227 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 16:34:27.290  1020  1227 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4258, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 16:34:27.290  1020  1227 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-13 16:34:27.290  1020  3773 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.290  1020  1227 D BatteryService: stay LED for charging
09-13 16:34:27.290  1020  3773 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:27.300  7124  7124 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-13 16:34:27.300  1020  1020 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-13 16:34:27.300  1020  1020 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-13 16:34:27.300  1020  1020 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
09-13 16:34:27.300  7124  7124 D ActivityThread: Added TimaKeyStore provider
,09-13 16:34:27.310  7142  7142 E Zygote  : MountEmulatedStorage()
09-13 16:34:27.310  7142  7142 I libpersona: KNOX_SDCARD checking this for 10055
09-13 16:34:27.310  7142  7142 E Zygote  : v2,
09-13 16:34:27.310  7142  7142 I libpersona: KNOX_SDCARD not a persona
09-13 16:34:27.310  7142  7142 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:34:27.310  1020  1045 D EnterpriseDeviceManagerService: Package has changed for user 0
09-13 16:34:27.310  1020  1045 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-13 16:34:27.310  1020  1045 W TextServicesManagerService: no available spell checker services found
09-13 16:34:27.310  7095  7136 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
09-13 16:34:27.310  7142  7142 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:34:27.310  1020  1020 I OTPFW   : ProvisionData::getAllEntries Enter
09-13 16:34:27.310  1020  3773 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7142 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-13 16:34:27.310  6116  7137 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-13 16:34:27.310  7142  7142 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 16:34:27.320  1020  1020 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-13 16:34:27.320  2813  2813 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-13 16:34:27.340  7142  7142 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:34:27.340  7142  7142 D ActivityThread: Added TimaKeyStore provider
,09-13 16:34:27.360  7095  7095 D elm:15121: ElmAgentService : onDestroy().
,09-13 16:34:27.370  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 16:34:27.380  1020  1483 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,09-13 16:34:27.380  1020  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:27.380  1020  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.380  1020  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:27.380  1020  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:27.390  7110  7158 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-13 16:34:27.390  7110  7158 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-13 16:34:27.400  7160  7160 E Zygote  : MountEmulatedStorage()
09-13 16:34:27.400  7160  7160 E Zygote  : v2
09-13 16:34:27.400  7160  7160 I libpersona: KNOX_SDCARD checking this for 1000
09-13 16:34:27.400  7160  7160 I libpersona: KNOX_SDCARD not a persona
,09-13 16:34:27.410  7110  7158 D SPPClientService: PushLog.txt file is not deleted.
09-13 16:34:27.410  7110  7158 D SPPClientService: PushLog.txt file is not deleted.
09-13 16:34:27.410  7110  7158 D SPPClientService: ============PushLog. stop!
09-13 16:34:27.410  1020  1483 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7160 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-13 16:34:27.410  1020  1020 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-13 16:34:27.410  7142  7142 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
09-13 16:34:27.410  1020  1020 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-13 16:34:27.410  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-13 16:34:27.410  1020  1483 I ActivityManager: Killing 5588:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
09-13 16:34:27.410  1020  1020 V EnterpriseBillingPolicy: uID is 10170
09-13 16:34:27.410  1020  1020 V EnterpriseBillingPolicy: Removed Packageuid is0
09-13 16:34:27.410  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-13 16:34:27.410  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-13 16:34:27.410  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-13 16:34:27.410  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-13 16:34:27.410  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-13 16:34:27.410  7160  7160 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:34:27.410  7160  7160 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:34:27.410  7160  7160 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 16:34:27.420  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
09-13 16:34:27.420  1020  1483 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-13 16:34:27.420  1020  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.420  1020  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.420  1020  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.420  1020  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:27.420  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,09-13 16:34:27.440  1020  1483 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7169 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 16:34:27.440  7142  7142 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
09-13 16:34:27.440  1020  1483 I ActivityManager: Killing 6307:com.samsung.android.sm/1000 (adj 15): empty #21
09-13 16:34:27.450  7142  7142 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-13 16:34:27.450  7142  7142 D UserAnalysis: Create SecureDbHelper
,09-13 16:34:27.450  7169  7169 E Zygote  : MountEmulatedStorage()
09-13 16:34:27.450  7169  7169 I libpersona: KNOX_SDCARD checking this for 10032
09-13 16:34:27.450  7169  7169 E Zygote  : v2
09-13 16:34:27.450  7169  7169 I libpersona: KNOX_SDCARD not a persona
09-13 16:34:27.450  7169  7169 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:34:27.450  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 16:34:27.450  1020  1139 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-13 16:34:27.450  7169  7169 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 16:34:27.450  7169  7169 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-13 16:34:27.450  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 16:34:27.470  1020  1139 W ActivityManager: userId = 0, bbcId = -10000,
09-13 16:34:27.470  1020  1139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:34:27.470  1020  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
09-13 16:34:27.470   304   304 I art     : Explicit concurrent mark sweep GC freed 8687(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 609us total 26.588ms
,09-13 16:34:27.480  7160  7160 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:34:27.480  7160  7160 D ActivityThread: Added TimaKeyStore provider
,09-13 16:34:27.480  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-13 16:34:27.480  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-13 16:34:27.480   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 16.561ms
,09-13 16:34:27.490  1020  3487 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,09-13 16:34:27.490  1020  1165 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,09-13 16:34:27.490  1020  1020 V EnterpriseBillingPolicy: uID is 10170
09-13 16:34:27.490  1020  1020 V EnterpriseBillingPolicy: Removed Packageuid is0
09-13 16:34:27.490  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-13 16:34:27.490  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-13 16:34:27.490  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-13 16:34:27.490  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-13 16:34:27.490  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-13 16:34:27.500  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-13 16:34:27.500  7142  7142 D IntelligenceServiceApplication: onCreate()
,09-13 16:34:27.500  1020  1519 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 16:34:27.500   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 17.264ms
09-13 16:34:27.500  1020  1519 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-13 16:34:27.500  1020  1519 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:34:27.500  1020  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:34:27.500  1020  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:34:27.500  7169  7169 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:34:27.500  7169  7169 D ActivityThread: Added TimaKeyStore provider
,09-13 16:34:27.510  7142  7142 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,09-13 16:34:27.510  7142  7142 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-13 16:34:27.530  1020  1020 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,09-13 16:34:27.530  1020  1139 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.samsung.android.sm/com.samsung.android.sm.common.SmartManagerReceiver}
09-13 16:34:27.530  1020  1139 W BroadcastQueue: android.os.DeadObjectException
09-13 16:34:27.530  1020  1139 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 16:34:27.530  1020  1139 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 16:34:27.530  1020  1139 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-13 16:34:27.530  1020  1139 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-13 16:34:27.530  1020  1139 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-13 16:34:27.530  1020  1139 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
09-13 16:34:27.530  1020  1139 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-13 16:34:27.530  1020  1139 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
09-13 16:34:27.530  1020  1139 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
09-13 16:34:27.530  1020  1139 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,09-13 16:34:27.540  1020  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.540  1020  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.540  1020  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.540  1020  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:27.540  1020  1061 I art     : Explicit concurrent mark sweep GC freed 13555(751KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 15.005ms total 350.955ms
,09-13 16:34:27.550  7191  7191 E Zygote  : MountEmulatedStorage()
09-13 16:34:27.550  7191  7191 I libpersona: KNOX_SDCARD checking this for 1000
09-13 16:34:27.550  7191  7191 E Zygote  : v2
09-13 16:34:27.550  7191  7191 I libpersona: KNOX_SDCARD not a persona
09-13 16:34:27.550  7191  7191 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:34:27.560  1020  1139 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=7191 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-13 16:34:27.560  7191  7191 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:34:27.560  7191  7191 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 16:34:27.570  1020  1754 W ActivityManager: Spurious death for ProcessRecord{2f982929 7191:com.samsung.android.sm/1000}, curProc for 6307: null
,09-13 16:34:27.570  1020  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-13 16:34:27.570  1020  1488 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:34:27.580  1020  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:34:27.580  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 16:34:27.580  1020  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:34:27.580  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-13 16:34:27.580  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-13 16:34:27.580  1663  1663 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-13 16:34:27.580  1663  1663 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-13 16:34:27.580  7191  7191 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:34:27.590  7191  7191 D ActivityThread: Added TimaKeyStore provider
,09-13 16:34:27.590  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 16:34:27.590  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 16:34:27.600  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-13 16:34:27.600  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
09-13 16:34:27.600  1020  1020 I MotionRecognitionService: Plugged
09-13 16:34:27.600  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 16:34:27.600  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-13 16:34:27.610  1020  1139 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 16:34:27.610  1020  1139 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:34:27.610  1020  1139 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-13 16:34:27.610  1020  1139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:34:27.610  1020  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:34:27.610  3406  3406 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 16:34:27.610  3406  3517 D HeadsetStateMachine: Disconnected process message: 10
,09-13 16:34:27.610  1020  1045 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-13 16:34:27.620  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 16:34:27.620  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 16:34:27.620  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 16:34:27.620  1020  1754 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,09-13 16:34:27.630  1020  1754 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.630  1020  1754 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.630  1020  1754 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.630  1020  1754 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:27.630  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,09-13 16:34:27.630  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,09-13 16:34:27.640  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
,09-13 16:34:27.640  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,09-13 16:34:27.640  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,09-13 16:34:27.640  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
09-13 16:34:27.640  7207  7207 I libpersona: KNOX_SDCARD checking this for 1000
09-13 16:34:27.640  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
09-13 16:34:27.640  7207  7207 I libpersona: KNOX_SDCARD not a persona
09-13 16:34:27.640  7207  7207 E Zygote  : MountEmulatedStorage()
09-13 16:34:27.640  1020  1754 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7207 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-13 16:34:27.640  7207  7207 E Zygote  : v2
09-13 16:34:27.640  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
09-13 16:34:27.640  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
,09-13 16:34:27.640  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
09-13 16:34:27.640  7207  7207 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 16:34:27.640  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
09-13 16:34:27.640  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,09-13 16:34:27.640  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
09-13 16:34:27.640  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
09-13 16:34:27.640  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
09-13 16:34:27.640  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
09-13 16:34:27.640  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
09-13 16:34:27.640  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
09-13 16:34:27.640  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,09-13 16:34:27.640  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
09-13 16:34:27.640  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
09-13 16:34:27.640  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
09-13 16:34:27.640  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
09-13 16:34:27.640  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
09-13 16:34:27.650  7207  7207 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:34:27.650  7169  7213 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
09-13 16:34:27.650  7169  7213 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
09-13 16:34:27.650  7207  7207 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 16:34:27.650  1020  3773 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:34:27.650  1020  3773 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:34:27.650  1020  3773 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:34:27.650  1020  3773 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:34:27.650  1020  3773 I ActivityManager: Killing 6219:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,09-13 16:34:27.660  7142  7142 D BluetoothAdapter: cancelDiscovery
09-13 16:34:27.660  1020  4006 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
09-13 16:34:27.660  1020  4006 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:34:27.660  1020  4006 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
09-13 16:34:27.660  1020  4006 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:34:27.660  1020  4006 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-13 16:34:27.670  1020  1754 I ActivityManager: Killing 6670:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,09-13 16:34:27.670  7169  7213 D SPPClientService: PushLog.txt file is not deleted.
,09-13 16:34:27.670  7207  7207 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:34:27.670  7207  7207 D ActivityThread: Added TimaKeyStore provider
,09-13 16:34:27.670  7169  7213 D SPPClientService: PushLog.txt file is not deleted.
,09-13 16:34:27.670  1836  7220 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-13 16:34:27.670  7169  7213 D SPPClientService: ============PushLog. stop!
,09-13 16:34:27.680  1020  3773 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
,09-13 16:34:27.680  1020  3773 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,09-13 16:34:27.680  1020  3773 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:34:27.680  3406  3512 D BluetoothAdapterProperties: mDiscovering is false
09-13 16:34:27.680  3406  3512 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
09-13 16:34:27.680  1020  3773 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:34:27.680  1020  3773 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,09-13 16:34:27.680  7142  7142 D BluetoothAdapter: cancelDiscovery = true
,09-13 16:34:27.680  7142  7142 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,09-13 16:34:27.680  7191  7191 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 16:34:27.700  1836  7220 D AccountUtils: Clearing selected account for com.test.thalitest
,09-13 16:34:27.700  1020  1061 D PackageManager: delete codoeFile: 
,09-13 16:34:27.700  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 16:34:27.710  1020  1061 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
,09-13 16:34:27.710  1020  1061 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,09-13 16:34:27.710  1020  1061 D PackageManager: result of delete: 1{645264521}
,09-13 16:34:27.720  1020  3773 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:34:27.720  1020  3773 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:34:27.720  7083  7083 D AndroidRuntime: Shutting down VM
,09-13 16:34:27.720  1020  3773 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:34:27.720  1020  3773 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-13 16:34:27.720  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 16:34:27.740  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-13 16:34:27.740  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
09-13 16:34:27.740  1020  3759 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:34:27.740  7142  7142 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-13 16:34:27.740  1020  3759 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:34:27.740  1020  3759 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:34:27.740  1020  3759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:34:27.750  7207  7207 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,09-13 16:34:27.750  1020  1061 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-13 16:34:27.750  1020  1061 D PackageManager: userId{-1}
09-13 16:34:27.750  1020  1061 D PackageManager: andCode{true}
09-13 16:34:27.750  1020  1488 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:34:27.750  1020  1488 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:34:27.750  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 16:34:27.750  1020  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 16:34:27.750  1020  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:34:27.760  1020  1033 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
,09-13 16:34:27.760  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,09-13 16:34:27.760  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:34:27.760  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:34:27.760  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,09-13 16:34:27.760  1020  1045 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-13 16:34:27.760  1020  1045 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 16:34:27.760  1020  1045 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 16:34:27.760  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 16:34:27.770  1020  1061 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-13 16:34:27.770  1020  4006 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 16:34:27.770  1020  4006 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
,09-13 16:34:27.770  1020  4006 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:34:27.770  1020  4006 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:34:27.770  1020  4006 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:34:27.770  1020  3759 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,09-13 16:34:27.780  1020  3759 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:27.780  1020  3759 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.780  1020  3759 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.780  1020  3759 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:27.780  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 16:34:27.780  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 16:34:27.790  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 16:34:27.790  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-13 16:34:27.790  7233  7233 E Zygote  : MountEmulatedStorage(),
,09-13 16:34:27.790  7233  7233 I libpersona: KNOX_SDCARD checking this for 10039
09-13 16:34:27.790  7233  7233 E Zygote  : v2
09-13 16:34:27.790  7233  7233 I libpersona: KNOX_SDCARD not a persona
09-13 16:34:27.790  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 16:34:27.790  1020  3759 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7233 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
09-13 16:34:27.790  7233  7233 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 16:34:27.790  1836  7220 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
09-13 16:34:27.790  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 16:34:27.790  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-13 16:34:27.790  7233  7233 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:34:27.790  7233  7233 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 16:34:27.790  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 16:34:27.800  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
09-13 16:34:27.800  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 16:34:27.800  1020  3759 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,09-13 16:34:27.810  1020  3759 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.810  1020  3759 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.810  1020  3759 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.810  1020  3759 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:27.820  7245  7245 E Zygote  : MountEmulatedStorage()
,09-13 16:34:27.820  7245  7245 I libpersona: KNOX_SDCARD checking this for 1000
09-13 16:34:27.820  7245  7245 E Zygote  : v2
09-13 16:34:27.820  7245  7245 I libpersona: KNOX_SDCARD not a persona
09-13 16:34:27.820  7245  7245 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:34:27.830  1020  3759 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7245 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-13 16:34:27.830  7245  7245 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 16:34:27.830  1020  1754 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-13 16:34:27.830  7245  7245 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 16:34:27.830  1020  1754 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,09-13 16:34:27.830  1020  1754 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:34:27.830  1020  1754 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:34:27.830  1020  1754 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:34:27.840  7233  7233 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:34:27.840  7233  7233 D ActivityThread: Added TimaKeyStore provider
,09-13 16:34:27.840  1836  1836 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-13 16:34:27.840  1836  1836 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-13 16:34:27.850  6116  7137 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 534 ms] updated apps [took 534 ms] 
,09-13 16:34:27.860  1020  1519 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:34:27.860  7245  7245 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:34:27.860  7245  7245 D ActivityThread: Added TimaKeyStore provider
09-13 16:34:27.860  1020  1519 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:34:27.860  1020  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:34:27.860  1020  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:34:27.870  1020  1754 I ActivityManager: Killing 6717:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,09-13 16:34:27.870  1020  1754 I ActivityManager: Killing 6698:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,09-13 16:34:27.870  7233  7233 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-13 16:34:27.870  7233  7233 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 16:34:27.870  7233  7233 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 16:34:27.870  7233  7233 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-13 16:34:27.880  7233  7233 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 16:34:27.880  7233  7233 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-13 16:34:27.880  7233  7233 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-13 16:34:27.880  1836  1836 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-13 16:34:27.880  1836  1836 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-13 16:34:27.880  6769  6769 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-13 16:34:27.880  6769  6769 I PCWCLIENTTRACE_PushUtil: sales region : global
09-13 16:34:27.880  6769  6769 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-13 16:34:27.880  6769  6769 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,09-13 16:34:27.890  1836  7257 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
09-13 16:34:27.890  1836  7257 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,09-13 16:34:27.890  1020  1227 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:34:27.890  1836  7257 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
,09-13 16:34:27.900  1020  1227 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:34:27.900  1020  1045 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-13 16:34:27.900  1836  7257 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
09-13 16:34:27.900  1020  1045 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
09-13 16:34:27.900  1020  1227 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 16:34:27.900  1020  1227 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:34:27.900  1020  3770 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 16:34:27.900  1020  3770 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,09-13 16:34:27.900  1020  3770 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:34:27.900  1020  3770 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:34:27.900  1020  3770 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:34:27.910  1020  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_6307/cgroup.procs: No such file or directory
09-13 16:34:27.910  1020  3770 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.910  1020  3770 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.910  1020  3770 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.910  1020  3770 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:27.920  7268  7268 E Zygote  : MountEmulatedStorage()
09-13 16:34:27.920  7268  7268 E Zygote  : v2
09-13 16:34:27.920  7268  7268 I libpersona: KNOX_SDCARD checking this for 10011
09-13 16:34:27.920  7268  7268 I libpersona: KNOX_SDCARD not a persona
09-13 16:34:27.920  7268  7268 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 16:34:27.920  7245  7267 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
,09-13 16:34:27.920  7245  7267 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
09-13 16:34:27.920  1020  3770 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=7268 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
09-13 16:34:27.920  7268  7268 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:34:27.930  7268  7268 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-13 16:34:27.930  1836  7257 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
09-13 16:34:27.930  1836  7257 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
09-13 16:34:27.930  7083  7083 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-13 16:34:27.930  1836  7257 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,09-13 16:34:27.940  1020  1488 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-13 16:34:27.950  1836  7257 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
09-13 16:34:27.950  1836  7257 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,09-13 16:34:27.960  1020  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.960  1020  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.960  7191  7191 I art     : Explicit concurrent mark sweep GC freed 2340(138KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 4MB/6MB, paused 726us total 133.124ms
,09-13 16:34:27.960  1020  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:27.960  1020  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:27.970  1836  7257 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,09-13 16:34:27.970  1836  7257 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
09-13 16:34:27.970  1836  7257 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0,
,09-13 16:34:27.970  1836  7257 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,09-13 16:34:27.970  7268  7268 D TimaKeyStoreProvider: TimaSignature is unavailable,
,09-13 16:34:27.970  7268  7268 D ActivityThread: Added TimaKeyStore provider
,09-13 16:34:27.980  7283  7283 E Zygote  : MountEmulatedStorage()
09-13 16:34:27.980  7283  7283 E Zygote  : v2
,09-13 16:34:27.980  7283  7283 I libpersona: KNOX_SDCARD checking this for 10117
09-13 16:34:27.980  7283  7283 I libpersona: KNOX_SDCARD not a persona
,09-13 16:34:27.990  7283  7283 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:34:27.990  1020  1488 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7283 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-13 16:34:27.990  7283  7283 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:34:27.990  7283  7283 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-13 16:34:28.000  1020  1489 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
09-13 16:34:28.000  1020  1489 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,09-13 16:34:28.000  1020  1489 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:34:28.000  1020  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:34:28.000  1020  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,09-13 16:34:28.010  1020  1488 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,09-13 16:34:28.010  1020  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:28.010  1020  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:28.010  1020  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:28.010  1020  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:28.010  7245  7245 D AcmsService: Enter Oncreate
,09-13 16:34:28.010  7245  7245 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 16:34:28.010  7245  7245 D AcmsService: creating AcmsCore
09-13 16:34:28.010  7245  7245 D AcmsCore: AcmsCore.getAcmsCore() - Enter
09-13 16:34:28.010  7245  7245 D AcmsCore: AcmsCore
,09-13 16:34:28.020  7283  7283 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:34:28.020  7191  7229 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,09-13 16:34:28.020  7245  7245 D AcmsCore: init
09-13 16:34:28.020  7245  7245 D AcmsCore: Looper handler is not null
09-13 16:34:28.020  7245  7245 D AcmsCore: Post to AcmsCoreHandler
09-13 16:34:28.020  7245  7245 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 16:34:28.020  7245  7245 D AcmsServiceMonitor: Incrementing - Counter value: 1
09-13 16:34:28.020  7245  7245 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
09-13 16:34:28.020  7245  7245 D AcmsService: onStartCommand
09-13 16:34:28.020  7245  7245 D AcmsService: Action: android.intent.action.PACKAGE_REMOVED
09-13 16:34:28.020  7245  7245 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
09-13 16:34:28.020  7245  7245 D AcmsServiceMonitor: Incrementing - Counter value: 2
09-13 16:34:28.020  7245  7245 D AcmsService: Incremented Counter Value : onStartCommand
,09-13 16:34:28.020  1020  1488 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7302 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,09-13 16:34:28.030  7302  7302 E Zygote  : MountEmulatedStorage(),
09-13 16:34:28.030  7302  7302 I libpersona: KNOX_SDCARD checking this for 10029
09-13 16:34:28.030  7302  7302 E Zygote  : v2
09-13 16:34:28.030  7302  7302 I libpersona: KNOX_SDCARD not a persona,
09-13 16:34:28.030  7302  7302 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 16:34:28.030  7283  7283 D ActivityThread: Added TimaKeyStore provider
,09-13 16:34:28.030  7302  7302 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-13 16:34:28.030  7302  7302 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 16:34:28.030  1020  1033 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,09-13 16:34:28.040  7245  7299 D AcmsCertificateMngr: AcmsCertificateMngr
09-13 16:34:28.040  7245  7245 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,09-13 16:34:28.040  7245  7299 D AcmsRevocationMngr: AcmsRevocationMngr
,09-13 16:34:28.050  1020  1483 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,09-13 16:34:28.050  1020  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:28.050  1020  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:28.050  1020  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:28.050  1020  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:28.060  7302  7302 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:34:28.070  7302  7302 D ActivityThread: Added TimaKeyStore provider
,09-13 16:34:28.070  7283  7283 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,09-13 16:34:28.080  1020  1483 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7320 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-13 16:34:28.080  1020  1483 I ActivityManager: Killing 6751:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,09-13 16:34:28.090  7320  7320 E Zygote  : MountEmulatedStorage()
09-13 16:34:28.090  7320  7320 E Zygote  : v2
09-13 16:34:28.090  7320  7320 I libpersona: KNOX_SDCARD checking this for 1000
09-13 16:34:28.090  7320  7320 I libpersona: KNOX_SDCARD not a persona
,09-13 16:34:28.090  7320  7320 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:34:28.090  7320  7320 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:34:28.100  7320  7320 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 16:34:28.110  6869  6882 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
09-13 16:34:28.110  6869  6882 D BadgeProvider: sendNotify, [notify] : null
09-13 16:34:28.110  6869  6882 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
09-13 16:34:28.110  6869  6882 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-13 16:34:28.110  6869  6882 D BadgeProvider: update, [UpdateCount] : 1
,09-13 16:34:28.110  1490  1490 D Launcher.Model: reloadBadges entered.
,09-13 16:34:28.120  7268  7268 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-13 16:34:28.120  7268  7268 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-13 16:34:28.120   288   288 E SMD     : DCD OFF
,09-13 16:34:28.130  7320  7320 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:34:28.130  7320  7320 D ActivityThread: Added TimaKeyStore provider
,09-13 16:34:28.160  1020  1139 W ActivityManager: getRunningAppProcesses: caller 10029 is using old GET_TASKS but privileged; allowing
,09-13 16:34:28.160  1836  7266 W BaseAppContext: Using Auth Proxy for data requests.
,09-13 16:34:28.160  7245  7245 D AcmsService: Inside handle Intent
,09-13 16:34:28.180  1836  7337 E SQLiteLog: (539) recovered 11 pages from /data/data/com.google.android.gms/databases/DocList.db-journal
,09-13 16:34:28.190  7268  7268 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>,
09-13 16:34:28.190  7268  7268 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,09-13 16:34:28.190  1836  7266 W BaseAppContext: Using Auth Proxy for data requests.
,09-13 16:34:28.200  7268  7268 I MultiDex: VM with version 2.1.0 has multidex support
09-13 16:34:28.200  7268  7268 I MultiDex: install
09-13 16:34:28.200  7268  7268 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-13 16:34:28.200  1836  7337 W DatabaseHelper: Upgrading database /data/data/com.google.android.gms/databases/DocList.db from version 88 to 143 databaseName=DocList.db
,09-13 16:34:28.200  7320  7320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,09-13 16:34:28.210  7245  7245 D AcmsService: App removed - package name: com.test.thalitest
09-13 16:34:28.210  7245  7245 D AcmsCore: Post to AcmsCoreHandler
09-13 16:34:28.210  7245  7245 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 16:34:28.210  7245  7245 D AcmsServiceMonitor: Incrementing - Counter value: 3
09-13 16:34:28.210  7245  7245 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>5
09-13 16:34:28.210  7245  7245 D AcmsService: Decremented Counter Value : handleStartIntent
09-13 16:34:28.210  7245  7245 D AcmsServiceMonitor: Decrementing - Counter value: 2
,09-13 16:34:28.210  1020  1489 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-13 16:34:28.210  1020  1489 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-13 16:34:28.210  1020  1489 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:34:28.210  1020  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 16:34:28.210  1020  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-13 16:34:28.220  1020  4006 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,09-13 16:34:28.220  7302  7338 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,09-13 16:34:28.230  1020  4006 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:28.230  1020  4006 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:28.230  1020  4006 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:28.230  1020  4006 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:28.230  1836  7266 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/databases/app_state.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
09-13 16:34:28.230  1836  7266 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-13 16:34:28.230  1836  7266 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-13 16:34:28.230  1836  7337 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/DocList.db-journal" with flag (131138) and mode_t (1b0) due to error (30)
,09-13 16:34:28.240  1836  7337 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/DocList.db-journal" with flag (131072) and mode_t (1b0) due to error (2)
,09-13 16:34:28.240  1836  7337 E SQLiteLog: (14) cannot open file at line 32510 of [b3bb660af9]
09-13 16:34:28.240  1836  7337 E SQLiteLog: (14) os_unix.c:32510: (2) open(/data/data/com.google.android.gms/databases/DocList.db-journal) - 
09-13 16:34:28.240  1836  7337 E SQLiteLog: (14) statement aborts at 21: [DROP VIEW "EntryView"] 
,09-13 16:34:28.240  7320  7344 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
,09-13 16:34:28.240  7320  7344 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
09-13 16:34:28.240  7320  7344 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 16:34:28.240  7320  7344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 16:34:28.240  7320  7344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 16:34:28.240  7320  7344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 16:34:28.240  7320  7344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 16:34:28.240  7320  7344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 16:34:28.240  7320  7344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 16:34:28.240  7320  7344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 16:34:28.240  7320  7344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 16:34:28.240  7320  7344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 16:34:28.240  7320  7344 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 16:34:28.240  7320  7344 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 16:34:28.240  7320  7344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 16:34:28.240  7320  7344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 16:34:28.240  7320  7344 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
09-13 16:34:28.240  7320  7344 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
09-13 16:34:28.240  7320  7344 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-13 16:34:28.240  7320  7344 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:34:28.240  7320  7344 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-13 16:34:28.240  7320  7344 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 16:34:28.240  7320  7344 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 16:34:28.240  7320  7344 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 16:34:28.240  7320  7344 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 16:34:28.240  7320  7344 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 16:34:28.240  7320  7344 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 16:34:28.240  7320  7344 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 16:34:28.240  7320  7344 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 16:34:28.240  7320  7344 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 16:34:28.240  7320  7344 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 16:34:28.240  7320  7344 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 16:34:28.240  7320  7344 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 16:34:28.240  7320  7344 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 16:34:28.240  7320  7344 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 16:34:28.240  7320  7344 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 16:34:28.240  7320  7344 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
09-13 16:34:28.240  7320  7344 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
09-13 16:34:28.240  7320  7344 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-13 16:34:28.240  7320  7344 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:34:28.240  7320  7344 W System.err: 	at android.os.Looper.loop(Looper.java:145)
09-13 16:34:28.240  7320  7344 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 16:34:28.240  1836  7266 E ClearPendingStateOp: Runtime exception while performing operation
09-13 16:34:28.240  1836  7266 E ClearPendingStateOp: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 16:34:28.240  1836  7266 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-13 16:34:28.240  1836  7266 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
09-13 16:34:28.240  1836  7266 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-13 16:34:28.240  1836  7266 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-13 16:34:28.240  1836  7266 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
09-13 16:34:28.240  1836  7266 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
09-13 16:34:28.240  1836  7266 E ClearPendingStateOp: 	at com.google.android.gms.common.i.a.b(SourceFile:283)
09-13 16:34:28.240  1836  7266 E ClearPendingStateOp: 	at com.google.android.gms.common.i.a.delete(SourceFile:273)
09-13 16:34:28.240  1836  7266 E ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:324)
09-13 16:34:28.240  1836  7266 E ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1352)
09-13 16:34:28.240  1836  7266 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
09-13 16:34:28.240  1836  7266 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
09-13 16:34:28.240  1836  7266 E ClearPendingStateOp: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
09-13 16:34:28.240  1836  7266 E ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
09-13 16:34:28.240  1836  7266 E ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
09-13 16:34:28.240  1836  7266 E ClearPendingStateOp: 	at java.lang.Thread.run(Thread.java:818)
,09-13 16:34:28.240  1836  7266 F ClearPendingStateOp: Killing (on development devices) due to RuntimeException
09-13 16:34:28.240  1836  7266 F ClearPendingStateOp: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 16:34:28.240  1836  7266 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-13 16:34:28.240  1836  7266 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
09-13 16:34:28.240  1836  7266 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-13 16:34:28.240  1836  7266 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-13 16:34:28.240  1836  7266 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
09-13 16:34:28.240  1836  7266 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
09-13 16:34:28.240  1836  7266 F ClearPendingStateOp: 	at com.google.android.gms.common.i.a.b(SourceFile:283)
09-13 16:34:28.240  1836  7266 F ClearPendingStateOp: 	at com.google.android.gms.common.i.a.delete(SourceFile:273)
09-13 16:34:28.240  1836  7266 F ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:324)
09-13 16:34:28.240  1836  7266 F ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1352)
09-13 16:34:28.240  1836  7266 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
09-13 16:34:28.240  1836  7266 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
09-13 16:34:28.240  1836  7266 F ClearPendingStateOp: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
09-13 16:34:28.240  1836  7266 F ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
09-13 16:34:28.240  1836  7266 F ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
09-13 16:34:28.240  1836  7266 F ClearPendingStateOp: 	at java.lang.Thread.run(Thread.java:818)
,09-13 16:34:28.250  7346  7346 E Zygote  : MountEmulatedStorage()
,09-13 16:34:28.250  7346  7346 E Zygote  : v2
09-13 16:34:28.250  7346  7346 I libpersona: KNOX_SDCARD checking this for 1000
09-13 16:34:28.250  7346  7346 I libpersona: KNOX_SDCARD not a persona
,09-13 16:34:28.250  1020  4006 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7346 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,09-13 16:34:28.250  7346  7346 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-13 16:34:28.250  1020  3771 I ActivityManager: Killing 6732:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,09-13 16:34:28.260  7346  7346 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-13 16:34:28.260  7233  7233 D NearbySource: Nearby Source Create!
,09-13 16:34:28.260  7233  7233 D NearbyContext: Nearby Context Create!
,09-13 16:34:28.270  7346  7346 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-13 16:34:28.270  1020  1489 I ActivityManager: Killing 6793:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,09-13 16:34:28.280  1020  1033 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 16:34:28.280  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
,09-13 16:34:28.280  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:34:28.280  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:34:28.280  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:34:28.290  1020  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:34:28.290  1020  7352 E DropBoxManagerService: Can't write: system_app_wtf
09-13 16:34:28.290  1020  7352 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop173.tmp: open failed: EROFS (Read-only file system)
09-13 16:34:28.290  1020  7352 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-13 16:34:28.290  1020  7352 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 16:34:28.290  1020  7352 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 16:34:28.290  1020  7352 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 16:34:28.290  1020  7352 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-13 16:34:28.290  1020  7352 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
09-13 16:34:28.290  1020  7352 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 16:34:28.290  1020  7352 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 16:34:28.290  1020  7352 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 16:34:28.290  1020  7352 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-13 16:34:28.290  1020  7352 E DropBoxManagerService: 	... 5 more
,09-13 16:34:28.300  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:34:28.300  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:34:28.300  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:34:28.300  1836  7337 E DatabaseHelper: An exception occurred during database upgrade.
09-13 16:34:28.300  1836  7337 E DatabaseHelper: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
09-13 16:34:28.300  1836  7337 E DatabaseHelper: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 16:34:28.300  1836  7337 E DatabaseHelper: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
09-13 16:34:28.300  1836  7337 E DatabaseHelper: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 16:34:28.300  1836  7337 E DatabaseHelper: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 16:34:28.300  1836  7337 E DatabaseHelper: 	at android.database.sqlite.SQLiteDatabase.executeSql(SQLiteDatabase.java:1814)
09-13 16:34:28.300  1836  7337 E DatabaseHelper: 	at android.database.sqlite.SQLiteDatabase.execSQL(SQLiteDatabase.java:1743)
09-13 16:34:28.300  1836  7337 E DatabaseHelper: 	at com.google.android.gms.drive.database.c.b(SourceFile:337)
09-13 16:34:28.300  1836  7337 E DatabaseHelper: 	at com.google.android.gms.drive.database.c.a(SourceFile:188)
09-13 16:34:28.300  1836  7337 E DatabaseHelper: 	at com.google.android.gms.drive.database.c.onUpgrade(SourceFile:159)
09-13 16:34:28.300  1836  7337 E DatabaseHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:256)
09-13 16:34:28.300  1836  7337 E DatabaseHelper: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 16:34:28.300  1836  7337 E DatabaseHelper: 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
09-13 16:34:28.300  1836  7337 E DatabaseHelper: 	at com.google.android.gms.drive.database.m.b(SourceFile:598)
09-13 16:34:28.300  1836  7337 E DatabaseHelper: 	at com.google.android.gms.drive.database.m.a(SourceFile:592)
09-13 16:34:28.300  1836  7337 E DatabaseHelper: 	at com.google.android.gms.drive.database.o.run(SourceFile:613)
09-13 16:34:28.300  1836  7337 W DatabaseHelper: Database upgrade completed in 98 ms
,09-13 16:34:28.300  1663  1663 I ConfigService: onCreate
,09-13 16:34:28.300  1020  1488 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 16:34:28.300  1020  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
09-13 16:34:28.300  1663  7364 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/config.db" with flag (131138) and mode_t (0) due to error (30)
09-13 16:34:28.300  1836  7337 W DatabaseHelper: Failed to delete database file: /data/data/com.google.android.gms/databases/DocList.db
,09-13 16:34:28.300  1836  7337 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/DocList.db" with flag (131138) and mode_t (0) due to error (30)
09-13 16:34:28.300  1836  7254 D ConnectivityManager: CallingUid : 10011, CallingPid : 1836
,09-13 16:34:28.310  1663  7364 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/config.db'.
09-13 16:34:28.310  1663  7364 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 16:34:28.310  1663  7364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 16:34:28.310  1663  7364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 16:34:28.310  1663  7364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 16:34:28.310  1663  7364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 16:34:28.310  1663  7364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 16:34:28.310  1663  7364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 16:34:28.310  1663  7364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 16:34:28.310  1663  7364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 16:34:28.310  1663  7364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 16:34:28.310  1663  7364 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 16:34:28.310  1663  7364 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 16:34:28.310  1663  7364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 16:34:28.310  1663  7364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 16:34:28.310  1663  7364 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-13 16:34:28.310  1663  7364 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-13 16:34:28.310  1663  7364 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-13 16:34:28.310  1663  7364 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-13 16:34:28.310  1663  7364 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 16:34:28.310  1663  7364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 16:34:28.310  1663  7364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 16:34:28.310  1663  7364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 16:34:28.310  1663  7364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 16:34:28.310  1663  7364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 16:34:28.310  1663  7364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 16:34:28.310  1663  7364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 16:34:28.310  1663  7364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 16:34:28.310  1663  7364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 16:34:28.310  1663  7364 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 16:34:28.310  1663  7364 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 16:34:28.310  1663  7364 E SQLiteOpenHelper:
```
