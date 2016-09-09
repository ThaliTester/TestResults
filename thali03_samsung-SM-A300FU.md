#### Test 8359176481a80d7_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
09-09 22:02:00.612  6914  6914 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
--------- beginning of system
09-09 22:02:00.612  1017  1057 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
09-09 22:02:00.612  1017  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
09-09 22:02:00.612  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:00.612  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:00.612  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:00.612  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:00.632  6947  6947 E Zygote  : MountEmulatedStorage()
09-09 22:02:00.632  6947  6947 E Zygote  : v2
09-09 22:02:00.632  6947  6947 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 22:02:00.632  6947  6947 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 22:02:00.632  6947  6947 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 22:02:00.632  6947  6947 I libpersona: KNOX_SDCARD checking this for 10003
09-09 22:02:00.632  6947  6947 I libpersona: KNOX_SDCARD not a persona
09-09 22:02:00.632  1017  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6947 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-09 22:02:00.632  1017  3703 I ActivityManager: Killing 6613:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
09-09 22:02:00.642  1939  4483 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
09-09 22:02:00.662  1017  1029 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
09-09 22:02:00.672  6932  6932 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
09-09 22:02:00.682  6947  6947 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 22:02:00.682  6947  6947 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:00.712  6717  6893 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
09-09 22:02:00.722  6932  6932 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
09-09 22:02:00.722  6932  6932 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
09-09 22:02:00.722  6932  6932 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
09-09 22:02:00.722   284   284 E installd: system dir 0 : /system/app/
09-09 22:02:00.722   284   284 E installd: system dir 1 : /system/priv-app/
09-09 22:02:00.722   284   284 E installd: system dir 2 : /vendor/app/
09-09 22:02:00.722   284   284 E installd: system dir 3 : /oem/app/
09-09 22:02:00.722  6932  6932 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
09-09 22:02:00.722  6932  6932 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
09-09 22:02:00.722  6932  6932 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
09-09 22:02:00.722  6932  6932 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
09-09 22:02:00.762  1017  1057 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
09-09 22:02:00.762  6932  6932 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
09-09 22:02:00.762  6932  6932 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
09-09 22:02:00.762  6932  6932 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
09-09 22:02:00.762  6932  6932 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
09-09 22:02:00.762  6932  6932 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
09-09 22:02:00.762  6932  6932 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
09-09 22:02:00.832  1939  4483 D Icing   : Loaded CLD2 Version V2.0 - 20141016
09-09 22:02:00.832  6736  6802 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-09 22:02:00.832  6736  6802 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 22:02:00.832  6736  6802 I GAv4    :   adb logcat -s GAv4
09-09 22:02:00.882  6736  6802 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
09-09 22:02:00.882  1017  3700 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
09-09 22:02:00.942  6736  6802 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
09-09 22:02:00.962  1017  3700 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-09 22:02:00.972  1017  3700 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4198, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-09 22:02:00.972  1017  3700 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-09 22:02:00.972  1017  3700 D BatteryService: stay LED for charging
09-09 22:02:00.972  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-09 22:02:00.972  1017  1017 I MotionRecognitionService: Plugged
09-09 22:02:00.972  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
09-09 22:02:00.972  1017  1320 I art     : Explicit concurrent mark sweep GC freed 140500(7MB) AllocSpace objects, 2(1824KB) LOS objects, 33% free, 23MB/34MB, paused 2.543ms total 171.335ms
09-09 22:02:00.972  6967  6967 D AndroidRuntime: 
09-09 22:02:00.972  6967  6967 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-09 22:02:00.982  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-09 22:02:00.982  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
09-09 22:02:00.982  6967  6967 D AndroidRuntime: CheckJNI is OFF
09-09 22:02:00.982  6967  6967 D AndroidRuntime: readGMSProperty: start
09-09 22:02:00.982  6967  6967 D AndroidRuntime: readGMSProperty: already setted!!
09-09 22:02:00.982  6967  6967 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-09 22:02:00.982  6967  6967 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-09 22:02:00.982  6967  6967 D AndroidRuntime: readGMSProperty: end
09-09 22:02:00.982  6967  6967 D AndroidRuntime: addProductProperty: start
09-09 22:02:00.982  1425  1425 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-09 22:02:00.982  1425  1425 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
09-09 22:02:00.992  6736  6802 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
09-09 22:02:01.002  6736  6973 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
09-09 22:02:01.002  3374  3374 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-09 22:02:01.002  3374  3486 D HeadsetStateMachine: Disconnected process message: 10
09-09 22:02:01.012  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-09 22:02:01.012  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-09 22:02:01.012  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-09 22:02:01.012  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-09 22:02:01.012  1180  1180 D SViewCoverView: level :100 plugged : 2
09-09 22:02:01.042  1939  4483 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
09-09 22:02:01.062  1017  1509 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-09 22:02:01.062  1017  1509 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:01.062  1017  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:01.062  1017  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-09 22:02:01.132  6967  6967 E AffinityControl: AffinityControl: registerfunction enter
09-09 22:02:01.152  6967  6967 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-09 22:02:01.162  1017  1506 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
09-09 22:02:01.162  1017  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:01.162  1017  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:01.162  1017  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:01.162  1017  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:01.172  1017  1477 E PersonaManagerService: inState():  stateMachine is null !!
09-09 22:02:01.172  1017  1477 I PersonaManagerService: PersonaId don't exist
09-09 22:02:01.172  1017  1477 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-09 22:02:01.182  6986  6986 E Zygote  : MountEmulatedStorage()
09-09 22:02:01.182  6986  6986 E Zygote  : v2
09-09 22:02:01.182  6986  6986 I libpersona: KNOX_SDCARD checking this for 1000
09-09 22:02:01.182  6986  6986 I libpersona: KNOX_SDCARD not a persona
09-09 22:02:01.182  6986  6986 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 22:02:01.182  1017  1506 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=6986 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-09 22:02:01.182  1017  1506 I ActivityManager: Killing 6638:com.sec.spp.push/u0a32 (adj 15): empty #21
09-09 22:02:01.182  6986  6986 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 22:02:01.182  6986  6986 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 22:02:01.192  1017  1477 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-09 22:02:01.212  1017  1477 W ActivityManager: mDVFSHelper.acquire()
09-09 22:02:01.212  1017  1477 D FocusedStackFrame: Set to : 0
09-09 22:02:01.222  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:01.222  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:01.222  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:01.222  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:01.222  6986  6986 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 22:02:01.222  6986  6986 D ActivityThread: Added TimaKeyStore provider
09-09 22:02:01.222  1017  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-09 22:02:01.222  1017  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-09 22:02:01.232  7003  7003 E Zygote  : MountEmulatedStorage()
09-09 22:02:01.232  7003  7003 E Zygote  : v2
09-09 22:02:01.232  7003  7003 I libpersona: KNOX_SDCARD checking this for 10170
09-09 22:02:01.232  7003  7003 I libpersona: KNOX_SDCARD not a persona
09-09 22:02:01.232  7003  7003 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 22:02:01.242  7003  7003 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 22:02:01.242  1017  1477 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7003 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-09 22:02:01.242  1017  1477 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-09 22:02:01.242  1017  1477 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-09 22:02:01.242  1017  1477 D InputDispatcher: Focused application set to: xxxx
09-09 22:02:01.242  1017  1477 D InputDispatcher: Focus left window: 1510
09-09 22:02:01.242  7003  7003 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-09 22:02:01.242  6967  6967 D AndroidRuntime: Shutting down VM
09-09 22:02:01.242  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-09 22:02:01.242  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-09 22:02:01.242   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
09-09 22:02:01.272  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 22:02:01.272  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
09-09 22:02:01.272  7003  7003 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 22:02:01.272  7003  7003 D ActivityThread: Added TimaKeyStore provider
09-09 22:02:01.272  1017  1509 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-09 22:02:01.272  1017  1017 V ActivityManager: Display changed displayId=0
09-09 22:02:01.282  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-09 22:02:01.282  6986  6986 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
09-09 22:02:01.292  6986  6986 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
09-09 22:02:01.302  1017  1509 D PersonaManager: isKioskContainerExistOnDevice
09-09 22:02:01.312  1017  1320 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
09-09 22:02:01.322  1017  1320 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
09-09 22:02:01.332  1017  1320 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:01.332  1017  1320 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:01.332  1017  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
09-09 22:02:01.332  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-09 22:02:01.332  1017  1210 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
09-09 22:02:01.342  6986  6986 I FilterInstaller: FilterPackageService : ACTION_CHANGED
09-09 22:02:01.362  6986  7020 E FilterInstaller: installFilters
09-09 22:02:01.362  6986  7020 E FilterInstaller: There is no requred permission
09-09 22:02:01.362  1017  4466 I ActivityManager: Killing 5203:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
09-09 22:02:01.382   258   444 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
09-09 22:02:01.382   258   448 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
09-09 22:02:01.392  1510  1510 V ActivityThread: updateVisibility : ActivityRecord{1be5df13 token=android.os.BinderProxy@f559271 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-09 22:02:01.392  1510  1510 D Launcher: onTrimMemory. Level: 20
09-09 22:02:01.422  6736  6983 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-09 22:02:01.422  6736  6983 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-09 22:02:01.452  6967  6967 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-09 22:02:01.452  7003  7003 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-09 22:02:01.472  7003  7003 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 6425-6428)
,09-09 22:02:01.472  7003  7003 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-09 22:02:01.482  6736  6983 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,09-09 22:02:01.502  7003  7003 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1b3f2a45}
,09-09 22:02:01.512  7003  7003 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-09 22:02:01.522  7003  7003 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 22:02:01.552  6736  6983 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-09 22:02:01.552  6736  6983 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@6e64fe3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-09 22:02:01.552  6736  6983 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-09 22:02:01.572  7003  7003 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-09 22:02:01.572  7003  7003 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 22:02:01.582  7003  7003 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 22:02:01.632  7003  7003 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 22:02:01.632  7003  7003 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 22:02:01.632  7003  7003 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 22:02:01.632  7003  7003 I Adreno-EGL: Local Branch: 
09-09 22:02:01.632  7003  7003 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 22:02:01.632  7003  7003 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 22:02:01.632  7003  7003 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 22:02:01.702  7003  7003 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 22:02:01.732  7003  7003 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-09 22:02:01.732  7003  7003 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-09 22:02:01.742  7003  7003 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-09 22:02:01.742  7003  7003 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-09 22:02:01.802  1017  1042 W ActivityManager: Activity pause timeout for ActivityRecord{17af4725 u0 com.test.thalitest/.MainActivity t163}
,09-09 22:02:01.842  7003  7003 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 22:02:01.862  7003  7003 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-09 22:02:01.872  7003  7003 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-09 22:02:01.872  7003  7003 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-09 22:02:01.882  7003  7003 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-09 22:02:01.882  7003  7003 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 22:02:01.882  7003  7003 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 22:02:01.932  7003  7047 D OpenGLRenderer: Render dirty regions requested: true
,09-09 22:02:01.942  1017  1030 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-09 22:02:01.942  1017  1030 D KnoxTimeoutHandler: postActiveUserChange for user 0
,09-09 22:02:01.942  1017  1030 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-09 22:02:01.942  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-09 22:02:01.942  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,09-09 22:02:01.942  7003  7034 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,09-09 22:02:01.952  7003  7003 V ActivityThread: updateVisibility : ActivityRecord{1db32f25 token=android.os.BinderProxy@3b689bee {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-09 22:02:01.952  7003  7003 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-09 22:02:01.952  7003  7003 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-09 22:02:01.962   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,09-09 22:02:01.982  1017  3700 D InputDispatcher: Focus entered window: 7003
,09-09 22:02:01.982  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-09 22:02:01.982  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 22:02:01.992  7003  7003 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-09 22:02:01.992  7003  7047 I OpenGLRenderer: Initialized EGL, version 1.4
,09-09 22:02:01.992  7003  7047 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,09-09 22:02:01.992  7003  7047 D OpenGLRenderer: Enabling debug mode 0
,09-09 22:02:02.022  1017  1320 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-09 22:02:02.022  1017  7051 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 22:02:02.022  1180  1180 D PanelView: There is/are notification(s) 
,09-09 22:02:02.042  1017  1047 I ActivityManager: Displayed Component not be shown by security: +733ms (total +819ms)
,09-09 22:02:02.042  1017  1047 W ActivityManager: mDVFSHelper.release()
09-09 22:02:02.042  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{17af4725 u0 com.test.thalitest/.MainActivity t163} time:96995
09-09 22:02:02.042  7003  7003 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-09 22:02:02.042  7003  7003 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3b689bee time:96998
09-09 22:02:02.052   258  1103 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,09-09 22:02:02.052   258   444 I SurfaceFlinger: id=12 Removed uhalitest (-2/9),
,09-09 22:02:02.062  1017  1078 I ActivityManager: Killing 6623:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,09-09 22:02:02.082  1874  1874 I SamsungIME: getCurrentCandidateView
,09-09 22:02:02.152  7003  7003 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7003
,09-09 22:02:02.222  1874  1874 D SamsungIME: Dismiss ExpandCandiate
,09-09 22:02:02.302  6717  6717 I Mms/MmsApp:  start initViewCache mms
,09-09 22:02:02.312  6717  6717 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1881.216562
09-09 22:02:02.312  6717  6717 D Mms/ComposeMessageFragment: fillCache, easy = false
,09-09 22:02:02.362  7003  7003 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 22:02:02.402  1874  1874 I SamsungIME: getDebugLevel  : 0x4f4c
,09-09 22:02:02.442  6717  6731 W art     : Suspending all threads took: 8.458ms
,09-09 22:02:02.442  6717  6717 D AbsListView: Get MotionRecognitionManager
,09-09 22:02:02.442  7003  7053 D jxcore_app_log: JniHelper::setJavaVM(0xb84a92b0), pthread_self() = -1197251256
,09-09 22:02:02.442  1017  4071 D MotionRecognitionService:  ssp status : false
,09-09 22:02:02.452  6717  6717 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 143.941511
,09-09 22:02:02.452  1874  1874 I SamsungIME: getDebugLevel  : 0x4f4c
,09-09 22:02:02.452  7003  7053 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 22:02:02.452  7003  7053 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 22:02:02.452  7003  7053 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 22:02:02.452  7003  7053 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 22:02:02.452  7003  7053 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-09 22:02:02.452  7003  7053 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41a4823 added. We now have 1 listener(s)
,09-09 22:02:02.462  7003  7053 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,09-09 22:02:02.462  7003  7053 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-09 22:02:02.462  7003  7053 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 22:02:02.462  7003  7053 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 22:02:02.472  7003  7053 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 22:02:02.472  7003  7053 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 22:02:02.472  7003  7053 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 22:02:02.472  7003  7053 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
09-09 22:02:02.472  7003  7053 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 22:02:02.472  7003  7053 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 22:02:02.472  7003  7053 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 22:02:02.472  7003  7053 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 22:02:02.472  7003  7053 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 22:02:02.472  7003  7053 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 22:02:02.472  7003  7053 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 22:02:02.472  7003  7053 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 22:02:02.472  7003  7053 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 22:02:02.472  7003  7053 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-09 22:02:02.472  7003  7053 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13a9dc9e added. We now have 1 listener(s)
,09-09 22:02:02.472  7003  7053 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 22:02:02.472  1874  1874 I SamsungIME: KeybaordView init() : load resources
,09-09 22:02:02.472  7003  7053 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 22:02:02.472  7003  7053 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-09 22:02:02.472  7003  7053 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-09 22:02:02.472  7003  7053 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 22:02:02.472  7003  7053 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-09 22:02:02.482  7003  7053 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 22:02:02.482  7003  7053 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,09-09 22:02:02.482  7003  7053 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage,
,09-09 22:02:02.492  7003  7053 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 22:02:02.492  7003  7053 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:02.492  7003  7053 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:02.492  7003  7053 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:02.492  7003  7053 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:02.492  7003  7053 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 22:02:02.492  7003  7053 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 22:02:02.492  7003  7053 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 22:02:02.492  7003  7053 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-09 22:02:02.492  7003  7053 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 22:02:02.492  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:02.492  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:02.492  7003  7053 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 22:02:02.502  1874  1874 I SamsungIME: getCurrentKeyboard
09-09 22:02:02.502  1874  1874 I SamsungIME: getTextKeyboard
,09-09 22:02:02.532  7003  7003 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,09-09 22:02:02.552  1874  1874 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-09 22:02:02.562  6717  6717 D Mms/BubbleViewCache: fillCache bubble = 1,
,09-09 22:02:02.812   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb72f27c8
09-09 22:02:02.812   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
09-09 22:02:02.812   273   273 I rmt_storage: wakelock acquired: 1, error no: 42
09-09 22:02:02.812   273   326 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1221647048)
,09-09 22:02:02.852   273   326 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504,
09-09 22:02:02.852   273   326 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
09-09 22:02:02.852   273   326 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1221647048) wakelock released: 1, error no: 0
09-09 22:02:02.852   273   326 I rmt_storage: 
,09-09 22:02:02.852   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb72f27c8,
,09-09 22:02:03.022   288   288 E SMD     : DCD OFF,
,09-09 22:02:03.122  7003  7061 W jxcore-log: Initializing JXcore engine
09-09 22:02:03.122  7003  7061 W jxcore-log: JXcore engine is ready
,09-09 22:02:03.182  2023  2023 E audit   : type=1400 msg=audit(1473451323.182:205): avc:  denied  { ioctl } for  pid=7061 comm="Thread-1320" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-09 22:02:03.182  2023  2023 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
09-09 22:02:03.182  2023  2023 E audit   : type=1300 msg=audit(1473451323.182:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9d1c68f8 items=0 ppid=308 ppcomm=main pid=7061 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1320" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-09 22:02:03.182  2023  2023 E audit   : type=1320 msg=audit(1473451323.182:205): 
,09-09 22:02:03.192  7003  7061 W jxcore-log: Starting JXcore engine
,09-09 22:02:03.302  7003  7061 W jxcore-log: Platform android
09-09 22:02:03.302  7003  7061 W jxcore-log: 
09-09 22:02:03.302  7003  7061 W jxcore-log: Process ARCH arm
09-09 22:02:03.302  7003  7061 W jxcore-log: 
09-09 22:02:03.502  7003  7061 I jxcore-log: JXcore Cordova bridge is ready!
09-09 22:02:03.502  7003  7061 I jxcore-log: 
09-09 22:02:03.502  7003  7061 W jxcore-log: JXcore engine is started
09-09 22:02:03.502  7003  7053 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-09 22:02:03.512  7003  7003 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 22:02:04.682  1017  3473 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 22:02:05.442  2629  2629 I ConfigService: onDestroy
,09-09 22:02:06.022   288   288 E SMD     : DCD OFF
,09-09 22:02:07.832  6698  6744 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,09-09 22:02:07.852  6698  6744 I AcmsKeyStoreHelper: Key Store exist
,09-09 22:02:07.852  6698  6744 I AcmsKeyStoreHelper: Hence loading the keystore file
,09-09 22:02:07.912  6698  6744 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
,09-09 22:02:07.912  6698  6744 I AcmsCertificateMngr: getKeyStoreForApplication success 
09-09 22:02:07.912  6698  6744 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
09-09 22:02:07.912  6698  6744 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,09-09 22:02:07.912  6698  6744 D AcmsServiceMonitor: Decrementing - Counter value: 1
09-09 22:02:07.912  6698  6744 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,09-09 22:02:07.912  6698  6744 D AcmsCore: This is NOT a valid MirrorLink app
,09-09 22:02:07.912  6698  6744 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
09-09 22:02:07.912  6698  6744 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-09 22:02:07.912  6698  6744 D AcmsServiceMonitor: Decrementing - Counter value: 0
09-09 22:02:07.912  6698  6744 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,09-09 22:02:07.912  6698  6698 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,09-09 22:02:07.912  6698  6698 D AcmsService: Enter onDestroy
09-09 22:02:07.912  6698  6698 I AcmsService: cleanUp(): inside service clean up
09-09 22:02:07.912  6698  6698 D AcmsCore: AcmsCore: inside DeInit
,09-09 22:02:07.912  6698  6698 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
09-09 22:02:07.912  6698  6698 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
,09-09 22:02:07.912  6698  6698 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
09-09 22:02:07.912  6698  6698 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
09-09 22:02:07.912  6698  6698 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,09-09 22:02:07.912  6698  6698 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,09-09 22:02:07.912  6698  6698 D AcmsService: killing acms process
09-09 22:02:07.912  6698  6698 I Process : Sending signal. PID: 6698 SIG: 9
,09-09 22:02:07.962  1017  1030 I ActivityManager: Process ACMS.Process (pid 6698)(adj 0) has died(31,729)
,09-09 22:02:08.492  1017  3453 D SSRM:n  : SIOP:: AP = 410
,09-09 22:02:09.022   288   288 E SMD     : DCD OFF
,09-09 22:02:09.682  1017  3473 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 22:02:10.812  1017  1057 D PackageManager: [MSG] MCS_UNBIND,
,09-09 22:02:10.812  1017  1029 I ActivityManager: Killing 6660:com.samsung.helphub/1000 (adj 15): empty #21
,09-09 22:02:11.012  1017  1506 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 22:02:11.012  1017  1506 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4268, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-09 22:02:11.012  1017  1506 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-09 22:02:11.012  1017  1506 D BatteryService: stay LED for charging
,09-09 22:02:11.012  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 22:02:11.022  1017  1017 I MotionRecognitionService: Plugged
,09-09 22:02:11.022  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 22:02:11.022  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-09 22:02:11.022  1425  1425 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-09 22:02:11.022  1425  1425 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-09 22:02:11.032  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 22:02:11.032  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-09 22:02:11.032  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-09 22:02:11.032  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-09 22:02:11.032  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-09 22:02:11.032  1180  1180 D SViewCoverView: level :100 plugged : 2
,09-09 22:02:11.032  3374  3374 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-09 22:02:11.032  3374  3486 D HeadsetStateMachine: Disconnected process message: 10
,09-09 22:02:11.222  1017  1057 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-09 22:02:12.032   288   288 E SMD     : DCD OFF,
,09-09 22:02:13.382  1017  1330 E Watchdog: !@Sync 3,
,09-09 22:02:14.032   316   316 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
09-09 22:02:14.032   316   316 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-09 22:02:15.032   288   288 E SMD     : DCD OFF
,09-09 22:02:15.132  1017  1096 V AlarmManager: waitForAlarm result :4
,09-09 22:02:15.132  1017  1096 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,09-09 22:02:15.142  1017  1017 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,09-09 22:02:15.142  1017  1017 V AlarmManagerEXT: <AppSync3 Whitelist>
09-09 22:02:15.142  1017  1017 V AlarmManagerEXT: (AppSync) ### 0 added ###
,09-09 22:02:15.142  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-09 22:02:15.142  1180  1180 D KeyguardUpdateMonitor: handleTimeUpdate
,09-09 22:02:15.152  1180  1180 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-09 22:02:15.172  1180  1180 D SecKeyguardClockView: HomeTimezone(): 1
,09-09 22:02:15.172  1180  1180 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 22:02:15.172  1180  1180 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
09-09 22:02:15.172  1180  1180 I KeyguardEffectViewController: *** don't update sliding image ***
,09-09 22:02:15.202  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 22:02:15.212  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 22:02:15.212  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 22:02:15.222  1180  1180 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,09-09 22:02:15.232  1180  1180 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 22:02:15.412  6223  6331 D Finsky  : [1144] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,09-09 22:02:15.412  6223  6223 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,09-09 22:02:15.782  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 22:02:15.782  7003  7061 I jxcore-log: 
,09-09 22:02:15.782  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 22:02:15.782  7003  7061 I jxcore-log: 
,09-09 22:02:15.792  7003  7061 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 22:02:15.792  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:15.792  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:15.792  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:15.792  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:15.792  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 22:02:15.792  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 22:02:15.792  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 22:02:15.792  7003  7061 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 22:02:15.792  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 22:02:15.792  7003  7061 I jxcore-log: 
,09-09 22:02:15.792  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 22:02:15.792  7003  7061 I jxcore-log: 
,09-09 22:02:16.442  7003  7061 D executeNativeTests: Running unit tests
,09-09 22:02:16.532  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 22:02:16.532  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3abe5033 added. We now have 2 listener(s)
,09-09 22:02:16.532  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-09 22:02:16.532  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 22:02:16.532  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 22:02:16.532  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:16.532  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 added. We now have 2 listener(s)
09-09 22:02:16.532  7003  7061 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 22:02:16.532  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 22:02:16.532  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 22:02:16.542  7003  7061 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 22:02:16.542  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:16.542  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:16.542  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:16.542  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:16.542  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 22:02:16.542  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 22:02:16.542  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 22:02:16.542  7003  7061 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 22:02:16.542  7003  7061 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 22:02:16.542  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:16.542  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 22:02:16.542  7003  7061 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 22:02:16.542  7003  7061 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 22:02:16.552  7003  7061 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-09 22:02:16.552  7003  7061 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 22:02:16.552  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 22:02:16.552  7003  7061 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 22:02:16.552  7003  7061 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 22:02:16.552  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:16.552  7003  7061 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 22:02:16.552  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:16.552  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:16.552  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:16.552  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:16.552  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 22:02:16.552  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 22:02:16.552  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3abe5033 removed from the list
09-09 22:02:16.552  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:16.552  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 removed from the list
09-09 22:02:16.552  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:16.552  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:16.552  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:16.552  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:16.552  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-09 22:02:16.552  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:16.552  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:16.552  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
,09-09 22:02:16.552  7003  7061 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported,
09-09 22:02:16.552  7003  7061 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:16.552  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:16.552  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 22:02:16.552  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:16.552  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:16.552  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:16.552  7003  7061 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3abe5033 not in the list
09-09 22:02:16.552  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:16.552  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
,09-09 22:02:16.552  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:16.552  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:16.552  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:16.552  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:16.552  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:16.552  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 22:02:16.552  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:16.552  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:16.552  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list,
,09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210],
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610],
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810],
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 22:02:16.562  7003  7061 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 22:02:16.562  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:16.562  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:16.562  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:16.562  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:16.562  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:16.562  7003  7061 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3abe5033 not in the list
,09-09 22:02:16.562  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:16.562  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:16.562  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:16.562  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:16.562  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:16.562  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 22:02:16.562  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:16.562  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:16.562  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:16.562  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:16.562  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:16.562  7003  7061 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 22:02:16.572  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 22:02:16.572  7003  7061 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 22:02:16.572  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:16.572  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:16.572  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:16.572  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:16.572  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 22:02:16.572  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 22:02:16.572  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 22:02:16.572  7003  7061 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 22:02:16.572  7003  7061 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 22:02:16.572  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 22:02:16.572  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 22:02:16.572  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 22:02:16.572  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 22:02:16.572  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 22:02:16.582  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:16.582  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:16.582  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 22:02:16.582  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 22:02:16.592  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 22:02:16.592  7003  7061 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-09 22:02:16.592  7003  7061 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-09 22:02:16.592  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 22:02:16.592  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 22:02:16.592  7003  7061 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 22:02:16.602  3374  3391 D BtGatt.GattService: registerClient() - UUID=e55467ed-a979-4d46-8a1c-78a1cac7d16e
,09-09 22:02:16.642  3374  3435 D BtGatt.GattService: onClientRegistered() - UUID=e55467ed-a979-4d46-8a1c-78a1cac7d16e, clientIf=6
,09-09 22:02:16.652  7003  7015 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-09 22:02:16.652  3374  3698 D BtGatt.GattService: start scan with filters,
09-09 22:02:16.652  3374  3483 D BtGatt.ScanManager: handling starting scan
,09-09 22:02:16.652  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 22:02:16.652  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 22:02:16.652  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 22:02:16.652  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 22:02:16.662  3374  3483 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
,09-09 22:02:16.662  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 22:02:16.662  7003  7003 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 22:02:16.662  3374  3435 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-09 22:02:16.672  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 22:02:16.672  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 22:02:16.672  3374  3483 D BtGatt.ScanManager: allow scan with filters
,09-09 22:02:16.672  3374  3483 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-09 22:02:16.672  3374  3483 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-09 22:02:16.672  3374  3435 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-09 22:02:16.672  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:16.672  3374  3483 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 22:02:16.672  3374  3483 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-09 22:02:16.682  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 22:02:16.682  3374  3435 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-09 22:02:16.682  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:16.682  3374  3435 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-09 22:02:16.682  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:16.692  7003  7061 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 22:02:16.692  7003  7061 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 22:02:16.692  7003  7061 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 22:02:16.692  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 22:02:16.692  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 22:02:16.692  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 22:02:16.702  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 22:02:16.702  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 22:02:16.702  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 22:02:16.702  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 22:02:16.702  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 22:02:16.702  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 22:02:16.702  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 22:02:16.702  3374  3391 D BtGatt.GattService: stopScan() - queue size =1
,09-09 22:02:16.702  3374  3483 D BtGatt.ScanManager: filter size is 1
,09-09 22:02:16.702  3374  3483 D BtGatt.ScanManager: delete FilterIndex - 3
,09-09 22:02:16.702  3374  3480 D BtGatt.GattService: unregisterClient() - clientIf=6,
,09-09 22:02:16.712  3374  3435 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-09 22:02:16.712  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 22:02:16.712  3374  3483 D BtGatt.ScanManager: stopping BLe Batch
,09-09 22:02:16.712  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 22:02:16.712  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 22:02:16.712  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-09 22:02:16.712  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 22:02:16.712  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 22:02:16.712  3374  3435 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-09 22:02:16.712  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:16.712  3374  3483 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 22:02:16.722  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 22:02:16.722  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 22:02:16.722  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 22:02:16.722  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 22:02:16.722  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 22:02:16.722  3374  3435 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-09 22:02:16.722  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:16.722  7003  7003 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 22:02:16.722  7003  7003 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 22:02:16.722  7003  7003 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 22:02:16.722  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 22:02:16.722  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 22:02:16.732  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 22:02:16.732  7003  7061 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3abe5033 not in the list
,09-09 22:02:16.732  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:16.732  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
,09-09 22:02:16.732  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:16.732  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:16.732  7003  7061 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 22:02:16.732  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 22:02:16.742  7003  7061 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 22:02:16.742  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:16.742  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:16.742  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:16.742  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:16.742  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 22:02:16.742  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 22:02:16.742  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 22:02:16.742  7003  7061 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 22:02:16.742  7003  7061 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 22:02:16.742  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:16.742  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:16.742  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 22:02:16.742  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 22:02:16.752  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
09-09 22:02:16.752  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 22:02:16.752  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 22:02:16.752  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 22:02:16.752  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 22:02:16.762  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 22:02:16.762  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 22:02:16.762  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 22:02:16.762  7003  7061 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 22:02:16.762  3374  3480 D BtGatt.GattService: registerClient() - UUID=eaacbc04-a927-4675-a01b-9db4fee42301
,09-09 22:02:16.802  3374  3435 D BtGatt.GattService: onClientRegistered() - UUID=eaacbc04-a927-4675-a01b-9db4fee42301, clientIf=6
,09-09 22:02:16.802  7003  7015 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-09 22:02:16.802  3374  3698 D BtGatt.GattService: start scan with filters
,09-09 22:02:16.812  3374  3483 D BtGatt.ScanManager: handling starting scan
,09-09 22:02:16.812  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 22:02:16.812  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 22:02:16.812  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 22:02:16.812  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 22:02:16.812  3374  3435 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-09 22:02:16.812  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:16.812  3374  3483 D BtGatt.ScanManager: allow scan with filters
,09-09 22:02:16.812  3374  3483 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-09 22:02:16.812  3374  3483 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-09 22:02:16.822  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 22:02:16.822  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 22:02:16.822  7003  7003 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 22:02:16.822  3374  3435 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-09 22:02:16.822  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 22:02:16.822  3374  3483 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 22:02:16.822  3374  3483 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-09 22:02:16.822  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 22:02:16.832  3374  3435 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-09 22:02:16.832  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:16.832  7003  7061 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 22:02:16.832  7003  7061 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 22:02:16.832  3374  3435 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-09 22:02:16.832  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:16.832  7003  7061 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 22:02:16.832  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:16.832  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 22:02:16.832  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:16.832  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 22:02:16.832  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 22:02:16.832  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 22:02:16.832  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 22:02:16.832  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 22:02:16.832  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 22:02:16.832  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 22:02:16.832  3374  3480 D BtGatt.GattService: stopScan() - queue size =1
,09-09 22:02:16.842  3374  3384 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 22:02:16.842  3374  3483 D BtGatt.ScanManager: filter size is 1
,09-09 22:02:16.842  3374  3483 D BtGatt.ScanManager: delete FilterIndex - 4
,09-09 22:02:16.842  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 22:02:16.842  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 22:02:16.842  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 22:02:16.842  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 22:02:16.842  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 22:02:16.842  3374  3435 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-09 22:02:16.842  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 22:02:16.842  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:16.842  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 22:02:16.842  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 22:02:16.842  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 22:02:16.842  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 22:02:16.842  3374  3483 D BtGatt.ScanManager: stopping BLe Batch
,09-09 22:02:16.852  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:16.852  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:16.852  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 22:02:16.852  7003  7061 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3abe5033 not in the list
09-09 22:02:16.852  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:16.852  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:16.852  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:16.852  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:16.852  7003  7003 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 22:02:16.852  7003  7003 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 22:02:16.852  7003  7003 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 22:02:16.852  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:16.852  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:16.852  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:16.852  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:16.852  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:16.852  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
,09-09 22:02:16.852  7003  7061 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 22:02:16.852  3374  3435 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-09 22:02:16.852  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 22:02:16.852  3374  3483 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 22:02:16.852  3374  3435 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-09 22:02:16.852  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:16.862  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 22:02:16.862  7003  7061 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 22:02:16.862  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:16.862  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:16.862  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:16.862  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:16.862  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 22:02:16.862  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 22:02:16.862  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 22:02:16.862  7003  7061 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 22:02:16.862  7003  7061 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 22:02:16.872  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 22:02:16.872  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 22:02:16.872  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 22:02:16.872  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 22:02:16.872  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 22:02:16.872  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:16.872  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:16.872  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 22:02:16.882  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 22:02:16.882  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 22:02:16.882  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 22:02:16.882  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 22:02:16.882  7003  7061 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 22:02:16.892  3374  3391 D BtGatt.GattService: registerClient() - UUID=69c6a9b1-fe38-4cd4-98fb-12d99313ea1a
,09-09 22:02:16.932  3374  3435 D BtGatt.GattService: onClientRegistered() - UUID=69c6a9b1-fe38-4cd4-98fb-12d99313ea1a, clientIf=6
,09-09 22:02:16.932  7003  7017 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-09 22:02:16.932  3374  3698 D BtGatt.GattService: start scan with filters
,09-09 22:02:16.932  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
,09-09 22:02:16.932  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
,09-09 22:02:16.932  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
09-09 22:02:16.932  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 22:02:16.932  3374  3483 D BtGatt.ScanManager: handling starting scan
09-09 22:02:16.932  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 22:02:16.932  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 22:02:16.932  7003  7003 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 22:02:16.932  3374  3435 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-09 22:02:16.932  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:16.942  3374  3483 D BtGatt.ScanManager: allow scan with filters
09-09 22:02:16.942  3374  3483 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-09 22:02:16.942  3374  3483 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-09 22:02:16.942  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 22:02:16.942  3374  3435 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-09 22:02:16.942  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:16.942  3374  3483 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 22:02:16.942  3374  3483 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-09 22:02:16.952  7003  7061 I io.jxcore.node.ConnectionHelper: start: OK
09-09 22:02:16.952  7003  7061 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:16.952  7003  7061 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 22:02:16.952  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:16.952  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 22:02:16.952  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:16.952  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 22:02:16.952  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 22:02:16.952  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 22:02:16.952  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 22:02:16.952  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 22:02:16.952  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 22:02:16.952  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 22:02:16.952  3374  3435 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-09 22:02:16.952  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:16.952  3374  3698 D BtGatt.GattService: stopScan() - queue size =1
,09-09 22:02:16.952  3374  3480 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 22:02:16.952  3374  3435 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-09 22:02:16.952  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:16.962  3374  3483 D BtGatt.ScanManager: filter size is 1
,09-09 22:02:16.962  3374  3483 D BtGatt.ScanManager: delete FilterIndex - 5
,09-09 22:02:16.962  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 22:02:16.962  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 22:02:16.962  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-09 22:02:16.962  3374  3435 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-09 22:02:16.962  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:16.962  3374  3483 D BtGatt.ScanManager: stopping BLe Batch
09-09 22:02:16.972  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-09 22:02:16.972  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 22:02:16.972  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 22:02:16.972  3374  3435 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-09 22:02:16.972  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:16.972  3374  3483 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 22:02:16.972  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 22:02:16.972  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 22:02:16.972  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 22:02:16.972  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 22:02:16.972  3374  3435 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-09 22:02:16.972  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:16.982  7003  7003 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 22:02:16.982  7003  7061 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:16.982  7003  7061 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 22:02:16.982  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:16.982  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:16.982  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:16.982  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:16.982  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 22:02:16.982  7003  7061 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3abe5033 not in the list
09-09 22:02:16.982  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:16.982  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:16.982  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:16.982  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:16.982  7003  7003 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 22:02:16.982  7003  7003 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 22:02:16.982  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:16.982  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:16.982  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:16.982  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:16.982  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 22:02:16.982  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:16.982  7003  7061 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-09 22:02:16.982  7003  7061 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 22:02:16.982  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:16.982  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:16.982  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:16.982  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,09-09 22:02:16.982  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:16.982  7003  7061 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3abe5033 not in the list
09-09 22:02:16.982  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 22:02:16.982  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:16.982  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:16.982  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 22:02:16.982  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:16.982  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:16.982  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:16.982  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:16.982  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:16.982  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:16.982  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list,
09-09 22:02:16.982  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 22:02:16.982  7003  7061 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-09 22:02:16.982  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:16.982  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
09-09 22:02:16.982  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 22:02:16.982  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:16.982  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:16.982  7003  7061 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3abe5033 not in the list
09-09 22:02:16.982  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 22:02:16.982  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:16.982  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:16.982  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 22:02:16.982  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:16.982  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:16.982  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:16.982  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 22:02:16.982  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:16.982  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:16.982  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:16.982  7003  7061 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-09 22:02:16.982  7003  7061 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:16.982  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 22:02:16.982  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:16.982  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-09 22:02:16.982  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:16.982  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:16.982  7003  7061 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3abe5033 not in the list,
09-09 22:02:16.982  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:16.982  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
,09-09 22:02:16.982  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:16.982  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:16.982  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:16.982  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:16.982  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:16.992  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 22:02:16.992  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:16.992  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:16.992  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:16.992  7003  7061 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-09 22:02:16.992  7003  7061 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 22:02:16.992  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
09-09 22:02:16.992  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:16.992  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 22:02:16.992  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:16.992  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:16.992  7003  7061 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3abe5033 not in the list
,09-09 22:02:16.992  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:16.992  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:16.992  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 22:02:16.992  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:16.992  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:16.992  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 22:02:16.992  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:16.992  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:16.992  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 22:02:16.992  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:16.992  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:16.992  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 22:02:16.992  7003  7061 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 22:02:16.992  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 22:02:16.992  7003  7061 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 22:02:16.992  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 22:02:16.992  7003  7061 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 22:02:16.992  7003  7061 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:16.992  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:16.992  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:16.992  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:16.992  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 22:02:16.992  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:16.992  7003  7061 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3abe5033 not in the list
09-09 22:02:16.992  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:16.992  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:16.992  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 22:02:16.992  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:16.992  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:16.992  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:16.992  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:16.992  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 22:02:16.992  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:16.992  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:16.992  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:16.992  7003  7061 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 22:02:17.002  7003  7061 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 22:02:17.002  7003  7061 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 22:02:17.002  7003  7061 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210],
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 22:02:17.002  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 22:02:17.002  7003  7061 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 22:02:17.002  7003  7061 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 22:02:17.002  7003  7061 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 22:02:17.002  7003  7061 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-09 22:02:17.002  7003  7061 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 22:02:17.002  7003  7061 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 22:02:17.002  7003  7061 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 22:02:17.002  7003  7061 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 22:02:17.002  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-09 22:02:17.002  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 22:02:17.002  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 22:02:17.002  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-09 22:02:17.012  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,09-09 22:02:17.012  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 22:02:17.012  7003  7061 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 22:02:17.012  7003  7061 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 22:02:17.012  7003  7061 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 22:02:17.012  7003  7061 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 22:02:17.012  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:17.012  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:17.012  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:17.012  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.012  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:17.012  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 22:02:17.012  7003  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1384)
09-09 22:02:17.012  7003  7061 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3abe5033 not in the list
09-09 22:02:17.012  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:17.012  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:17.012  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 22:02:17.012  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.012  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.012  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.012  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.012  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 22:02:17.012  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:17.012  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:17.012  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:17.012  7003  7061 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 22:02:17.012  7003  7061 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 22:02:17.012  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:17.012  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:17.012  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:17.012  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.012  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:17.012  7003  7061 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3abe5033 not in the list
09-09 22:02:17.012  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:17.012  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:17.012  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:17.012  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 22:02:17.012  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.012  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.012  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.012  7003  7073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1384
09-09 22:02:17.012  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 22:02:17.012  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:17.012  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:17.012  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:17.012  7003  7061 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 22:02:17.012  7003  7061 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 22:02:17.012  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:17.012  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:17.012  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:17.012  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.012  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.012  7003  7061 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3abe5033 not in the list
09-09 22:02:17.012  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:17.012  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:17.012  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:17.012  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 22:02:17.012  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.012  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.012  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:17.022  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:17.022  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 22:02:17.022  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:17.022  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:17.022  7003  7061 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 22:02:17.022  7003  7061 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 22:02:17.022  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 22:02:17.022  7003  7061 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 22:02:17.022  7003  7061 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 22:02:17.022  7003  7061 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 22:02:17.022  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 22:02:17.022  7003  7061 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 22:02:17.022  7003  7061 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 22:02:17.022  7003  7061 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 22:02:17.022  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 22:02:17.022  7003  7061 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,09-09 22:02:17.022  7003  7061 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:17.022  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:17.022  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:17.022  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:17.022  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.022  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.022  7003  7061 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3abe5033 not in the list,
09-09 22:02:17.022  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:17.022  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:17.022  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:17.022  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.022  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.022  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.022  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.022  7003  7072 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-09 22:02:17.022  7003  7072 D BluetoothSocket: connect(): myUserId = 0
09-09 22:02:17.022  7003  7072 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 22:02:17.022  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:17.022  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:17.022  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:17.022  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
,09-09 22:02:17.032  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:17.032  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.032  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.032  7003  7061 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3abe5033 not in the list
09-09 22:02:17.032  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:17.032  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:17.032  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:17.032  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.032  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.032  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:17.032  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:17.032  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:17.032  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.032  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.032  7003  7061 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3abe5033 not in the list
,09-09 22:02:17.032  7003  7061 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:17.032  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:17.032  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:17.032  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:17.032  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.032  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.032  7003  7061 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3abe5033 not in the list
09-09 22:02:17.032  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:17.032  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:17.032  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:17.032  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.032  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.032  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.032  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.032  3374  3391 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 22:02:17.032  7003  7072 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
,09-09 22:02:17.032  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:17.032  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:17.032  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:17.032  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
,09-09 22:02:17.032  7003  7061 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 22:02:17.032  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-09 22:02:17.032  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 22:02:17.032  7003  7061 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 22:02:17.032  7003  7061 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 22:02:17.032  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 22:02:17.032  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 22:02:17.032  7003  7003 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 22:02:17.032  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:17.032  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 22:02:17.032  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 22:02:17.032  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-09 22:02:17.032  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.032  7003  7061 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 22:02:17.032  7003  7061 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3abe5033 not in the list
09-09 22:02:17.032  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:17.032  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 22:02:17.032  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 22:02:17.032  7003  7003 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 22:02:17.032  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 22:02:17.032  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.032  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.032  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 22:02:17.032  7003  7074 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 22:02:17.032  7003  7003 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 22:02:17.032  7003  7074 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 22:02:17.032  7003  7003 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 22:02:17.032  7003  7003 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 22:02:17.032  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:17.032  7003  7061 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 22:02:17.032  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:17.032  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:17.032  7003  7003 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 22:02:17.032  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:17.032  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.032  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.032  7003  7061 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3abe5033 not in the list
09-09 22:02:17.032  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:17.032  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:17.032  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:17.032  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.032  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.032  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.032  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.042  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:17.042  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:17.042  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:17.042  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:17.042  7003  7061 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 22:02:17.042  7003  7061 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 22:02:17.042  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 22:02:17.042  7003  7061 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 22:02:17.042  7003  7061 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:17.042  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:17.042  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:17.042  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:17.042  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.042  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.042  7003  7061 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3abe5033 not in the list
09-09 22:02:17.042  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:17.042  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:17.042  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:17.042  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.042  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.042  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.042  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.042  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:17.042  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:17.042  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:17.042  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:17.042  7003  7061 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:17.042  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:17.042  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:17.042  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:17.042  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.042  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.042  7003  7061 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3abe5033 not in the list
09-09 22:02:17.042  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:17.042  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:17.042  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:17.042  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.042  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.042  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.042  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.042  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:17.042  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:17.042  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:17.042  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:17.052  7003  7061 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:17.052  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:17.052  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:17.052  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:17.052  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.052  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.052  7003  7061 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3abe5033 not in the list
09-09 22:02:17.052  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:17.052  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:17.052  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:17.052  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.052  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.052  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:17.052  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:17.052  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:17.052  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:17.052  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:17.052  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39e9dff0 not in the list
09-09 22:02:17.052  7003  7061 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 22:02:17.052  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 22:02:17.052  7003  7061 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 22:02:17.052  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 22:02:17.052  7003  7061 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 22:02:17.052  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 22:02:17.052  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 22:02:17.052  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-09 22:02:17.052  7003  7061 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-09 22:02:17.052  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 22:02:17.052  7003  7061 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 22:02:17.052  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 22:02:17.052  7003  7061 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 22:02:17.052  7003  7061 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-09 22:02:17.052  7003  7061 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-09 22:02:17.052  7003  7061 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-09 22:02:17.052  7003  7061 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 22:02:17.052  7003  7061 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-09 22:02:17.052  7003  7061 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-09 22:02:17.052  7003  7061 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-09 22:02:17.052  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:17.052  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2251b152 added. We now have 2 listener(s)
09-09 22:02:17.052  7003  7061 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 22:02:17.052  7003  7061 D BluetoothAdapter: enable()
09-09 22:02:17.062  7003  7061 D BluetoothAdapter: enable(): BT is already enabled..!
09-09 22:02:17.062  1017  1078 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-09 22:02:17.062  1017  1078 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 22:02:17.062  1017  1078 D SecContentProvider2: mCursor = null
09-09 22:02:17.062  1017  1078 D WifiService: setWifiEnabled: true pid=7003, uid=10170
09-09 22:02:17.062  1017  1078 W ActivityManager: Permission Denial: getCurrentUser() from pid=7003, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-09 22:02:17.062  1017  1078 W WifiService: Failed getting userId using ActivityManagerNative
09-09 22:02:17.062  1017  1078 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7003, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-09 22:02:17.062  1017  1078 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-09 22:02:17.062  1017  1078 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-09 22:02:17.062  1017  1078 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-09 22:02:17.062  1017  1078 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-09 22:02:17.062  1017  1078 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-09 22:02:17.062  1017  1078 D SettingsProvider: name = wifi_on
09-09 22:02:17.062  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:17.062  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@383bac23 added. We now have 3 listener(s)
09-09 22:02:17.062  7003  7061 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 22:02:17.072  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:17.072  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@25ed2520 added. We now have 4 listener(s)
09-09 22:02:17.072  7003  7061 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 22:02:17.072  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:17.072  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e08bed9 added. We now have 5 listener(s)
09-09 22:02:17.072  7003  7061 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 22:02:17.072  1017  1320 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-09 22:02:17.072  1017  1320 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 22:02:17.072  1017  1320 D SecContentProvider2: mCursor = null
09-09 22:02:17.072  1017  1320 D WifiService: setWifiEnabled: false pid=7003, uid=10170
09-09 22:02:17.072  1017  1320 D SettingsProvider: name = wifi_on
09-09 22:02:17.082  7003  7061 D BluetoothAdapter: disable()
09-09 22:02:17.082  1017  1129 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 22:02:17.082  1354  1354 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 22:02:17.082  1354  1354 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-09 22:02:17.082  1354  1354 I wpa_supplicant: P2P: Current p2p state = IDLE
09-09 22:02:17.082  1354  1354 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-09 22:02:17.092  1017  3703 D SettingsProvider: name = bluetooth_on
09-09 22:02:17.092  1017  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 22:02:17.102  3374  3432 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
09-09 22:02:17.102  1017  4465 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:17.102  3374  3432 D BluetoothAdapterProperties: Setting state to 13
09-09 22:02:17.102  1017  4465 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-09 22:02:17.102  3374  3432 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 22:02:17.102  3374  3432 D BluetoothAdapterService: Bluetooth PBAP supproted is true,
09-09 22:02:17.102  3374  3432 D BluetoothAdapterService: updateAdapterState state is 13,
09-09 22:02:17.102  1017  4465 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:17.102  1017  4465 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:17.102  1017  4465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
09-09 22:02:17.102  3374  3374 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-09 22:02:17.112  1017  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-09 22:02:17.102  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 22:02:17.112  1354  1354 I wpa_supplicant: Scan aborted because the firmware maybe busy.
09-09 22:02:17.112  1354  1354 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
09-09 22:02:17.112  1354  1354 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
09-09 22:02:17.112  3374  3374 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@64a737c, channel: 19, state: LISTENING
09-09 22:02:17.112  3374  3374 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@64a737c, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@290b8be4, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2acb2405mSocket: android.net.LocalSocket@3e560c5a impl:android.net.LocalSocketImpl@2a02de8b fd:FileDescriptor[80]
09-09 22:02:17.112  3374  3374 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3e560c5a impl:android.net.LocalSocketImpl@2a02de8b fd:FileDescriptor[80]
09-09 22:02:17.112  1017  1129 E WifiNative-wlan0: do suspend true
09-09 22:02:17.112  3374  3432 D BluetoothAdapterService: Autoconnection is available 
09-09 22:02:17.112  3374  3432 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-09 22:02:17.112  3374  3432 D BluetoothAdapterService: terminating service from this receiver
09-09 22:02:17.112  4988  4988 D BluetoothPbap: Proxy object disconnected
09-09 22:02:17.112  4988  4988 D PbapServerProfile: Bluetooth service disconnected
,09-09 22:02:17.112  1017  1499 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:17.112  1017  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:17.112  1017  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:17.112  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:17.112  7003  7061 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 22:02:17.112  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:17.112  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:17.112  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:17.112  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 22:02:17.112  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 22:02:17.112  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 22:02:17.112  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 22:02:17.122  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:17.122  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,09-09 22:02:17.122  3374  3432 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 22:02:17.122  3374  3432 D BluetoothAdapterProperties: mDiscovering is false
,09-09 22:02:17.122  1017  3703 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-09 22:02:17.122  3374  3432 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-09 22:02:17.122  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:17.122  7003  7061 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 22:02:17.122  7003  7061 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 22:02:17.122  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:17.132  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:17.132  1180  1180 D BluetoothTile:  onBluetoothStateChange:
,09-09 22:02:17.132  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 22:02:17.132  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:17.132  1180  1180 D BluetoothTile:  getBluetoothState : 13
09-09 22:02:17.132  1180  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 22:02:17.132  1874  1874 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 22:02:17.132  1180  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 22:02:17.142  1017  1499 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 22:02:17.142  1180  1731 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-09 22:02:17.142  1017  1477 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-09 22:02:17.142  4988  4988 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:17.142  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 22:02:17.142  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-09 22:02:17.152  3374  3374 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@32defb81, channel: 5, state: LISTENING,
09-09 22:02:17.152  3374  3374 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@32defb81, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@14e2384d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@20589426mSocket: android.net.LocalSocket@3e3ed867 impl:android.net.LocalSocketImpl@2d5bb614 fd:FileDescriptor[82]
09-09 22:02:17.152  3374  3374 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3e3ed867 impl:android.net.LocalSocketImpl@2d5bb614 fd:FileDescriptor[82]
09-09 22:02:17.152  3374  3374 I BtOppRfcommListener: stopping Accept Thread
09-09 22:02:17.152  3374  3374 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@28fecebd, channel: 12, state: LISTENING
,09-09 22:02:17.152  3374  3374 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@28fecebd, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c760a6f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3aa9ccb2mSocket: android.net.LocalSocket@3a569403 impl:android.net.LocalSocketImpl@35481f80 fd:FileDescriptor[86]
09-09 22:02:17.152  3374  3374 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3a569403 impl:android.net.LocalSocketImpl@35481f80 fd:FileDescriptor[86]
09-09 22:02:17.152  3374  5473 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 22:02:17.152  3374  5473 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 22:02:17.152  3374  3435 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 22:02:17.152  3374  3435 D BluetoothAdapterProperties: Scan Mode:20
,09-09 22:02:17.152  7003  7003 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:17.152  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:17.152  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:17.152  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:17.152  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:17.152  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 22:02:17.152  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 22:02:17.152  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 22:02:17.152  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 22:02:17.152  3374  3432 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-09 22:02:17.152  3374  3432 E bt-btif : btif_dm_generic_evtsock_thread_handle:6, rfc_init:1, vhci_init:1
,09-09 22:02:17.162  3374  3432 E bt-btif : cmd socket is not created
09-09 22:02:17.162  7003  7072 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3f92e77f, channel: -1, state: INIT
,09-09 22:02:17.162  7003  7072 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3f92e77f, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f4f734c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2bd6f95mSocket: android.net.LocalSocket@4e618aa impl:android.net.LocalSocketImpl@2ef87c9b fd:FileDescriptor[106]
09-09 22:02:17.162  7003  7072 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@4e618aa impl:android.net.LocalSocketImpl@2ef87c9b fd:FileDescriptor[106]
09-09 22:02:17.162  3374  3374 V BluetoothOppManager: cleanUp...
09-09 22:02:17.162  7003  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1384)
09-09 22:02:17.162  3374  3437 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,09-09 22:02:17.162  3374  3432 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-09 22:02:17.162  7003  7003 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:17.162  7003  7003 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 22:02:17.162  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:17.172  4988  4988 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 22:02:17.172  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:17.172  1017  1030 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-09 22:02:17.172  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 22:02:17.172  3374  3437 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
,09-09 22:02:17.172  3374  3437 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
09-09 22:02:17.172  3374  3437 W bt-btif : invalid rfc slot id: 4
,09-09 22:02:17.172  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:17.172  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:17.172  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
09-09 22:02:17.172  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:17.182  3374  3437 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-09 22:02:17.182  3374  3437 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 22:02:17.182  3374  3437 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 22:02:17.182  3374  3437 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 22:02:17.182  3374  3437 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 22:02:17.182  3374  3437 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-09 22:02:17.182  2629  2629 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 22:02:17.182  1017  1128 D WifiP2pService: InactiveState{ what=143375 }
09-09 22:02:17.182  1017  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 22:02:17.182   278   991 D CommandListener: Clearing all IP addresses on wlan0
,09-09 22:02:17.192  2629  2666 V NativeCrypto: Read error: ssl=0xb89bd8c0: I/O error during system call, Connection timed out
,09-09 22:02:17.192  1017  1131 E ConnectivityService: updateNetworkInfo()
,09-09 22:02:17.192  1017  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 22:02:17.192  1017  1131 E ConnectivityService: updateNetworkInfo()
09-09 22:02:17.192  1017  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,09-09 22:02:17.192  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 22:02:17.192  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,09-09 22:02:17.192  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:17.192  2629  2666 V NativeCrypto: SSL shutdown failed: ssl=0xb89bd8c0: I/O error during system call, Broken pipe
09-09 22:02:17.192  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:17.192  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:17.192  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:17.202  1017  1128 D WifiP2pService: InactiveState{ what=131204 }
09-09 22:02:17.202  1017  1128 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-09 22:02:17.202  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 22:02:17.202  1017  1750 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-09 22:02:17.202  1017  1509 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
09-09 22:02:17.202  1017  1750 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-09 22:02:17.202  1017  1128 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-09 22:02:17.202  1017  1750 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
,09-09 22:02:17.202  1017  1750 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-09 22:02:17.202  1017  1750 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
09-09 22:02:17.202  1017  1129 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 22:02:17.202  1017  1750 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 22:02:17.212  1017  1750 I qtaguid : Tagging socket 353 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1017, getuid(): 1000
,09-09 22:02:17.212  4988  4988 D DockEventReceiver: finishStartingService: stopping service
,09-09 22:02:17.212  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 22:02:17.212  1017  1017 D RttService: SCAN_AVAILABLE : 1
,09-09 22:02:17.222  1017  1152 D RttService: EnabledState got{ when=-3ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-09 22:02:17.222  1017  1151 D WifiScanningService: DefaultState got{ when=-4ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 22:02:17.222  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 22:02:17.222  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
09-09 22:02:17.222  1017  1750 I qtaguid : Untagging socket 353
09-09 22:02:17.222  1017  1750 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 22:02:17.222  4988  4988 D BluetoothNotiBroadcastReceiver: onReceive
09-09 22:02:17.222  1017  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-09 22:02:17.222  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 22:02:17.222  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:17.222  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 22:02:17.222  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-09 22:02:17.232  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:17.232  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:17.232  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:17.232  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:17.232  1017  1128 D WifiP2pService: P2pDisablingState
09-09 22:02:17.232  1017  1128 D WifiP2pService: P2pDisablingState{ what=147458 }
09-09 22:02:17.232  1017  1128 D WifiP2pService: p2p socket connection lost
09-09 22:02:17.232  1017  1128 D WifiP2pService: P2pDisabledState
,09-09 22:02:17.232  1017  1129 E WifiNative-wlan0: do suspend true
,09-09 22:02:17.232  1017  1128 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-09 22:02:17.232  1017  1128 D WifiP2pService: DefaultState{ what=143375 }
,09-09 22:02:17.242  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:17.242  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-09 22:02:17.252  1017  1524 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-09 22:02:17.252  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 22:02:17.252  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null,
09-09 22:02:17.252  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-09 22:02:17.252  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 22:02:17.252  1017  1047 D WifiDisplayController: disconnect
09-09 22:02:17.252  1017  1047 D WifiDisplayController: updateConnection,
09-09 22:02:17.252  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false,
09-09 22:02:17.252  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false],
09-09 22:02:17.252  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 22:02:17.252  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
09-09 22:02:17.252  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:17.252  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 22:02:17.252  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 22:02:17.252  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 22:02:17.252  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 22:02:17.252  1017  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:17.252  1017  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:17.252  1017  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:17.252  1017  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:17.252  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:17.252  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:17.252  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:17.252  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:17.262   278   987 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
09-09 22:02:17.262   278   987 D Netd    : getNetworkForDns: using netid 0 for uid 1000
09-09 22:02:17.262   278   991 D CommandListener: Clearing all IP addresses on wlan0
09-09 22:02:17.262  1017  1131 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-09 22:02:17.262  1017  1131 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:17.262  1017  1131 V NetworkStats: updateIfacesLocked()
09-09 22:02:17.262  1017  1131 V NetworkStats: performPollLocked(flags=0x1)
09-09 22:02:17.262  1017  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 22:02:17.262  1017  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 22:02:17.262  1017  1131 V NetworkStats: performPollLocked() took 4ms
09-09 22:02:17.262  1017  1131 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:17.262  1017  1750 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-09 22:02:17.262  1017  1750 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-09 22:02:17.272  7085  7085 E Zygote  : MountEmulatedStorage()
09-09 22:02:17.272  7085  7085 E Zygote  : v2
09-09 22:02:17.272  7085  7085 I libpersona: KNOX_SDCARD checking this for 10055
09-09 22:02:17.272  7085  7085 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:17.272  7085  7085 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-09 22:02:17.272  1017  1524 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7085 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
09-09 22:02:17.272  1354  1354 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED,
09-09 22:02:17.272  7085  7085 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 22:02:17.282  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-09 22:02:17.282  1017  1131 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
09-09 22:02:17.282  7085  7085 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 22:02:17.282  1017  1131 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 22:02:17.282  1180  1701 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,09-09 22:02:17.282  1017  1131 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-09 22:02:17.282  1478  1478 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 22:02:17.282  1017  1131 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-09 22:02:17.282  1478  1478 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 22:02:17.282  1017  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 22:02:17.282  1017  1128 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-09 22:02:17.282  1017  1750 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-5ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 22:02:17.282  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-09 22:02:17.292  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:17.292  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:17.292  1017  1131 D ConnectivityService: nai.networkMonitor.doQuit()
09-09 22:02:17.292  1017  1131 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-09 22:02:17.292  1017  1131 E ConnectivityService: updateNetworkInfo()
09-09 22:02:17.292  1017  1131 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 22:02:17.292  1017  1131 E ConnectivityService: updateNetworkInfo()
,09-09 22:02:17.302  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 22:02:17.302  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-09 22:02:17.302  1180  1180 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-09 22:02:17.302  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:17.302  1017  3703 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 22:02:17.302  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 22:02:17.302  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:17.302  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:17.302  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:17.302  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:17.302  1017  1129 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 22:02:17.302  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 22:02:17.302  1017  1129 D SecContentProvider2: mCursor = null
,09-09 22:02:17.302  1180  1180 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 22:02:17.302  7085  7085 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:17.302  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 22:02:17.302  7085  7085 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:17.302  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:17.302  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 22:02:17.302  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:17.302  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:17.312  4988  4988 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 22:02:17.312  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:17.312  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-09 22:02:17.312  1017  1132 D Tethering: MasterInitialState.processMessage what=3
09-09 22:02:17.312  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:17.312  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:17.312  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-09 22:02:17.312  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 22:02:17.312  1180  1731 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 22:02:17.312  1180  1180 D HotspotTile: onReceive : 0, 0
,09-09 22:02:17.312  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:17.312  1017  1126 V NetworkStats: updateIfacesLocked()
09-09 22:02:17.312  1017  1126 V NetworkStats: performPollLocked(flags=0x1)
09-09 22:02:17.312  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 22:02:17.312  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 22:02:17.312  7003  7003 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:17.312  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:17.312  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:17.312  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:17.312  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 22:02:17.312  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 22:02:17.312  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:17.312  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:17.312  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:17.312  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:17.312  1017  1126 V NetworkStats: performPollLocked() took 5ms
,09-09 22:02:17.322  7003  7003 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:17.322  7003  7003 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 22:02:17.322  1180  1180 D StatusBar.NetworkController: EthernetConnected: false
09-09 22:02:17.322  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-09 22:02:17.322  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-09 22:02:17.322  1180  1180 D StatusBar.NetworkController: updateDataNetType()
,09-09 22:02:17.322  7003  7003 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:17.322  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:17.322  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:17.322  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:17.322  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 22:02:17.322  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 22:02:17.322  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:17.322  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:17.322  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:17.322  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:17.322  1017  1127 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-09 22:02:17.322  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 22:02:17.322  1180  1180 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-09 22:02:17.322  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:17.322  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:17.322  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:17.322  7003  7003 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:17.322  7003  7003 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 22:02:17.322  1180  1180 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-09 22:02:17.322  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 20 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-09 22:02:17.322  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-09 22:02:17.322  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,09-09 22:02:17.332  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 22:02:17.332  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 22:02:17.332  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 22:02:17.332  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:17.332  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:17.332  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:17.332  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:17.332  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:17.332  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:17.352  7085  7085 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-09 22:02:17.362  3374  3432 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-09 22:02:17.362  3374  3432 D BtConfig.SecureMode: isSecureModeOn:false
09-09 22:02:17.362  3374  3432 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,09-09 22:02:17.362  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
09-09 22:02:17.362  3374  3432 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
,09-09 22:02:17.362  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-09 22:02:17.362  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-09 22:02:17.362  3374  3432 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-09 22:02:17.362  1017  3700 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:17.362  1017  3700 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-09 22:02:17.362  1017  3700 W ActivityManager: userId = 0, bbcId = -10000,
09-09 22:02:17.362  1017  3700 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:17.362  1017  3700 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:17.372  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-09 22:02:17.372  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-09 22:02:17.372  3374  3432 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-09 22:02:17.372  3374  3374 D HeadsetService: Received stop request...Stopping profile...
,09-09 22:02:17.372  1017  1499 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:17.372  1017  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 22:02:17.372  1017  1499 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:17.372  1017  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:17.372  1017  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:17.372  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc,
09-09 22:02:17.372  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-09 22:02:17.372  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,09-09 22:02:17.372  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-09 22:02:17.382  3374  3432 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-09 22:02:17.382  1017  1509 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:17.382  3374  3374 D A2dpService: Received stop request...Stopping profile...
09-09 22:02:17.382  1017  1509 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-09 22:02:17.382  3374  3504 D A2dpStateMachine: Exit Disconnected: -1
09-09 22:02:17.382  1017  1509 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:17.382  1017  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:17.382  1017  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 22:02:17.382  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-09 22:02:17.382  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-09 22:02:17.382  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
,09-09 22:02:17.382  3374  3432 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-09 22:02:17.382  4988  4988 D HeadsetProfile: Bluetooth service disconnected
,09-09 22:02:17.382  1017  1017 D BluetoothA2dp: Proxy object disconnected
,09-09 22:02:17.382  1017  1078 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 22:02:17.382  1017  1078 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-09 22:02:17.382  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-09 22:02:17.382  1017  1078 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:17.382  1017  1078 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:17.382  1017  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:17.392  4988  4988 D BluetoothA2dp: Proxy object disconnected
09-09 22:02:17.392  4988  4988 D A2dpProfile: Bluetooth service disconnected
09-09 22:02:17.392  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-09 22:02:17.392  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-09 22:02:17.392  3374  3432 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-09 22:02:17.392  1017  3703 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 22:02:17.392  1017  3703 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 22:02:17.392  1017  3703 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:17.392  1017  3703 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:17.392  1017  3703 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:17.392  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-09 22:02:17.392  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-09 22:02:17.392  3374  3432 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-09 22:02:17.392  7085  7085 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-09 22:02:17.392  7085  7085 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-09 22:02:17.392  7085  7085 D UserAnalysis: Create SecureDbHelper
,09-09 22:02:17.392  1017  4071 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 22:02:17.392  1017  4071 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 22:02:17.392  1017  4071 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:17.392  1017  4071 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:17.392  1017  4071 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:17.402  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-09 22:02:17.402  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-09 22:02:17.402  3374  3432 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-09 22:02:17.402  1017  3700 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:17.402  1017  3700 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 22:02:17.402  1017  3700 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:17.402  1017  3700 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:17.402  1017  3700 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:17.402  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-09 22:02:17.402  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-09 22:02:17.402  3374  3432 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-09 22:02:17.402  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-09 22:02:17.402  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 22:02:17.402  7085  7085 D IntelligenceServiceApplication: onCreate()
,09-09 22:02:17.402  3374  3432 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-09 22:02:17.402  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-09 22:02:17.402  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-09 22:02:17.402  3374  3432 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-09 22:02:17.402  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-09 22:02:17.402  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-09 22:02:17.412  3374  3432 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-09 22:02:17.412  3374  3432 D BluetoothAdapterState: Stopping profile services that were post enabled
09-09 22:02:17.412  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-09 22:02:17.412  3374  3374 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 22:02:17.412  3374  3374 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-09 22:02:17.412  1017  1078 I ActivityManager: Killing 6170:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,09-09 22:02:17.412  3374  3374 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-09 22:02:17.412  3374  3374 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-09 22:02:17.412  3374  3374 D HidService: Received stop request...Stopping profile...
09-09 22:02:17.412  3374  3374 D HidService: Stopping Bluetooth HidService
09-09 22:02:17.412  3374  3374 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 22:02:17.412  3374  3374 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-09 22:02:17.412  3374  3374 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 22:02:17.412  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
,09-09 22:02:17.422  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-09 22:02:17.422  3374  3374 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 22:02:17.422  3374  3374 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-09 22:02:17.422  3374  3374 D BluetoothA2dp: Proxy object disconnected
09-09 22:02:17.422  3374  3374 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,09-09 22:02:17.422  7085  7085 D IntelligenceServiceApplication: no applications having user consent for prediction
09-09 22:02:17.422  3374  3505 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-09 22:02:17.422  3374  3374 I GKI_LINUX: GKI_exit_task 2 done
09-09 22:02:17.422  3374  3374 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-09 22:02:17.422  3374  3374 D HealthService: Received stop request...Stopping profile...
09-09 22:02:17.422  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
,09-09 22:02:17.422  4988  4988 D BluetoothInputDevice: Proxy object disconnected
,09-09 22:02:17.422  4988  4988 D HidProfile: Bluetooth service disconnected
,09-09 22:02:17.422  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 22:02:17.422  1017  1210 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-09 22:02:17.422  3374  3374 D PanService: Received stop request...Stopping profile...
,09-09 22:02:17.422  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
,09-09 22:02:17.432  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 22:02:17.432  7085  7085 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-09 22:02:17.432  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 22:02:17.432  4988  4988 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 22:02:17.432  4988  4988 D PanProfile: Bluetooth service disconnected
09-09 22:02:17.432  3374  3374 D BluetoothMapService: Received stop request...Stopping profile...
,09-09 22:02:17.432  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 22:02:17.432  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 22:02:17.432  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 22:02:17.432  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
09-09 22:02:17.432  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 22:02:17.432  4988  4988 D BluetoothMap: Proxy object disconnected
09-09 22:02:17.432  4988  4988 D MapProfile: Bluetooth service disconnected
,09-09 22:02:17.432  3374  3374 D SapService: Received stop request...Stopping profile...
09-09 22:02:17.432  3374  3374 D SapService: Stopping Bluetooth SapService
09-09 22:02:17.432  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
,09-09 22:02:17.432  4988  4988 D Bluetoothsap: BluetoothSAP Proxy object disconnected
,09-09 22:02:17.442  4988  4988 D SapProfile: Bluetooth service disconnected
,09-09 22:02:17.442  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-09 22:02:17.442  3374  3374 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-09 22:02:17.442  3374  3374 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:17.442  3374  3374 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:17.442  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
09-09 22:02:17.442  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-09 22:02:17.442  3374  3374 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-09 22:02:17.442  3374  3374 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:17.442  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-09 22:02:17.442  3374  3374 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:17.442  3374  3374 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 22:02:17.442  3374  3374 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 22:02:17.442  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-09 22:02:17.442  3374  3374 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-09 22:02:17.442  3374  3374 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:17.442  3374  3374 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:17.442  3374  3374 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 22:02:17.442  3374  3374 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-09 22:02:17.442  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-09 22:02:17.442  3374  3374 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-09 22:02:17.442  3374  3374 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 22:02:17.442  3374  3374 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-09 22:02:17.442  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-09 22:02:17.442  3374  3374 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-09 22:02:17.442  3374  3374 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-09 22:02:17.442  3374  3374 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
09-09 22:02:17.442  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:17.442  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:17.442  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 22:02:17.442  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:17.442  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-09 22:02:17.442  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:17.442  1354  1354 I wpa_supplicant: Blacklist: Clear (all) 
09-09 22:02:17.442  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 22:02:17.442  7085  7085 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
09-09 22:02:17.442  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-09 22:02:17.442  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 22:02:17.442  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 22:02:17.452  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 22:02:17.452  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 22:02:17.452  7107  7107 E Zygote  : MountEmulatedStorage()
09-09 22:02:17.452  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 22:02:17.452  7107  7107 I libpersona: KNOX_SDCARD checking this for 10105
09-09 22:02:17.452  7107  7107 E Zygote  : v2
09-09 22:02:17.452  7107  7107 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:17.452  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 22:02:17.452  7107  7107 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 22:02:17.462  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 22:02:17.462  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 22:02:17.462  7107  7107 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 22:02:17.462  7107  7107 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 22:02:17.462  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 22:02:17.462  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 22:02:17.462  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 22:02:17.462  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 22:02:17.462  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 22:02:17.462  1017  1030 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7107 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-09 22:02:17.462  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 22:02:17.472  1354  1354 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-09 22:02:17.472  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 22:02:17.472  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 22:02:17.472  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 22:02:17.472  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 22:02:17.472  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-09 22:02:17.472  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 22:02:17.472  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-09 22:02:17.472  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 22:02:17.472  3374  3432 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-09 22:02:17.472  3374  3432 D BluetoothAdapterProperties: Setting state to 10
09-09 22:02:17.472  3374  3432 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-09 22:02:17.472  3374  3432 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 22:02:17.472  3374  3432 D BluetoothAdapterService: updateAdapterState state is 10
09-09 22:02:17.472  3374  3432 D BluetoothAdapterService: Autoconnection is available 
09-09 22:02:17.472  3374  3432 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-09 22:02:17.472  3374  3432 I BluetoothAdapterState: Entering OffState
,09-09 22:02:17.472  4988  5000 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-09 22:02:17.472  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:17.472  1017  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 22:02:17.472  4988  4998 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 22:02:17.472  4988  5000 D Bluetoothsap: onBluetoothStateChange: up=false
09-09 22:02:17.472  4988  5000 D Bluetoothsap: Unbinding service...
,09-09 22:02:17.482  1478  2128 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:17.482  1478  2128 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 22:02:17.482  3374  3480 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 22:02:17.482  1451  1466 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:17.482  1451  1466 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 22:02:17.482  1465  1484 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:17.482  1465  1484 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 22:02:17.482  4988  4998 D BluetoothPbap: onBluetoothStateChange: up=false,
,09-09 22:02:17.482  7003  7017 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 22:02:17.482  7003  7017 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 22:02:17.482  7003  7017 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false,
09-09 22:02:17.482  7003  7017 D BluetoothLeAdvertiser: Exit stop advertising
09-09 22:02:17.482  7003  7017 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-09 22:02:17.482  7003  7017 D BluetoothLeScanner: Exiting stopAllScan,
09-09 22:02:17.482  3374  3384 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:17.482  3374  3384 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 22:02:17.482  1754  2001 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:17.482  1754  2001 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 22:02:17.482  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 22:02:17.492  7107  7107 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 22:02:17.492  4988  5000 D BluetoothMap: onBluetoothStateChange: up=false
09-09 22:02:17.492  7107  7107 D ActivityThread: Added TimaKeyStore provider
09-09 22:02:17.492  2629  4501 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 22:02:17.492  2629  4501 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 22:02:17.492  1180  1190 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:17.492  1180  1190 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 22:02:17.492  4988  4998 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:17.492  4988  4998 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 22:02:17.492  1354  1354 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-09 22:02:17.492  1354  1354 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-09 22:02:17.492  1354  1354 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-09 22:02:17.492  1354  1354 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-09 22:02:17.492  1354  1354 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-09 22:02:17.492  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:17.492  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:17.492  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
09-09 22:02:17.492  1017  1132 D Tethering: InitialState.processMessage what=4
,09-09 22:02:17.492  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:17.492  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:17.492  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
09-09 22:02:17.492  1017  1132 E Tethering: No numeric data
,09-09 22:02:17.502  1017  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 22:02:17.502  1017  1132 D Tethering: clearTetheredNotification()
,09-09 22:02:17.502  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:17.502  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:17.502  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 22:02:17.502  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:17.502  1017  1126 V NetworkStats: performPollLocked(flags=0x1)
09-09 22:02:17.502  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 22:02:17.502  1180  1180 D HotspotTile: updateTetherState():false, false
09-09 22:02:17.502  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 22:02:17.502  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 22:02:17.502  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:17.502  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
09-09 22:02:17.502  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-09 22:02:17.502  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:17.502  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:17.502  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
09-09 22:02:17.502  1017  1126 V NetworkStats: performPollLocked() took 4ms
09-09 22:02:17.502  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:17.512  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-09 22:02:17.512  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:17.512  1180  1180 D BluetoothTile:  getBluetoothState : 10
,09-09 22:02:17.512  1874  1874 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 22:02:17.512  1017  3700 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 22:02:17.512  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-09 22:02:17.512  1017  4465 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-09 22:02:17.512  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-09 22:02:17.522  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 22:02:17.522  4988  4988 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:17.522  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:17.522  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:17.522  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:17.532  7003  7003 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,09-09 22:02:17.612   257   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-09 22:02:17.612   257   534 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 22:02:17.612  7107  7136 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-09 22:02:17.612   257   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-09 22:02:17.612   257   534 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 22:02:17.612  7107  7136 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-09 22:02:17.702  1354  1354 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 22:02:17.752  7107  7107 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.io.File.exists(File.java:363)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-09 22:02:17.752  7107  7107 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 22:02:17.752  7107  7107 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 22:02:17.752  7107  7107 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.q.e.b(PG:170)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09,-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 22:02:17.752  7107  7107 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.q.k.d(PG:583)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.q.e.b(PG:170)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 22:02:17.752  7107  7107 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.io.File.exists(File.java:363)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 22:02:17.752  7107  7107 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.io.File.exists(File.java:363)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 22:02:17.752  7107  7107 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 22:02:17.752  7107  7107 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 22:02:17.762  1017  1029 I ActivityManager: Killing 6463:com.samsung.android.sm/1000 (adj 15): empty #21
09-09 22:02:17.762  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 22:02:17.762  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 22:02:17.762  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:17.762  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:17.762  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 22:02:17.772  1632  1632 I Hs20UtilService: Starting #8
09-09 22:02:17.772  1632  1662 I Hs20UtilService: Message received 5007
09-09 22:02:17.772  4988  4988 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 22:02:17.772  4988  4988 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 22:02:17.782  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-09 22:02:17.782  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 22:02:17.782  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 22:02:17.782  4988  4988 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 22:02:17.792  4988  4988 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 22:02:17.792  4988  5054 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 22:02:17.792  4988  4988 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 22:02:17.792  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-09 22:02:17.792  1017  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 22:02:17.802  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 22:02:17.802  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 22:02:17.802  4988  4988 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 22:02:17.802  4988  5054 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-09 22:02:17.802  1017  1017 I ApplicationPolicy: updateDataUsageMap
09-09 22:02:17.812  1354  1354 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-09 22:02:17.812  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:17.812  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:17.812  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
09-09 22:02:17.822  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 22:02:17.822  1017  1508 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
09-09 22:02:17.822  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 22:02:17.822  1017  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:17.822  1017  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:17.822  1017  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:17.822  1017  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:17.832  7146  7146 E Zygote  : MountEmulatedStorage()
,09-09 22:02:17.842  7146  7146 E Zygote  : v2
09-09 22:02:17.842  7146  7146 I libpersona: KNOX_SDCARD checking this for 10064
09-09 22:02:17.842  7146  7146 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:17.842  7146  7146 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 22:02:17.842  7146  7146 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 22:02:17.842  1017  1508 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7146 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 22:02:17.842  7146  7146 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 22:02:17.842  1017  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-09 22:02:17.842  1017  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-09 22:02:17.842  7107  7145 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-09 22:02:17.862  1754  2204 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 22:02:17.862  4988  4988 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 22:02:17.862  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 22:02:17.862  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:17.862  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 22:02:17.862  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:17.862  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:17.862  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:17.862  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:17.862  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:17.862  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:17.862  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-09 22:02:17.862  1180  1731 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 22:02:17.862  1180  1180 D HotspotTile: onReceive : 1, 0
,09-09 22:02:17.862  1017  1210 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:17.872  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:17.872  1017  1210 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:17.872  1017  1210 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:17.872  1017  1210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-09 22:02:17.872  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:17.872  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 22:02:17.882  7146  7146 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:17.882  7146  7146 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:17.892  7146  7146 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-09 22:02:17.912  7146  7146 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 22:02:17.912  7146  7146 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-09 22:02:17.942  7146  7146 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 22:02:17.942  1017  3703 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-09 22:02:17.942  1017  3703 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:17.942  1017  3703 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:17.942  1017  3703 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:17.942  1017  3703 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:17.952  7163  7163 E Zygote  : MountEmulatedStorage()
,09-09 22:02:17.952  1017  3703 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7163 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 22:02:17.952  7163  7163 E Zygote  : v2
09-09 22:02:17.952  7163  7163 I libpersona: KNOX_SDCARD checking this for 10065
09-09 22:02:17.952  7163  7163 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 22:02:17.952  7163  7163 I libpersona: KNOX_SDCARD not a persona
09-09 22:02:17.952  1017  3703 I ActivityManager: Killing 5630:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,09-09 22:02:17.962  7163  7163 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 22:02:17.962  7163  7163 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-09 22:02:17.972  7163  7163 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:17.972  7163  7163 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:18.002  7163  7163 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 22:02:18.002  1017  3703 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:18.002  1017  3703 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:18.002  1017  3703 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-09 22:02:18.002  1017  3703 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,09-09 22:02:18.002  1017  3703 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:18.012  1017  3703 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:18.012  1017  3703 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:18.012  1017  3703 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:18.022  7178  7178 E Zygote  : MountEmulatedStorage(),
09-09 22:02:18.022  7178  7178 E Zygote  : v2
09-09 22:02:18.022  7178  7178 I libpersona: KNOX_SDCARD checking this for 10102
,09-09 22:02:18.022  7178  7178 I libpersona: KNOX_SDCARD not a persona,
09-09 22:02:18.022  7178  7178 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 22:02:18.022  1017  3703 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7178 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-09 22:02:18.022  1017  3703 I ActivityManager: Killing 6682:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,09-09 22:02:18.022  7178  7178 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 22:02:18.022  7178  7178 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 22:02:18.032   288   288 E SMD     : DCD OFF
,09-09 22:02:18.042  7178  7178 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:18.042  7178  7178 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:18.062  7178  7178 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-09 22:02:18.242  7178  7198 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-09 22:02:18.242  7178  7198 I Babel_SMS: MmsConfig.loadMmsSettings
,09-09 22:02:18.242  7178  7198 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-09 22:02:18.242  7178  7198 I Babel_SMS: MmsConfig.loadFromDatabase
,09-09 22:02:18.252  1017  1049 I PowerManagerService: [PWL] Off : 50s ago
,09-09 22:02:18.252  1017  1049 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-09 22:02:18.252  1017  1049 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-09 22:02:18.252  1017  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1017, ws=null) (elapsedTime=952)
,09-09 22:02:18.272  7178  7198 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-09 22:02:18.272  7178  7198 I Babel_SMS: MmsConfig.loadFromResources
,09-09 22:02:18.272  7178  7198 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-09 22:02:18.272  7178  7198 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-09 22:02:18.302  1017  1499 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,09-09 22:02:18.302  1017  1499 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-09 22:02:18.302  1017  1499 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:18.302  1017  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:18.302  1017  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-09 22:02:18.332  7178  7178 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 22:02:18.342  7178  7178 I Babel_Crash: startup - clean
,09-09 22:02:18.362  1017  1078 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 22:02:18.372  1017  1078 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 22:02:18.372  1017  1078 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:18.372  1017  1078 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:18.372  1017  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 22:02:18.372  4988  4988 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 22:02:18.372  4988  4988 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 22:02:18.382  1632  1632 I Hs20UtilService: Starting #9
09-09 22:02:18.382  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 22:02:18.382  1632  1662 I Hs20UtilService: Message received 5007
,09-09 22:02:18.382  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 22:02:18.382  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 22:02:18.382  4988  4988 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 22:02:18.382  4988  5054 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 22:02:18.382  7178  7178 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 22:02:18.392  1017  1506 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 22:02:18.392  1017  1506 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 22:02:18.392  1017  1506 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:18.392  1017  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:18.392  1017  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 22:02:18.392  1632  1632 I Hs20UtilService: Starting #10
,09-09 22:02:18.392  7178  7178 W AudioCapabilities: Unsupported mime audio/evrc
09-09 22:02:18.392  1017  1210 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,09-09 22:02:18.392  7178  7178 W AudioCapabilities: Unsupported mime audio/qcelp
,09-09 22:02:18.392  1632  1662 I Hs20UtilService: Message received 5011
,09-09 22:02:18.392  1017  1210 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:18.392  1017  1210 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:18.392  1017  1210 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:18.392  1017  1210 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:18.402  7178  7178 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-09 22:02:18.402  7178  7178 W AudioCapabilities: Unsupported mime audio/mpeg-L2
09-09 22:02:18.402  7178  7178 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-09 22:02:18.402  7178  7178 W AudioCapabilities: Unsupported mime audio/x-ima
,09-09 22:02:18.402  7178  7178 W AudioCapabilities: Unsupported mime audio/qcelp
,09-09 22:02:18.402  7178  7178 W AudioCapabilities: Unsupported mime audio/evrc
,09-09 22:02:18.412  7201  7201 E Zygote  : MountEmulatedStorage(),
09-09 22:02:18.412  7201  7201 E Zygote  : v2
09-09 22:02:18.412  7201  7201 I libpersona: KNOX_SDCARD checking this for 1000
09-09 22:02:18.412  7201  7201 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:18.412  7201  7201 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 22:02:18.412  7201  7201 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-09 22:02:18.412  7201  7201 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 22:02:18.412  1017  1210 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7201 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-09 22:02:18.422  7178  7178 W VideoCapabilities: Unsupported mime video/wvc1,
,09-09 22:02:18.422  7178  7178 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-09 22:02:18.432   308   308 I art     : Explicit concurrent mark sweep GC freed 8710(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 605us total 24.755ms
,09-09 22:02:18.442  7201  7201 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 22:02:18.442  7201  7201 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:18.452  7178  7178 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-09 22:02:18.452  7178  7178 W VideoCapabilities: Unsupported mime video/wvc1
,09-09 22:02:18.452  7178  7178 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-09 22:02:18.462   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 898us total 19.235ms
09-09 22:02:18.462  7178  7178 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-09 22:02:18.462  7178  7178 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-09 22:02:18.462  7178  7178 W VideoCapabilities: Unsupported mime video/mp43
,09-09 22:02:18.472  7178  7178 W VideoCapabilities: Unsupported mime video/sorenson
,09-09 22:02:18.482   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 17.518ms
,09-09 22:02:18.482  7178  7178 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-09 22:02:18.482  1017  1044 D Tethering: interfaceRemoved wlan0
,09-09 22:02:18.482  1017  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-09 22:02:18.492  7201  7201 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 22:02:18.492  7201  7201 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-09 22:02:18.492  7201  7201 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 22:02:18.492  7201  7201 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 22:02:18.502  1017  4465 I ActivityManager: Killing 6736:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,09-09 22:02:18.502  1017  1078 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:18.502  1017  1078 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:18.502  1017  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:18.512  1017  3453 D SSRM:n  : SIOP:: AP = 380
,09-09 22:02:18.512  7178  7178 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es,
09-09 22:02:18.512  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:18.512  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:18.512  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:18.512  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:18.512  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:18.512  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:18.522  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:18.522  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:18.522  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:18.522  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:18.522  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:18.522  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:18.532  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:18.532  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:18.532  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:18.532  7178  7178 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 22:02:18.532  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:18.532  7178  7178 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 22:02:18.532  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:18.532  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:18.542  7178  7178 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 22:02:18.542  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:18.542  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:18.542  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:18.542  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:18.542  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:18.542  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:18.542  7178  7178 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 22:02:18.542  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:18.542  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:18.542  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:18.552  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:18.552  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:18.552  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:18.552  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:18.552  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:18.552  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:18.552  1017  1508 I ActivityManager: Killing 6275:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,09-09 22:02:18.552  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:18.552  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:18.552  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:18.562  7178  7178 I vclib   : onServiceConnected
,09-09 22:02:18.562  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:18.562  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:18.562  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:18.562  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:18.562  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:18.562  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:18.572  4988  4988 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 22:02:18.572  1017  1499 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-09 22:02:18.572  1017  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 22:02:18.572  1017  1499 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:18.572  1017  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:18.572  1017  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 22:02:18.582  2629  2629 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 22:02:18.582  4988  4988 D DockEventReceiver: finishStartingService: stopping service
,09-09 22:02:18.582  4988  4988 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 22:02:18.592  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:18.592  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-09 22:02:18.612  6824  6824 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-09 22:02:18.612  6824  6824 I PCWCLIENTTRACE_PushUtil: sales region : global
09-09 22:02:18.612  6824  6824 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 22:02:18.612  6824  6824 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-09 22:02:18.622  1017  1509 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,09-09 22:02:18.622  1017  1509 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
09-09 22:02:18.622  1017  1509 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
09-09 22:02:18.622  1017  1509 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,09-09 22:02:18.622  6824  7219 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-09 22:02:18.622  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-09 22:02:18.632  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:18.632  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:18.632  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:18.632  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:18.642  7221  7221 E Zygote  : MountEmulatedStorage()
09-09 22:02:18.642  7221  7221 I libpersona: KNOX_SDCARD checking this for 10001
09-09 22:02:18.642  7221  7221 E Zygote  : v2
09-09 22:02:18.642  7221  7221 I libpersona: KNOX_SDCARD not a persona
09-09 22:02:18.642  7221  7221 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 22:02:18.642  1017  1044 D Tethering: interfaceRemoved p2p0
09-09 22:02:18.642  1017  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-09 22:02:18.642  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7221 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 22:02:18.642  7221  7221 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 22:02:18.652  7221  7221 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 22:02:18.662  7221  7221 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:18.662  7221  7221 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:18.732  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-09 22:02:18.732  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:18.732  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:18.732  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:18.732  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:18.752  7239  7239 E Zygote  : MountEmulatedStorage()
09-09 22:02:18.752  7239  7239 E Zygote  : v2
09-09 22:02:18.752  7239  7239 I libpersona: KNOX_SDCARD checking this for 1000
,09-09 22:02:18.752  7239  7239 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:18.752  7239  7239 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 22:02:18.752  1017  1029 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7239 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-09 22:02:18.752  1017  1029 I ActivityManager: Killing 6780:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
09-09 22:02:18.752  7239  7239 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 22:02:18.752  7239  7239 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 22:02:18.772  7239  7239 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:18.772  7239  7239 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:18.802  7239  7239 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-09 22:02:18.952  7239  7239 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-09 22:02:18.962  7239  7239 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-09 22:02:18.962  7239  7239 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-09 22:02:18.962  7239  7239 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 22:02:18.962  7239  7239 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-09 22:02:18.972  7239  7239 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-09 22:02:18.972  1017  1508 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-09 22:02:18.972  1017  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:18.972  1017  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:18.972  1017  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:18.972  1017  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:18.982  1017  1508 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7254 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 22:02:18.982  1017  1508 I ActivityManager: Killing 6804:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,09-09 22:02:18.982  7254  7254 E Zygote  : MountEmulatedStorage()
,09-09 22:02:18.982  7254  7254 E Zygote  : v2
09-09 22:02:18.992  7254  7254 I libpersona: KNOX_SDCARD checking this for 10008
09-09 22:02:18.992  7254  7254 I libpersona: KNOX_SDCARD not a persona
09-09 22:02:18.992  7254  7254 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 22:02:18.992  7254  7254 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 22:02:18.992  7254  7254 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-09 22:02:19.012  7254  7254 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:19.012  7254  7254 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:19.032   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 22:02:19.092  1017  1477 I ActivityManager: Killing 6766:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,09-09 22:02:19.092  1017  1210 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 22:02:19.092  1017  1210 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-09 22:02:19.092  1017  1210 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:19.092  1017  1210 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:19.092  1017  1210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:19.112  1939  1939 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 22:02:19.112  1939  2823 I iu.UploadsManager: num queued entries: 0
,09-09 22:02:19.112  1939  2823 I iu.UploadsManager: num updated entries: 0
,09-09 22:02:19.112  1939  2823 I iu.SyncManager: NEXT; no task
,09-09 22:02:19.112  1017  1499 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 22:02:19.112  1017  1499 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,09-09 22:02:19.122  1017  1499 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:19.122  1017  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:19.122  1017  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:19.132  1939  1939 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 22:02:19.132  1939  1939 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,09-09 22:02:19.142  2827  2827 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 09 22:02:19 GMT+02:00 2016
,09-09 22:02:19.142  1017  1078 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-09 22:02:19.142  1017  1078 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-09 22:02:19.142  1017  1078 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:19.142  1017  1078 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:19.142  1017  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-09 22:02:19.142  2827  2827 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-09 22:02:19.152  2827  2827 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-09 22:02:19.152  2827  2827 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-09 22:02:19.152  1017  1508 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-09 22:02:19.152  1017  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:19.152  1017  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:19.152  1017  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:19.152  2827  2827 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
09-09 22:02:19.152  1017  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:19.162  2827  7270 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) },
,09-09 22:02:19.162  2827  7270 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-09 22:02:19.162  2827  7270 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-09 22:02:19.162  2827  7270 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-09 22:02:19.192  7273  7273 E Zygote  : MountEmulatedStorage()
09-09 22:02:19.192  7273  7273 E Zygote  : v2
09-09 22:02:19.192  7273  7273 I libpersona: KNOX_SDCARD checking this for 10031
09-09 22:02:19.192  7273  7273 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:19.192  7273  7273 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 22:02:19.192  1017  1508 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7273 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,09-09 22:02:19.202  7273  7273 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 22:02:19.202  7273  7273 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 22:02:19.212  2827  2827 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-09 22:02:19.222  7273  7273 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:19.222  7273  7273 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:19.252  7273  7273 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-09 22:02:19.252  1017  1029 I ActivityManager: Killing 6860:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,09-09 22:02:19.262  1017  4466 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-09 22:02:19.262  1017  4466 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:19.262  1017  4466 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:19.262  1017  4466 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:19.262  1017  4466 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:19.272  2763  7288 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-09 22:02:19.272  2763  7288 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-09 22:02:19.272  2763  7288 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-09 22:02:19.272  2763  7288 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-09 22:02:19.282  7289  7289 E Zygote  : MountEmulatedStorage(),
09-09 22:02:19.282  7289  7289 E Zygote  : v2
09-09 22:02:19.282  7289  7289 I libpersona: KNOX_SDCARD checking this for 10032
09-09 22:02:19.282  7289  7289 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:19.282  7289  7289 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 22:02:19.282  7289  7289 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 22:02:19.282  7289  7289 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-09 22:02:19.282  2763  7288 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
09-09 22:02:19.282  1017  4466 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7289 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 22:02:19.302  7289  7289 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:19.302  7289  7289 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:19.352  7289  7304 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-09 22:02:19.352  7289  7304 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-09 22:02:19.362  7289  7289 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-09 22:02:19.362  1017  1320 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,09-09 22:02:19.362  1017  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:19.362  1017  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:19.362  1017  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:19.362  1017  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:19.362  7289  7304 D SPPClientService: PushLog.txt file is not deleted.
,09-09 22:02:19.362  7289  7304 D SPPClientService: PushLog.txt file is not deleted.
09-09 22:02:19.362  7289  7304 D SPPClientService: ============PushLog. stop!
,09-09 22:02:19.382  1017  1320 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7306 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
09-09 22:02:19.382  1017  1320 I ActivityManager: Killing 6880:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21,
,09-09 22:02:19.382  7306  7306 E Zygote  : MountEmulatedStorage(),
09-09 22:02:19.382  7306  7306 I libpersona: KNOX_SDCARD checking this for 10036
09-09 22:02:19.382  7306  7306 E Zygote  : v2
09-09 22:02:19.382  7306  7306 I libpersona: KNOX_SDCARD not a persona
09-09 22:02:19.382  7306  7306 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-09 22:02:19.382  1017  1506 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-09 22:02:19.382  1017  1506 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:19.382  1017  1506 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
09-09 22:02:19.382  1017  1506 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-09 22:02:19.382  1017  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-09 22:02:19.382  7306  7306 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 22:02:19.382  7306  7306 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,09-09 22:02:19.402  7306  7306 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:19.402  7306  7306 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:19.412  7289  7312 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-09 22:02:19.432  1017  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-09 22:02:19.442  7306  7306 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@6ccb68d
,09-09 22:02:19.452  7306  7306 I SA      : [SSP] onCreated
,09-09 22:02:19.462  7306  7306 I SA      : [TPM] There is no property file
,09-09 22:02:19.462  7306  7306 I SA      : [SCU] isHaveSA() - false
,09-09 22:02:19.462  7306  7306 I SA      : [TPM] getModelProperty : null
,09-09 22:02:19.462  7306  7306 I SA      : [TPM] getCSCProperty : null
,09-09 22:02:19.462  7306  7306 I SA      : [DM] FLOATING AMOLED FEATURE: true
,09-09 22:02:19.462  7306  7306 I SA      : [DM] PRODUCT AMOLED FEATURE: false
,09-09 22:02:19.472  7306  7306 I SA      : [DM] TFT FEATURE: false
,09-09 22:02:19.472  7306  7306 I SA      : [DM] init START
,09-09 22:02:19.472  7306  7306 I SA      : [DM] This device is not a Vodafone
,09-09 22:02:19.472  7306  7306 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,09-09 22:02:19.482  7306  7306 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
09-09 22:02:19.482  7306  7306 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
09-09 22:02:19.482  7306  7306 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
09-09 22:02:19.482  7306  7306 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
09-09 22:02:19.482  7306  7306 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
09-09 22:02:19.482  7306  7306 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
09-09 22:02:19.482  7306  7306 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 22:02:19.482  7306  7306 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
09-09 22:02:19.482  7306  7306 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
09-09 22:02:19.482  7306  7306 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
09-09 22:02:19.482  7306  7306 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
09-09 22:02:19.482  7306  7306 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
09-09 22:02:19.482  7306  7306 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
09-09 22:02:19.492  7306  7306 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
09-09 22:02:19.492  7306  7306 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
09-09 22:02:19.492  7306  7306 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
09-09 22:02:19.492  7306  7306 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
09-09 22:02:19.492  7306  7306 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
09-09 22:02:19.492  7306  7306 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
09-09 22:02:19.492  7306  7306 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-09 22:02:19.492  7306  7306 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-09 22:02:19.492  7306  7306 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,09-09 22:02:19.492  7306  7306 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,09-09 22:02:19.492  7306  7306 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,09-09 22:02:19.492  7306  7306 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
09-09 22:02:19.492  7306  7306 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,09-09 22:02:19.492  7306  7306 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-09 22:02:19.502  7306  7306 I SA      : [SCU] isHaveSA() - false
09-09 22:02:19.502  7306  7306 I SA      : support phone number id : false
09-09 22:02:19.502  7306  7306 I SA      : [DM] Supports Ref Jpn : true
,09-09 22:02:19.502  7306  7306 I SA      : [DM] init END
,09-09 22:02:19.502  7306  7306 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-09 22:02:19.502  7306  7306 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-09 22:02:19.502  7306  7306 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-09 22:02:19.512  7306  7306 I SA      : [SLFUCHKMGR] constructor called
,09-09 22:02:19.522  7306  7306 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-09 22:02:19.522  7306  7306 I SA      : [OR] == isSIMCardReady false ==
,09-09 22:02:19.522  7306  7306 I SA      : [SCU] == networkStateCheck == false
,09-09 22:02:19.522  7306  7306 I SA      : [OR] onReceive END
,09-09 22:02:19.532  1017  1508 I ActivityManager: Killing 6717:com.android.mms/u0a41 (adj 15): empty #21
,09-09 22:02:19.532  1232  1232 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-09 22:02:19.542  1799  1799 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 22:02:19.552  2679  2691 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,09-09 22:02:19.552  1799  1799 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-09 22:02:19.552  1799  1799 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,09-09 22:02:19.552  1799  1799 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,09-09 22:02:19.552  1799  1799 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-09 22:02:19.562  1799  1799 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 22:02:19.562  1799  1799 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-09 22:02:19.562  1017  1320 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-09 22:02:19.562  1017  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:19.562  1017  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:19.562  1017  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:19.562  1017  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:19.582  7328  7328 E Zygote  : MountEmulatedStorage(),
09-09 22:02:19.582  7328  7328 E Zygote  : v2
09-09 22:02:19.582  7328  7328 I libpersona: KNOX_SDCARD checking this for 10077
09-09 22:02:19.582  7328  7328 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:19.582  7328  7328 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 22:02:19.582  1017  1320 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7328 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 22:02:19.582  7328  7328 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 22:02:19.582  7328  7328 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL,
,09-09 22:02:19.592  7328  7328 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:19.602  7328  7328 D ActivityThread: Added TimaKeyStore provider,
,09-09 22:02:19.622  1017  4071 D CountryDetector: No listener is left
,09-09 22:02:19.772  1017  4071 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-09 22:02:19.772  1017  4071 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-09 22:02:19.772  1017  4071 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:19.772  1017  4071 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:19.772  1017  4071 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-09 22:02:19.782  1017  4466 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-09 22:02:19.782  1017  4466 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:19.782  1017  4466 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:19.782  1017  4466 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:19.782  1017  4466 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:19.792  1017  4466 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7346 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 22:02:19.792  7346  7346 E Zygote  : MountEmulatedStorage()
09-09 22:02:19.792  7346  7346 E Zygote  : v2
09-09 22:02:19.792  7346  7346 I libpersona: KNOX_SDCARD checking this for 10110
09-09 22:02:19.792  7346  7346 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:19.792  7346  7346 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 22:02:19.802  1017  1524 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-09 22:02:19.802  1017  1524 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
09-09 22:02:19.802  1017  1524 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:19.802  1017  1524 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:19.802  1017  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-09 22:02:19.802  7346  7346 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 22:02:19.802  7346  7346 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-09 22:02:19.802  7178  7345 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-09 22:02:19.812  1017  1210 I ActivityManager: Killing 6898:com.sec.android.provider.badge/u0a68 (adj 15): empty #21,
,09-09 22:02:19.812  7346  7346 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:19.812  7346  7346 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:19.952  1017  1506 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-09 22:02:20.032   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 22:02:20.052   257   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-09 22:02:20.052   257   534 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 22:02:20.052  7346  7364 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-09 22:02:20.062   257   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-09 22:02:20.062   257   534 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 22:02:20.062  7346  7364 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-09 22:02:20.082   257   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-09 22:02:20.082   257   534 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 22:02:20.082  7346  7365 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-09 22:02:20.082   257   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-09 22:02:20.082   257   534 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 22:02:20.092  7346  7365 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-09 22:02:20.102  7346  7346 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 22:02:20.102  7346  7346 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 22:02:20.102  7346  7346 I GAv4    :   adb logcat -s GAv4
,09-09 22:02:20.122  7346  7346 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-09 22:02:20.122  1017  1030 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-09 22:02:20.122  1017  1509 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-09 22:02:20.122  1017  1509 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-09 22:02:20.122  1017  1509 D SecContentProvider2: mCursor = null
,09-09 22:02:20.122  1017  1509 D WifiService: setWifiEnabled: true pid=7003, uid=10170
,09-09 22:02:20.132  1017  1509 W ActivityManager: Permission Denial: getCurrentUser() from pid=7003, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-09 22:02:20.132  1017  1509 W WifiService: Failed getting userId using ActivityManagerNative
09-09 22:02:20.132  1017  1509 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7003, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-09 22:02:20.132  1017  1509 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-09 22:02:20.132  1017  1509 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-09 22:02:20.132  1017  1509 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-09 22:02:20.132  1017  1509 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-09 22:02:20.132  1017  1509 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-09 22:02:20.132  1017  1509 D SettingsProvider: name = wifi_on
,09-09 22:02:20.132  7346  7346 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 22:02:20.142  1017  1129 E WifiHW  : ##################### set firmware type 0 #####################
,09-09 22:02:20.142  7346  7367 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 22:02:20.382  1017  1509 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:20.392  1017  1509 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:20.392  1017  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 22:02:20.392  1017  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-09 22:02:20.402  7346  7346 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-09 22:02:20.432  7346  7346 I cr.library_loader: Time to load native libraries: 15 ms (timestamps 5372-5387)
,09-09 22:02:20.432  7346  7346 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-09 22:02:20.442  7346  7346 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {64a737c}
,09-09 22:02:20.442  7346  7346 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-09 22:02:20.442  7346  7346 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 22:02:20.462  7346  7346 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-09 22:02:20.462  7346  7346 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 22:02:20.472  7346  7346 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 22:02:20.482  7346  7346 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 22:02:20.482  7346  7346 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 22:02:20.482  7346  7346 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 22:02:20.482  7346  7346 I Adreno-EGL: Local Branch: 
09-09 22:02:20.482  7346  7346 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 22:02:20.482  7346  7346 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 22:02:20.482  7346  7346 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 22:02:20.512  1017  1044 D Tethering: interfaceAdded wlan0
,09-09 22:02:20.522  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 22:02:20.522  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:20.522  1017  1044 D Tethering: interfaceStatusChanged wlan0, false,
09-09 22:02:20.522  1017  1132 E Tethering: No numeric data
,09-09 22:02:20.522  1017  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-09 22:02:20.522  1017  1132 D Tethering: clearTetheredNotification()
09-09 22:02:20.522  1017  1132 D Tethering: InitialState.processMessage what=4
,09-09 22:02:20.532  1017  1044 D Tethering: interfaceAdded p2p0
,09-09 22:02:20.532   278   991 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-09 22:02:20.532  1017  1132 E Tethering: No numeric data
09-09 22:02:20.532   278   991 D SoftapController: Softap fwReload - Ok
,09-09 22:02:20.532  1017  1126 V NetworkStats: performPollLocked(flags=0x1)
,09-09 22:02:20.532  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-09 22:02:20.532  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
09-09 22:02:20.532  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:20.532  1180  1180 D HotspotTile: updateTetherState():false, false
09-09 22:02:20.532  1017  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 22:02:20.532  1017  1132 D Tethering: clearTetheredNotification()
,09-09 22:02:20.532  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 22:02:20.532  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 22:02:20.532  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-09 22:02:20.532  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox updated,
09-09 22:02:20.532  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 22:02:20.542   278   991 D CommandListener: Setting iface cfg
09-09 22:02:20.542  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 22:02:20.542   278   991 D CommandListener: Trying to bring down wlan0,
09-09 22:02:20.542  1180  1180 D HotspotTile: updateTetherState():false, false
,09-09 22:02:20.542   278   991 D CommandListener: Clearing all IP addresses on wlan0,
09-09 22:02:20.542  1017  1126 V NetworkStats: performPollLocked() took 5ms
09-09 22:02:20.542  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
09-09 22:02:20.542  1017  1126 V NetworkStats: performPollLocked(flags=0x1)
09-09 22:02:20.542  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
09-09 22:02:20.542  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-09 22:02:20.542  1017  1126 V NetworkStats: performPollLocked() took 2ms
09-09 22:02:20.542  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 22:02:20.542  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:20.542  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:20.542  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:20.542  1017  1129 E WifiHW  : supplicant_name : p2p_supplicant
09-09 22:02:20.542  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:20.542  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:20.572  7346  7346 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 22:02:20.572  7346  7404 W cr.media: Requires BLUETOOTH permission
,09-09 22:02:20.572  7346  7346 I NSApplication: Starting up...
,09-09 22:02:20.582  1017  1210 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-09 22:02:20.582  1017  3700 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-09 22:02:20.582  1017  1477 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-09 22:02:20.592  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:20.592  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:20.592  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:20.592  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:20.602  1017  1477 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7409 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-09 22:02:20.602  7400  7400 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-09 22:02:20.602  7400  7400 I wpa_supplicant: Successfully initialized wpa_supplicant
09-09 22:02:20.602  1017  1477 I ActivityManager: Killing 6914:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,09-09 22:02:20.602  7400  7400 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-09 22:02:20.602  7409  7409 E Zygote  : MountEmulatedStorage(),
09-09 22:02:20.612  7409  7409 E Zygote  : v2
09-09 22:02:20.612  7409  7409 I libpersona: KNOX_SDCARD checking this for 10117
09-09 22:02:20.612  7409  7409 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:20.612  7409  7409 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 22:02:20.612  7409  7409 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 22:02:20.612  7409  7409 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 22:02:20.632  7400  7400 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,09-09 22:02:20.642   358   358 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7400
09-09 22:02:20.642   358   358 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
09-09 22:02:20.642  7400  7400 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-09 22:02:20.642  7400  7400 I wpa_supplicant: ssSupport state is = 1
09-09 22:02:20.642  7400  7400 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-09 22:02:20.642  7400  7400 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,09-09 22:02:20.642   358   358 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7400
09-09 22:02:20.642   358   358 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,09-09 22:02:20.642  7409  7409 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:20.642  7409  7409 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:20.642  1017  1129 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-09 22:02:20.662  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 22:02:20.662  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:20.662  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 22:02:20.662  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:20.662  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:20.662  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:20.662  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:20.662  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:20.662  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:20.662  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-09 22:02:20.662  1180  1731 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 22:02:20.672  4988  4988 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:20.672  1180  1180 D HotspotTile: onReceive : 2, 0
,09-09 22:02:20.672  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:20.672  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-09 22:02:20.672  7409  7409 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 22:02:20.832   358   358 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,09-09 22:02:20.842  7400  7400 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,09-09 22:02:20.882  7400  7400 I wpa_supplicant: Ctrl_iface: loading cred from phone
,09-09 22:02:20.882  7400  7400 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-09 22:02:20.892  7400  7400 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-09 22:02:20.892   358   358 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7400
09-09 22:02:20.892   358   358 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
09-09 22:02:20.892  7400  7400 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
,09-09 22:02:20.892  7400  7400 I wpa_supplicant: ssSupport state is = 1
09-09 22:02:20.902  7400  7400 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-09 22:02:20.902  7400  7400 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-09 22:02:20.902  7400  7400 E wpa_supplicant: SIM READ ERROR
09-09 22:02:20.902  7400  7400 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 22:02:20.902  7400  7400 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-09 22:02:20.902  7400  7400 E wpa_supplicant: SIM READ ERROR
09-09 22:02:20.902  7400  7400 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 22:02:20.902  7400  7400 I wpa_supplicant: wpa_default_ap_write_once
,09-09 22:02:20.902  7400  7400 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-09 22:02:20.902  7400  7400 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 22:02:20.902  7400  7400 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-09 22:02:20.902  7400  7400 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-09 22:02:20.902  7400  7400 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-09 22:02:20.902  7400  7400 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-09 22:02:20.902  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
09-09 22:02:20.902  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:20.902  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 22:02:20.962  7400  7400 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-09 22:02:21.032   288   288 E SMD     : DCD OFF
,09-09 22:02:21.032   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 22:02:21.042  1017  4466 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-09 22:02:21.052  1017  4466 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.052  1017  4466 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.052  1017  4466 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.052  1017  4466 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.062  7432  7432 E Zygote  : MountEmulatedStorage()
09-09 22:02:21.062  7432  7432 I libpersona: KNOX_SDCARD checking this for 10121
09-09 22:02:21.062  7432  7432 E Zygote  : v2
09-09 22:02:21.062  7432  7432 I libpersona: KNOX_SDCARD not a persona
09-09 22:02:21.062  7432  7432 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 22:02:21.072  7432  7432 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 22:02:21.072  1017  4466 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7432 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
09-09 22:02:21.072  1017  1509 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-09 22:02:21.072  1017  1509 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4252, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-09 22:02:21.072  1017  1509 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-09 22:02:21.072  1017  1509 D BatteryService: stay LED for charging
,09-09 22:02:21.072  1017  4466 I ActivityManager: Killing 6932:com.wsomacp/u0a23 (adj 15): empty #21
09-09 22:02:21.072  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-09 22:02:21.072  7432  7432 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 22:02:21.072  1017  1017 I MotionRecognitionService: Plugged
09-09 22:02:21.072  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 22:02:21.082  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-09 22:02:21.082  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 22:02:21.082  7400  7400 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-09 22:02:21.082  7400  7400 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-09 22:02:21.082  1425  1425 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-09 22:02:21.082  1425  1425 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-09 22:02:21.102  7400  7400 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
09-09 22:02:21.102   358   358 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7400
09-09 22:02:21.102   358   358 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-09 22:02:21.102  7400  7400 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-09 22:02:21.102  7400  7400 I wpa_supplicant: ssSupport state is = 1
,09-09 22:02:21.102  7432  7432 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:21.102  7432  7432 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:21.112  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-09 22:02:21.112  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-09 22:02:21.112  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-09 22:02:21.112  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-09 22:02:21.112  1180  1180 D SViewCoverView: level :100 plugged : 2
,09-09 22:02:21.112  7400  7400 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-09 22:02:21.112  7400  7400 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-09 22:02:21.122  7400  7400 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-09 22:02:21.122   358   358 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7400
09-09 22:02:21.122   358   358 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
09-09 22:02:21.122  7400  7400 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-09 22:02:21.122  7400  7400 I wpa_supplicant: ssSupport state is = 1
09-09 22:02:21.122  7400  7400 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 22:02:21.122  7400  7400 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 22:02:21.122  7400  7400 E wpa_supplicant: SIM READ ERROR
09-09 22:02:21.122  7400  7400 I wpa_supplicant: wpa_default_ap_write_once
09-09 22:02:21.122  7400  7400 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-09 22:02:21.122  7400  7400 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 22:02:21.132  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 22:02:21.132  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 22:02:21.132  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-09 22:02:21.132  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 22:02:21.132  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 22:02:21.132  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-09 22:02:21.132  7432  7432 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 22:02:21.132  7432  7432 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.,
09-09 22:02:21.132  7432  7432 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 22:02:21.142  7432  7432 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-09 22:02:21.152  7432  7432 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-09 22:02:21.152  7432  7432 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-09 22:02:21.152  1017  1499 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,09-09 22:02:21.152  1017  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.152  1017  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.152  1017  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.152  1017  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.172  7451  7451 E Zygote  : MountEmulatedStorage()
,09-09 22:02:21.172  7451  7451 E Zygote  : v2
09-09 22:02:21.172  7451  7451 I libpersona: KNOX_SDCARD checking this for 10141
09-09 22:02:21.172  7451  7451 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:21.172  7451  7451 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-09 22:02:21.172  1017  1499 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7451 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,09-09 22:02:21.172  7451  7451 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-09 22:02:21.172  1017  1499 I ActivityManager: Killing 6986:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,09-09 22:02:21.172  7451  7451 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 22:02:21.202   308   308 I art     : Explicit concurrent mark sweep GC freed 8700(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 20.159ms
,09-09 22:02:21.202  7451  7451 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 22:02:21.202  7451  7451 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:21.212   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 17.125ms
,09-09 22:02:21.212  7400  7400 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-09 22:02:21.212  7400  7400 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-09 22:02:21.222  7451  7451 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-09 22:02:21.222  7451  7451 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 22:02:21.222  7451  7451 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 22:02:21.222  7451  7451 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 22:02:21.232   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 653us total 17.669ms
,09-09 22:02:21.272  1017  4465 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 22:02:21.282  1017  1524 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 22:02:21.312  7400  7400 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-09 22:02:21.312  7400  7400 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=,
09-09 22:02:21.312  7400  7400 I wpa_supplicant: Skip scan - bUseNetwork false
,09-09 22:02:21.312  1017  4466 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 22:02:21.322  1017  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-09 22:02:21.322  1017  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-09 22:02:21.322  7400  7400 I wpa_supplicant: HOTSPOT20_ENABLE called
09-09 22:02:21.322  7400  7400 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 22:02:21.322  7400  7400 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 22:02:21.322  7400  7400 E wpa_supplicant: SIM READ ERROR
09-09 22:02:21.322  7400  7400 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 22:02:21.332  1017  1320 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 22:02:21.352  7400  7400 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-09 22:02:21.362  7400  7400 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-09 22:02:21.362  1017  1129 D WifiConfigStore: Loading config and enabling all networks ,
,09-09 22:02:21.372  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 22:02:21.372  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:21.372  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 22:02:21.372  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:21.372  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:21.372  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:21.372  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:21.372  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:21.372  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:21.372  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-09 22:02:21.372  1180  1731 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 22:02:21.372  1180  1180 D HotspotTile: onReceive : 3, 0
,09-09 22:02:21.382  4988  4988 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:21.382  1017  4465 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,09-09 22:02:21.382  1017  1129 E WifiConfigStore: Not a HS20
,09-09 22:02:21.382  1017  4466 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 22:02:21.382  1017  4465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.382  1017  4465 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.382  1017  4465 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.382  1017  4465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.392  7003  7003 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:21.392  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:21.392  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:21.392  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:21.392  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:21.392  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 22:02:21.392  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:21.392  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:21.392  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:21.392  7003  7003 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:21.392  7003  7003 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 22:02:21.392  1017  1499 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 22:02:21.392  7477  7477 E Zygote  : MountEmulatedStorage()
,09-09 22:02:21.392  7477  7477 E Zygote  : v2
09-09 22:02:21.402  7477  7477 I libpersona: KNOX_SDCARD checking this for 10068
09-09 22:02:21.402  7477  7477 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:21.402  7477  7477 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 22:02:21.402  1017  4465 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7477 uid=10068 gids={50068, 9997} abi=armeabi-v7a,
09-09 22:02:21.402  7477  7477 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 22:02:21.402  7003  7003 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:21.402  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:21.402  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:21.402  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:21.402  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:21.402  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 22:02:21.402  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,09-09 22:02:21.402  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:21.402  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 22:02:21.402  1017  1129 D WifiNative-wlan0: callSECApiInt - ID [65]
09-09 22:02:21.402  7477  7477 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-09 22:02:21.402  7003  7003 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:21.402  7003  7003 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 22:02:21.402  1017  1129 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-09 22:02:21.402  7400  7400 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-09 22:02:21.402  7400  7400 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-09 22:02:21.402  7400  7400 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 22:02:21.402  7400  7400 I wpa_supplicant: P2P: Current p2p state = IDLE
09-09 22:02:21.402  7400  7400 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-09 22:02:21.402  7400  7400 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-09 22:02:21.402  7400  7400 I wpa_supplicant: First Scan Start
,09-09 22:02:21.402  7400  7400 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-09 22:02:21.412  1017  1129 D WifiNative-wlan0: Setting external_sim to 1
,09-09 22:02:21.412  1017  1129 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 22:02:21.412  1017  1129 I WifiNative-HAL: startHal
09-09 22:02:21.412  1017  1129 E wifi    : getStaticLongField sWifiHalHandle 0x9ee0188c
09-09 22:02:21.412  1017  1129 I WifiNative-HAL: Could not start hal
09-09 22:02:21.412  7178  7178 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 22:02:21.412  1017  1129 E WifiNative-wlan0: do suspend true
,09-09 22:02:21.412  1017  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-09 22:02:21.412  1017  1128 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-09 22:02:21.422  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
,09-09 22:02:21.422  1017  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-09 22:02:21.422   278   991 D CommandListener: Setting iface cfg
09-09 22:02:21.422  1017  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 22:02:21.422  1017  1129 E WifiNative-wlan0: invaild command id : 215
09-09 22:02:21.422   278   991 D CommandListener: Trying to bring up p2p0
09-09 22:02:21.422  1017  1017 D RttService: SCAN_AVAILABLE : 3
09-09 22:02:21.422  1017  1151 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 22:02:21.422  1017  1152 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-09 22:02:21.422  1017  1151 I WifiNative-HAL: startHal
09-09 22:02:21.422  1017  1151 E wifi    : getStaticLongField sWifiHalHandle 0x9ddc19bc
09-09 22:02:21.422  1017  1151 I WifiNative-HAL: Could not start hal
09-09 22:02:21.422  1017  1151 E WifiScanningService: could not start HAL
,09-09 22:02:21.422  1017  1128 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 22:02:21.422  1017  1128 D WifiP2pService: P2pEnablingState
09-09 22:02:21.422  1017  1128 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-09 22:02:21.422  7400  7400 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-09 22:02:21.422  1017  1128 D WifiP2pService: P2p socket connection successful
09-09 22:02:21.422  7400  7400 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-09 22:02:21.422  1017  1128 D WifiP2pService: P2pEnabledState
09-09 22:02:21.422  1017  1131 E ConnectivityService: updateNetworkInfo()
09-09 22:02:21.422  1017  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-09 22:02:21.422  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-09 22:02:21.422  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-09 22:02:21.422  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 22:02:21.422  1017  1047 D WifiDisplayController: disconnect
09-09 22:02:21.422  1017  1047 D WifiDisplayController: updateConnection
09-09 22:02:21.422  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 22:02:21.422  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 22:02:21.422  7400  7400 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,09-09 22:02:21.432  1017  1129 E WifiStateMachine: Failed to set frequency band 0
,09-09 22:02:21.432  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 22:02:21.432  1017  1129 D SecContentProvider2: mCursor = null
,09-09 22:02:21.432  1017  1506 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 22:02:21.432  1180  1180 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-09 22:02:21.432  1017  4466 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 22:02:21.432  1180  1180 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 22:02:21.432  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 22:02:21.432  1017  1128 D WifiNative-p2p0: p2pGetDeviceAddress
09-09 22:02:21.432  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
09-09 22:02:21.432  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 22:02:21.432  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
09-09 22:02:21.432  1017  1128 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,09-09 22:02:21.432  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 22:02:21.432  1017  1129 D SecContentProvider2: mCursor = null
,09-09 22:02:21.442  1017  1128 D WifiP2pService: DeviceAddress: 0a:75:42
,09-09 22:02:21.442  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-09 22:02:21.442  1017  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-09 22:02:21.442  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
09-09 22:02:21.442  1017  1047 D WifiDisplayController:  secondary type: null
09-09 22:02:21.442  1017  1047 D WifiDisplayController:  wps: 0
09-09 22:02:21.442  1017  1047 D WifiDisplayController:  grpcapab: 0
09-09 22:02:21.442  1017  1047 D WifiDisplayController:  devcapab: 0
09-09 22:02:21.442  1017  1047 D WifiDisplayController:  status: 3
09-09 22:02:21.442  1017  1047 D WifiDisplayController:  wfdInfo: null
09-09 22:02:21.442  1017  1047 D WifiDisplayController:  groupownerAddress: null
09-09 22:02:21.442  1017  1047 D WifiDisplayController:  GOdeviceName: null
09-09 22:02:21.442  1017  1047 D WifiDisplayController:  interfaceAddress: 
09-09 22:02:21.442  1017  1047 D WifiDisplayController:  SConnectInfo : null
,09-09 22:02:21.442  7477  7477 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 22:02:21.442  1017  1524 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-09 22:02:21.442  7477  7477 D ActivityThread: Added TimaKeyStore provider,
09-09 22:02:21.442  1017  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.442  1017  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.442  1017  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.442  1017  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.452  7492  7492 E Zygote  : MountEmulatedStorage(),
09-09 22:02:21.452  7492  7492 I libpersona: KNOX_SDCARD checking this for 10009
09-09 22:02:21.452  7492  7492 E Zygote  : v2
09-09 22:02:21.452  7492  7492 I libpersona: KNOX_SDCARD not a persona
09-09 22:02:21.462  1017  1524 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7492 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,09-09 22:02:21.462  7492  7492 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 22:02:21.462  1017  1128 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-09 22:02:21.462  1017  1524 I ActivityManager: Killing 6947:com.android.defcontainer/u0a3 (adj 15): empty #21
,09-09 22:02:21.462  7492  7492 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 22:02:21.462  1017  1477 I ActivityManager: Killing 6223:com.android.vending/u0a26 (adj 15): empty #21
,09-09 22:02:21.462  7492  7492 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-09 22:02:21.462  1017  1128 D WifiP2pService: InactiveState
09-09 22:02:21.472  1017  1128 D WifiP2pService: InactiveState{ what=143376 }
09-09 22:02:21.472  1017  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 22:02:21.472  7400  7400 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-09 22:02:21.472  1017  1128 D WifiP2pService: InactiveState{ what=143376 }
09-09 22:02:21.472  1017  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 22:02:21.502  7492  7492 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:21.502  7492  7492 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:21.522  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 22:02:21.522  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 22:02:21.522  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-09 22:02:21.632  1017  1078 I art     : Explicit concurrent mark sweep GC freed 72892(4MB) AllocSpace objects, 12(240KB) LOS objects, 33% free, 23MB/34MB, paused 2.478ms total 156.553ms
,09-09 22:02:21.652  7477  7477 D BadgeProvider: onCreate
,09-09 22:02:21.662  7477  7477 D BadgeProvider: DatabaseHelper
,09-09 22:02:21.672  7477  7485 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-09 22:02:21.682  7477  7485 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-09 22:02:21.682  7477  7485 D BadgeProvider: sendNotify, [notify] : null
09-09 22:02:21.682  7477  7485 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-09 22:02:21.682  7477  7485 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-09 22:02:21.682  7477  7485 D BadgeProvider: update, [UpdateCount] : 1
,09-09 22:02:21.682  1017  4465 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,09-09 22:02:21.692  1510  1510 D Launcher.Model: reloadBadges entered.
,09-09 22:02:21.692  1017  4465 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-09 22:02:21.692  1017  4466 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-09 22:02:21.702  1017  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-09 22:02:21.722  1017  4466 I ActivityManager: Killing 7146:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,09-09 22:02:21.732  1017  4071 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 22:02:21.732  1017  4071 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 22:02:21.732  1017  4071 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:21.732  1017  4071 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:21.732  1017  4071 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 22:02:21.732  1632  1632 I Hs20UtilService: Starting #11
,09-09 22:02:21.732  1632  1662 I Hs20UtilService: Message received 5011
,09-09 22:02:21.742  7201  7201 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 22:02:21.742  7201  7201 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 22:02:21.742  7201  7201 D SecurityLogAgent: StateMachine : Current State = 1
09-09 22:02:21.742  7201  7201 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 22:02:21.752  1017  1506 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 22:02:21.752  1017  1506 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 22:02:21.752  1017  1506 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:21.752  1017  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:21.752  1017  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 22:02:21.752  1632  1632 I Hs20UtilService: Starting #12
09-09 22:02:21.752  1632  1662 I Hs20UtilService: Message received 5011
,09-09 22:02:21.752  7201  7201 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 22:02:21.762  7201  7201 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-09 22:02:21.762  7201  7201 D SecurityLogAgent: StateMachine : Current State = 1
09-09 22:02:21.762  7201  7201 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 22:02:21.762  1017  3700 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 22:02:21.762  1017  3700 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
09-09 22:02:21.762  1017  3700 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:21.762  1017  3700 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:21.762  1017  3700 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 22:02:21.772  1632  1632 I Hs20UtilService: Starting #13
09-09 22:02:21.772  1632  1662 I Hs20UtilService: Message received 5011
,09-09 22:02:21.772  1017  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,09-09 22:02:21.772  1017  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
,09-09 22:02:21.772  1017  1129 E WifiNative-wlan0: invaild command id : 215
,09-09 22:02:21.772  7201  7201 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 22:02:21.772  7201  7201 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-09 22:02:21.772  7201  7201 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 22:02:21.772  7201  7201 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 22:02:21.782  4988  4988 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-09 22:02:21.782  4988  4988 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 22:02:21.782  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 22:02:21.782  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 22:02:21.782  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-09 22:02:21.782  4988  4988 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 22:02:21.792  4988  5054 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 22:02:21.792  1017  1508 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-09 22:02:21.792  1017  1508 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.samsung.android.app.FileShareClient/com.samsung.android.app.FileShareClient.ClientBroadcastReceiver}
09-09 22:02:21.792  1017  1508 W BroadcastQueue: android.os.TransactionTooLargeException
09-09 22:02:21.792  1017  1508 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 22:02:21.792  1017  1508 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 22:02:21.792  1017  1508 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-09 22:02:21.792  1017  1508 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-09 22:02:21.792  1017  1508 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-09 22:02:21.792  1017  1508 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
09-09 22:02:21.792  1017  1508 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-09 22:02:21.792  1017  1508 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
09-09 22:02:21.792  1017  1508 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,09-09 22:02:21.792  1017  1508 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-09 22:02:21.792  1017  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.792  1017  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.792  1017  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.792  1017  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.812  7512  7512 E Zygote  : MountEmulatedStorage()
,09-09 22:02:21.812  7512  7512 E Zygote  : v2
09-09 22:02:21.812  7512  7512 I libpersona: KNOX_SDCARD checking this for 10064
09-09 22:02:21.812  7512  7512 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:21.812  7512  7512 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-09 22:02:21.812  1017  1508 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7512 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 22:02:21.812  7512  7512 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 22:02:21.812  7512  7512 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 22:02:21.832  7512  7512 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:21.832  7512  7512 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:21.842  1017  1041 W libprocessgroup: failed to open /acct/uid_10064/pid_7146/cgroup.procs: No such file or directory
,09-09 22:02:21.842  7512  7512 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-09 22:02:21.852  7512  7512 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 22:02:21.862  7512  7512 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-09 22:02:21.892  7512  7512 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 22:02:21.892  7163  7163 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 22:02:21.892  1017  1509 I ActivityManager: Killing 7085:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,09-09 22:02:22.042   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 22:02:22.692  7400  7400 I wpa_supplicant: nl80211: Received scan results (36 BSSes)
09-09 22:02:22.692  7400  7400 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-09 22:02:22.692  7400  7400 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-09 22:02:22.692  7400  7400 I wpa_supplicant: Trying to associate with  'G700'
09-09 22:02:22.692  7400  7400 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
09-09 22:02:22.692  7400  7400 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-09 22:02:22.702  1017  7471 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-09 22:02:22.712  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-09 22:02:22.712  1017  1129 D SecContentProvider2: mCursor = null
,09-09 22:02:22.812  7400  7400 E wpa_supplicant: Cmd 35605 not handled
,09-09 22:02:22.812  7400  7400 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 22:02:22.812  7400  7400 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-09 22:02:22.812  7400  7400 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-09 22:02:22.812  7400  7400 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-09 22:02:22.812  7400  7400 I wpa_supplicant: Associated with F4.99.3E
09-09 22:02:22.812  7400  7400 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 22:02:22.812  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:22.812  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:22.812  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
09-09 22:02:22.812  7400  7400 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-09 22:02:22.812  7400  7400 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-09 22:02:22.822  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 22:02:22.822  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:22.822  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 22:02:22.822  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 22:02:22.822  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,09-09 22:02:22.822  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 22:02:22.822  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 22:02:22.822  1017  1129 D SecContentProvider2: mCursor = null
,09-09 22:02:22.822  7400  7400 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e,
,09-09 22:02:22.822  7400  7400 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
09-09 22:02:22.832  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-09 22:02:22.832  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-09 22:02:22.832  1017  1129 D SecContentProvider2: mCursor = null
09-09 22:02:22.832  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
09-09 22:02:22.832  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
09-09 22:02:22.832  7400  7400 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,09-09 22:02:22.832  7400  7400 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-09 22:02:22.832  7400  7400 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 22:02:22.832  7400  7400 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-09 22:02:22.832  7400  7400 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-09 22:02:22.832  7400  7400 I wpa_supplicant: Blacklist: Clear (temp) 
,09-09 22:02:22.832  7400  7400 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-09 22:02:22.832  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-09 22:02:22.832  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
09-09 22:02:22.832  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,09-09 22:02:22.832  1017  1132 E Tethering: No numeric data
,09-09 22:02:22.832  1017  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 22:02:22.832  1017  1132 D Tethering: clearTetheredNotification()
,09-09 22:02:22.832  1017  1129 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-09 22:02:22.832  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:22.832  1017  1126 V NetworkStats: performPollLocked(flags=0x1)
09-09 22:02:22.842  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 22:02:22.842  1180  1180 D HotspotTile: updateTetherState():false, false
,09-09 22:02:22.842  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 22:02:22.842  1017  1129 E WifiConfigStore: setLastSelectedConfiguration -1
09-09 22:02:22.842  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 22:02:22.842  1017  1126 V NetworkStats: performPollLocked() took 5ms
09-09 22:02:22.842  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:22.842  1017  1129 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-09 22:02:22.842  1017  1131 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-09 22:02:22.842  1017  1131 E ConnectivityService: updateNetworkInfo()
,09-09 22:02:22.842  1017  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-09 22:02:22.852  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 22:02:22.852  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 22:02:22.852  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 22:02:22.852  1017  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 22:02:22.852  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:22.852  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:22.852  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:22.852  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:22.852  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:22.852  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:22.862  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 22:02:22.862  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
,09-09 22:02:22.862  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:22.862  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:22.862  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 22:02:22.862  1632  1632 I Hs20UtilService: Starting #14
09-09 22:02:22.862  1632  1662 I Hs20UtilService: Message received 5007
,09-09 22:02:22.862  4988  4988 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
09-09 22:02:22.862  4988  4988 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null,
,09-09 22:02:22.872  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 22:02:22.872  1017  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 22:02:22.872  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 22:02:22.872  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-09 22:02:22.872  4988  4988 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 22:02:22.872  4988  5054 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 22:02:22.882   278   991 D CommandListener: Setting iface cfg
,09-09 22:02:22.892  1017  1129 E WifiStateMachine: Start Dhcp Watchdog 2
,09-09 22:02:22.892  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-09 22:02:22.892  1017  1129 D SecContentProvider2: mCursor = null
,09-09 22:02:22.902  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 22:02:22.902  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 22:02:22.902  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 22:02:22.902  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:22.902  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:22.902  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:22.912  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:22.912  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-09 22:02:22.912  1017  1129 D SecContentProvider2: mCursor = null
,09-09 22:02:22.922  1017  1129 E WifiNative-wlan0: do suspend false
,09-09 22:02:22.922  1017  1128 D WifiP2pService: InactiveState{ what=143375 }
,09-09 22:02:22.922  1017  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 22:02:23.042   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 22:02:23.132  7529  7529 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-09 22:02:23.142  1017  1029 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-09 22:02:23.142  1017  1029 D WifiService: setWifiEnabled: false pid=7003, uid=10170
09-09 22:02:23.142  1017  1029 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 22:02:23.142  1017  1029 D SecContentProvider2: mCursor = null
09-09 22:02:23.142  1017  1029 D SettingsProvider: name = wifi_on
,09-09 22:02:23.152  7529  7529 I dhcpcd  : version 5.5.6 starting
,09-09 22:02:23.152  7529  7529 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-09 22:02:23.152  1017  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 22:02:23.172  1017  1129 E WifiNative-wlan0: do suspend true,
,09-09 22:02:23.192  1017  1128 D WifiP2pService: InactiveState{ what=143375 },
09-09 22:02:23.192  1017  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 22:02:23.192   278   991 D CommandListener: Clearing all IP addresses on wlan0
,09-09 22:02:23.202  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-09 22:02:23.202  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:23.202  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 22:02:23.202  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:23.202  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:23.202  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:23.202  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:23.202  1017  1131 E ConnectivityService: updateNetworkInfo()
09-09 22:02:23.202  1017  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 22:02:23.202  1017  1131 E ConnectivityService: updateNetworkInfo()
09-09 22:02:23.202  1017  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
09-09 22:02:23.202  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 22:02:23.212   278   991 E Netd    : no such netId 503
,09-09 22:02:23.212  1017  1131 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:23.212  1017  1131 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
09-09 22:02:23.212  1017  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 22:02:23.212  1017  1131 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-09 22:02:23.212  1017  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 22:02:23.212  1017  1131 V NetworkStats: updateIfacesLocked(),
09-09 22:02:23.212  1017  1129 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 22:02:23.212  1017  1131 V NetworkStats: performPollLocked(flags=0x1)
09-09 22:02:23.212  1017  1128 D WifiP2pService: InactiveState{ what=131204 }
09-09 22:02:23.212  1017  1128 D WifiP2pService: P2pEnabledState{ what=131204 }
09-09 22:02:23.212  1017  1128 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-09 22:02:23.212  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 22:02:23.212  1017  1151 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-09 22:02:23.212  1017  1017 D RttService: SCAN_AVAILABLE : 1
09-09 22:02:23.212  1017  1524 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 22:02:23.212  1017  1524 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 22:02:23.212  1017  1152 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-09 22:02:23.212  1017  1524 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:23.212  1017  1524 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:23.212  1017  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 22:02:23.222  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 22:02:23.222  1632  1632 I Hs20UtilService: Starting #15
09-09 22:02:23.222  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:23.222  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 22:02:23.222  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:23.222  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:23.222  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:23.222  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:23.222  1632  1662 I Hs20UtilService: Message received 5007
,09-09 22:02:23.222  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 22:02:23.222  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
09-09 22:02:23.222  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 22:02:23.222  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
09-09 22:02:23.222  1017  1131 V NetworkStats: performPollLocked() took 10ms,
09-09 22:02:23.222  1017  1131 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:23.222  1017  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-09 22:02:23.222  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-09 22:02:23.222  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-09 22:02:23.222  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 22:02:23.222  1017  1047 D WifiDisplayController: disconnect
09-09 22:02:23.222  1017  1047 D WifiDisplayController: updateConnection
09-09 22:02:23.222  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 22:02:23.222  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 22:02:23.222  1017  1128 D WifiP2pService: P2pDisablingState
09-09 22:02:23.222  1017  1128 D WifiP2pService: P2pDisablingState{ what=147458 }
09-09 22:02:23.222  1017  1128 D WifiP2pService: p2p socket connection lost
09-09 22:02:23.222  4988  4988 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 22:02:23.222  1017  1128 D WifiP2pService: P2pDisabledState
,09-09 22:02:23.222  4988  4988 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 22:02:23.222  7529  7529 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-09 22:02:23.222  1017  1129 E WifiNative-wlan0: do suspend true
09-09 22:02:23.232  7529  7529 E dhcpcd  : wlan0: sendmsg: Network is unreachable
,09-09 22:02:23.232  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 22:02:23.232  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 22:02:23.232  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 22:02:23.232  4988  4988 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 22:02:23.232  4988  5054 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 22:02:23.232  1017  7527 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 22:02:23.232  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-09 22:02:23.232  1017  1131 D ConnectivityService: nai.networkMonitor.doQuit()
09-09 22:02:23.232  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
09-09 22:02:23.232  1017  1131 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-09 22:02:23.232  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 22:02:23.232  1017  1131 E ConnectivityService: updateNetworkInfo()
09-09 22:02:23.232  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
09-09 22:02:23.232  1017  1131 E ConnectivityService: updateNetworkInfo()
09-09 22:02:23.232  1017  1131 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
09-09 22:02:23.232  1017  1131 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-09 22:02:23.232  1017  7527 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-09 22:02:23.232  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:23.232  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:23.232  1180  1180 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-09 22:02:23.232  1017  3700 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 22:02:23.232  1180  1180 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 22:02:23.242  4988  4988 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-09 22:02:23.242  4988  4988 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 22:02:23.242  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 22:02:23.242  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 22:02:23.242  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 22:02:23.242  4988  4988 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 22:02:23.242  4988  5054 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 22:02:23.252  7512  7512 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 22:02:23.252  7512  7512 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-09 22:02:23.252  7512  7512 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 22:02:23.252  7163  7163 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 22:02:23.252  7529  7529 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,09-09 22:02:23.252  7529  7529 I dhcpcd  : bssid match
,09-09 22:02:23.262  7529  7529 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
09-09 22:02:23.262  1017  1128 D WifiP2pService: P2pDisabledState{ what=143375 }
09-09 22:02:23.262   278   991 D CommandListener: Clearing all IP addresses on wlan0
09-09 22:02:23.262  1017  1128 D WifiP2pService: DefaultState{ what=143375 }
,09-09 22:02:23.262  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-09 22:02:23.262  7400  7400 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
09-09 22:02:23.262  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:23.262  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 22:02:23.262  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-09 22:02:23.262  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-09 22:02:23.262  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:23.262  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:23.262  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 22:02:23.272  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 22:02:23.272  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:23.272  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 22:02:23.272  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:23.272  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:23.272  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:23.272  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,09-09 22:02:23.282  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 22:02:23.282  1017  1129 D SecContentProvider2: mCursor = null
,09-09 22:02:23.282  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 22:02:23.282  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:23.282  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 22:02:23.282  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:23.282  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:23.282  1017  1508 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 22:02:23.282  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:23.282  4988  4988 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 22:02:23.282  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:23.282  1017  1508 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 22:02:23.282  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:23.282  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:23.282  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-09 22:02:23.282  1180  1731 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 22:02:23.282  7003  7003 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:23.282  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:23.282  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:23.282  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:23.282  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 22:02:23.282  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 22:02:23.282  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:23.282  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:23.282  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:23.282  7003  7003 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:23.282  1180  1180 D HotspotTile: onReceive : 0, 0
09-09 22:02:23.282  7003  7003 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 22:02:23.282  1017  1508 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:23.282  1017  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:23.282  1017  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 22:02:23.292  1632  1632 I Hs20UtilService: Starting #16
09-09 22:02:23.292  1632  1662 I Hs20UtilService: Message received 5007
,09-09 22:02:23.292  7003  7003 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 22:02:23.292  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-09 22:02:23.292  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:23.292  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:23.292  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 22:02:23.292  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 22:02:23.292  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:23.292  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:23.292  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 22:02:23.292  7003  7003 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:23.292  7003  7003 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 22:02:23.292  4988  4988 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
09-09 22:02:23.292  4988  4988 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 22:02:23.292  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 22:02:23.292  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 22:02:23.292  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-09 22:02:23.292  4988  4988 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 22:02:23.302  4988  5054 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 22:02:23.302  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 22:02:23.302  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 22:02:23.302  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:23.312  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:23.312  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 22:02:23.312  1632  1632 I Hs20UtilService: Starting #17
,09-09 22:02:23.312  1632  1662 I Hs20UtilService: Message received 5011
,09-09 22:02:23.312  7201  7201 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 22:02:23.312  7201  7201 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 22:02:23.312  7201  7201 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 22:02:23.312  7201  7201 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 22:02:23.342  7529  7529 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,09-09 22:02:23.382  7529  7529 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
,09-09 22:02:23.382  7400  7400 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 22:02:23.432  7400  7400 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
09-09 22:02:23.432  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 22:02:23.432  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 22:02:23.432  1017  1044 D Tethering: interfaceStatusChanged p2p0, false,
,09-09 22:02:23.452  7400  7400 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-09 22:02:23.452  7400  7400 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-09 22:02:23.452  7400  7400 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-09 22:02:23.452  7400  7400 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-09 22:02:23.452  7400  7400 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-09 22:02:23.452  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 22:02:23.452  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,09-09 22:02:23.452  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
09-09 22:02:23.462  1017  1132 D Tethering: InitialState.processMessage what=4
09-09 22:02:23.462  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:23.462  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:23.462  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 22:02:23.462  1017  1132 E Tethering: No numeric data,
,09-09 22:02:23.462  1017  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 22:02:23.462  1017  1132 D Tethering: clearTetheredNotification()
09-09 22:02:23.462  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:23.462  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:23.462  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 22:02:23.462  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:23.462  1017  1126 V NetworkStats: performPollLocked(flags=0x1),
09-09 22:02:23.462  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 22:02:23.462  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 22:02:23.462  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 22:02:23.462  1180  1180 D HotspotTile: updateTetherState():false, false
09-09 22:02:23.462  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:23.462  1017  1126 V NetworkStats: performPollLocked() took 3ms
,09-09 22:02:23.472  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:23.472  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:23.552  1017  1096 V AlarmManager: waitForAlarm result :4
,09-09 22:02:23.562   278   987 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 22:02:23.562   278   987 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-09 22:02:23.582  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:23.582  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:23.582  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-09 22:02:23.722  7400  7400 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 22:02:23.802  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
09-09 22:02:23.802  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 22:02:23.802  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
09-09 22:02:23.802  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:23.802  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
09-09 22:02:23.802  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
09-09 22:02:23.802  7400  7400 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-09 22:02:23.912  1017  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0,
09-09 22:02:23.912  1017  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21],
,09-09 22:02:23.922  7178  7178 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,09-09 22:02:23.922  4988  4988 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 22:02:23.932  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 22:02:23.932  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:23.932  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 22:02:23.932  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:23.932  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:23.932  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:23.932  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:23.932  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:23.932  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-09 22:02:23.932  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 22:02:23.932  1180  1731 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 22:02:23.932  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:23.932  1180  1180 D HotspotTile: onReceive : 1, 0
,09-09 22:02:23.932  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:23.932  1754  2204 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 22:02:23.942  1017  4465 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 22:02:23.942  1017  4465 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 22:02:23.942  1017  4465 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:23.942  1017  4465 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:23.942  1017  4465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 22:02:23.942  1632  1632 I Hs20UtilService: Starting #18
,09-09 22:02:23.942  1632  1662 I Hs20UtilService: Message received 5011
,09-09 22:02:23.952  7201  7201 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 22:02:23.952  7201  7201 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 22:02:23.952  7201  7201 D SecurityLogAgent: StateMachine : Current State = 1
09-09 22:02:23.952  7201  7201 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 22:02:24.032   288   288 E SMD     : DCD OFF,
,09-09 22:02:24.042   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-09 22:02:24.642   278   985 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,09-09 22:02:24.642  1017  1044 D Tethering: interfaceRemoved wlan0
,09-09 22:02:24.642  1017  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-09 22:02:24.802  1017  1044 D Tethering: interfaceRemoved p2p0
,09-09 22:02:24.802  1017  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-09 22:02:25.142  6098  6098 D FactoryTest: Not factory mode
,09-09 22:02:25.142  6098  6098 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-09 22:02:25.142  6098  6098 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-09 22:02:25.142  6098  6098 D MTPRx   : still no open session command from host, so toast
,09-09 22:02:25.152  6098  6098 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
,09-09 22:02:25.152  6098  6098 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 ,
,09-09 22:02:25.152  6098  6098 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:120107,
09-09 22:02:25.152  1017  1506 E PersonaManagerService: inState():  stateMachine is null !!
,09-09 22:02:25.152  1017  1506 I PersonaManagerService: PersonaId don't exist
09-09 22:02:25.152  1017  1506 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-09 22:02:25.162  1017  1506 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,09-09 22:02:25.162  1017  1506 W ActivityManager: userId = 0, bbcId = -10000,
09-09 22:02:25.162  1017  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:25.162  1017  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-09 22:02:25.172  1017  1506 W ActivityManager: mDVFSHelper.acquire()
,09-09 22:02:25.182  1017  1506 D PersonaManager: isKioskContainerExistOnDevice
,09-09 22:02:25.192  1017  1506 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-09 22:02:25.192  1017  1506 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-09 22:02:25.192  1017  1506 D InputDispatcher: Focused application set to: xxxx
,09-09 22:02:25.192  1017  1506 D InputDispatcher: Focus left window: 7003
,09-09 22:02:25.202  6098  6098 E MTPRx   : started activity for popup
,09-09 22:02:25.202  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 22:02:25.202  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 22:02:25.232  6098  6098 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-09 22:02:25.232  6098  6098 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-09 22:02:25.232  6098  6098 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-09 22:02:25.232  6098  6098 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 22:02:25.232  6098  6098 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 22:02:25.232  6098  6098 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 22:02:25.252  6098  6098 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-09 22:02:25.252  1017  1509 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-09 22:02:25.252  1017  1509 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-09 22:02:25.252  1017  1509 D InputDispatcher: Focused application set to: xxxx
,09-09 22:02:25.252  1017  1509 D InputDispatcher: Focus entered window: 7003
,09-09 22:02:25.252  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-09 22:02:25.262  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 22:02:25.262  1017  4071 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-09 22:02:25.262  1017  4071 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3735b6a9 attribute=null, token = android.os.BinderProxy@2d78445a
,09-09 22:02:25.302  6098  6098 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-09 22:02:25.302  6098  6098 D PhoneWindow: *FMB* installDecor mIsFloating : true
,09-09 22:02:25.302  6098  6098 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-09 22:02:25.322  7003  7003 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-09 22:02:25.322  7003  7003 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
09-09 22:02:25.322  7003  7003 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-09 22:02:25.322  7003  7003 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-09 22:02:25.322  1017  1320 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-09 22:02:25.322  1017  1320 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-09 22:02:25.322  1017  1320 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-09 22:02:25.332  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-09 22:02:25.332  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,09-09 22:02:25.342  7003  7003 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 22:02:25.342  7003  7003 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-09 22:02:25.342  7003  7003 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1045394a Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@30a67838, 16908290=android.view.AbsSavedState$1@30a67838}, android:focusedViewId=100}]}]
09-09 22:02:25.342  7003  7003 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-09 22:02:25.342  7003  7003 V ActivityThread: updateVisibility : ActivityRecord{1db32f25 token=android.os.BinderProxy@3b689bee {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-09 22:02:25.342  7003  7003 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 22:02:25.342  7003  7003 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-09 22:02:25.352  7003  7003 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3b689bee time:120300
,09-09 22:02:25.362  1017  3703 D PersonaManager: isKioskContainerExistOnDevice
,09-09 22:02:25.542  1017  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-09 22:02:26.152  7003  7061 D BluetoothAdapter: enable()
,09-09 22:02:26.152  1017  1320 W ActivityManager: Permission Denial: getCurrentUser() from pid=7003, uid=10170 requires android.permission.INTERACT_ACROSS_USERS,
,09-09 22:02:26.152  1017  1320 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
09-09 22:02:26.152  1017  1320 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7003, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-09 22:02:26.152  1017  1320 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-09 22:02:26.152  1017  1320 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-09 22:02:26.152  1017  1320 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-09 22:02:26.152  1017  1320 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
,09-09 22:02:26.152  1017  1320 W BluetoothManagerService: ,	at android.os.Binder.execTransact(Binder.java:446)
09-09 22:02:26.152  1017  1320 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-09 22:02:26.152  1017  1320 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 22:02:26.162  1017  1320 D SettingsProvider: name = bluetooth_on
,09-09 22:02:26.172  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
09-09 22:02:26.172  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 22:02:26.172  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-09 22:02:26.172  3374  3432 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-09 22:02:26.172  3374  3432 D BluetoothAdapterProperties: Setting state to 11
09-09 22:02:26.172  3374  3432 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-09 22:02:26.172  3374  3432 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 22:02:26.172  3374  3432 D BluetoothAdapterService: updateAdapterState state is 11
,09-09 22:02:26.182  3374  3432 D BluetoothAdapterService: Autoconnection is available 
,09-09 22:02:26.182  3374  3432 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-09 22:02:26.182  3374  3432 D BtConfig.SecureMode: isSecureModeOn:false
09-09 22:02:26.182  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-09 22:02:26.182  3374  3432 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
09-09 22:02:26.182  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-09 22:02:26.182  3374  3432 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
09-09 22:02:26.182  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 22:02:26.182  3374  3432 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-09 22:02:26.182  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 22:02:26.182  3374  3432 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-09 22:02:26.182  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 22:02:26.182  3374  3432 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-09 22:02:26.182  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 22:02:26.182  3374  3432 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-09 22:02:26.182  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:26.182  3374  3432 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-09 22:02:26.182  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 22:02:26.182  3374  3432 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-09 22:02:26.182  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 22:02:26.182  3374  3432 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 22:02:26.182  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 22:02:26.182  3374  3432 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-09 22:02:26.182  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 22:02:26.182  3374  3432 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-09 22:02:26.182  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-09 22:02:26.182  3374  3432 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-09 22:02:26.182  3374  3432 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-09 22:02:26.182  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-09 22:02:26.182  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-09 22:02:26.182  3374  3432 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-09 22:02:26.182  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:26.182  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,09-09 22:02:26.192  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 22:02:26.192  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:26.192  1180  1180 D BluetoothTile:  getBluetoothState : 11
,09-09 22:02:26.192  1874  1874 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
09-09 22:02:26.192  4988  4988 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:26.192  1017  1499 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:26.192  1017  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-09 22:02:26.192  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:26.192  1017  1210 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 22:02:26.202  1017  1499 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:26.202  1017  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:26.202  1017  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:26.202  1017  1078 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 22:02:26.202  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:26.202  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-09 22:02:26.202  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 22:02:26.202  3374  3432 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-09 22:02:26.202  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-09 22:02:26.202  1180  1731 D BluetoothTile:  handleUpdatestate:false name:null
09-09 22:02:26.202  1180  1731 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
09-09 22:02:26.202  2629  2629 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 22:02:26.202  1017  1509 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:26.202  3374  3374 D HeadsetService: Received start request. Starting profile...
09-09 22:02:26.202  1017  1509 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-09 22:02:26.202  3374  3374 D HeadsetService: start()
09-09 22:02:26.202  3374  3374 D HeadsetStateMachine: make
,09-09 22:02:26.202  1017  1509 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:26.202  1017  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:26.202  1017  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:26.212  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-09 22:02:26.212  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 22:02:26.212  3374  3432 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-09 22:02:26.212  3374  3374 E HeadsetStateMachine: # of Max HF connection is 2
,09-09 22:02:26.222  4988  4988 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 22:02:26.222  1017  1210 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-09 22:02:26.222  1017  1210 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
09-09 22:02:26.222  1017  1210 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:26.222  1017  1210 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:26.222  1017  1210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-09 22:02:26.222  1017  1320 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:26.222  1017  1320 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 22:02:26.222  1017  1320 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:26.222  1017  1320 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:26.222  1017  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:26.222  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-09 22:02:26.222  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 22:02:26.222  3374  3432 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-09 22:02:26.222  1017  3700 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:26.222  1017  3700 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-09 22:02:26.222  1017  3700 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:26.222  1017  3700 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:26.222  1017  3700 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:26.232  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,09-09 22:02:26.232  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 22:02:26.232  3374  3432 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-09 22:02:26.232  1017  3700 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:26.232  1017  3700 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 22:02:26.232  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:26.232  1017  3700 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:26.232  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
09-09 22:02:26.232  1017  3700 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:26.232  1017  3700 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:26.232  1017  4071 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-09 22:02:26.232  1017  4071 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-09 22:02:26.232  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-09 22:02:26.232  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:26.232  3374  3432 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-09 22:02:26.232  1017  4071 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:26.232  1017  4071 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:26.232  1017  4071 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-09 22:02:26.232  3374  3374 I bluedroid: get_profile_interface handsfree
09-09 22:02:26.232  1017  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:26.232  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 22:02:26.242  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:26.242  1017  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:26.242  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:26.242  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-09 22:02:26.242  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 22:02:26.242  3374  3432 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-09 22:02:26.242  1017  4465 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-09 22:02:26.242  1017  4465 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:26.242  1017  4465 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:26.242  1017  4465 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:26.242  1017  4465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:26.252  7567  7567 E Zygote  : MountEmulatedStorage()
09-09 22:02:26.252  7567  7567 I libpersona: KNOX_SDCARD checking this for 10055
,09-09 22:02:26.252  7567  7567 E Zygote  : v2
09-09 22:02:26.252  7567  7567 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:26.262  7567  7567 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 22:02:26.262  1017  4465 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7567 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
09-09 22:02:26.262  1017  1210 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:26.262  1017  1210 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 22:02:26.262  7567  7567 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 22:02:26.262  7567  7567 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 22:02:26.262  1017  1210 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:26.262  1017  1210 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:26.262  1017  1210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:26.272  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-09 22:02:26.272  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 22:02:26.272  3374  3432 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-09 22:02:26.272  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-09 22:02:26.272  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 22:02:26.272  3374  3432 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-09 22:02:26.272  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-09 22:02:26.272  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 22:02:26.272  3374  3432 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-09 22:02:26.272  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-09 22:02:26.272  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-09 22:02:26.272  3374  3432 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-09 22:02:26.272  3374  3432 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-09 22:02:26.272  3374  3374 E DualScoManager: Dual Sco Manager already instantiated
09-09 22:02:26.272  3374  3374 I DualScoManager: Set HeadsetServiceHelper
09-09 22:02:26.272  3374  3374 D BluetoothAtMessage: createCMTIContentObservers
,09-09 22:02:26.272  1017  1499 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-09 22:02:26.272  1017  1499 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:26.272  1017  1499 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 22:02:26.272  1017  1499 D SettingsProvider: selectionArgs: false
09-09 22:02:26.272  1017  1499 D SettingsProvider: selectionArgs: 1002
09-09 22:02:26.272  1017  1499 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 22:02:26.272  1017  1499 D SettingsProvider: ret = -1
,09-09 22:02:26.272  3374  7566 D HeadsetStateMachine: Enter Disconnected: -2
,09-09 22:02:26.272  3374  3374 D HeadsetService: mStartError = false
09-09 22:02:26.272  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
,09-09 22:02:26.272  3374  3374 D A2dpService: Received start request. Starting profile...
09-09 22:02:26.272  3374  3374 D A2dpService: start()
09-09 22:02:26.272  3374  3374 I bluedroid: get_profile_interface avrcp
,09-09 22:02:26.282  3374  7566 D HeadsetStateMachine: Clear mHeadsetBrsf
09-09 22:02:26.282  3374  7566 D HeadsetStateMachine: map size, before remove : 0
09-09 22:02:26.282  3374  7566 D HeadsetStateMachine: map size, after remove: 0
,09-09 22:02:26.282  3374  3374 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-09 22:02:26.282  3374  3374 D Avrcp   : Initialize Media Controller
09-09 22:02:26.282  3374  3374 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-09 22:02:26.282  3374  3374 E Avrcp   : getActiveSessions
,09-09 22:02:26.282  3374  3374 D Avrcp   : pick active media Controller
09-09 22:02:26.282  3374  3374 D Avrcp   : Get the active Media Controller 
,09-09 22:02:26.292  3374  3374 I Avrcp   :  Updating now playing list upon AVRCP Start
09-09 22:02:26.292  3374  7580 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-09 22:02:26.292  3374  3374 D A2dpStateMachine: make
,09-09 22:02:26.292  3374  3374 I bluedroid: get_profile_interface a2dp
,09-09 22:02:26.292  3374  7584 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-09 22:02:26.292  3374  3374 E bt-btif : warning : media task started media_task_refcnt 1 
,09-09 22:02:26.292  3374  3374 D A2dpService: mStartError = false
09-09 22:02:26.292  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
09-09 22:02:26.292  3374  7583 D A2dpStateMachine: Enter Disconnected: -2
09-09 22:02:26.292  3374  3374 D HeadsetStateMachine: Try to query the phonestate on bind
09-09 22:02:26.302  1451  1488 I Telecom : BluetoothPhoneService: queryPhoneState
,09-09 22:02:26.302  1451  1451 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-09 22:02:26.302  1451  1451 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-09 22:02:26.302  1451  1488 I Telecom : BluetoothPhoneService: Result of Message : true
,09-09 22:02:26.302  3374  3374 D HidService: Received start request. Starting profile...
09-09 22:02:26.302  3374  3374 D HidService: start()
09-09 22:02:26.302  3374  3374 I bluedroid: get_profile_interface hidhost
09-09 22:02:26.302  3374  3374 D HidService: setHidService(): set to: null
09-09 22:02:26.302  3374  3374 D HidService: mStartError = false
09-09 22:02:26.302  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
,09-09 22:02:26.302  7567  7567 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:26.302  3374  3374 D HealthService: Received start request. Starting profile...
09-09 22:02:26.302  3374  3374 D HealthService: start()
09-09 22:02:26.302  7567  7567 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:26.312  3374  3374 I bluedroid: get_profile_interface health
09-09 22:02:26.312  3374  3374 D HealthService: mStartError = false
09-09 22:02:26.312  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
09-09 22:02:26.312  3374  3374 D HeadsetStateMachine: Proxy object connected
,09-09 22:02:26.312  3374  3374 D PanService: Received start request. Starting profile...
09-09 22:02:26.312  3374  3374 D PanService: start()
09-09 22:02:26.312  3374  3374 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 22:02:26.312  3374  3374 I bluedroid: get_profile_interface pan
09-09 22:02:26.312  3374  3374 D PanService: mStartError = false
09-09 22:02:26.312  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
,09-09 22:02:26.312  3374  3374 D BluetoothMapService: Received start request. Starting profile...
09-09 22:02:26.312  3374  3374 D BluetoothMapService: start()
,09-09 22:02:26.312  3374  3374 D BluetoothMapService: mStartError = false
,09-09 22:02:26.312  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
09-09 22:02:26.312  3374  3374 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-09 22:02:26.312  3374  7566 D HeadsetStateMachine: Disconnected process message: 11
,09-09 22:02:26.312  3374  7580 D BluetoothMediaBrowser: no now playing list
09-09 22:02:26.312  3374  7580 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
09-09 22:02:26.312  3374  3374 D SapService: Received start request. Starting profile...
09-09 22:02:26.312  3374  3374 D SapService: start()
09-09 22:02:26.312  3374  3374 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-09 22:02:26.312  3374  3374 I bluedroid: get_profile_interface sap
09-09 22:02:26.312  3374  3374 D SapService: mStartError = false
09-09 22:02:26.312  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
09-09 22:02:26.312  3374  3374 D HeadsetPhoneState: sendDeviceDataStateChanged
09-09 22:02:26.312  3374  3374 D HeadsetPhoneState: Signal level : previous=0 curr=4
09-09 22:02:26.312  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-09 22:02:26.312  3374  3374 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-09 22:02:26.312  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-09 22:02:26.312  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-09 22:02:26.312  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-09 22:02:26.312  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-09 22:02:26.322  3374  7566 D HeadsetStateMachine: Disconnected process message: 18
09-09 22:02:26.322  3374  7566 D HeadsetStateMachine: Disconnected process message: 10
09-09 22:02:26.322  3374  7566 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 22:02:26.322  3374  7566 D HeadsetStateMachine: Disconnected process message: 11
,09-09 22:02:26.332  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-09 22:02:26.332  7567  7567 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-09 22:02:26.332  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-09 22:02:26.332  3374  3432 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-09 22:02:26.332  3374  3432 I bluedroid: enable
,09-09 22:02:26.342  3374  3435 E bt-btif : Calling BTA_HhEnable
,09-09 22:02:26.342  3374  3435 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-09 22:02:26.342  3374  3435 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-09 22:02:26.342  3374  3435 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-09 22:02:26.342  3374  3435 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
,09-09 22:02:26.342  3374  3435 E BluetoothServiceJni: populateRssiValuesNative
,09-09 22:02:26.342  3374  3435 I bluedroid: getModelRssiValues
,09-09 22:02:26.342  3374  3435 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-09 22:02:26.352  3374  3435 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-09 22:02:26.352  1017  1017 D SettingsProvider: name = bluetooth_name
,09-09 22:02:26.352  3374  3435 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-09 22:02:26.352  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:26.362  3374  3435 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-09 22:02:26.362  3374  3435 D BluetoothAdapterProperties: Scan Mode:20
09-09 22:02:26.362  3374  3435 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 22:02:26.362  3374  3435 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
09-09 22:02:26.362  3374  3435 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
09-09 22:02:26.362  3374  3435 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,09-09 22:02:26.362  3374  3435 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-09 22:02:26.362  3374  3435 E bt-btif : JVenable fails
,09-09 22:02:26.362  3374  3435 D bte_conf: Device ID record 1 : primary
09-09 22:02:26.362  3374  3435 D bte_conf:   vendorId            = 0075
09-09 22:02:26.362  3374  3435 D bte_conf:   vendorIdSource      = 0001
09-09 22:02:26.362  3374  3435 D bte_conf:   product             = 0100
09-09 22:02:26.362  3374  3435 D bte_conf:   version             = 0200
09-09 22:02:26.362  3374  3435 D bte_conf:   clientExecutableURL = 
09-09 22:02:26.362  3374  3435 D bte_conf:   serviceDescription  = 
09-09 22:02:26.362  3374  3435 D bte_conf:   documentationURL    = 
,09-09 22:02:26.362  3374  3435 D bte_conf: bte_load_did_conf no section named DID2.
09-09 22:02:26.362  3374  3435 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-09 22:02:26.362  3374  3435 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 22:02:26.362  3374  3432 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-09 22:02:26.362  3374  3432 D BluetoothAdapterProperties: ScanMode =  20
09-09 22:02:26.362  3374  3432 D BluetoothAdapterProperties: State =  11
,09-09 22:02:26.362  1017  1509 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-09 22:02:26.362  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:26.372  3374  3432 D BluetoothAdapterProperties: Setting state to 12,
09-09 22:02:26.372  3374  3432 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 22:02:26.372  7567  7567 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-09 22:02:26.372  7567  7567 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-09 22:02:26.372  7567  7567 D UserAnalysis: Create SecureDbHelper
,09-09 22:02:26.372  3374  3435 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 22:02:26.372  3374  3435 D BluetoothAdapterProperties: Scan Mode:21
09-09 22:02:26.372  3374  3435 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 22:02:26.372  1017  1030 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-09 22:02:26.372  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:26.372  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 22:02:26.372  1017  1030 D SettingsProvider: selectionArgs: false
09-09 22:02:26.372  1017  1030 D SettingsProvider: selectionArgs: 1002
09-09 22:02:26.372  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 22:02:26.372  1017  1030 D SettingsProvider: ret = -1
,09-09 22:02:26.372  3374  3432 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 22:02:26.372  3374  3432 D BluetoothAdapterService: updateAdapterState state is 12
,09-09 22:02:26.372  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:26.372  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 22:02:26.372  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:26.372  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:26.372  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:26.382  7567  7567 D IntelligenceServiceApplication: onCreate()
,09-09 22:02:26.382  3374  3432 D BluetoothAdapterService: Autoconnection is available 
09-09 22:02:26.382  3374  3432 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-09 22:02:26.382  3374  3432 D BluetoothAdapterService: starting service from this receiver
,09-09 22:02:26.382  3374  3374 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12,
09-09 22:02:26.382  1017  1524 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:26.382  3374  3374 I BluetoothPbapService: Handler(): got msg=1
09-09 22:02:26.382  1017  1524 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-09 22:02:26.382  4988  4998 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 22:02:26.382  1017  1506 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-09 22:02:26.382  1017  1524 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:26.382  1017  1524 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:26.382  1017  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:26.382  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-09 22:02:26.382  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 22:02:26.392  3374  3432 I BluetoothAdapterState: Entering On State from state = 11
,09-09 22:02:26.392  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:26.392  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:26.392  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:26.392  7567  7567 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-09 22:02:26.392  1017  1320 I ActivityManager: Killing 7107:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,09-09 22:02:26.392  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:26.392  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:26.392  3374  7589 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-09 22:02:26.392  1478  2128 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:26.392  1017  4465 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-09 22:02:26.402  1017  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 22:02:26.402  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 22:02:26.402  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:26.402  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:26.402  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:26.402  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 22:02:26.402  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:26.402  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:26.402  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,09-09 22:02:26.402  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 22:02:26.402  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:26.402  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:26.402  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
09-09 22:02:26.402  7567  7567 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-09 22:02:26.402  1478  2128 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 22:02:26.402  4988  5000 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 22:02:26.402  3374  7589 D BluetoothSocket: bindListen(): myUserId = 0
,09-09 22:02:26.402  3374  7589 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 22:02:26.402  4988  5000 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-09 22:02:26.402  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 22:02:26.402  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 22:02:26.402  7003  7003 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 22:02:26.402  3374  7589 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-09 22:02:26.402  3374  7589 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 22:02:26.402  3374  7589 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 22:02:26.402  3374  7589 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@186908f8
09-09 22:02:26.402  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:26.402  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:26.402  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:26.402  3374  7589 D BluetoothSocket: channel: 19
09-09 22:02:26.402  3374  7589 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-09 22:02:26.402  4988  4998 D Bluetoothsap: onBluetoothStateChange: up=true
09-09 22:02:26.402  4988  4998 D Bluetoothsap: Binding service...
,09-09 22:02:26.412  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:26.412  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:26.412  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:26.412  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 22:02:26.412  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:26.412  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:26.412  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:26.412  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:26.412  7567  7567 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
09-09 22:02:26.412  4988  4988 D BluetoothInputDevice: Proxy object connected
09-09 22:02:26.412  4988  4988 D HidProfile: Bluetooth service connected
,09-09 22:02:26.422  4988  4988 D BluetoothA2dp: Proxy object connected
09-09 22:02:26.422  7003  7003 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 22:02:26.422  4988  4988 D A2dpProfile: Bluetooth service connected
09-09 22:02:26.422  4988  4998 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-09 22:02:26.422  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-09 22:02:26.422  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 22:02:26.422  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:26.422  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:26.422  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:26.422  4988  4998 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-09 22:02:26.422  4988  4988 D Bluetoothsap: BluetoothSAP Proxy object connected
09-09 22:02:26.422  4988  4988 D SapProfile: Bluetooth service connected
09-09 22:02:26.422  4988  4988 D Bluetoothsap: getConnectedDevices()
,09-09 22:02:26.422  1478  1502 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:26.422  1478  1502 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:26.422  1017  1046 D BluetoothPan: Binding service...
09-09 22:02:26.422  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-09 22:02:26.422  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 22:02:26.422  3374  3391 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 22:02:26.422  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 22:02:26.422  3374  3391 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:26.432  1017  1046 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 22:02:26.432  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 22:02:26.432  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:26.432  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:26.432  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:26.432  3374  3374 D BluetoothA2dp: Proxy object connected
09-09 22:02:26.432  3374  3374 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-09 22:02:26.432  1451  1466 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:26.432  1451  1466 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:26.432  1465  1494 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:26.432  1465  1494 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 22:02:26.432  4988  7591 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 22:02:26.432  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-09 22:02:26.432  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 22:02:26.432  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:26.432  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:26.432  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:26.432  7003  7015 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:26.432  7003  7015 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:26.432  4988  4988 D BluetoothPbap: Proxy object connected
,09-09 22:02:26.432  4988  4988 D PbapServerProfile: Bluetooth service connected
09-09 22:02:26.432  3374  3480 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:26.432  3374  3480 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 22:02:26.432  4988  5000 D BluetoothPan: Binding service...
,09-09 22:02:26.442  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-09 22:02:26.442  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 22:02:26.442  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:26.442  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:26.442  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:26.442  1754  1763 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:26.442  1754  1763 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 22:02:26.442  4988  4988 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 22:02:26.442  4988  4988 D PanProfile: Bluetooth service connected
,09-09 22:02:26.442  4988  4998 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:26.442  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 22:02:26.442  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 22:02:26.442  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:26.442  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:26.442  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:26.442  4988  4998 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 22:02:26.442  1451  3484 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:26.442  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 22:02:26.442  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 22:02:26.442  4988  4988 D HeadsetProfile: Bluetooth service connected
09-09 22:02:26.442  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:26.442  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:26.442  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:26.442  1451  3484 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 22:02:26.442  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 22:02:26.442  1017  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-09 22:02:26.452  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 22:02:26.452  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 22:02:26.452  1017  1017 D BluetoothA2dp: Proxy object connected
,09-09 22:02:26.452  1451  1466 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:26.452  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 22:02:26.452  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 22:02:26.452  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:26.452  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:26.452  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:26.452  1451  1466 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 22:02:26.452  4988  5000 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 22:02:26.452  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-09 22:02:26.452  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 22:02:26.452  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:26.452  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:26.452  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:26.452  1017  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-09 22:02:26.452  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 22:02:26.452  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 22:02:26.452  1017  1046 E BluetoothHeadset: BluetoothHeadset service is binded
09-09 22:02:26.452  2629  2673 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:26.452  2629  2673 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:26.452  1180  1642 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:26.452  1180  1642 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:26.452  4988  4998 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:26.452  4988  4998 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 22:02:26.462  4988  4988 D BluetoothMap: Proxy object connected
09-09 22:02:26.462  4988  4988 D MapProfile: Bluetooth service connected
09-09 22:02:26.462  4988  4988 D BluetoothMap: getConnectedDevices()
,09-09 22:02:26.522  1017  1046 E BluetoothManagerService: Unable to call onBluetoothStateChange() on callback #24
09-09 22:02:26.522  1017  1046 E BluetoothManagerService: android.os.DeadObjectException
09-09 22:02:26.522  1017  1046 E BluetoothManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 22:02:26.522  1017  1046 E BluetoothManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 22:02:26.522  1017  1046 E BluetoothManagerService: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub$Proxy.onBluetoothStateChange(IBluetoothStateChangeCallback.java:84)
09-09 22:02:26.522  1017  1046 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:1053)
09-09 22:02:26.522  1017  1046 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2007)
09-09 22:02:26.522  1017  1046 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
09-09 22:02:26.522  1017  1046 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1576)
09-09 22:02:26.522  1017  1046 E BluetoothManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:26.522  1017  1046 E BluetoothManagerService: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:26.522  1017  1046 E BluetoothManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 22:02:26.522  1017  1046 E BluetoothManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-09 22:02:26.522  1451  3484 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:26.522  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-09 22:02:26.522  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 22:02:26.522  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:26.522  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:26.522  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-09 22:02:26.522  1451  3484 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 22:02:26.522  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-09 22:02:26.522  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-09 22:02:26.532  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:26.532  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
09-09 22:02:26.532  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-09 22:02:26.532  1451  1451 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@41a4823, true
,09-09 22:02:26.532  1451  1451 D BluetoothHeadset: registerMessageListener
,09-09 22:02:26.532  1180  1180 D BluetoothTile:  onBluetoothStateChange:
,09-09 22:02:26.542  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-09 22:02:26.542  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:26.542  1180  1180 D BluetoothTile:  getBluetoothState : 12
,09-09 22:02:26.542  1180  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 22:02:26.542  1180  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 22:02:26.542  1017  1508 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 22:02:26.542  1017  1030 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-09 22:02:26.542  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 22:02:26.542  1180  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 22:02:26.552  1874  1874 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 22:02:26.552  4988  4988 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:26.562  3374  3698 D HeadsetService: registerMessageListener
,09-09 22:02:26.562  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:26.562  4988  4988 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-09 22:02:26.562  4988  4988 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-09 22:02:26.562  4988  4988 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-09 22:02:26.562  4988  4988 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-09 22:02:26.562  3374  3698 D HeadsetService: registerMessageListener
,09-09 22:02:26.562  3374  7566 D HeadsetStateMachine: Disconnected process message: 70
09-09 22:02:26.562  3374  7566 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2345f436
,09-09 22:02:26.562  1451  1451 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-09 22:02:26.562  1451  1451 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-09 22:02:26.572  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:26.572  3374  7592 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-09 22:02:26.572  1451  1451 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-09 22:02:26.572  1451  1451 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-09 22:02:26.572  1451  1451 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-09 22:02:26.572  3374  7566 D HeadsetStateMachine: Disconnected process message: 9
09-09 22:02:26.572  3374  7566 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6,
09-09 22:02:26.572  3374  7592 D BluetoothSocket: bindListen(): myUserId = 0
09-09 22:02:26.572  3374  7592 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 22:02:26.572  4988  4988 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 22:02:26.572  3374  7592 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
,09-09 22:02:26.572  1017  3700 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-09 22:02:26.572  1017  3700 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 22:02:26.572  3374  7592 D BluetoothSocket: bindListen(), new LocalSocket 
,09-09 22:02:26.572  1017  3700 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:26.572   283   697 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-09 22:02:26.572   283   697 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-09 22:02:26.572   283   697 V voice   : voice_set_parameters: exit with code(-2)
09-09 22:02:26.572   283   697 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-09 22:02:26.572   283   697 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-09 22:02:26.572   283   697 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-09 22:02:26.572   283   697 V audio_hw_primary: adev_set_parameters: exit
,09-09 22:02:26.572  3374  7566 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
09-09 22:02:26.572  1017  3700 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:26.572  1017  3700 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
09-09 22:02:26.572  3374  7592 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,09-09 22:02:26.582  3374  7592 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2cf59f37
09-09 22:02:26.582  3374  7592 D BluetoothSocket: channel: 5
,09-09 22:02:26.582  2629  2629 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 22:02:26.592  4988  4988 D DockEventReceiver: finishStartingService: stopping service
,09-09 22:02:26.592  4988  4988 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 22:02:26.592  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:26.592  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-09 22:02:26.602  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc,
09-09 22:02:26.602  3374  3374 D BtConfig.SecureMode: isSecureModeOn:false
,09-09 22:02:26.602  1017  3700 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:26.602  1017  3700 W ActivityManager: userId = 0, bbcId = -10000,
09-09 22:02:26.602  1017  3700 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
09-09 22:02:26.602  1017  3700 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:26.602  1017  3700 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:26.612  1017  1078 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-09 22:02:26.612  1017  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:26.612  1017  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:26.612  1017  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:26.612  1017  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:26.622  7595  7595 E Zygote  : MountEmulatedStorage()
,09-09 22:02:26.622  1017  1078 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7595 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-09 22:02:26.622  7595  7595 E Zygote  : v2
09-09 22:02:26.622  7595  7595 I libpersona: KNOX_SDCARD checking this for 10105
09-09 22:02:26.622  7595  7595 I libpersona: KNOX_SDCARD not a persona
09-09 22:02:26.632  1017  4465 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-09 22:02:26.632  7595  7595 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 22:02:26.632  7595  7595 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 22:02:26.632  7595  7595 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 22:02:26.652  3374  7604 D BluetoothSocket: bindListen(): myUserId = 0
,09-09 22:02:26.652  3374  7604 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 22:02:26.652  3374  7604 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
09-09 22:02:26.652  3374  7604 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 22:02:26.652  3374  7604 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 22:02:26.652  3374  7604 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@9faf7d3
,09-09 22:02:26.652  3374  7604 D BluetoothSocket: channel: 12
,09-09 22:02:26.652  3374  7604 I BtOppRfcommListener: Accept thread started.
,09-09 22:02:26.662  7595  7595 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:26.662  7595  7595 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:26.752   257   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-09 22:02:26.752   257   534 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 22:02:26.752  7595  7616 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-09 22:02:26.762   257   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-09 22:02:26.762   257   534 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 22:02:26.762  7595  7616 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-09 22:02:26.912  7595  7595 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.io.File.exists(File.java:363)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-09 22:02:26.912  7595  7595 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-09 22:02:26.912  7595  7595 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-09 22:02:26.912  7595  7595 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.q.e.b(PG:170)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-09 22:02:26.912  7595  7595 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.q.k.d(PG:583)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.q.e.b(PG:170)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-09 22:02:26.912  7595  7595 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.io.File.exists(File.java:363)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-09 22:02:26.912  7595  7595 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.io.File.exists(File.java:363)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515),
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
,09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
,09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 22:02:26.912  7595  7595 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-09 22:02:26.922  7595  7595 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 22:02:26.922  7595  7595 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 22:02:26.922  7595  7595 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-09 22:02:26.922  7595  7595 D StrictMode: 	at java.io.File.lastModified(File.java:571),
09-09 22:02:26.922  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-09 22:02:26.922  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 22:02:26.922  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-09 22:02:26.922  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 22:02:26.922  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 22:02:26.922  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-09 22:02:26.922  7595  7595 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-09 22:02:26.922  7595  7595 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 22:02:26.922  7595  7595 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 22:02:26.922  7595  7595 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
,09-09 22:02:26.922  7595  7595 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 22:02:26.922  7595  7595 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:26.922  7595  7595 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:26.922  7595  7595 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 22:02:26.922  7595  7595 D StrictMode: 	at j,ava.lang.reflect.Method.invoke(Native Method)
09-09 22:02:26.922  7595  7595 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 22:02:26.922  7595  7595 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
,09-09 22:02:26.922  7595  7595 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 22:02:26.922  1017  1477 I ActivityManager: Killing 6824:com.sec.pcw.device/1000 (adj 15): empty #21
,09-09 22:02:26.972  7595  7626 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.,
,09-09 22:02:26.992  1017  1210 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:27.002  1017  1210 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:27.002  1017  1210 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:27.002  1017  1210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-09 22:02:27.032   288   288 E SMD     : DCD OFF
,09-09 22:02:28.172  1017  1042 W ActivityManager: mDVFSHelper.release(),
,09-09 22:02:28.542  1017  3453 D SSRM:n  : SIOP:: AP = 350
,09-09 22:02:29.042   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 22:02:29.172  7003  7061 D BluetoothAdapter: disable(),
,09-09 22:02:29.172  1017  1030 D SettingsProvider: name = bluetooth_on
,09-09 22:02:29.182  3374  3432 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-09 22:02:29.182  3374  3432 D BluetoothAdapterProperties: Setting state to 13
09-09 22:02:29.182  3374  3432 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 22:02:29.182  3374  3432 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 22:02:29.182  3374  3432 D BluetoothAdapterService: updateAdapterState state is 13
,09-09 22:02:29.182  1017  1508 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 22:02:29.182  1017  1508 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 22:02:29.192  1017  1508 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:29.192  1017  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:29.192  1017  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:29.192  3374  3374 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-09 22:02:29.192  3374  3432 D BluetoothAdapterService: Autoconnection is available 
09-09 22:02:29.192  3374  3432 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-09 22:02:29.192  3374  3432 D BluetoothAdapterService: terminating service from this receiver
,09-09 22:02:29.192  3374  3374 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@378fff10, channel: 19, state: LISTENING
,09-09 22:02:29.192  3374  3374 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@378fff10, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@186908f8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1e66aa09mSocket: android.net.LocalSocket@57b540e impl:android.net.LocalSocketImpl@39f33e2f fd:FileDescriptor[80]
,09-09 22:02:29.192  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:29.192  3374  3374 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@57b540e impl:android.net.LocalSocketImpl@39f33e2f fd:FileDescriptor[80]
09-09 22:02:29.192  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,09-09 22:02:29.202  1180  1180 D BluetoothTile:  onBluetoothStateChange:,
,09-09 22:02:29.212  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-09 22:02:29.212  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:29.212  1180  1180 D BluetoothTile:  getBluetoothState : 13
,09-09 22:02:29.212  1180  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 22:02:29.212  1874  1874 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 22:02:29.212  1180  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 22:02:29.212  4988  4988 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:29.212  1180  1731 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-09 22:02:29.212  1017  1210 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 22:02:29.222  1017  1509 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-09 22:02:29.222  1017  1509 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:29.222  1017  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:29.222  1017  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:29.232  3374  3432 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 22:02:29.232  3374  3432 D BluetoothAdapterProperties: mDiscovering is false
,09-09 22:02:29.232  1017  3703 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-09 22:02:29.232  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ),
09-09 22:02:29.232  1017  1078 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-09 22:02:29.232  3374  3432 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-09 22:02:29.242  7003  7003 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:29.242  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:29.242  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:29.242  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:29.242  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 22:02:29.242  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 22:02:29.242  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:29.242  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:29.242  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:29.242  7003  7003 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:29.242  4988  4988 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 22:02:29.242  1017  3700 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-09 22:02:29.242  1017  3700 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 22:02:29.242  7003  7003 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 22:02:29.242  1017  3700 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:29.242  1017  3700 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:29.242  1017  3700 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 22:02:29.252  7003  7003 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:29.252  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:29.252  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:29.252  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:29.252  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 22:02:29.252  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 22:02:29.252  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:29.252  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:29.252  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:29.252  7003  7003 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 22:02:29.252  7003  7003 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
,09-09 22:02:29.252  3374  3374 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@10ddfc3c, channel: 5, state: LISTENING
09-09 22:02:29.252  3374  3374 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@10ddfc3c, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2cf59f37, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@23c6ddc5mSocket: android.net.LocalSocket@1e9ca31a impl:android.net.LocalSocketImpl@27f8e4b fd:FileDescriptor[82]
09-09 22:02:29.252  3374  3374 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1e9ca31a impl:android.net.LocalSocketImpl@27f8e4b fd:FileDescriptor[82]
09-09 22:02:29.252  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 22:02:29.252  3374  3374 I BtOppRfcommListener: stopping Accept Thread
09-09 22:02:29.252  3374  3374 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@6aca028, channel: 12, state: LISTENING
09-09 22:02:29.252  3374  3374 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@6aca028, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@9faf7d3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@373c9141mSocket: android.net.LocalSocket@1251d6e6 impl:android.net.LocalSocketImpl@1836c427 fd:FileDescriptor[86]
09-09 22:02:29.252  3374  3374 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1251d6e6 impl:android.net.LocalSocketImpl@1836c427 fd:FileDescriptor[86]
09-09 22:02:29.262  3374  3435 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 22:02:29.262  3374  3435 D BluetoothAdapterProperties: Scan Mode:20
09-09 22:02:29.262  3374  7604 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 22:02:29.262  3374  7604 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-09 22:02:29.262  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-09 22:02:29.262  4988  4988 D BluetoothPbap: Proxy object disconnected
,09-09 22:02:29.262  4988  4988 D PbapServerProfile: Bluetooth service disconnected
09-09 22:02:29.262  3374  3432 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-09 22:02:29.262  3374  3432 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
09-09 22:02:29.262  3374  3432 E bt-btif : cmd socket is not created
,09-09 22:02:29.262  3374  3432 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-09 22:02:29.262  3374  3437 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,09-09 22:02:29.272  3374  3374 V BluetoothOppManager: cleanUp...
,09-09 22:02:29.272  3374  3437 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
09-09 22:02:29.272  3374  3437 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 22:02:29.272  3374  3437 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-09 22:02:29.272  3374  3437 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 22:02:29.272  3374  3437 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 22:02:29.272  3374  3437 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-09 22:02:29.272  2629  2629 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 22:02:29.272  4988  4988 D DockEventReceiver: finishStartingService: stopping service,
,09-09 22:02:29.272  4988  4988 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 22:02:29.282  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:29.282  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-09 22:02:29.472  3374  3432 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-09 22:02:29.472  3374  3432 D BtConfig.SecureMode: isSecureModeOn:false
09-09 22:02:29.472  3374  3432 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-09 22:02:29.472  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
09-09 22:02:29.472  3374  3432 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
09-09 22:02:29.472  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-09 22:02:29.472  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-09 22:02:29.472  1017  1524 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:29.472  3374  3432 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-09 22:02:29.472  1017  1524 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-09 22:02:29.472  1017  1524 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:29.472  1017  1524 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:29.472  1017  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:29.472  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,09-09 22:02:29.472  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-09 22:02:29.472  3374  3432 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-09 22:02:29.472  1017  1078 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 22:02:29.472  3374  3374 D HeadsetService: Received stop request...Stopping profile...
,09-09 22:02:29.472  1017  1078 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 22:02:29.472  1017  1078 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:29.472  1017  1078 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:29.482  1017  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:29.482  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,09-09 22:02:29.482  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-09 22:02:29.482  3374  3432 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-09 22:02:29.482  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
,09-09 22:02:29.482  1017  3700 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 22:02:29.482  1017  3700 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 22:02:29.482  1017  3700 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:29.482  1017  3700 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:29.482  1017  3700 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:29.482  4988  4988 D HeadsetProfile: Bluetooth service disconnected
,09-09 22:02:29.492  3374  3374 D A2dpService: Received stop request...Stopping profile...
,09-09 22:02:29.492  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-09 22:02:29.492  3374  7583 D A2dpStateMachine: Exit Disconnected: -1
,09-09 22:02:29.492  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-09 22:02:29.492  1017  1210 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:29.492  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 22:02:29.492  1017  1210 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-09 22:02:29.492  3374  3432 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-09 22:02:29.492  1017  1210 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:29.492  1017  1210 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:29.492  1017  1210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:29.492  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-09 22:02:29.492  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 22:02:29.492  3374  3432 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-09 22:02:29.492  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:29.492  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 22:02:29.492  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:29.492  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:29.492  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:29.502  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
09-09 22:02:29.502  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,09-09 22:02:29.502  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:29.502  3374  3432 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-09 22:02:29.502  4988  4988 D BluetoothA2dp: Proxy object disconnected
,09-09 22:02:29.502  4988  4988 D A2dpProfile: Bluetooth service disconnected
,09-09 22:02:29.502  1017  3700 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 22:02:29.502  1017  3700 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 22:02:29.502  1017  1017 D BluetoothA2dp: Proxy object disconnected
09-09 22:02:29.502  1017  3700 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:29.502  1017  3700 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:29.502  1017  3700 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 22:02:29.502  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-09 22:02:29.502  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-09 22:02:29.502  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 22:02:29.502  3374  3432 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-09 22:02:29.502  1017  1506 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:29.502  1017  1506 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 22:02:29.502  1017  1506 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:29.502  1017  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:29.502  1017  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:29.512  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-09 22:02:29.512  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-09 22:02:29.512  3374  3432 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-09 22:02:29.512  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-09 22:02:29.512  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 22:02:29.512  3374  3432 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,09-09 22:02:29.512  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-09 22:02:29.512  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 22:02:29.512  3374  3432 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-09 22:02:29.512  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
,09-09 22:02:29.512  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-09 22:02:29.512  3374  3432 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-09 22:02:29.512  3374  3432 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-09 22:02:29.512  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true,
09-09 22:02:29.512  3374  3374 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService,
09-09 22:02:29.512  3374  3374 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-09 22:02:29.512  3374  3374 D HidService: Received stop request...Stopping profile...
,09-09 22:02:29.512  3374  3374 D HidService: Stopping Bluetooth HidService,
09-09 22:02:29.512  3374  3374 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 22:02:29.512  3374  3374 W bt-btif : cleanup: HH disabling or disabled already, status = 0
,09-09 22:02:29.512  3374  3374 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 22:02:29.512  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
09-09 22:02:29.512  3374  3374 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 22:02:29.512  3374  3374 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 22:02:29.512  4988  4988 D BluetoothInputDevice: Proxy object disconnected
,09-09 22:02:29.512  4988  4988 D HidProfile: Bluetooth service disconnected
,09-09 22:02:29.512  3374  3374 D HealthService: Received stop request...Stopping profile...
,09-09 22:02:29.512  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
,09-09 22:02:29.522  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-09 22:02:29.522  3374  3374 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 22:02:29.522  3374  3374 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-09 22:02:29.522  3374  3374 D PanService: Received stop request...Stopping profile...
,09-09 22:02:29.522  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
,09-09 22:02:29.522  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-09 22:02:29.522  3374  3374 D BluetoothA2dp: Proxy object disconnected
09-09 22:02:29.522  3374  3374 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,09-09 22:02:29.522  3374  7584 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-09 22:02:29.522  4988  4988 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 22:02:29.522  4988  4988 D PanProfile: Bluetooth service disconnected
09-09 22:02:29.522  3374  3374 I GKI_LINUX: GKI_exit_task 2 done
09-09 22:02:29.522  3374  3374 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-09 22:02:29.522  3374  3374 D BluetoothMapService: Received stop request...Stopping profile...
,09-09 22:02:29.522  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
,09-09 22:02:29.532  3374  3374 D SapService: Received stop request...Stopping profile...
,09-09 22:02:29.532  3374  3374 D SapService: Stopping Bluetooth SapService
09-09 22:02:29.532  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
09-09 22:02:29.532  4988  4988 D BluetoothMap: Proxy object disconnected
09-09 22:02:29.532  4988  4988 D MapProfile: Bluetooth service disconnected
,09-09 22:02:29.532  4988  4988 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-09 22:02:29.532  4988  4988 D SapProfile: Bluetooth service disconnected
,09-09 22:02:29.532  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,09-09 22:02:29.532  3374  3374 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-09 22:02:29.532  3374  3374 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:29.532  3374  3374 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-09 22:02:29.532  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-09 22:02:29.532  3374  3374 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-09 22:02:29.532  3374  3374 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:29.532  3374  3374 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:29.532  3374  3374 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-09 22:02:29.532  3374  3374 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 22:02:29.532  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-09 22:02:29.532  3374  3374 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-09 22:02:29.532  3374  3374 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:29.532  3374  3374 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:29.532  3374  3374 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 22:02:29.532  3374  3374 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-09 22:02:29.532  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,09-09 22:02:29.532  3374  3374 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-09 22:02:29.532  3374  3374 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 22:02:29.532  3374  3374 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService,
09-09 22:02:29.532  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-09 22:02:29.532  3374  3374 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-09 22:02:29.532  3374  3374 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-09 22:02:29.532  3374  3374 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-09 22:02:29.532  3374  3432 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-09 22:02:29.532  3374  3432 D BluetoothAdapterProperties: Setting state to 10
09-09 22:02:29.532  3374  3432 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-09 22:02:29.532  3374  3432 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 22:02:29.532  3374  3432 D BluetoothAdapterService: updateAdapterState state is 10
,09-09 22:02:29.542  3374  3432 D BluetoothAdapterService: Autoconnection is available 
09-09 22:02:29.542  3374  3432 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-09 22:02:29.542  3374  3432 I BluetoothAdapterState: Entering OffState
09-09 22:02:29.542  4988  7591 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 22:02:29.542  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:29.542  1017  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 22:02:29.542  4988  5000 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 22:02:29.542  4988  4998 D Bluetoothsap: onBluetoothStateChange: up=false
,09-09 22:02:29.542  4988  4998 D Bluetoothsap: Unbinding service...
,09-09 22:02:29.542  1478  2128 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 22:02:29.542  1478  2128 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 22:02:29.542  3374  3384 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 22:02:29.542  1451  1466 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 22:02:29.542  1451  1466 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 22:02:29.542  1465  1494 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:29.542  1465  1494 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 22:02:29.542  4988  7591 D BluetoothPbap: onBluetoothStateChange: up=false
,09-09 22:02:29.542  7003  7015 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:29.542  7003  7015 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 22:02:29.542  7003  7015 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-09 22:02:29.542  7003  7015 D BluetoothLeAdvertiser: Exit stop advertising
09-09 22:02:29.542  7003  7015 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-09 22:02:29.542  7003  7015 D BluetoothLeScanner: Exiting stopAllScan
,09-09 22:02:29.542  3374  3480 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:29.542  3374  3480 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 22:02:29.552  1754  2001 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:29.552  1754  2001 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 22:02:29.552  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 22:02:29.552  4988  7591 D BluetoothMap: onBluetoothStateChange: up=false
,09-09 22:02:29.552  2629  4501 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 22:02:29.552  2629  4501 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 22:02:29.552  1180  1642 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:29.552  1180  1642 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 22:02:29.552  4988  5000 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:29.552  4988  5000 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan,
09-09 22:02:29.552  7595  7606 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:29.552  7595  7606 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan,
,09-09 22:02:29.552  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:29.552  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
09-09 22:02:29.552  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-09 22:02:29.562  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 22:02:29.562  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:29.562  1180  1180 D BluetoothTile:  getBluetoothState : 10
,09-09 22:02:29.562  1874  1874 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 22:02:29.572  4988  4988 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:29.572  1017  1499 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 22:02:29.572  1017  4071 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-09 22:02:29.572  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-09 22:02:29.572  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:29.572  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:29.572  4988  4988 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 22:02:29.572  1017  1524 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-09 22:02:29.572  1017  1524 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 22:02:29.572  1017  1524 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:29.572  1017  1524 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:29.572  1017  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 22:02:29.582  2629  2629 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 22:02:29.592  4988  4988 D DockEventReceiver: finishStartingService: stopping service
,09-09 22:02:29.592  4988  4988 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 22:02:29.592  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:29.592  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-09 22:02:29.682  1017  3473 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 22:02:30.042   288   288 E SMD     : DCD OFF
,09-09 22:02:30.042   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 22:02:31.042   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 22:02:31.132  1017  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 22:02:31.132  1017  1320 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4300, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-09 22:02:31.132  1017  1320 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-09 22:02:31.132  1017  1320 D BatteryService: stay LED for charging
09-09 22:02:31.132  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 22:02:31.132  1017  1017 I MotionRecognitionService: Plugged,
,09-09 22:02:31.132  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false,
,09-09 22:02:31.142  1425  1425 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-09 22:02:31.142  1425  1425 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
09-09 22:02:31.142  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-09 22:02:31.142  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 22:02:31.162  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-09 22:02:31.162  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-09 22:02:31.162  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-09 22:02:31.162  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-09 22:02:31.162  1180  1180 D SViewCoverView: level :100 plugged : 2
,09-09 22:02:32.042   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 22:02:32.192  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 22:02:32.192  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:33.042   288   288 E SMD     : DCD OFF
,09-09 22:02:33.042   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 22:02:34.042   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,09-09 22:02:35.192  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 22:02:35.192  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@22d27011 added. We now have 6 listener(s),
09-09 22:02:35.192  7003  7061 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 22:02:35.192  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-09 22:02:35.192  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2fe51576 added. We now have 7 listener(s),
09-09 22:02:35.192  7003  7061 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 22:02:35.192  7003  7061 I System.out: IsBluetoothEnabled,
09-09 22:02:35.192  7003  7061 D BluetoothAdapter: disable()
09-09 22:02:35.202  1017  1477 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-09 22:02:35.202  7003  7061 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-09 22:02:35.202  7003  7061 D BluetoothAdapter: enable(),
,09-09 22:02:35.212  1017  3703 W ActivityManager: Permission Denial: getCurrentUser() from pid=7003, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-09 22:02:35.212  1017  3703 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-09 22:02:35.212  1017  3703 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7003, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-09 22:02:35.212  1017  3703 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-09 22:02:35.212  1017  3703 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-09 22:02:35.212  1017  3703 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-09 22:02:35.212  1017  3703 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-09 22:02:35.212  1017  3703 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-09 22:02:35.212  1017  3703 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 22:02:35.212  1017  3703 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 22:02:35.212  1017  3703 D SettingsProvider: name = bluetooth_on,
,09-09 22:02:35.222  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
09-09 22:02:35.222  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 22:02:35.222  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-09 22:02:35.232  3374  3432 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-09 22:02:35.232  3374  3432 D BluetoothAdapterProperties: Setting state to 11
,09-09 22:02:35.232  3374  3432 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-09 22:02:35.232  3374  3432 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-09 22:02:35.232  3374  3432 D BluetoothAdapterService: updateAdapterState state is 11
,09-09 22:02:35.232  3374  3432 D BluetoothAdapterService: Autoconnection is available 
,09-09 22:02:35.232  3374  3432 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-09 22:02:35.232  3374  3432 D BtConfig.SecureMode: isSecureModeOn:false
,09-09 22:02:35.232  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-09 22:02:35.232  3374  3432 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
09-09 22:02:35.232  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-09 22:02:35.232  3374  3432 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
,09-09 22:02:35.232  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 22:02:35.232  3374  3432 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-09 22:02:35.232  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-09 22:02:35.232  3374  3432 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-09 22:02:35.232  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-09 22:02:35.232  3374  3432 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-09 22:02:35.232  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 22:02:35.232  3374  3432 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-09 22:02:35.232  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-09 22:02:35.232  3374  3432 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-09 22:02:35.232  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 22:02:35.232  3374  3432 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-09 22:02:35.242  1017  1509 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:35.232  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 22:02:35.242  1017  1509 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-09 22:02:35.232  3374  3432 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,09-09 22:02:35.232  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService,
09-09 22:02:35.232  3374  3432 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-09 22:02:35.232  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 22:02:35.232  3374  3432 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
,09-09 22:02:35.232  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-09 22:02:35.232  3374  3432 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-09 22:02:35.232  3374  3432 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-09 22:02:35.232  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-09 22:02:35.232  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-09 22:02:35.232  3374  3432 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-09 22:02:35.242  1017  1509 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:35.242  1017  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:35.242  1017  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:35.242  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-09 22:02:35.242  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 22:02:35.242  3374  3432 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-09 22:02:35.242  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:35.242  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,09-09 22:02:35.252  3374  3374 D HeadsetService: Received start request. Starting profile...
09-09 22:02:35.252  3374  3374 D HeadsetService: start()
09-09 22:02:35.252  3374  3374 D HeadsetStateMachine: make
,09-09 22:02:35.262  1874  1874 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
09-09 22:02:35.262  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:35.262  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-09 22:02:35.262  1180  1180 D BluetoothTile:  getBluetoothState : 11
,09-09 22:02:35.262  4988  4988 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:35.262  3374  3374 E HeadsetStateMachine: # of Max HF connection is 2
,09-09 22:02:35.262  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:35.262  1017  3703 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 22:02:35.262  1017  1477 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 22:02:35.272  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 22:02:35.272  1180  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 22:02:35.272  1180  1731 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-09 22:02:35.272  1017  1506 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:35.272  1017  1506 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 22:02:35.282  1017  1506 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:35.282  1017  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:35.282  1017  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:35.282  1017  1524 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-09 22:02:35.282  1017  1524 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-09 22:02:35.282  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,09-09 22:02:35.282  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 22:02:35.282  3374  3432 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-09 22:02:35.282  1017  1524 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:35.282  1017  4465 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:35.282  1017  1524 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:35.282  1017  4465 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-09 22:02:35.282  1017  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-09 22:02:35.282  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-09 22:02:35.292  1017  4465 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:35.292  1017  4465 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:35.292  1017  4465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:35.292  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-09 22:02:35.292  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 22:02:35.292  3374  3432 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-09 22:02:35.292  2629  2629 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 22:02:35.292  1017  1508 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:35.292  1017  1508 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-09 22:02:35.292  1017  1508 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:35.292  1017  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:35.292  1017  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:35.302  1017  1210 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-09 22:02:35.302  1017  1210 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
09-09 22:02:35.302  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-09 22:02:35.302  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 22:02:35.302  3374  3432 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-09 22:02:35.302  1017  1210 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:35.302  1017  1210 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:35.302  1017  1210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-09 22:02:35.302  1017  1078 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:35.302  1017  1078 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 22:02:35.302  3374  3374 I bluedroid: get_profile_interface handsfree
,09-09 22:02:35.302  1017  1078 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:35.302  1017  1078 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:35.302  1017  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 22:02:35.302  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-09 22:02:35.302  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:35.302  3374  3432 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-09 22:02:35.302  1017  1499 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:35.302  1017  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 22:02:35.312  1017  1499 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:35.312  1017  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:35.312  1017  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:35.312  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-09 22:02:35.312  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 22:02:35.312  3374  3432 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-09 22:02:35.312  4988  4988 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 22:02:35.312  1017  4466 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 22:02:35.312  1017  4466 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 22:02:35.312  1017  4466 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:35.312  1017  4466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:35.312  1017  4466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 22:02:35.322  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-09 22:02:35.322  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 22:02:35.322  3374  3432 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-09 22:02:35.322  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-09 22:02:35.322  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-09 22:02:35.322  3374  3432 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-09 22:02:35.322  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-09 22:02:35.322  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 22:02:35.322  3374  3432 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-09 22:02:35.322  3374  3432 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-09 22:02:35.322  3374  3432 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-09 22:02:35.322  3374  3432 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService,
09-09 22:02:35.322  3374  3432 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-09 22:02:35.322  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:35.322  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-09 22:02:35.322  3374  3374 E DualScoManager: Dual Sco Manager already instantiated
,09-09 22:02:35.322  3374  3374 I DualScoManager: Set HeadsetServiceHelper
09-09 22:02:35.322  3374  3374 D BluetoothAtMessage: createCMTIContentObservers
09-09 22:02:35.322  1017  3700 D SettingsProvider: name = bluetooth_hfp_allowed_bvra,
09-09 22:02:35.322  1017  3700 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:35.322  1017  3700 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
09-09 22:02:35.322  1017  3700 D SettingsProvider: selectionArgs: false
09-09 22:02:35.322  1017  3700 D SettingsProvider: selectionArgs: 1002
,09-09 22:02:35.322  1017  3700 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 22:02:35.322  1017  3700 D SettingsProvider: ret = -1
09-09 22:02:35.322  3374  7640 D HeadsetStateMachine: Enter Disconnected: -2
,09-09 22:02:35.332  3374  3374 D HeadsetService: mStartError = false
09-09 22:02:35.332  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
,09-09 22:02:35.332  3374  3374 D HeadsetStateMachine: Try to query the phonestate on bind
09-09 22:02:35.332  1451  3484 I Telecom : BluetoothPhoneService: queryPhoneState
,09-09 22:02:35.332  3374  7640 D HeadsetStateMachine: Clear mHeadsetBrsf
,09-09 22:02:35.332  3374  7640 D HeadsetStateMachine: map size, before remove : 0
09-09 22:02:35.332  3374  7640 D HeadsetStateMachine: map size, after remove: 0
09-09 22:02:35.332  1451  1451 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-09 22:02:35.332  1451  1451 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-09 22:02:35.332  1451  3484 I Telecom : BluetoothPhoneService: Result of Message : true
,09-09 22:02:35.332  3374  3374 D A2dpService: Received start request. Starting profile...
09-09 22:02:35.332  3374  3374 D A2dpService: start()
09-09 22:02:35.332  3374  3374 I bluedroid: get_profile_interface avrcp
,09-09 22:02:35.332  3374  3374 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 22:02:35.332  3374  3374 D Avrcp   : Initialize Media Controller
09-09 22:02:35.332  3374  3374 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-09 22:02:35.342  3374  3374 E Avrcp   : getActiveSessions
,09-09 22:02:35.342  3374  3374 D Avrcp   : pick active media Controller
09-09 22:02:35.342  3374  3374 D Avrcp   : Get the active Media Controller 
,09-09 22:02:35.342  3374  3374 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-09 22:02:35.342  3374  7641 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-09 22:02:35.342  3374  3374 D A2dpStateMachine: make
,09-09 22:02:35.342  3374  3374 I bluedroid: get_profile_interface a2dp
,09-09 22:02:35.342  3374  7643 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-09 22:02:35.342  3374  3374 E bt-btif : warning : media task started media_task_refcnt 1 
,09-09 22:02:35.352  3374  3374 D A2dpService: mStartError = false
09-09 22:02:35.352  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
,09-09 22:02:35.352  3374  7642 D A2dpStateMachine: Enter Disconnected: -2
,09-09 22:02:35.352  3374  3374 D HidService: Received start request. Starting profile...
09-09 22:02:35.352  3374  3374 D HidService: start()
09-09 22:02:35.352  3374  3374 I bluedroid: get_profile_interface hidhost
09-09 22:02:35.352  3374  3374 D HidService: setHidService(): set to: null
09-09 22:02:35.352  3374  3374 D HidService: mStartError = false
09-09 22:02:35.352  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
,09-09 22:02:35.352  3374  3374 D HealthService: Received start request. Starting profile...
,09-09 22:02:35.352  3374  3374 D HealthService: start()
,09-09 22:02:35.352  3374  3374 I bluedroid: get_profile_interface health
09-09 22:02:35.352  3374  3374 D HealthService: mStartError = false
09-09 22:02:35.352  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
,09-09 22:02:35.352  3374  3374 D HeadsetStateMachine: Proxy object connected
09-09 22:02:35.352  3374  3374 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-09 22:02:35.352  3374  3374 D PanService: Received start request. Starting profile...
09-09 22:02:35.352  3374  3374 D PanService: start()
09-09 22:02:35.352  3374  3374 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 22:02:35.352  3374  3374 I bluedroid: get_profile_interface pan
09-09 22:02:35.352  3374  3374 D PanService: mStartError = false
09-09 22:02:35.352  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
,09-09 22:02:35.352  3374  7640 D HeadsetStateMachine: Disconnected process message: 11
,09-09 22:02:35.362  3374  3374 D BluetoothMapService: Received start request. Starting profile...
09-09 22:02:35.362  3374  3374 D BluetoothMapService: start()
,09-09 22:02:35.362  3374  3374 D BluetoothMapService: mStartError = false
,09-09 22:02:35.362  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
09-09 22:02:35.362  3374  3374 D HeadsetPhoneState: sendDeviceDataStateChanged
,09-09 22:02:35.362  3374  3374 D HeadsetPhoneState: Signal level : previous=0 curr=4
,09-09 22:02:35.362  3374  3374 D SapService: Received start request. Starting profile...
09-09 22:02:35.362  3374  3374 D SapService: start()
09-09 22:02:35.362  3374  3374 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-09 22:02:35.362  3374  3374 I bluedroid: get_profile_interface sap
09-09 22:02:35.362  3374  3374 D SapService: mStartError = false
09-09 22:02:35.362  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
09-09 22:02:35.362  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-09 22:02:35.362  3374  3374 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-09 22:02:35.362  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-09 22:02:35.362  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-09 22:02:35.362  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-09 22:02:35.362  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-09 22:02:35.362  3374  7640 D HeadsetStateMachine: Disconnected process message: 18
09-09 22:02:35.362  3374  7640 D HeadsetStateMachine: Disconnected process message: 10
,09-09 22:02:35.362  3374  7640 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 22:02:35.362  3374  7640 D HeadsetStateMachine: Disconnected process message: 11
,09-09 22:02:35.372  3374  7641 D BluetoothMediaBrowser: no now playing list
,09-09 22:02:35.372  3374  7641 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-09 22:02:35.372  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-09 22:02:35.382  3374  3374 E BluetoothAdapterService(705538748): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-09 22:02:35.382  3374  3432 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-09 22:02:35.382  3374  3432 I bluedroid: enable
,09-09 22:02:35.382  3374  3435 E bt-btif : Calling BTA_HhEnable
,09-09 22:02:35.382  3374  3435 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-09 22:02:35.382  3374  3435 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-09 22:02:35.382  3374  3435 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-09 22:02:35.382  3374  3435 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
09-09 22:02:35.382  3374  3435 E BluetoothServiceJni: populateRssiValuesNative
09-09 22:02:35.382  3374  3435 I bluedroid: getModelRssiValues
09-09 22:02:35.382  3374  3435 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-09 22:02:35.382  3374  3435 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-09 22:02:35.392  3374  3435 D BluetoothAdapterProperties: Name is: Galaxy A3
09-09 22:02:35.392  1017  1017 D SettingsProvider: name = bluetooth_name
,09-09 22:02:35.392  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:35.392  3374  3435 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-09 22:02:35.392  3374  3435 D BluetoothAdapterProperties: Scan Mode:20
09-09 22:02:35.392  3374  3435 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 22:02:35.392  3374  3435 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
,09-09 22:02:35.392  3374  3435 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
09-09 22:02:35.392  3374  3435 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,09-09 22:02:35.392  3374  3435 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-09 22:02:35.392  3374  3435 E bt-btif : JVenable fails
,09-09 22:02:35.392  3374  3435 D bte_conf: Device ID record 1 : primary
09-09 22:02:35.392  3374  3435 D bte_conf:   vendorId            = 0075
09-09 22:02:35.392  3374  3435 D bte_conf:   vendorIdSource      = 0001
09-09 22:02:35.392  3374  3435 D bte_conf:   product             = 0100
09-09 22:02:35.392  3374  3435 D bte_conf:   version             = 0200
09-09 22:02:35.392  3374  3435 D bte_conf:   clientExecutableURL = 
09-09 22:02:35.392  3374  3435 D bte_conf:   serviceDescription  = 
09-09 22:02:35.392  3374  3435 D bte_conf:   documentationURL    = 
09-09 22:02:35.392  3374  3435 D bte_conf: bte_load_did_conf no section named DID2.
09-09 22:02:35.392  3374  3435 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-09 22:02:35.402  3374  3432 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-09 22:02:35.402  3374  3432 D BluetoothAdapterProperties: ScanMode =  20
09-09 22:02:35.402  3374  3432 D BluetoothAdapterProperties: State =  11
,09-09 22:02:35.402  3374  3435 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 22:02:35.402  1017  1030 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-09 22:02:35.402  3374  3432 D BluetoothAdapterProperties: Setting state to 12
,09-09 22:02:35.402  3374  3432 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-09 22:02:35.402  1017  3703 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-09 22:02:35.402  1017  3703 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:35.402  1017  3703 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 22:02:35.402  1017  3703 D SettingsProvider: selectionArgs: false
,09-09 22:02:35.402  1017  3703 D SettingsProvider: selectionArgs: 1002
09-09 22:02:35.402  1017  3703 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-09 22:02:35.402  1017  3703 D SettingsProvider: ret = -1
,09-09 22:02:35.402  3374  3432 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 22:02:35.402  3374  3432 D BluetoothAdapterService: updateAdapterState state is 12
,09-09 22:02:35.402  1017  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 22:02:35.402  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 22:02:35.412  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:35.412  1017  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:35.412  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:35.412  3374  3432 D BluetoothAdapterService: Autoconnection is available 
09-09 22:02:35.412  3374  3432 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-09 22:02:35.412  3374  3432 D BluetoothAdapterService: starting service from this receiver
,09-09 22:02:35.412  4988  4998 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 22:02:35.412  1017  1320 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:35.412  3374  3435 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 22:02:35.412  1017  1320 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-09 22:02:35.412  3374  3435 D BluetoothAdapterProperties: Scan Mode:21
09-09 22:02:35.412  3374  3435 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 22:02:35.412  1017  1320 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:35.412  1017  1320 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:35.412  1017  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:35.422  3374  3374 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-09 22:02:35.422  3374  3374 I BluetoothPbapService: Handler(): got msg=1
,09-09 22:02:35.422  3374  3432 I BluetoothAdapterState: Entering On State from state = 11,
,09-09 22:02:35.432  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:35.432  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:35.432  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:35.432  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 22:02:35.432  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:35.432  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:35.432  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:35.432  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:35.432  7003  7003 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 22:02:35.562  1017  1046 I art     : Explicit concurrent mark sweep GC freed 57636(3MB) AllocSpace objects, 6(97KB) LOS objects, 33% free, 23MB/34MB, paused 2.481ms total 147.398ms
,09-09 22:02:35.562  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-09 22:02:35.562  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-09 22:02:35.562  1017  1030 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-09 22:02:35.572  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:35.572  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:35.572  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:35.572  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:35.572  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:35.572  3374  7649 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-09 22:02:35.572  1478  2128 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:35.572  1017  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 22:02:35.572  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 22:02:35.572  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:35.572  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:35.572  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:35.582  1478  2128 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 22:02:35.582  3374  7649 D BluetoothSocket: bindListen(): myUserId = 0
,09-09 22:02:35.582  4988  7591 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 22:02:35.582  3374  7649 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 22:02:35.582  3374  7649 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,09-09 22:02:35.582  3374  7649 D BluetoothSocket: bindListen(), new LocalSocket 
,09-09 22:02:35.582  3374  7649 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 22:02:35.582  3374  7649 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@203910cc
09-09 22:02:35.582  3374  7649 D BluetoothSocket: channel: 19
09-09 22:02:35.582  3374  7649 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-09 22:02:35.582  4988  4988 D BluetoothInputDevice: Proxy object connected
,09-09 22:02:35.592  4988  4988 D HidProfile: Bluetooth service connected
,09-09 22:02:35.592  4988  7591 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:35.592  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 22:02:35.592  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 22:02:35.592  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:35.592  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:35.592  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:35.592  4988  7650 D Bluetoothsap: onBluetoothStateChange: up=true
09-09 22:02:35.592  4988  7650 D Bluetoothsap: Binding service...
,09-09 22:02:35.592  4988  4988 D BluetoothA2dp: Proxy object connected
,09-09 22:02:35.592  4988  4988 D A2dpProfile: Bluetooth service connected
09-09 22:02:35.592  4988  7650 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-09 22:02:35.592  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-09 22:02:35.592  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 22:02:35.592  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:35.592  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:35.592  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:35.602  4988  7650 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-09 22:02:35.602  1478  2129 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 22:02:35.602  1478  2129 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 22:02:35.602  1017  1046 D BluetoothPan: Binding service...
,09-09 22:02:35.602  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-09 22:02:35.602  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 22:02:35.602  3374  7648 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 22:02:35.602  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 22:02:35.602  3374  7648 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:35.602  4988  4988 D Bluetoothsap: BluetoothSAP Proxy object connected
09-09 22:02:35.602  4988  4988 D SapProfile: Bluetooth service connected
09-09 22:02:35.602  4988  4988 D Bluetoothsap: getConnectedDevices()
,09-09 22:02:35.602  1017  1046 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-09 22:02:35.602  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 22:02:35.602  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:35.602  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:35.602  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:35.612  3374  3374 D BluetoothA2dp: Proxy object connected
09-09 22:02:35.612  3374  3374 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-09 22:02:35.612  1451  3484 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:35.612  1451  3484 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:35.612  1465  1484 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:35.612  1465  1484 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:35.612  4988  7591 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 22:02:35.612  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,09-09 22:02:35.612  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 22:02:35.612  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:35.612  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:35.612  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:35.612  4988  4988 D BluetoothPbap: Proxy object connected
,09-09 22:02:35.612  4988  4988 D PbapServerProfile: Bluetooth service connected
09-09 22:02:35.612  7003  7017 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:35.612  7003  7017 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 22:02:35.622  3374  7651 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:35.622  3374  7651 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:35.622  4988  7650 D BluetoothPan: Binding service...
,09-09 22:02:35.622  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-09 22:02:35.622  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 22:02:35.622  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:35.622  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:35.622  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:35.622  4988  4988 D BluetoothPan: BluetoothPAN Proxy object connected,
09-09 22:02:35.622  4988  4988 D PanProfile: Bluetooth service connected
,09-09 22:02:35.622  1754  1763 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:35.622  1754  1763 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:35.622  4988  4998 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:35.622  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 22:02:35.622  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 22:02:35.622  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:35.622  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:35.622  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-09 22:02:35.632  4988  4998 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 22:02:35.632  4988  4988 D HeadsetProfile: Bluetooth service connected
,09-09 22:02:35.632  1451  7632 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:35.632  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 22:02:35.632  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 22:02:35.632  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:35.632  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:35.632  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-09 22:02:35.632  1451  7632 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 22:02:35.632  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 22:02:35.632  1017  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:35.632  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 22:02:35.632  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 22:02:35.632  1017  1017 D BluetoothA2dp: Proxy object connected
,09-09 22:02:35.632  1451  1466 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:35.632  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 22:02:35.632  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 22:02:35.642  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:35.642  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:35.642  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:35.642  1451  1466 E BluetoothHeadset: BluetoothHeadset service is binded
09-09 22:02:35.642  4988  4998 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 22:02:35.642  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-09 22:02:35.642  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 22:02:35.642  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:35.642  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:35.642  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:35.642  1017  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:35.642  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 22:02:35.642  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-09 22:02:35.642  1017  1046 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 22:02:35.642  2629  4501 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 22:02:35.642  2629  4501 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 22:02:35.642  4988  4988 D BluetoothMap: Proxy object connected
,09-09 22:02:35.642  4988  4988 D MapProfile: Bluetooth service connected
09-09 22:02:35.642  4988  4988 D BluetoothMap: getConnectedDevices()
09-09 22:02:35.642  1180  1190 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:35.642  1180  1190 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:35.642  4988  7650 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 22:02:35.642  4988  7650 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 22:02:35.642  7595  7607 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:35.642  7595  7607 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:35.652  1451  7632 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:35.652  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 22:02:35.652  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 22:02:35.652  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:35.652  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:35.652  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-09 22:02:35.652  1451  7632 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 22:02:35.652  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-09 22:02:35.652  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-09 22:02:35.652  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:35.652  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
09-09 22:02:35.652  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-09 22:02:35.652  1451  1451 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2f3d9120, true
,09-09 22:02:35.652  1451  1451 D BluetoothHeadset: registerMessageListener
,09-09 22:02:35.662  1180  1180 D BluetoothTile:  onBluetoothStateChange:,
,09-09 22:02:35.662  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 22:02:35.662  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:35.662  1180  1180 D BluetoothTile:  getBluetoothState : 12
,09-09 22:02:35.662  1180  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 22:02:35.662  1874  1874 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
09-09 22:02:35.672  1180  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 22:02:35.672  4988  4988 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:35.672  1017  4071 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 22:02:35.672  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:35.672  3374  3698 D HeadsetService: registerMessageListener
,09-09 22:02:35.672  1017  1030 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-09 22:02:35.672  1180  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 22:02:35.672  3374  3698 D HeadsetService: registerMessageListener
09-09 22:02:35.672  3374  7640 D HeadsetStateMachine: Disconnected process message: 70
09-09 22:02:35.672  3374  7640 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@25327f15
,09-09 22:02:35.672  1451  1451 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-09 22:02:35.672  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-09 22:02:35.672  1451  1451 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-09 22:02:35.682  1451  1451 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,09-09 22:02:35.682  1451  1451 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-09 22:02:35.682  1451  1451 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-09 22:02:35.682  3374  7652 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-09 22:02:35.682  4988  4988 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-09 22:02:35.682  4988  4988 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-09 22:02:35.682  4988  4988 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-09 22:02:35.682  4988  4988 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-09 22:02:35.682  3374  7640 D HeadsetStateMachine: Disconnected process message: 9
,09-09 22:02:35.682  3374  7640 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-09 22:02:35.692   283   703 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-09 22:02:35.692   283   703 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-09 22:02:35.692   283   703 V voice   : voice_set_parameters: exit with code(-2)
09-09 22:02:35.692   283   703 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-09 22:02:35.692   283   703 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-09 22:02:35.692   283   703 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-09 22:02:35.692   283   703 V audio_hw_primary: adev_set_parameters: exit
,09-09 22:02:35.692  3374  7640 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-09 22:02:35.692  3374  7652 D BluetoothSocket: bindListen(): myUserId = 0
,09-09 22:02:35.692  3374  7652 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 22:02:35.692  3374  7652 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
,09-09 22:02:35.692  3374  7652 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 22:02:35.692  3374  7652 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 22:02:35.692  3374  7652 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1876b22a
,09-09 22:02:35.692  3374  7652 D BluetoothSocket: channel: 5
09-09 22:02:35.692  4988  4988 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 22:02:35.692  1017  3703 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-09 22:02:35.692  1017  3703 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 22:02:35.692  1017  3703 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:35.692  1017  3703 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:35.692  1017  3703 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 22:02:35.702  2629  2629 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 22:02:35.712  4988  4988 D DockEventReceiver: finishStartingService: stopping service
,09-09 22:02:35.712  4988  4988 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 22:02:35.712  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:35.712  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-09 22:02:35.722  3374  3374 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0daabc
,09-09 22:02:35.722  3374  3374 D BtConfig.SecureMode: isSecureModeOn:false
,09-09 22:02:35.722  1017  1210 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:35.722  1017  1210 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-09 22:02:35.722  1017  1210 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:35.722  1017  1210 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:35.722  1017  1210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:35.732  1017  1499 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-09 22:02:35.742  3374  7657 D BluetoothSocket: bindListen(): myUserId = 0
09-09 22:02:35.742  3374  7657 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 22:02:35.742  3374  7657 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
,09-09 22:02:35.742  3374  7657 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 22:02:35.742  3374  7657 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,09-09 22:02:35.742  3374  7657 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11a5c6f6
09-09 22:02:35.742  3374  7657 D BluetoothSocket: channel: 12
09-09 22:02:35.742  3374  7657 I BtOppRfcommListener: Accept thread started.
,09-09 22:02:36.042   288   288 E SMD     : DCD OFF
,09-09 22:02:36.242  7003  7061 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-09 22:02:36.242  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:36.242  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:36.242  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 22:02:36.242  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:36.242  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:36.242  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:36.242  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:36.242  7003  7061 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 22:02:36.242  1017  4071 D WifiService: setWifiEnabled: false pid=7003, uid=10170
09-09 22:02:36.242  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:36.242  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@584777 added. We now have 8 listener(s)
09-09 22:02:36.242  7003  7061 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 22:02:36.242  1017  4071 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-09 22:02:36.242  1017  4071 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 22:02:36.242  1017  4071 D SecContentProvider2: mCursor = null,
09-09 22:02:36.242  1017  4071 D SettingsProvider: name = wifi_on
,09-09 22:02:36.252  7003  7061 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:36.252  1017  4465 D SecContentProvider: uri = 18 selection = isWifiEnabled,
09-09 22:02:36.252  1017  4465 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed,
09-09 22:02:36.252  1017  4465 D SecContentProvider2: mCursor = null
,09-09 22:02:36.252  1017  4465 D WifiService: setWifiEnabled: true pid=7003, uid=10170
,09-09 22:02:36.252  1017  4465 W ActivityManager: Permission Denial: getCurrentUser() from pid=7003, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-09 22:02:36.252  1017  4465 W WifiService: Failed getting userId using ActivityManagerNative
09-09 22:02:36.252  1017  4465 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7003, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-09 22:02:36.252  1017  4465 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-09 22:02:36.252  1017  4465 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-09 22:02:36.252  1017  4465 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-09 22:02:36.252  1017  4465 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-09 22:02:36.252  1017  4465 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-09 22:02:36.262  1017  4465 D SettingsProvider: name = wifi_on
,09-09 22:02:36.262  1017  1129 E WifiHW  : ##################### set firmware type 0 #####################
,09-09 22:02:36.262  1017  1096 V AlarmManager: waitForAlarm result :4
,09-09 22:02:36.282   278   987 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 22:02:36.282   278   987 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-09 22:02:36.302  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:36.302  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 22:02:36.302  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-09 22:02:36.592  1017  1044 D Tethering: interfaceAdded wlan0
,09-09 22:02:36.602  1017  1132 E Tethering: No numeric data
,09-09 22:02:36.602  1017  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-09 22:02:36.602  1017  1132 D Tethering: clearTetheredNotification()
,09-09 22:02:36.602  1017  1126 V NetworkStats: performPollLocked(flags=0x1)
,09-09 22:02:36.602  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:36.602  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-09 22:02:36.612  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 22:02:36.612  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
09-09 22:02:36.612  1180  1180 D HotspotTile: updateTetherState():false, false
,09-09 22:02:36.612  1017  1126 V NetworkStats: performPollLocked() took 9ms
09-09 22:02:36.612  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:36.612  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:36.612  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:36.612  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 22:02:36.622  1017  1132 D Tethering: InitialState.processMessage what=4
09-09 22:02:36.622  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:36.622  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:36.622  1017  1132 E Tethering: No numeric data
,09-09 22:02:36.622  1017  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 22:02:36.622  1017  1132 D Tethering: clearTetheredNotification()
09-09 22:02:36.622  1017  1044 D Tethering: interfaceAdded p2p0,
09-09 22:02:36.622  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
09-09 22:02:36.632  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 22:02:36.632  1180  1180 D HotspotTile: updateTetherState():false, false
,09-09 22:02:36.632  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:36.632  1017  1126 V NetworkStats: performPollLocked(flags=0x1)
,09-09 22:02:36.632  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 22:02:36.632  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 22:02:36.632  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
09-09 22:02:36.632  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 22:02:36.632  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 22:02:36.632   278   991 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-09 22:02:36.642   278   991 D SoftapController: Softap fwReload - Ok
,09-09 22:02:36.642  1017  1126 V NetworkStats: performPollLocked() took 8ms
09-09 22:02:36.642  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:36.642   278   991 D CommandListener: Setting iface cfg
09-09 22:02:36.642   278   991 D CommandListener: Trying to bring down wlan0
,09-09 22:02:36.642  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit,
09-09 22:02:36.642  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:36.642   278   991 D CommandListener: Clearing all IP addresses on wlan0
,09-09 22:02:36.652  1017  1129 E WifiHW  : supplicant_name : p2p_supplicant
,09-09 22:02:36.652  1017  1129 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-09 22:02:36.672  4988  4988 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 22:02:36.672  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 22:02:36.672  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 22:02:36.672  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:36.672  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 22:02:36.682  1180  1731 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 22:02:36.672  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:36.682  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:36.672  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:36.672  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:36.672  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:36.672  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:36.672  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-09 22:02:36.682  1017  1078 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 22:02:36.682  1017  1078 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 22:02:36.682  1017  1078 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:36.682  1017  1078 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:36.682  1017  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 22:02:36.682  1180  1180 D HotspotTile: onReceive : 2, 0
,09-09 22:02:36.682  7201  7201 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 22:02:36.682  7201  7201 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 22:02:36.682  7201  7201 D SecurityLogAgent: StateMachine : Current State = 1
09-09 22:02:36.682  7201  7201 D SecurityLogAgent: StateMachine : Changed Current State = 1
09-09 22:02:36.692  1632  1632 I Hs20UtilService: Starting #19
,09-09 22:02:36.692  1632  1662 I Hs20UtilService: Message received 5011
,09-09 22:02:36.712  7672  7672 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,09-09 22:02:36.712  7672  7672 I wpa_supplicant: Successfully initialized wpa_supplicant
09-09 22:02:36.712  7672  7672 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-09 22:02:36.722  7672  7672 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
09-09 22:02:36.722   358   358 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7672
09-09 22:02:36.722   358   358 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,09-09 22:02:36.722  7672  7672 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-09 22:02:36.722  7672  7672 I wpa_supplicant: ssSupport state is = 1
,09-09 22:02:36.722  7672  7672 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-09 22:02:36.722  7672  7672 I SecureStorage: [INFO]: SPID(0x00000000)Processing data,
09-09 22:02:36.722   358   358 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7672
09-09 22:02:36.722   358   358 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-09 22:02:36.872   358   358 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,09-09 22:02:36.872  7672  7672 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,09-09 22:02:36.922  7672  7672 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-09 22:02:36.922  7672  7672 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-09 22:02:36.932  7672  7672 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-09 22:02:36.932   358   358 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7672
09-09 22:02:36.932   358   358 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
,09-09 22:02:36.932  7672  7672 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-09 22:02:36.932  7672  7672 I wpa_supplicant: ssSupport state is = 1
09-09 22:02:36.932  7672  7672 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 22:02:36.932  7672  7672 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-09 22:02:36.932  7672  7672 E wpa_supplicant: SIM READ ERROR
09-09 22:02:36.932  7672  7672 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 22:02:36.932  7672  7672 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 22:02:36.932  7672  7672 E wpa_supplicant: SIM READ ERROR,
09-09 22:02:36.932  7672  7672 I wpa_supplicant: Blacklist: Clear (all) 
09-09 22:02:36.932  7672  7672 I wpa_supplicant: wpa_default_ap_write_once
09-09 22:02:36.932  7672  7672 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-09 22:02:36.932  7672  7672 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 22:02:36.932  7672  7672 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
,09-09 22:02:36.932  7672  7672 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 22:02:36.932  7672  7672 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-09 22:02:36.932  7672  7672 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-09 22:02:36.942  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:36.942  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:36.942  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 22:02:37.042  7672  7672 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-09 22:02:37.292  7672  7672 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-09 22:02:37.292  7672  7672 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-09 22:02:37.302  7672  7672 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,09-09 22:02:37.302   358   358 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7672
09-09 22:02:37.302   358   358 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-09 22:02:37.302  7672  7672 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
09-09 22:02:37.302  7672  7672 I wpa_supplicant: ssSupport state is = 1
09-09 22:02:37.302  7672  7672 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-09 22:02:37.302  7672  7672 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-09 22:02:37.322  7672  7672 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-09 22:02:37.322   358   358 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7672
09-09 22:02:37.322   358   358 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-09 22:02:37.322  7672  7672 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-09 22:02:37.322  7672  7672 I wpa_supplicant: ssSupport state is = 1,
09-09 22:02:37.322  7672  7672 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 22:02:37.322  7672  7672 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-09 22:02:37.322  7672  7672 E wpa_supplicant: SIM READ ERROR
09-09 22:02:37.322  7672  7672 I wpa_supplicant: wpa_default_ap_write_once
09-09 22:02:37.322  7672  7672 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-09 22:02:37.322  7672  7672 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-09 22:02:37.332  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 22:02:37.332  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
,09-09 22:02:37.332  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-09 22:02:37.332  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false,
09-09 22:02:37.332  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 22:02:37.332  1017  1044 D Tethering: interfaceStatusChanged p2p0, false,
,09-09 22:02:37.382  7672  7672 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-09 22:02:37.382  7672  7672 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-09 22:02:37.442  7672  7672 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-09 22:02:37.442  7672  7672 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,09-09 22:02:37.442  7672  7672 I wpa_supplicant: Skip scan - bUseNetwork false
,09-09 22:02:37.452  1017  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
09-09 22:02:37.452  1017  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-09 22:02:37.452  7672  7672 I wpa_supplicant: HOTSPOT20_ENABLE called,
09-09 22:02:37.452  7672  7672 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-09 22:02:37.462  7672  7672 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 22:02:37.462  7672  7672 E wpa_supplicant: SIM READ ERROR
09-09 22:02:37.462  7672  7672 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 22:02:37.482  7672  7672 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-09 22:02:37.492  7672  7672 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-09 22:02:37.492  1017  1129 D WifiConfigStore: Loading config and enabling all networks ,
,09-09 22:02:37.502  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 22:02:37.502  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:37.502  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:37.502  1180  1731 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 22:02:37.502  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
09-09 22:02:37.502  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:37.502  1180  1180 D HotspotTile: onReceive : 3, 0
09-09 22:02:37.502  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:37.502  4988  4988 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:37.502  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:37.502  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:37.502  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:37.502  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-09 22:02:37.512  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:37.512  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:37.512  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:37.512  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:37.512  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:37.512  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:37.512  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:37.512  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:37.512  7003  7003 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 22:02:37.512  1017  4465 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 22:02:37.512  1017  4465 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 22:02:37.512  1017  4465 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:37.512  1017  4465 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:37.512  1017  4465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 22:02:37.512  1632  1632 I Hs20UtilService: Starting #20
09-09 22:02:37.512  1632  1662 I Hs20UtilService: Message received 5011
,09-09 22:02:37.522  7201  7201 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 22:02:37.522  7201  7201 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 22:02:37.522  7201  7201 D SecurityLogAgent: StateMachine : Current State = 1
09-09 22:02:37.522  7201  7201 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 22:02:37.522  1017  1129 E WifiConfigStore: Not a HS20
,09-09 22:02:37.522  1017  1129 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-09 22:02:37.522  1017  1129 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-09 22:02:37.522  7672  7672 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-09 22:02:37.522  7672  7672 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-09 22:02:37.522  7672  7672 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 22:02:37.522  7672  7672 I wpa_supplicant: P2P: Current p2p state = IDLE
09-09 22:02:37.522  7672  7672 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-09 22:02:37.522  7672  7672 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-09 22:02:37.522  7672  7672 I wpa_supplicant: First Scan Start
09-09 22:02:37.522  7672  7672 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-09 22:02:37.532  7178  7178 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 22:02:37.532  1017  1129 D WifiNative-wlan0: Setting external_sim to 1
,09-09 22:02:37.532  1017  1129 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 22:02:37.532  1017  1129 I WifiNative-HAL: startHal
09-09 22:02:37.532  1017  1129 E wifi    : getStaticLongField sWifiHalHandle 0x9ee0188c
09-09 22:02:37.532  1017  1129 I WifiNative-HAL: Could not start hal
,09-09 22:02:37.532  1017  1129 E WifiNative-wlan0: do suspend true
,09-09 22:02:37.532  1017  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-09 22:02:37.532  1017  1128 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-09 22:02:37.542  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
,09-09 22:02:37.542  1017  1151 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 22:02:37.542  1017  1151 I WifiNative-HAL: startHal
09-09 22:02:37.542  1017  1151 E wifi    : getStaticLongField sWifiHalHandle 0x9ddc19bc
09-09 22:02:37.542  1017  1151 I WifiNative-HAL: Could not start hal
09-09 22:02:37.542  1017  1151 E WifiScanningService: could not start HAL
,09-09 22:02:37.542  1017  1017 D RttService: SCAN_AVAILABLE : 3
09-09 22:02:37.542  1017  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-09 22:02:37.542  1017  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 22:02:37.542  1017  1129 E WifiNative-wlan0: invaild command id : 215
,09-09 22:02:37.542  1017  1152 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-09 22:02:37.542  1017  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-09 22:02:37.542  1017  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 22:02:37.542  1017  1129 E WifiNative-wlan0: invaild command id : 215
,09-09 22:02:37.542   278   991 D CommandListener: Setting iface cfg
09-09 22:02:37.542   278   991 D CommandListener: Trying to bring up p2p0
,09-09 22:02:37.542  7672  7672 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
09-09 22:02:37.542  1017  1128 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 22:02:37.542  1017  1128 D WifiP2pService: P2pEnablingState
09-09 22:02:37.542  1017  1128 D WifiP2pService: P2pEnablingState{ what=147457 },
09-09 22:02:37.542  7672  7672 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-09 22:02:37.542  1017  1128 D WifiP2pService: P2p socket connection successful
,09-09 22:02:37.542  1017  1128 D WifiP2pService: P2pEnabledState
,09-09 22:02:37.542  7672  7672 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-09 22:02:37.542  1017  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-09 22:02:37.542  1017  1131 E ConnectivityService: updateNetworkInfo()
09-09 22:02:37.542  1017  1129 E WifiStateMachine: Failed to set frequency band 0
,09-09 22:02:37.542  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 22:02:37.542  1017  1129 D SecContentProvider2: mCursor = null
09-09 22:02:37.542  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-09 22:02:37.552  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-09 22:02:37.552  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-09 22:02:37.552  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 22:02:37.552  1017  1047 D WifiDisplayController: disconnect
09-09 22:02:37.552  1017  1129 D SecContentProvider2: mCursor = null
09-09 22:02:37.552  1017  1047 D WifiDisplayController: updateConnection
09-09 22:02:37.552  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-09 22:02:37.552  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 22:02:37.552  1017  1128 D WifiNative-p2p0: p2pGetDeviceAddress
,09-09 22:02:37.552  1017  1128 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,09-09 22:02:37.552  1017  1128 D WifiP2pService: DeviceAddress: 0a:75:42
,09-09 22:02:37.552  4988  4988 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 22:02:37.562  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 22:02:37.552  4988  4988 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 22:02:37.562  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
,09-09 22:02:37.562  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 22:02:37.562  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
09-09 22:02:37.562  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-09 22:02:37.562  1017  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-09 22:02:37.562  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
09-09 22:02:37.562  1017  1047 D WifiDisplayController:  secondary type: null
09-09 22:02:37.562  1017  1047 D WifiDisplayController:  wps: 0
09-09 22:02:37.562  1017  1047 D WifiDisplayController:  grpcapab: 0
09-09 22:02:37.562  1017  1047 D WifiDisplayController:  devcapab: 0
09-09 22:02:37.562  1017  1047 D WifiDisplayController:  status: 3
09-09 22:02:37.562  1017  1047 D WifiDisplayController:  wfdInfo: null
09-09 22:02:37.562  1017  1047 D WifiDisplayController:  groupownerAddress: null
09-09 22:02:37.562  1017  1047 D WifiDisplayController:  GOdeviceName: null
09-09 22:02:37.562  1017  1047 D WifiDisplayController:  interfaceAddress: 
09-09 22:02:37.562  1017  1047 D WifiDisplayController:  SConnectInfo : null
,09-09 22:02:37.562  1180  1180 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-09 22:02:37.562  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-09 22:02:37.562  1017  1509 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 22:02:37.562  1180  1180 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 22:02:37.562  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 22:02:37.562  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 22:02:37.562  4988  4988 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 22:02:37.562  4988  5054 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 22:02:37.562  7512  7512 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 22:02:37.562  7512  7512 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-09 22:02:37.562  7512  7512 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 22:02:37.572  7163  7163 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 22:02:37.582  1017  1128 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-09 22:02:37.582  1017  1128 D WifiP2pService: InactiveState
,09-09 22:02:37.582  1017  1128 D WifiP2pService: InactiveState{ what=143376 }
09-09 22:02:37.582  1017  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 22:02:37.582  7672  7672 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-09 22:02:37.582  1017  1128 D WifiP2pService: InactiveState{ what=143376 }
,09-09 22:02:37.582  1017  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 22:02:37.612  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-09 22:02:37.612  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 22:02:37.612  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-09 22:02:38.282  7003  7061 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:38.282  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:38.282  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:38.282  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:38.282  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:38.282  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:38.282  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:38.282  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:38.282  7003  7061 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 22:02:38.282  7003  7061 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-09 22:02:38.282  7003  7061 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-09 22:02:38.282  7003  7061 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1045394a Bundle[{}]
09-09 22:02:38.292  7003  7061 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 22:02:38.292  7003  7061 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-09 22:02:38.292  7003  7061 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-09 22:02:38.292  7003  7061 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-09 22:02:38.292  7003  7061 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-09 22:02:38.292  7003  7061 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 22:02:38.302  7003  7061 I System.out: Running OutgoingSocketThread
,09-09 22:02:38.302  7003  7681 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1414)
,09-09 22:02:38.302  7003  7681 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 46745
,09-09 22:02:38.302  7003  7681 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 22:02:38.552  1017  3453 D SSRM:n  : SIOP:: AP = 330
,09-09 22:02:38.652  7672  7672 I wpa_supplicant: nl80211: Received scan results (27 BSSes),
09-09 22:02:38.652  7672  7672 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-09 22:02:38.652  7672  7672 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,09-09 22:02:38.652  7672  7672 I wpa_supplicant: Trying to associate with  'G700'
09-09 22:02:38.652  7672  7672 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,09-09 22:02:38.652  7672  7672 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-09 22:02:38.652  1017  7678 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-09 22:02:38.672  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-09 22:02:38.672  1017  1129 D SecContentProvider2: mCursor = null,
,09-09 22:02:38.802  7672  7672 E wpa_supplicant: Cmd 35605 not handled
09-09 22:02:38.802  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:38.802  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:38.802  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
09-09 22:02:38.802  7672  7672 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-09 22:02:38.802  7672  7672 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,09-09 22:02:38.802  7672  7672 I wpa_supplicant: Associated with F4.99.3E
09-09 22:02:38.802  7672  7672 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 22:02:38.802  7672  7672 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-09 22:02:38.802  7672  7672 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
09-09 22:02:38.802  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:38.802  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:38.802  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 22:02:38.802  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
,09-09 22:02:38.802  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-09 22:02:38.802  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,09-09 22:02:38.802  1017  1132 E Tethering: No numeric data,
,09-09 22:02:38.802  1017  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 22:02:38.802  1017  1126 V NetworkStats: performPollLocked(flags=0x1)
09-09 22:02:38.802  1017  1132 D Tethering: clearTetheredNotification()
09-09 22:02:38.802  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 22:02:38.802  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:38.802  1180  1180 D HotspotTile: updateTetherState():false, false
09-09 22:02:38.812  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 22:02:38.812  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 22:02:38.812  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 22:02:38.812  1017  1129 D SecContentProvider2: mCursor = null
09-09 22:02:38.812  1017  1126 V NetworkStats: performPollLocked() took 6ms
09-09 22:02:38.812  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:38.812  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:38.812  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:38.812  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 22:02:38.812  1017  1129 D SecContentProvider2: mCursor = null
,09-09 22:02:38.842  7672  7672 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 22:02:38.842  7672  7672 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-09 22:02:38.842  7672  7672 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-09 22:02:38.842  7672  7672 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-09 22:02:38.842  7672  7672 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 22:02:38.842  7672  7672 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,09-09 22:02:38.842  7672  7672 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-09 22:02:38.842  7672  7672 I wpa_supplicant: Blacklist: Clear (temp) 
09-09 22:02:38.842  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-09 22:02:38.842  7672  7672 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-09 22:02:38.842  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
09-09 22:02:38.842  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,09-09 22:02:38.842  1017  1129 D WifiNative-wlan0: callSECApiVoid - ID [50],
,09-09 22:02:38.842  1017  1129 E WifiConfigStore: setLastSelectedConfiguration -1
,09-09 22:02:38.852  1017  1129 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-09 22:02:38.852  1017  1131 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-09 22:02:38.852  1017  1131 E ConnectivityService: updateNetworkInfo()
09-09 22:02:38.852  1017  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-09 22:02:38.852  1017  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 22:02:38.862  1017  1508 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 22:02:38.862  1017  1508 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 22:02:38.862  1017  1508 W ActivityManager: userId = 0, bbcId = -10000,
09-09 22:02:38.862  1017  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-09 22:02:38.862  1017  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 22:02:38.862  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 22:02:38.862  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 22:02:38.862  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 22:02:38.862  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:38.862  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:38.862  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:38.862  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:38.862  1632  1632 I Hs20UtilService: Starting #21
09-09 22:02:38.872  4988  4988 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 22:02:38.872  4988  4988 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 22:02:38.872  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 22:02:38.872  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 22:02:38.872  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 22:02:38.872  4988  4988 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 22:02:38.872  1632  1662 I Hs20UtilService: Message received 5007
09-09 22:02:38.872  4988  5054 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 22:02:38.872  1017  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 22:02:38.892   278   991 D CommandListener: Setting iface cfg
09-09 22:02:38.892  1017  1129 E WifiStateMachine: Start Dhcp Watchdog 3,
09-09 22:02:38.892  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-09 22:02:38.892  1017  1129 D SecContentProvider2: mCursor = null
,09-09 22:02:38.912  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-09 22:02:38.912  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:38.912  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 22:02:38.912  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-09 22:02:38.912  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:38.912  1017  1128 D WifiP2pService: InactiveState{ what=143375 }
09-09 22:02:38.912  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:38.912  1017  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 22:02:38.912  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:38.912  1017  1129 E WifiNative-wlan0: do suspend false
09-09 22:02:38.912  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 22:02:38.912  1017  1129 D SecContentProvider2: mCursor = null,
,09-09 22:02:39.042   288   288 E SMD     : DCD OFF,
,09-09 22:02:39.122  7684  7684 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-09 22:02:39.132  7684  7684 I dhcpcd  : version 5.5.6 starting
,09-09 22:02:39.132  7684  7684 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-09 22:02:39.182  7684  7684 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-09 22:02:39.182  7684  7684 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-09 22:02:39.182  7684  7684 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-09 22:02:39.182  7684  7684 I dhcpcd  : bssid match
09-09 22:02:39.182  7684  7684 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,09-09 22:02:39.252  7684  7684 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,09-09 22:02:39.282  7684  7684 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,09-09 22:02:39.302  7003  7061 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1415)
09-09 22:02:39.302  7003  7061 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1415)
,09-09 22:02:39.302  7003  7061 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1420)
,09-09 22:02:39.302  7003  7061 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-09 22:02:39.302  7003  7061 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1421)
,09-09 22:02:39.312  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
09-09 22:02:39.312  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@866dfe4 added. We now have 2 listener(s)
,09-09 22:02:39.312  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-09 22:02:39.312  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 22:02:39.312  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 22:02:39.312  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:39.312  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a5cfc4d added. We now have 9 listener(s)
09-09 22:02:39.312  7003  7061 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 22:02:39.312  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 22:02:39.322  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-09 22:02:39.322  7003  7061 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 22:02:39.322  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:39.322  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:39.322  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:39.322  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:39.322  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:39.322  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:39.322  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 22:02:39.332  7003  7061 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 22:02:39.332  7003  7061 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 22:02:39.332  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 22:02:39.332  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@367fe413 added. We now have 3 listener(s)
,09-09 22:02:39.332  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:39.332  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-09 22:02:39.332  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 22:02:39.332  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 22:02:39.332  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:39.332  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a41650 added. We now have 10 listener(s)
,09-09 22:02:39.332  7003  7061 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 22:02:39.332  7003  7061 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:39.332  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:39.332  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:39.332  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:39.332  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:39.332  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 22:02:39.332  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 22:02:39.332  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@866dfe4 removed from the list
09-09 22:02:39.332  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 22:02:39.332  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a5cfc4d removed from the list
09-09 22:02:39.332  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 22:02:39.332  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:39.332  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:39.332  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:39.332  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:39.332  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 22:02:39.332  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:39.332  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:39.332  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a5cfc4d not in the list
09-09 22:02:39.332  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:39.332  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-09 22:02:39.332  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:39.332  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 22:02:39.332  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:39.332  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a41650 removed from the list
09-09 22:02:39.332  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:39.332  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:39.332  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:39.332  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 22:02:39.332  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@367fe413 removed from the list
09-09 22:02:39.342  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 22:02:39.342  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@178a1049 added. We now have 2 listener(s)
,09-09 22:02:39.342  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-09 22:02:39.342  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 22:02:39.342  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 22:02:39.342  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:39.342  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38355d4e added. We now have 9 listener(s)
09-09 22:02:39.342  7003  7061 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 22:02:39.342  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 22:02:39.352  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 22:02:39.352  7003  7061 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 22:02:39.352  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:39.352  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:39.352  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:39.352  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:39.352  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:39.352  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false,
09-09 22:02:39.352  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:39.352  7003  7061 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 22:02:39.352  7003  7061 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 22:02:39.352  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 22:02:39.352  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@233c477c added. We now have 3 listener(s)
,09-09 22:02:39.352  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 22:02:39.352  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-09 22:02:39.352  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 22:02:39.352  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 22:02:39.352  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 22:02:39.352  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:39.362  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@245a6805 added. We now have 10 listener(s)
,09-09 22:02:39.362  7003  7061 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 22:02:39.362  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 22:02:39.362  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 22:02:39.362  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 22:02:39.362  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 22:02:39.362  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 22:02:39.362  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,09-09 22:02:39.362  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 22:02:39.362  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,09-09 22:02:39.372  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
09-09 22:02:39.372  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 22:02:39.372  7003  7061 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 22:02:39.382  3374  7648 D BtGatt.GattService: registerClient() - UUID=59700ea6-a8a7-4b7d-b0f1-518db9c1684d
,09-09 22:02:39.422  3374  3435 D BtGatt.GattService: onClientRegistered() - UUID=59700ea6-a8a7-4b7d-b0f1-518db9c1684d, clientIf=6,
,09-09 22:02:39.422  7003  7015 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-09 22:02:39.422  3374  3480 D BtGatt.GattService: start scan with filters
,09-09 22:02:39.422  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 22:02:39.422  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 22:02:39.422  3374  3483 D BtGatt.ScanManager: handling starting scan
09-09 22:02:39.432  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 22:02:39.432  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 22:02:39.432  3374  3435 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
09-09 22:02:39.432  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:39.432  3374  3483 D BtGatt.ScanManager: allow scan with filters
09-09 22:02:39.432  3374  3483 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-09 22:02:39.432  3374  3483 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
09-09 22:02:39.432  3374  3435 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-09 22:02:39.432  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 22:02:39.432  3374  3483 D BtGatt.ScanManager: Starting BLE batch scan
09-09 22:02:39.432  3374  3483 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-09 22:02:39.432  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 22:02:39.432  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 22:02:39.432  7003  7003 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 22:02:39.432  3374  3435 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-09 22:02:39.432  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:39.442  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 22:02:39.442  3374  3435 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-09 22:02:39.442  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:39.452  7003  7061 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 22:02:39.452  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:39.452  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 22:02:39.452  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 22:02:39.452  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 22:02:39.452  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 22:02:39.452  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 22:02:39.452  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 22:02:39.452  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 22:02:39.452  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 22:02:39.452  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 22:02:39.452  3374  7651 D BtGatt.GattService: stopScan() - queue size =1,
,09-09 22:02:39.452  3374  3384 D BtGatt.GattService: unregisterClient() - clientIf=6
09-09 22:02:39.462  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 22:02:39.462  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 22:02:39.462  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-09 22:02:39.462  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 22:02:39.462  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 22:02:39.462  3374  3483 D BtGatt.ScanManager: filter size is 1
09-09 22:02:39.462  3374  3483 D BtGatt.ScanManager: delete FilterIndex - 6
,09-09 22:02:39.462  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 22:02:39.462  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 22:02:39.462  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 22:02:39.462  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 22:02:39.462  3374  3435 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-09 22:02:39.462  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 22:02:39.462  3374  3483 D BtGatt.ScanManager: stopping BLe Batch
09-09 22:02:39.462  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 22:02:39.462  7003  7003 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 22:02:39.462  7003  7003 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 22:02:39.462  7003  7003 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 22:02:39.462  3374  3435 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-09 22:02:39.462  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 22:02:39.462  3374  3483 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 22:02:39.472  3374  3435 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-09 22:02:39.472  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:39.472  7003  7061 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:39.472  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:39.472  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
09-09 22:02:39.472  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:39.472  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:39.472  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 22:02:39.472  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 22:02:39.472  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@178a1049 removed from the list
09-09 22:02:39.472  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:39.472  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38355d4e removed from the list
09-09 22:02:39.472  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:39.472  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:39.472  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 22:02:39.472  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:39.482  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-09 22:02:39.482  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:39.482  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:39.482  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38355d4e not in the list
09-09 22:02:39.482  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:39.482  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:39.482  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 22:02:39.482  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:39.482  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:39.482  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@245a6805 removed from the list
09-09 22:02:39.482  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:39.482  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:39.482  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:39.482  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 22:02:39.482  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@233c477c removed from the list
,09-09 22:02:39.482  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 22:02:39.482  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@301e7f81 added. We now have 2 listener(s)
,09-09 22:02:39.492  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
,09-09 22:02:39.492  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 22:02:39.492  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 22:02:39.492  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:39.492  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@269bc826 added. We now have 9 listener(s)
,09-09 22:02:39.492  7003  7061 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 22:02:39.492  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 22:02:39.502  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 22:02:39.512  7003  7061 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 22:02:39.512  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:39.512  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:39.512  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:39.512  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:39.512  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:39.512  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:39.512  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:39.522  7003  7061 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 22:02:39.522  7003  7061 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 22:02:39.522  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 22:02:39.522  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-09 22:02:39.532  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 22:02:39.532  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14340a14 added. We now have 3 listener(s)
,09-09 22:02:39.532  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-09 22:02:39.532  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 22:02:39.532  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 22:02:39.532  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:39.532  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14b292bd added. We now have 10 listener(s)
09-09 22:02:39.532  7003  7061 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 22:02:39.532  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 22:02:39.532  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 22:02:39.532  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 22:02:39.532  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 22:02:39.532  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 22:02:39.532  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 22:02:39.542  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,09-09 22:02:39.542  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 22:02:39.542  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 22:02:39.552  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 22:02:39.552  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 22:02:39.552  7003  7061 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 22:02:39.552  3374  3384 D BtGatt.GattService: registerClient() - UUID=9685ccb1-b223-4f5a-8989-46d002080fed,
,09-09 22:02:39.602  3374  3435 D BtGatt.GattService: onClientRegistered() - UUID=9685ccb1-b223-4f5a-8989-46d002080fed, clientIf=6
,09-09 22:02:39.602  7003  7015 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-09 22:02:39.602  3374  3698 D BtGatt.GattService: start scan with filters
,09-09 22:02:39.602  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 22:02:39.602  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 22:02:39.602  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 22:02:39.602  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 22:02:39.602  3374  3483 D BtGatt.ScanManager: handling starting scan
,09-09 22:02:39.602  3374  3435 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-09 22:02:39.602  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:39.602  3374  3483 D BtGatt.ScanManager: allow scan with filters
,09-09 22:02:39.602  3374  3483 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-09 22:02:39.602  3374  3483 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,09-09 22:02:39.602  3374  3435 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-09 22:02:39.602  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:39.602  3374  3483 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 22:02:39.602  3374  3483 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-09 22:02:39.612  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 22:02:39.612  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 22:02:39.612  7003  7003 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 22:02:39.612  3374  3435 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-09 22:02:39.612  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:39.612  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 22:02:39.612  3374  3435 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-09 22:02:39.612  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:39.622  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
09-09 22:02:39.622  7003  7061 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 22:02:39.622  7003  7061 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 22:02:39.622  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 22:02:39.622  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 22:02:39.622  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:39.622  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 22:02:39.622  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 22:02:39.622  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 22:02:39.632  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@301e7f81 removed from the list
,09-09 22:02:39.632  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:39.632  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@269bc826 removed from the list
,09-09 22:02:39.632  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:39.632  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 22:02:39.632  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-09 22:02:39.632  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-09 22:02:39.632  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:39.632  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 22:02:39.632  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 22:02:39.632  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:39.632  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 22:02:39.632  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@269bc826 not in the list
,09-09 22:02:39.632  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 22:02:39.632  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 22:02:39.632  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 22:02:39.632  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 22:02:39.632  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 22:02:39.642  3374  7648 D BtGatt.GattService: stopScan() - queue size =1
,09-09 22:02:39.642  3374  3483 D BtGatt.ScanManager: filter size is 1
,09-09 22:02:39.642  3374  3483 D BtGatt.ScanManager: delete FilterIndex - 7
,09-09 22:02:39.642  3374  3435 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-09 22:02:39.642  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:39.642  3374  3480 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 22:02:39.642  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 22:02:39.642  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 22:02:39.642  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 22:02:39.642  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 22:02:39.642  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 22:02:39.642  3374  3483 D BtGatt.ScanManager: stopping BLe Batch
,09-09 22:02:39.652  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 22:02:39.652  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 22:02:39.652  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 22:02:39.652  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 22:02:39.652  3374  3435 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-09 22:02:39.652  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:39.652  3374  3483 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 22:02:39.652  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:39.652  3374  3435 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-09 22:02:39.652  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:39.662  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:39.662  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:39.662  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:39.662  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14b292bd removed from the list
09-09 22:02:39.662  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:39.662  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:39.662  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:39.662  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 22:02:39.662  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14340a14 removed from the list
,09-09 22:02:39.662  7003  7003 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 22:02:39.662  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 22:02:39.662  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@337a9db9 added. We now have 2 listener(s)
,09-09 22:02:39.662  7003  7003 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 22:02:39.662  7003  7003 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 22:02:39.662  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-09 22:02:39.662  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 22:02:39.662  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 22:02:39.662  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:39.662  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d59b5fe added. We now have 9 listener(s)
,09-09 22:02:39.662  7003  7061 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 22:02:39.662  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 22:02:39.672  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-09 22:02:39.672  7003  7061 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 22:02:39.672  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,09-09 22:02:39.672  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:39.672  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:39.672  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:39.672  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:39.672  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:39.672  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false,
,09-09 22:02:39.672  7003  7061 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 22:02:39.672  7003  7061 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 22:02:39.682  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 22:02:39.682  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bde87ac added. We now have 3 listener(s)
,09-09 22:02:39.682  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-09 22:02:39.682  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-09 22:02:39.682  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 22:02:39.682  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 22:02:39.682  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 22:02:39.682  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61e5c75 added. We now have 10 listener(s)
09-09 22:02:39.682  7003  7061 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 22:02:39.682  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 22:02:39.682  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 22:02:39.682  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 22:02:39.682  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 22:02:39.682  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 22:02:39.682  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:39.682  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 22:02:39.692  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 22:02:39.692  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 22:02:39.692  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 22:02:39.692  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 22:02:39.692  7003  7061 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 22:02:39.702  3374  7651 D BtGatt.GattService: registerClient() - UUID=29962747-c01a-4ab5-8f31-4097d9132f37
,09-09 22:02:39.722  1017  1129 E WifiNative-wlan0: do suspend true
,09-09 22:02:39.742  3374  3435 D BtGatt.GattService: onClientRegistered() - UUID=29962747-c01a-4ab5-8f31-4097d9132f37, clientIf=6
,09-09 22:02:39.742  7003  7015 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-09 22:02:39.742  3374  3384 D BtGatt.GattService: start scan with filters
,09-09 22:02:39.742  1017  1128 D WifiP2pService: InactiveState{ what=143375 }
,09-09 22:02:39.742  3374  3483 D BtGatt.ScanManager: handling starting scan
,09-09 22:02:39.742  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 22:02:39.742  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 22:02:39.742  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 22:02:39.742  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 22:02:39.742  1017  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
09-09 22:02:39.752  1017  1129 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-09 22:02:39.752  1017  1129 E WifiStateMachine: VerifyingLinkState enter
09-09 22:02:39.752  3374  3435 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-09 22:02:39.752  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 22:02:39.752  1017  1131 E ConnectivityService: updateNetworkInfo()
09-09 22:02:39.752  3374  3483 D BtGatt.ScanManager: allow scan with filters
09-09 22:02:39.752  3374  3483 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-09 22:02:39.752  3374  3483 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
09-09 22:02:39.752  1017  1131 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
09-09 22:02:39.752  1017  1131 D ConnectivityService: Adding iface wlan0 to network 504
09-09 22:02:39.762  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 22:02:39.762  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 22:02:39.762  7003  7003 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 22:02:39.772  3374  3435 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-09 22:02:39.772  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 22:02:39.772  3374  3483 D BtGatt.ScanManager: Starting BLE batch scan
09-09 22:02:39.772  1017  1145 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
09-09 22:02:39.772  3374  3483 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-09 22:02:39.772  1017  1145 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 22:02:39.772  1017  1145 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 22:02:39.772  1017  1145 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 22:02:39.772  1017  1145 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 22:02:39.782  3374  3435 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-09 22:02:39.782  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 22:02:39.782  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 22:02:39.782  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:39.782  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 22:02:39.782  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:39.782  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:39.782  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:39.782  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:39.782  3374  3435 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-09 22:02:39.782  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 22:02:39.792  1017  4465 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 22:02:39.792  1017  4465 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 22:02:39.792  1017  1129 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
09-09 22:02:39.792  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 22:02:39.792  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:39.792  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 22:02:39.792  1017  4465 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:39.792  1017  4465 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:39.792  1017  4465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 22:02:39.792  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 22:02:39.802  1017  1131 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
09-09 22:02:39.792  1632  1632 I Hs20UtilService: Starting #22
09-09 22:02:39.802  1017  1131 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
09-09 22:02:39.802  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:39.802  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:39.802  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:39.802  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:39.802  1632  1662 I Hs20UtilService: Message received 5007
09-09 22:02:39.802  1017  1131 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
09-09 22:02:39.802  1017  1131 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 22:02:39.812  4988  4988 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 22:02:39.812  1017  1131 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
09-09 22:02:39.812  1017  1131 D ConnectivityService: LTETest block dns file not exists
09-09 22:02:39.812  4988  4988 I NearbySettings: MountReceiver.onReceive - Keep current state
09-09 22:02:39.812  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 22:02:39.812  7003  7061 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:39.812  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:39.812  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 22:02:39.822  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 22:02:39.822  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:39.822  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 22:02:39.822  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 22:02:39.822  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@337a9db9 removed from the list
09-09 22:02:39.822  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:39.822  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d59b5fe removed from the list
09-09 22:02:39.822  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:39.822  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 22:02:39.822  1017  1131 V NetworkStats: updateIfacesLocked()
09-09 22:02:39.822  1017  1131 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:39.822  1017  1131 V NetworkStats: performPollLocked(flags=0x1)
,09-09 22:02:39.822  1017  1129 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 22:02:39.822  1017  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 22:02:39.822  1017  1129 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-09 22:02:39.822  1017  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 22:02:39.822  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:39.822  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-09 22:02:39.822  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:39.822  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 22:02:39.822  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 22:02:39.832  1017  1131 V NetworkStats: performPollLocked() took 5ms
09-09 22:02:39.832  1017  1017 I WifiTrafficPoller: mBoosterFLAG : 0
09-09 22:02:39.832  1017  1017 I WifiTrafficPoller: current booster mode : FullMode
,09-09 22:02:39.832  1017  1131 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:39.832  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-09 22:02:39.832  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 22:02:39.832  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 22:02:39.832  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:39.832  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:39.832  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:39.832  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:39.832  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:39.832  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:39.832  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:39.832  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d59b5fe not in the list
09-09 22:02:39.832  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 22:02:39.832  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 22:02:39.832  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 22:02:39.832  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 22:02:39.832  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 22:02:39.832  1017  1131 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-09 22:02:39.832  1017  1131 E ConnectivityService: updateNetworkInfo()
09-09 22:02:39.832  1017  1131 E ConnectivityService: updateNetworkInfo()
09-09 22:02:39.832  1017  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-09 22:02:39.832  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:39.832  1017  1131 V NetworkStats: updateIfacesLocked()
09-09 22:02:39.832  1017  1131 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:39.832  1017  1131 V NetworkStats: performPollLocked(flags=0x1)
09-09 22:02:39.832  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 22:02:39.832  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:39.832  1017  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 22:02:39.832  1017  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 22:02:39.832  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:39.832  3374  7651 D BtGatt.GattService: stopScan() - queue size =1
,09-09 22:02:39.832  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:39.832  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:39.832  3374  3384 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 22:02:39.842  1017  1131 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:39.842  1017  1131 V NetworkStats: performPollLocked() took 6ms
,09-09 22:02:39.842  3374  3483 D BtGatt.ScanManager: filter size is 1
09-09 22:02:39.842  3374  3483 D BtGatt.ScanManager: delete FilterIndex - 8
,09-09 22:02:39.842  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 22:02:39.842  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 22:02:39.842  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 22:02:39.842  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 22:02:39.842  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 22:02:39.852  3374  3435 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-09 22:02:39.852  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:39.852  3374  3483 D BtGatt.ScanManager: stopping BLe Batch
,09-09 22:02:39.852  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 22:02:39.852  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:39.852  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:39.852  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 22:02:39.852  3374  3435 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-09 22:02:39.852  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 22:02:39.852  3374  3483 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 22:02:39.852  7003  7061 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 22:02:39.852  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 22:02:39.852  3374  3435 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-09 22:02:39.852  3374  3435 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:39.852  1017  1131 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-09 22:02:39.852  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:39.852  1017  1131 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-09 22:02:39.852  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:39.852  1017  7682 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-09 22:02:39.852  1017  7682 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-09 22:02:39.852  1017  7682 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 22:02:39.852  1017  7682 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,09-09 22:02:39.862  1017  7682 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 22:02:39.862  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:39.862  1017  1524 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 22:02:39.862  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:39.862  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:39.862  1017  1131 D ConnectivityService:    accepting network in place of null
09-09 22:02:39.862  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:39.862  7003  7003 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 22:02:39.862  7003  7003 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 22:02:39.862  7003  7003 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 22:02:39.862  1017  1128 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-09 22:02:39.862  1017  1129 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 22:02:39.862  1017  1524 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 22:02:39.862  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61e5c75 removed from the list
09-09 22:02:39.862  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:39.862  1017  1131 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-09 22:02:39.862  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:39.862  1017  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 22:02:39.862  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:39.862  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 22:02:39.862  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bde87ac removed from the list
09-09 22:02:39.862  1017  1524 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:39.862  1017  1524 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:39.862  1017  1131 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-09 22:02:39.862  1017  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 22:02:39.862  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 22:02:39.862  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f054af1 added. We now have 2 listener(s)
09-09 22:02:39.862  1478  1478 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true,
09-09 22:02:39.862  1632  1632 I Hs20UtilService: Starting #23
09-09 22:02:39.862  1017  1131 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,09-09 22:02:39.862   278   987 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 22:02:39.862   278   987 D Netd    : getNetworkForDns: using netid 504 for uid 1000
09-09 22:02:39.862  1632  1662 I Hs20UtilService: Message received 5007
09-09 22:02:39.862  1478  1478 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 22:02:39.862  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,09-09 22:02:39.862  1017  1132 D Tethering: MasterInitialState.processMessage what=3
,09-09 22:02:39.862  1017  1131 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,09-09 22:02:39.872  1017  1126 V NetworkStats: updateIfacesLocked()
09-09 22:02:39.872  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:39.872  1017  1126 V NetworkStats: performPollLocked(flags=0x1)
,09-09 22:02:39.872  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
09-09 22:02:39.872  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 22:02:39.872  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 22:02:39.872  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-09 22:02:39.872  1180  1180 D StatusBar.NetworkController: EthernetConnected: false
09-09 22:02:39.872  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-09 22:02:39.872  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-09 22:02:39.872  1180  1180 D StatusBar.NetworkController: updateDataNetType()
,09-09 22:02:39.872  1180  1701 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 22:02:39.872  1017  1126 V NetworkStats: performPollLocked() took 4ms
09-09 22:02:39.872  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:39.872  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 22:02:39.872  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 22:02:39.872  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:39.872  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:39.872  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@197c86d6 added. We now have 9 listener(s)
09-09 22:02:39.872  7003  7061 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 22:02:39.872  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:39.872  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:39.872  1017  1127 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-09 22:02:39.872  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:39.872  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 22:02:39.872  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 22:02:39.872  1180  1180 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-09 22:02:39.872  1180  1180 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,09-09 22:02:39.872  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 20 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,09-09 22:02:39.882  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
,09-09 22:02:39.882  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,09-09 22:02:39.882  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:39.882  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,09-09 22:02:39.882  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:39.882  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:39.882  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:39.882  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:39.882  4988  4988 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 22:02:39.882  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 22:02:39.882  4988  4988 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 22:02:39.882  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,09-09 22:02:39.882  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 22:02:39.882  4988  4988 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
09-09 22:02:39.882  4988  4988 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-09 22:02:39.882  7003  7061 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-09 22:02:39.882  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:39.882  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:39.882  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:39.882  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:39.882  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 22:02:39.882  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 22:02:39.882  7003  7061 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 22:02:39.892  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:39.892  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:39.892  7003  7061 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 22:02:39.892  7003  7061 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 22:02:39.892  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 22:02:39.892  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30782044 added. We now have 3 listener(s)
,09-09 22:02:39.892  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:39.892  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:39.892  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-09 22:02:39.892  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 22:02:39.892  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 22:02:39.892  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:39.892  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3592a52d added. We now have 10 listener(s)
09-09 22:02:39.892  7003  7061 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 22:02:39.892  7003  7061 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:39.892  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:39.892  7003  7061 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:39.892  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:39.892  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:39.892  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 22:02:39.892  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 22:02:39.892  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f054af1 removed from the list
09-09 22:02:39.892  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:39.892  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@197c86d6 removed from the list
09-09 22:02:39.892  7003  7061 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:39.892  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:39.902  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:39.902  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:39.902  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:39.902  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 22:02:39.902  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:39.902  7003  7061 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@197c86d6 not in the list
09-09 22:02:39.902  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:39.902  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:39.902  1017  4466 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 22:02:39.902  1017  4466 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 22:02:39.902  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:39.902  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:39.902  7003  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:39.902  7003  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3592a52d removed from the list
09-09 22:02:39.902  7003  7061 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:39.902  7003  7061 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:39.902  7003  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:39.902  7003  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 22:02:39.902  7003  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30782044 removed from the list
09-09 22:02:39.902  1017  4466 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:39.902  1017  4466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:39.902  1017  4466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 22:02:39.902  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 22:02:39.902  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 22:02:39.902  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 22:02:39.902  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 22:02:39.902  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 22:02:39.902  7003  7061 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 22:02:39.912  4988  4988 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 22:02:39.912  1632  1632 I Hs20UtilService: Starting #24
,09-09 22:02:39.912  4988  4988 I NearbySettings: MountReceiver.onReceive - Keep current state
09-09 22:02:39.912  1632  1662 I Hs20UtilService: Message received 5007
,09-09 22:02:39.912  7003  7720 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1428, name: My test thread name)
09-09 22:02:39.912  7003  7720 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1428, thread name: My test thread name)
09-09 22:02:39.912  7003  7720 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1428, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-09 22:02:39.912  1017  1524 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-09 22:02:39.922  1017  3703 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-09 22:02:39.922  1017  3703 D SecContentProvider2: mCursor = null
,09-09 22:02:39.922  7003  7721 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1430, name: My test thread name)
09-09 22:02:39.922  7003  7721 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1430, thread name: My test thread name)
09-09 22:02:39.922  7003  7721 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1430, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-09 22:02:39.922  1017  1320 D SecContentProvider2: uri = 15 selection = getToastGravity
09-09 22:02:39.922  1017  1320 D SecContentProvider2: mCursor = null
,09-09 22:02:39.922  1017  1506 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,09-09 22:02:39.922  1017  1506 D SecContentProvider2: mCursor = null
09-09 22:02:39.922  7003  7061 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-09 22:02:39.922  7003  7061 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-09 22:02:39.922  7003  7061 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-09 22:02:39.922  7003  7061 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-09 22:02:39.922  7003  7061 D com.test.thalitest.ThaliTestRunner: Total duration: 23393 ms
09-09 22:02:39.922  1017  1210 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-09 22:02:39.922  1017  1210 D SecContentProvider2: mCursor = null
09-09 22:02:39.922  7003  7061 I jxcore-log: *Native tests were executed*
09-09 22:02:39.922  7003  7061 I jxcore-log: 
09-09 22:02:39.922  7003  7061 I jxcore-log: Total number of executed tests:  80
09-09 22:02:39.922  7003  7061 I jxcore-log: 
09-09 22:02:39.922  7003  7061 I jxcore-log: Number of passed tests:  80
09-09 22:02:39.922  7003  7061 I jxcore-log: 
09-09 22:02:39.922  7003  7061 I jxcore-log: Number of failed tests:  0
09-09 22:02:39.922  7003  7061 I jxcore-log: 
09-09 22:02:39.922  7003  7061 I jxcore-log: Number of ignored tests:  0
09-09 22:02:39.922  7003  7061 I jxcore-log: 
09-09 22:02:39.922  7003  7061 I jxcore-log: Total duration:  23393
09-09 22:02:39.922  7003  7061 I jxcore-log: 
09-09 22:02:39.922  7003  7061 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-09 22:02:39.922  7003  7061 I jxcore-log: 
09-09 22:02:39.922  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 22:02:39.922  7003  7061 I jxcore-log: 
,09-09 22:02:39.932  1017  1499 D SecContentProvider2: uri = 15 selection = getToastEnabledState
09-09 22:02:39.932  1017  1499 D SecContentProvider2: mCursor = null
09-09 22:02:39.932  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 22:02:39.932  7003  7061 I jxcore-log: 
09-09 22:02:39.932  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 22:02:39.932  7003  7061 I jxcore-log: 
09-09 22:02:39.932  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 22:02:39.932  7003  7061 I jxcore-log: 
09-09 22:02:39.932  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 22:02:39.932  7003  7061 I jxcore-log: 
09-09 22:02:39.932  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 22:02:39.932  7003  7061 I jxcore-log: 
09-09 22:02:39.932  7003  7003 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-09 22:02:39.932  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 22:02:39.932  7003  7061 I jxcore-log: 
09-09 22:02:39.932  1017  4465 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
09-09 22:02:39.932  1017  4465 D SecContentProvider2: mCursor = null
09-09 22:02:39.942  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 22:02:39.942  7003  7061 I jxcore-log: 
09-09 22:02:39.942  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 22:02:39.942  7003  7061 I jxcore-log: 
09-09 22:02:39.942  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 22:02:39.942  7003  7061 I jxcore-log: 
09-09 22:02:39.942  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 22:02:39.942  7003  7061 I jxcore-log: 
09-09 22:02:39.942  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 22:02:39.942  7003  7061 I jxcore-log: 
,09-09 22:02:39.942  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 22:02:39.942  7003  7061 I jxcore-log: 
,09-09 22:02:39.952  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 22:02:39.952  7003  7061 I jxcore-log: 
09-09 22:02:39.952  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 22:02:39.952  7003  7061 I jxcore-log: 
,09-09 22:02:39.952  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 22:02:39.952  7003  7061 I jxcore-log: 
,09-09 22:02:39.952  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 22:02:39.952  7003  7061 I jxcore-log: 
,09-09 22:02:39.952  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
09-09 22:02:39.952  7003  7061 I jxcore-log: 
09-09 22:02:39.952  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 22:02:39.952  7003  7061 I jxcore-log: 
09-09 22:02:39.952  1017  7682 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-09 22:02:39.952  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 22:02:39.952  7003  7061 I jxcore-log: 
,09-09 22:02:39.952  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 22:02:39.952  7003  7061 I jxcore-log: 
09-09 22:02:39.952  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 22:02:39.952  7003  7061 I jxcore-log: 
,09-09 22:02:39.952  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
09-09 22:02:39.952  7003  7061 I jxcore-log: 
,09-09 22:02:39.952  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 22:02:39.952  7003  7061 I jxcore-log: 
,09-09 22:02:39.962  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
09-09 22:02:39.962  7003  7061 I jxcore-log: 
,09-09 22:02:39.962  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 22:02:39.962  7003  7061 I jxcore-log: 
,09-09 22:02:39.962  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
09-09 22:02:39.962  7003  7061 I jxcore-log: 
,09-09 22:02:39.962   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,09-09 22:02:39.962  7003  7003 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 22:02:39.962  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
09-09 22:02:39.962  7003  7061 I jxcore-log: 
,09-09 22:02:39.982  1017  1030 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
,09-09 22:02:40.002  1180  1180 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-09 22:02:40.012  1017  7682 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 20:02:40 GMT], X-Android-Received-Millis=[1473451360019], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473451359989]}
09-09 22:02:40.012  1017  7682 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 22:02:40.012  1017  7682 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-09 22:02:40.012  1017  1131 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
09-09 22:02:40.012  1017  1131 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-09 22:02:40.012  1017  1131 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-09 22:02:40.012  1017  1131 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,09-09 22:02:40.012  1017  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-09 22:02:40.012  1180  1701 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-09 22:02:40.022  1180  1180 D StatusBar.NetworkController: EthernetConnected: false
,09-09 22:02:40.022  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): 0,
,09-09 22:02:40.022  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
,09-09 22:02:40.022  1180  1180 D StatusBar.NetworkController: updateDataNetType()
,09-09 22:02:40.032  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-09 22:02:40.032  1180  1180 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-09 22:02:40.032  1180  1180 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,09-09 22:02:40.032  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 20 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,09-09 22:02:40.032  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
,09-09 22:02:40.032  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,09-09 22:02:40.032  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 22:02:40.032  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,09-09 22:02:40.032  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:40.042  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:40.042  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:40.042  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:40.162  7003  7003 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-09 22:02:40.162  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 22:02:40.162  7003  7061 I jxcore-log: 
,09-09 22:02:40.222  7722  7722 D AndroidRuntime: 
09-09 22:02:40.222  7722  7722 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-09 22:02:40.232  7722  7722 D AndroidRuntime: CheckJNI is OFF,
09-09 22:02:40.232  7722  7722 D AndroidRuntime: readGMSProperty: start
,09-09 22:02:40.232  7722  7722 D AndroidRuntime: readGMSProperty: already setted!!
09-09 22:02:40.232  7722  7722 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-09 22:02:40.232  7722  7722 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
,09-09 22:02:40.232  7722  7722 D AndroidRuntime: readGMSProperty: end
09-09 22:02:40.232  7722  7722 D AndroidRuntime: addProductProperty: start
,09-09 22:02:40.362  7003  7003 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-09 22:02:40.362  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 22:02:40.362  7003  7061 I jxcore-log: 
09-09 22:02:40.362  1017  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 22:02:40.382  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 22:02:40.392  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-09 22:02:40.392  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:40.392  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:40.392  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:40.392  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:40.402  7003  7003 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:40.402  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:40.402  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:40.402  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:40.402  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:40.402  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 22:02:40.402  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 22:02:40.402  7003  7003 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 22:02:40.402  7722  7722 E AffinityControl: AffinityControl: registerfunction enter
,09-09 22:02:40.412  7003  7003 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 22:02:40.412  7003  7061 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 22:02:40.412  7003  7061 I jxcore-log: 
,09-09 22:02:40.422  1017  1042 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7731 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,09-09 22:02:40.432  7731  7731 E Zygote  : MountEmulatedStorage(),
09-09 22:02:40.432  7731  7731 E Zygote  : v2
09-09 22:02:40.432  7731  7731 I libpersona: KNOX_SDCARD checking this for 1000
09-09 22:02:40.432  7731  7731 I libpersona: KNOX_SDCARD not a persona,
,09-09 22:02:40.432  7731  7731 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-09 22:02:40.442  7731  7731 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 22:02:40.442  7722  7722 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-09 22:02:40.442  7731  7731 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-09 22:02:40.452  1017  1506 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
09-09 22:02:40.452  1017  1506 D PackageManager: START PACKAGE DELETE: observer{638310639}
09-09 22:02:40.452  1017  1506 D PackageManager: pkg{<packageName>}
09-09 22:02:40.452  1017  1506 D PackageManager: user{0}
09-09 22:02:40.452  1017  1506 D PackageManager: caller{2000}
09-09 22:02:40.452  1017  1506 D PackageManager: flags{2}
,09-09 22:02:40.452  1017  1506 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-09 22:02:40.452  1017  1506 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,09-09 22:02:40.462  1017  1506 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-09 22:02:40.462  1017  1506 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-09 22:02:40.462  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
09-09 22:02:40.462  1017  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-09 22:02:40.462  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-09 22:02:40.462  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
09-09 22:02:40.462  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-09 22:02:40.472  1017  1057 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,09-09 22:02:40.472  1017  1042 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,09-09 22:02:40.472  1017  1042 I ActivityManager: Killing 7003:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-09 22:02:40.472  1017  1042 I ActivityManager:   Force finishing activity ActivityRecord{17af4725 u0 com.test.thalitest/.MainActivity t163}
,09-09 22:02:40.482  1017  1042 D InputDispatcher: Focus left window: 7003
,09-09 22:02:40.482   258   448 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
09-09 22:02:40.482   258  1103 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,09-09 22:02:40.492  7731  7731 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:40.492  7731  7731 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:40.532  1017  1042 D InputDispatcher: Focused application released
,09-09 22:02:40.532  1017  1047 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!,
,09-09 22:02:40.532  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 22:02:40.532  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 22:02:40.622  7731  7731 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-09 22:02:40.622  7731  7731 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-09 22:02:40.622  7731  7731 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-09 22:02:40.632  1017  1057 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,09-09 22:02:40.642  1017  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-09 22:02:40.662  7731  7731 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-09 22:02:40.662  7731  7731 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-09 22:02:40.662  7731  7731 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 22:02:40.662  7731  7731 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-09 22:02:40.672  1017  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-09 22:02:40.682  2843  2843 I art     : Explicit concurrent mark sweep GC freed 17338(1022KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 793us total 41.231ms
,09-09 22:02:40.682  1874  1874 E SamsungIME: mOCRHelper is null
,09-09 22:02:40.692  1754  2020 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-09 22:02:40.702  1017  1320 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
09-09 22:02:40.702  1017  1320 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
09-09 22:02:40.702  1017  1320 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
09-09 22:02:40.702  1017  1320 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,09-09 22:02:40.712  1017  1320 I ActivityManager: Killing 7221:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,09-09 22:02:40.722  1017  1126 V NetworkStats: removeUidsLocked() for UIDs [10170]
09-09 22:02:40.722  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:40.722  1017  1126 V NetworkStats: performPollLocked(flags=0x3)
,09-09 22:02:40.732  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 22:02:40.732  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 22:02:40.732  1465  1465 D PersonaManager: isKioskContainerExistOnDevice
,09-09 22:02:40.742  1017  1126 V NetworkStats: performPollLocked() took 15ms
09-09 22:02:40.742  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:40.742  1465  1465 D RegisteredServicesCache: empty dynamic service
,09-09 22:02:40.742  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:40.742  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:40.762  1465  1465 D RegisteredComponentCache: Collect Tech packages for Knox
,09-09 22:02:40.772  1465  1465 D PersonaManager: isKioskContainerExistOnDevice
,09-09 22:02:40.772  1017  4465 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-09 22:02:40.772  1017  4465 D SecContentProvider2: mCursor = null
,09-09 22:02:40.822  1017  1017 I art     : Explicit concurrent mark sweep GC freed 63675(4MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 23MB/35MB, paused 2.846ms total 183.304ms
,09-09 22:02:40.822  1017  1057 I art     : WaitForGcToComplete blocked for 111.896ms for cause Explicit
,09-09 22:02:40.842  1017  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
09-09 22:02:40.842  1017  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,09-09 22:02:40.842  1017  1041 W TextServicesManagerService: no available spell checker services found
,09-09 22:02:40.852  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 22:02:40.862  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 22:02:40.862  1017  1131 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-09 22:02:40.872  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 22:02:40.872  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,09-09 22:02:40.872  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-09 22:02:40.872  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 22:02:40.872  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-09 22:02:40.872  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-09 22:02:40.872  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,09-09 22:02:40.892  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,09-09 22:02:40.902  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-09 22:02:40.962  1017  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-09 22:02:40.962  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 22:02:40.962  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 22:02:40.992  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 22:02:40.992  1017  1057 I art     : Explicit concurrent mark sweep GC freed 12467(590KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.335ms total 162.708ms
,09-09 22:02:41.022  1017  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 22:02:41.022  1017  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 22:02:41.022  1017  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 22:02:41.032  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 22:02:41.042  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 22:02:41.052  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 22:02:41.052  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 22:02:41.052  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 22:02:41.052  1017  1057 D PackageManager: delete codoeFile: 
,09-09 22:02:41.052  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 22:02:41.062  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
09-09 22:02:41.062  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 22:02:41.062  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 22:02:41.062  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 22:02:41.062  1017  1057 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
,09-09 22:02:41.062  1017  1057 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,09-09 22:02:41.062  1017  1057 D PackageManager: result of delete: 1{638310639}
,09-09 22:02:41.062  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 22:02:41.062  1017  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
,09-09 22:02:41.072  1017  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-09 22:02:41.072  7722  7722 D AndroidRuntime: Shutting down VM
,09-09 22:02:41.072  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-09 22:02:41.072  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-09 22:02:41.072  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-09 22:02:41.072  1017  1017 V EnterpriseBillingPolicy: uID is 10170
09-09 22:02:41.072  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
09-09 22:02:41.072  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-09 22:02:41.082  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-09 22:02:41.082  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-09 22:02:41.082  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-09 22:02:41.082  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-09 22:02:41.082  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-09 22:02:41.082  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-09 22:02:41.082  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-09 22:02:41.082  1017  1017 V EnterpriseBillingPolicy: uID is 10170
09-09 22:02:41.082  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
09-09 22:02:41.082  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-09 22:02:41.082  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-09 22:02:41.082  1017  3453 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-09 22:02:41.082  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-09 22:02:41.082  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-09 22:02:41.082  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-09 22:02:41.082  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
09-09 22:02:41.082  1017  1162 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,09-09 22:02:41.092  1017  1017 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,09-09 22:02:41.152  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-09 22:02:41.162  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:41.162  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:41.162  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:41.162  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:41.172  1017  4466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 22:02:41.172  1017  4466 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4231, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-09 22:02:41.172  1017  4466 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-09 22:02:41.172  1017  4466 D BatteryService: stay LED for charging
,09-09 22:02:41.172  7750  7750 E Zygote  : MountEmulatedStorage()
,09-09 22:02:41.172  7750  7750 E Zygote  : v2
09-09 22:02:41.172  7750  7750 I libpersona: KNOX_SDCARD checking this for 10001
09-09 22:02:41.172  7750  7750 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:41.172  7750  7750 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 22:02:41.182  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7750 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-09 22:02:41.182  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 22:02:41.182  1017  1017 I MotionRecognitionService: Plugged
09-09 22:02:41.182  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 22:02:41.182  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-09 22:02:41.182  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
09-09 22:02:41.182  7750  7750 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 22:02:41.182  1425  1425 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-09 22:02:41.182  1425  1425 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-09 22:02:41.192  7750  7750 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-09 22:02:41.192  3374  3374 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-09 22:02:41.192  3374  7640 D HeadsetStateMachine: Disconnected process message: 10
,09-09 22:02:41.212  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-09 22:02:41.212  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-09 22:02:41.212  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-09 22:02:41.212  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-09 22:02:41.212  1180  1180 D SViewCoverView: level :100 plugged : 2
,09-09 22:02:41.222  7750  7750 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:41.222  7750  7750 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:41.282  7722  7722 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-09 22:02:41.282  7239  7239 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE,
09-09 22:02:41.282  7239  7239 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 22:02:41.282  7239  7239 I DIAGMON_AGENT: ./extraInfo: "NG700"
09-09 22:02:41.282  7239  7239 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,09-09 22:02:41.302  1017  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-09 22:02:41.302  1017  1057 D PackageManager: userId{-1}
09-09 22:02:41.302  1017  1057 D PackageManager: andCode{true}
,09-09 22:02:41.312  1017  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-09 22:02:41.332  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:41.332  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:41.332  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:41.332  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:41.352  7769  7769 E Zygote  : MountEmulatedStorage(),
09-09 22:02:41.352  7769  7769 E Zygote  : v2
09-09 22:02:41.352  7769  7769 I libpersona: KNOX_SDCARD checking this for 10003
09-09 22:02:41.352  7769  7769 I libpersona: KNOX_SDCARD not a persona,
,09-09 22:02:41.352  7769  7769 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 22:02:41.362  1017  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7769 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a,
,09-09 22:02:41.362  7769  7769 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 22:02:41.372  7769  7769 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-09 22:02:41.402  7769  7769 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-09 22:02:41.402  7769  7769 D ActivityThread: Added TimaKeyStore provider,
,09-09 22:02:41.412  3374  3433 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-09 22:02:41.462  1017  4465 I ActivityManager: Killing 7273:com.sec.android.soagent/u0a31 (adj 15): empty #21
,09-09 22:02:41.472  7254  7254 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,09-09 22:02:41.472  7254  7254 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,09-09 22:02:41.482  7254  7254 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,09-09 22:02:41.482  7254  7254 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory

```
