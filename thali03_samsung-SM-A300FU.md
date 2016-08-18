#### Test 8180285668baf36_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
08-18 14:08:31.399  6610  6610 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
08-18 14:08:31.399  1018  1488 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:31.399  1018  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-18 14:08:31.399  1018  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
--------- beginning of system
08-18 14:08:31.399  1018  1488 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-18 14:08:31.399  1018  1488 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
08-18 14:08:31.409   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 16.998ms
08-18 14:08:31.409  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:31.409  6888  6888 D TimaKeyStoreProvider: TimaSignature is unavailable
08-18 14:08:31.409  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-18 14:08:31.409  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
08-18 14:08:31.409  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
08-18 14:08:31.419  6888  6888 D ActivityThread: Added TimaKeyStore provider
08-18 14:08:31.429  1018  1385 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
08-18 14:08:31.429  1018  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:31.429  1018  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:31.429  1018  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:31.429  1018  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:31.439  6909  6909 E Zygote  : MountEmulatedStorage()
08-18 14:08:31.439  6909  6909 E Zygote  : v2
08-18 14:08:31.439  6909  6909 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-18 14:08:31.439  6909  6909 I libpersona: KNOX_SDCARD checking this for 10087
08-18 14:08:31.439  6909  6909 I libpersona: KNOX_SDCARD not a persona
08-18 14:08:31.449  6909  6909 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-18 14:08:31.449  1018  1385 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6909 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
08-18 14:08:31.469  6909  6909 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-18 14:08:31.479  1018  1385 I ActivityManager: Killing 6494:com.android.mms/u0a41 (adj 15): empty #21
08-18 14:08:31.479  1018  1385 I ActivityManager: Killing 6523:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-18 14:08:31.489  6909  6909 D TimaKeyStoreProvider: TimaSignature is unavailable
08-18 14:08:31.499  6909  6909 D ActivityThread: Added TimaKeyStore provider
08-18 14:08:31.529  6888  6888 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-18 14:08:31.529  6888  6888 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-18 14:08:31.529  6888  6888 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
08-18 14:08:31.539  1018  4318 E EdmStorageProvider: Admin not in database, something went wrong
08-18 14:08:31.539  6805  6919 D ContactProvider: getAllContactInfoList Start
08-18 14:08:31.569  1018  1487 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-18 14:08:31.589  1018  1031 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-18 14:08:31.589  6888  6888 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-18 14:08:31.589  6888  6888 I PCWCLIENTTRACE_PushUtil: sales region : global
08-18 14:08:31.589  6888  6888 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-18 14:08:31.589  6888  6888 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_ADDED
08-18 14:08:31.589  6805  6919 D ContactProvider: getAllContactInfoList End
08-18 14:08:31.589  6805  6919 I syncContacts: thread: 1253, sync time = 74
08-18 14:08:31.639  1018  4320 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-18 14:08:31.649  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:31.649  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:31.649  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:31.649  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:31.649  1018  1548 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-18 14:08:31.679  6932  6932 E Zygote  : MountEmulatedStorage()
08-18 14:08:31.679  6932  6932 E Zygote  : v2
08-18 14:08:31.679  6932  6932 I libpersona: KNOX_SDCARD checking this for 1000
08-18 14:08:31.679  6932  6932 I libpersona: KNOX_SDCARD not a persona
08-18 14:08:31.679  6932  6932 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-18 14:08:31.679  1018  1043 I ActivityManager: Start proc com.samsung.aasaservice for service com.samsung.aasaservice/.AASAService: pid=6932 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-18 14:08:31.689  6932  6932 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-18 14:08:31.689  6932  6932 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-18 14:08:31.719  6932  6932 D TimaKeyStoreProvider: TimaSignature is unavailable
08-18 14:08:31.719  6932  6932 D ActivityThread: Added TimaKeyStore provider
08-18 14:08:31.749  1918  6836 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-18 14:08:31.749  1918  6836 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-18 14:08:31.749  1918  6836 I System.out: (HTTPLog)-Static: isShipBuild true
08-18 14:08:31.749  1918  6836 I System.out: (HTTPLog)-Thread-252-971769342: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-18 14:08:31.749  1918  6836 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-18 14:08:31.749  1018  1042 E libprocessgroup: failed to kill 1 processes for processgroup 6494
08-18 14:08:31.759   279  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-18 14:08:31.759   279  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10011
08-18 14:08:31.759  6929  6929 D AndroidRuntime: 
08-18 14:08:31.759  6929  6929 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-18 14:08:31.769  6929  6929 D AndroidRuntime: CheckJNI is OFF
08-18 14:08:31.769  6929  6929 D AndroidRuntime: readGMSProperty: start
08-18 14:08:31.769  6929  6929 D AndroidRuntime: readGMSProperty: already setted!!
08-18 14:08:31.769  6929  6929 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-18 14:08:31.769  6929  6929 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-18 14:08:31.769  6929  6929 D AndroidRuntime: readGMSProperty: end
08-18 14:08:31.769  6929  6929 D AndroidRuntime: addProductProperty: start
08-18 14:08:31.789  1018  1385 I art     : Explicit concurrent mark sweep GC freed 138671(7MB) AllocSpace objects, 3(1847KB) LOS objects, 33% free, 22MB/34MB, paused 2.578ms total 195.994ms
08-18 14:08:31.789  1018  4318 D ActivityManager: startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
08-18 14:08:31.789  1018  4318 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:31.789  1018  4318 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:31.789  1018  4318 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:31.789  1018  4318 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:31.789  6805  6805 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
08-18 14:08:31.809  6953  6953 E Zygote  : MountEmulatedStorage()
08-18 14:08:31.809  6953  6953 E Zygote  : v2
08-18 14:08:31.809  6953  6953 I libpersona: KNOX_SDCARD checking this for 10026
08-18 14:08:31.809  6953  6953 I libpersona: KNOX_SDCARD not a persona
08-18 14:08:31.819  6953  6953 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-18 14:08:31.819  1018  4318 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6953 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-18 14:08:31.819  1018  4318 I ActivityManager: Killing 6538:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
08-18 14:08:31.819  6953  6953 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-18 14:08:31.819  6953  6953 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-18 14:08:31.819  1018  4317 D LocationManagerService: getProviders()=[passive, gps]
08-18 14:08:31.839  1918  6836 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-18 14:08:31.849  1918  6836 I qtaguid : Tagging socket 103 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1918, getuid(): 10011
08-18 14:08:31.869  1018  1385 D CountryDetector: No listener is left
08-18 14:08:31.869  1018  1381 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
08-18 14:08:31.879  1018  1381 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:31.879  1018  1381 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:31.879  1018  1381 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:31.879  1018  1381 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:31.879  6953  6953 D TimaKeyStoreProvider: TimaSignature is unavailable
08-18 14:08:31.879  6953  6953 D ActivityThread: Added TimaKeyStore provider
08-18 14:08:31.889  1918  6836 I qtaguid : Tagging socket 107 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1918, getuid(): 10011
08-18 14:08:31.889  6932  6932 D AASAservice: onCreate()
08-18 14:08:31.889  6932  6932 E AASAservice: getConfirmRuleVersion() : Version File is not exist.
08-18 14:08:31.919  1018  1381 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=6980 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
08-18 14:08:31.919  6980  6980 E Zygote  : MountEmulatedStorage()
08-18 14:08:31.919  6980  6980 E Zygote  : v2
08-18 14:08:31.919  6980  6980 I libpersona: KNOX_SDCARD checking this for 10041
08-18 14:08:31.919  6980  6980 I libpersona: KNOX_SDCARD not a persona
08-18 14:08:31.929  6980  6980 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-18 14:08:31.929  6980  6980 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-18 14:08:31.929  6980  6980 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-18 14:08:31.929  6775  6840 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-18 14:08:31.939  2726  2726 I DBG_POLICYDM: [com.sec.android.policydm.aasa.AASAUpdater$1(72/onServiceConnected)] AASA: onServiceConnected
08-18 14:08:31.939  6929  6929 E AffinityControl: AffinityControl: registerfunction enter
08-18 14:08:31.959  6980  6980 D TimaKeyStoreProvider: TimaSignature is unavailable
08-18 14:08:31.959  6980  6980 D ActivityThread: Added TimaKeyStore provider
08-18 14:08:31.969  6929  6929 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-18 14:08:31.979  1018  1031 E PersonaManagerService: inState():  stateMachine is null !!
08-18 14:08:31.979  6980  6980 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-18 14:08:31.979  6980  6980 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-18 14:08:31.979  6980  6980 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-18 14:08:31.979  6980  6980 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-18 14:08:31.979  6980  6980 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
08-18 14:08:31.989  1018  1031 I PersonaManagerService: PersonaId don't exist
08-18 14:08:31.989  1018  1548 I ActivityManager: Killing 6420:com.android.defcontainer/u0a3 (adj 15): empty #21
08-18 14:08:31.989  1018  1031 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-18 14:08:31.989  1018  1502 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
08-18 14:08:31.989  1018  1502 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
08-18 14:08:31.989  1018  1502 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:31.989  1018  1502 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-18 14:08:31.989  1018  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
08-18 14:08:31.999  1918  6841 W BaseAppContext: Using Auth Proxy for data requests.
08-18 14:08:31.999  1918  6841 W BaseAppContext: Using Auth Proxy for data requests.
08-18 14:08:31.999  1018  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-18 14:08:32.019  1018  1031 W ActivityManager: mDVFSHelper.acquire()
08-18 14:08:32.019  1018  1031 D FocusedStackFrame: Set to : 0
08-18 14:08:32.039  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:32.039  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:32.039  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:32.039  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:32.039  1018  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-18 14:08:32.039  1018  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-18 14:08:32.049  6999  6999 E Zygote  : MountEmulatedStorage()
08-18 14:08:32.049  6999  6999 E Zygote  : v2
08-18 14:08:32.049  6999  6999 I libpersona: KNOX_SDCARD checking this for 10170
08-18 14:08:32.049  6999  6999 I libpersona: KNOX_SDCARD not a persona
08-18 14:08:32.049  6999  6999 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-18 14:08:32.059  1018  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-18 14:08:32.059  1018  1031 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6999 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-18 14:08:32.059  1018  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-18 14:08:32.059  1018  1031 D InputDispatcher: Focused application set to: xxxx
08-18 14:08:32.059  1018  1031 D InputDispatcher: Focus left window: 1495
08-18 14:08:32.059  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-18 14:08:32.059  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-18 14:08:32.059   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-18 14:08:32.069  6929  6929 D AndroidRuntime: Shutting down VM
08-18 14:08:32.069  6980  6980 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
08-18 14:08:32.079  6999  6999 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-18 14:08:32.079  6999  6999 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-18 14:08:32.089  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-18 14:08:32.089  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-18 14:08:32.099  6999  6999 D TimaKeyStoreProvider: TimaSignature is unavailable
08-18 14:08:32.099  6999  6999 D ActivityThread: Added TimaKeyStore provider
08-18 14:08:32.099  1018  4317 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-18 14:08:32.109  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-18 14:08:32.129  1018  1018 V ActivityManager: Display changed displayId=0
08-18 14:08:32.139  1018  4317 D PersonaManager: isKioskContainerExistOnDevice
08-18 14:08:32.159   259   453 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
08-18 14:08:32.159  1018  1453 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
08-18 14:08:32.159   259  1162 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-18 14:08:32.159  1018  1453 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
08-18 14:08:32.159  1495  1495 V ActivityThread: updateVisibility : ActivityRecord{260b177c token=android.os.BinderProxy@23a4b0f4 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-18 14:08:32.169  1018  1453 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:32.169  1018  1453 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-18 14:08:32.169  1018  1453 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
08-18 14:08:32.169  1495  1495 D Launcher: onTrimMemory. Level: 20
08-18 14:08:32.189  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-18 14:08:32.199  1918  6841 W BaseAppContext: Using Auth Proxy for data requests.
08-18 14:08:32.249  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-18 14:08:32.259   289   289 E SMD     : DCD OFF
08-18 14:08:32.269  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-18 14:08:32.269  1655  1664 I art     : Explicit concurrent mark sweep GC freed 13273(630KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 8MB/13MB, paused 1.071ms total 46.045ms
08-18 14:08:32.279  6929  6929 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-18 14:08:32.289  6999  6999 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-18 14:08:32.299  1018  4319 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
08-18 14:08:32.299  1018  4319 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:32.299  1018  4319 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:32.299  1018  4319 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:32.299  1018  4319 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:32.309  7019  7019 E Zygote  : MountEmulatedStorage()
08-18 14:08:32.309  7019  7019 E Zygote  : v2
08-18 14:08:32.309  7019  7019 I libpersona: KNOX_SDCARD checking this for 10148
08-18 14:08:32.309  7019  7019 I libpersona: KNOX_SDCARD not a persona
08-18 14:08:32.309  1018  4319 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7019 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
08-18 14:08:32.309  7019  7019 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-18 14:08:32.319  7019  7019 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-18 14:08:32.319  7019  7019 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-18 14:08:32.319  1018  1212 I ActivityManager: Killing 6557:com.wsomacp/u0a23 (adj 15): empty #21
08-18 14:08:32.329  6999  6999 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 5064-5067)
08-18 14:08:32.329  6999  6999 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-18 14:08:32.329  1918  6841 W BaseAppContext: Using Auth Proxy for data requests.
08-18 14:08:32.339  1918  6841 W BaseAppContext: Using Auth Proxy for data requests.
08-18 14:08:32.349  7019  7019 D TimaKeyStoreProvider: TimaSignature is unavailable
08-18 14:08:32.349  7019  7019 D ActivityThread: Added TimaKeyStore provider
08-18 14:08:32.379  6980  6980 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 251.711ms
08-18 14:08:32.389  6953  6953 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
08-18 14:08:32.389  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-18 14:08:32.409  1918  6841 W BaseAppContext: Using Auth Proxy for data requests.
08-18 14:08:32.409  6999  6999 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {12d1cc6d}
08-18 14:08:32.409  6999  6999 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-18 14:08:32.409  7019  7019 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
08-18 14:08:32.419  1018  1381 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
08-18 14:08:32.429  1018  1381 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:32.429  1018  1381 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:32.429  1018  1381 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:32.429  1018  1381 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:32.429  6999  6999 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-18 14:08:32.449  7044  7044 E Zygote  : MountEmulatedStorage()
08-18 14:08:32.449  7044  7044 E Zygote  : v2
08-18 14:08:32.449  7044  7044 I libpersona: KNOX_SDCARD checking this for 1000
08-18 14:08:32.449  7044  7044 I libpersona: KNOX_SDCARD not a persona
08-18 14:08:32.449  7044  7044 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-18 14:08:32.449  7044  7044 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-18 14:08:32.449  1018  1381 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=7044 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-18 14:08:32.449  1018  1381 I ActivityManager: Killing 6573:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
08-18 14:08:32.459  7044  7044 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-18 14:08:32.459  1018  1487 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-18 14:08:32.469  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:32.469  1018  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-18 14:08:32.469  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
08-18 14:08:32.479  7044  7044 D TimaKeyStoreProvider: TimaSignature is unavailable
08-18 14:08:32.479  7044  7044 D ActivityThread: Added TimaKeyStore provider
08-18 14:08:32.479  1018  1212 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-18 14:08:32.479  1018  1212 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-18 14:08:32.489  1018  1212 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:32.489  1018  1212 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-18 14:08:32.489  6999  6999 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-18 14:08:32.489  1018  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-18 14:08:32.489  6999  6999 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-18 14:08:32.499  6999  6999 E SysUtils: ApplicationContext is null in ApplicationStatus
08-18 14:08:32.509  7044  7044 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
08-18 14:08:32.549  1018  4319 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-18 14:08:32.549  1018  4319 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:32.549  1018  4319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-18 14:08:32.549  1018  4319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
08-18 14:08:32.569  1018  1502 D PowerManagerService: [api] handleWakeLockDeath : release WakeLock : PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10081, pid=6573, ws=null) (elapsedTime=2843)
08-18 14:08:32.579  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-18 14:08:32.579  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:32.579  1018  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-18 14:08:32.579  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-18 14:08:32.579  1018  4319 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
08-18 14:08:32.589  1018  4319 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:32.589  1018  4319 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:32.589  1018  4319 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:32.589  1018  4319 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:32.599  6980  6980 W art     : Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 217.911ms
08-18 14:08:32.599  6980  6980 D Mms/TelephonyPermission: start operation mode monitor
08-18 14:08:32.609  7063  7063 E Zygote  : MountEmulatedStorage()
08-18 14:08:32.609  7063  7063 E Zygote  : v2
08-18 14:08:32.609  7063  7063 I libpersona: KNOX_SDCARD checking this for 10152
08-18 14:08:32.609  7063  7063 I libpersona: KNOX_SDCARD not a persona
08-18 14:08:32.609  7063  7063 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-18 14:08:32.609  6980  6980 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-18 14:08:32.609  6980  7062 D Mms/ArtClassLoader: init before art
08-18 14:08:32.609  7063  7063 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-18 14:08:32.619  1018  4319 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7063 uid=10152 gids={50152, 9997} abi=armeabi-v7a
08-18 14:08:32.619  1018  4319 I ActivityManager: Killing 6590:com.sec.esdk.elm/u0a90 (adj 15): empty #21
08-18 14:08:32.619  7063  7063 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-18 14:08:32.629  6980  6980 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-18 14:08:32.629  6980  6980 D Mms/TelephonyPermission: isDefault true
08-18 14:08:32.629  6980  6980 D Mms/MmsApp: onCreate() com.android.mms
08-18 14:08:32.639  7063  7063 D TimaKeyStoreProvider: TimaSignature is unavailable
08-18 14:08:32.639  7063  7063 D ActivityThread: Added TimaKeyStore provider
08-18 14:08:32.649  1018  1043 W ActivityManager: Activity pause timeout for ActivityRecord{446d081 u0 com.test.thalitest/.MainActivity t163}
08-18 14:08:32.659  6790  6834 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
08-18 14:08:32.659  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-18 14:08:32.659  6999  6999 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-18 14:08:32.659  6999  6999 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-18 14:08:32.659  6999  6999 I Adreno-EGL: Build Date: 04/06/15 Mon
08-18 14:08:32.659  6999  6999 I Adreno-EGL: Local Branch: 
08-18 14:08:32.659  6999  6999 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-18 14:08:32.659  6999  6999 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-18 14:08:32.659  6999  6999 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-18 14:08:32.669  1018  1385 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-18 14:08:32.679  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-18 14:08:32.689  6790  6834 I AcmsKeyStoreHelper: Key Store exist
08-18 14:08:32.689  6790  6834 I AcmsKeyStoreHelper: Hence loading the keystore file
08-18 14:08:32.699  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-18 14:08:32.699  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-18 14:08:32.699  1018  1487 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-18 14:08:32.699  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-18 14:08:32.699  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:32.709  1018  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-18 14:08:32.709  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-18 14:08:32.729  7063  7063 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
08-18 14:08:32.729  7063  7063 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
08-18 14:08:32.729  6980  7062 W art     : Verification of void com.android.mms.ui.ConversationListFragment.<init>(android.content.Intent) took 110.972ms
08-18 14:08:32.739  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-18 14:08:32.739  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-18 14:08:32.739  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-18 14:08:32.749  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-18 14:08:32.759  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-18 14:08:32.759  1918  1932 W art     : Suspending all threads took: 8.073ms
08-18 14:08:32.759  7063  7063 I TapandpayWidget:Utils: Clear T&P info.
08-18 14:08:32.759  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-18 14:08:32.759  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-18 14:08:32.759  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-18 14:08:32.769  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-18 14:08:32.769  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-18 14:08:32.769  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-18 14:08:32.769  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-18 14:08:32.769  6980  6980 D Mms/MmsApp: [start]    initCountryIso consume time = 700.135156
08-18 14:08:32.769  6953  6953 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-18 14:08:32.769  1018  1031 D CountryDetector: The first listener is added
08-18 14:08:32.789  6790  6834 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
08-18 14:08:32.789  6790  6834 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-18 14:08:32.789  6790  6834 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-18 14:08:32.789  6790  6834 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-18 14:08:32.789  6790  6834 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-18 14:08:32.789  6790  6834 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
08-18 14:08:32.789  7063  7063 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
08-18 14:08:32.789  6790  6834 D AcmsCore: This is NOT a valid MirrorLink app
08-18 14:08:32.789  6790  6834 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-18 14:08:32.789  1018  1487 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
08-18 14:08:32.789  6790  6834 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-18 14:08:32.789  6790  6834 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-18 14:08:32.789  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:32.789  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:32.789  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:32.789  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:32.799  6980  6980 D Mms/MmsApp: [end]    initCountryIso consume time = 23.802396
08-18 14:08:32.799  6980  6980 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.116302
08-18 14:08:32.799  6775  6840 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 865 ms] updated apps [took 865 ms] 
08-18 14:08:32.799  7105  7105 E Zygote  : MountEmulatedStorage()
08-18 14:08:32.799  7105  7105 E Zygote  : v2
08-18 14:08:32.799  7105  7105 I libpersona: KNOX_SDCARD checking this for 10009
08-18 14:08:32.799  7105  7105 I libpersona: KNOX_SDCARD not a persona
08-18 14:08:32.799  7105  7105 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-18 14:08:32.809  7105  7105 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-18 14:08:32.809  7105  7105 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-18 14:08:32.789  6790  6834 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
08-18 14:08:32.809  1018  1487 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7105 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-18 14:08:32.819  1018  1487 I ActivityManager: Killing 6334:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
08-18 14:08:32.819  1018  1307 I ActivityManager: Killing 6352:com.android.calendar/u0a131 (adj 15): empty #21
08-18 14:08:32.829  6953  6953 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-18 14:08:32.829  6980  6980 D Mms/MmsConfig: before partial update
08-18 14:08:32.829  6790  6790 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-18 14:08:32.829  6790  6790 D AcmsService: Enter onDestroy
08-18 14:08:32.829  6790  6790 I AcmsService: cleanUp(): inside service clean up
08-18 14:08:32.829  6790  6790 D AcmsCore: AcmsCore: inside DeInit
08-18 14:08:32.829  6790  6790 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
08-18 14:08:32.829  6790  6790 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
08-18 14:08:32.829  6790  6790 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-18 14:08:32.829  6790  6790 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-18 14:08:32.829  6790  6790 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
08-18 14:08:32.839  7105  7105 D TimaKeyStoreProvider: TimaSignature is unavailable
08-18 14:08:32.839  6790  6790 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-18 14:08:32.839  6790  6790 D AcmsService: killing acms process
08-18 14:08:32.839  6790  6790 I Process : Sending signal. PID: 6790 SIG: 9
08-18 14:08:32.839  7105  7105 D ActivityThread: Added TimaKeyStore provider
08-18 14:08:32.839  6953  6953 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-18 14:08:32.849  6999  6999 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-18 14:08:32.869  6999  6999 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-18 14:08:32.869  1918  6836 I qtaguid : Untagging socket 103
08-18 14:08:32.879  6999  6999 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-18 14:08:32.889  6980  6980 D Mms/MmsConfig: Load Resize quality : 80
08-18 14:08:32.889  6999  6999 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-18 14:08:32.889  6999  6999 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-18 14:08:32.909  6980  6980 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
08-18 14:08:32.909  6909  6951 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-18 14:08:32.909  6909  6951 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-18 14:08:32.909  6909  6951 I GAv4    :   adb logcat -s GAv4
08-18 14:08:32.919  6980  6980 D EasySignUpManager_1.0.1: isAuth is false
08-18 14:08:32.919  6980  6980 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
08-18 14:08:32.929  1471  1733 D TP/MmsSmsProvider: query,matched:2117, calling pid = 6980
08-18 14:08:32.929  1471  1733 D TP/MmsSmsProvider: match 2117:Elapsed time : 4.168 ms
08-18 14:08:32.939  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-18 14:08:32.939  1918  1918 I ConfigFetchService: fetch service done; releasing wakelock
08-18 14:08:32.949  1018  4319 I ActivityManager: Process ACMS.Process (pid 6790)(adj 0) has died(68,736)
08-18 14:08:32.959  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-18 14:08:32.959  6953  6953 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-18 14:08:32.959  1918  1918 I ConfigFetchService: stopping self
08-18 14:08:32.979  1018  1043 W ProcessCpuTracker: Skipping unknown process pid 6790
08-18 14:08:32.989  6980  6980 D EasySignUpManager_1.0.1: isAuth is false
08-18 14:08:32.989  6980  6980 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
08-18 14:08:32.989  6980  6980 E CscParser: mps_code.dat does not exist
08-18 14:08:32.989  6980  6980 E CscParser: customer_path =/system/csc/customer.xml
08-18 14:08:32.989  6980  6980 E CscParser: fileName + /system/csc/customer.xml
08-18 14:08:32.999  1018  1502 I ActivityManager: Killing 6621:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
08-18 14:08:32.999  6909  6951 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-18 14:08:33.009  6980  6980 E CscParser: mps_code.dat does not exist
08-18 14:08:33.009  6980  6980 E CscParser: customer_path =/system/csc/customer.xml
08-18 14:08:33.009  6980  6980 E CscParser: fileName + /system/csc/customer.xml
08-18 14:08:33.019  6980  6980 D CscParser: getInstance fileName =/system/csc/customer.xml
08-18 14:08:33.019  1018  1307 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-18 14:08:33.019  6980  6980 D Mms/MmsConfig:  enable multiwindow = false
,08-18 14:08:33.039  6980  6980 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-18 14:08:33.039  6980  6980 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-18 14:08:33.049  6980  6980 D Mms/MmsConfig: [end]    init() consume time = 252.642396
,08-18 14:08:33.049  6980  6980 D Mms/Contact: [start]    init() consume time = 1.128125
,08-18 14:08:33.059  6909  6951 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-18 14:08:33.069  1018  1381 I ActivityManager: Killing 6643:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-18 14:08:33.069  6980  6980 D Mms/Contact: [end]    init consume time = 21.887865
,08-18 14:08:33.079  6980  7131 D Mms/DraftCache: [start]    rebuildCache consume time = 10.071614
,08-18 14:08:33.089  6953  6953 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-18 14:08:33.089  1471  1486 D TP/MmsSmsProvider: query,matched:12, calling pid = 6980
,08-18 14:08:33.109  1471  1486 D TP/MmsSmsProvider: match 12:Elapsed time : 14.176 ms
,08-18 14:08:33.109  1471  1733 D TP/MmsSmsProvider: query,matched:13, calling pid = 6980
,08-18 14:08:33.109  1471  1733 D TP/MmsSmsProvider: match 13:Elapsed time : 2.158 ms
,08-18 14:08:33.119  1018  4320 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
08-18 14:08:33.119  1018  4320 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,08-18 14:08:33.119  1018  4320 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:33.119  1018  4320 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-18 14:08:33.119  1018  4320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,08-18 14:08:33.129  6909  6951 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
08-18 14:08:33.129  6953  7133 D Ads     : Skipping gmscore version check
,08-18 14:08:33.129  6980  7131 D Mms/DraftCache: [end]    rebuildCache consume time = 50.184427
,08-18 14:08:33.159  6980  6980 D Mms/MethodReflector: getSubId is called
08-18 14:08:33.159  6980  6980 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,08-18 14:08:33.159  6980  6980 D Mms/MethodReflector: getTelephonyProperty is called,
08-18 14:08:33.159  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-18 14:08:33.159  6980  6980 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-18 14:08:33.159  1018  1030 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4181, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-18 14:08:33.159  6980  6980 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
,08-18 14:08:33.159  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-18 14:08:33.159  6980  6980 D Mms/DownloadManager: auto download without roaming -> true
08-18 14:08:33.159  1018  1030 D BatteryService: stay LED for charging
08-18 14:08:33.159  6980  6980 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-18 14:08:33.159  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
08-18 14:08:33.159  6980  6980 D Mms/MethodReflector: getSubId is called
,08-18 14:08:33.179  6909  7130 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-18 14:08:33.179  6980  6980 D Mms/MethodReflector: getDefaultSmsSubId is called
08-18 14:08:33.179  6980  6980 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
08-18 14:08:33.179  6980  6980 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
08-18 14:08:33.179  6980  6980 D Mms/MethodReflector: getTelephonyProperty is called
08-18 14:08:33.179  6980  6980 D Mms/DownloadManager: roaming -> false (slotId = 1)
08-18 14:08:33.179  6980  6980 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-18 14:08:33.179  6980  6980 D Mms/DownloadManager: auto download without roaming -> true
08-18 14:08:33.179  6980  6980 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-18 14:08:33.179  6980  6980 D Mms/DownloadManager: auto download during roaming secondary -> false
08-18 14:08:33.179  6980  6980 D Mms/DownloadManager: mAutoDownload ------> true
,08-18 14:08:33.189  6953  6953 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-18 14:08:33.189  1018  1018 I MotionRecognitionService: Plugged
08-18 14:08:33.189  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-18 14:08:33.189  6909  6927 W art     : Suspending all threads took: 7.403ms
,08-18 14:08:33.189  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-18 14:08:33.189  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-18 14:08:33.189  1423  1423 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-18 14:08:33.189  1423  1423 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-18 14:08:33.199  6999  6999 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-18 14:08:33.209  3195  3195 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-18 14:08:33.209  3195  3318 D HeadsetStateMachine: Disconnected process message: 10
,08-18 14:08:33.219  1018  1453 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-18 14:08:33.219  1018  1453 W ActivityManager: userId = 0, bbcId = -10000
,08-18 14:08:33.219  6999  6999 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-18 14:08:33.219  1018  1453 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-18 14:08:33.219  1018  1453 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,08-18 14:08:33.229  1173  1173 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-18 14:08:33.229  1173  1173 D SViewCoverView: level :100 plugged : 2
,08-18 14:08:33.239  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-18 14:08:33.239  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-18 14:08:33.239  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-18 14:08:33.239  6999  6999 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-18 14:08:33.239  6999  6999 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-18 14:08:33.249  6999  6999 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-18 14:08:33.249  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-18 14:08:33.259  6999  6999 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-18 14:08:33.259  6999  6999 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-18 14:08:33.299  6980  6980 D ComposerPerformance: 1471522113313 ms / [DONE] Composer constructor
,08-18 14:08:33.299  6980  6980 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,08-18 14:08:33.299  6980  6980 I Mms/ReservationManager: ReservationManager()
08-18 14:08:33.299  6980  6980 I Mms/ReservationManager: resetAfterConnected()
,08-18 14:08:33.299  1471  1486 D TP/MmsSmsProvider: query,matched:7, calling pid = 6980
08-18 14:08:33.309  1471  1486 D TP/MmsSmsProvider: match 7:Elapsed time : 2.231 ms
,08-18 14:08:33.319  6980  7142 D Mms/Conversation: [start]    init() consume time = 183.045886
,08-18 14:08:33.319  1471  1733 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,08-18 14:08:33.319  1471  1733 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-18 14:08:33.319  1471  1733 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,08-18 14:08:33.319  1471  1733 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,08-18 14:08:33.319  6980  7062 D Mms/ArtClassLoader: init [DONE] art
,08-18 14:08:33.319  6980  6980 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,08-18 14:08:33.329  1471  1733 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-18 14:08:33.329  1471  1733 D TP/MmsSmsProvider: need read changed broadcast:false
,08-18 14:08:33.329  6980  7142 D Mms/Conversation: [end]    init consume time = 13.587395
,08-18 14:08:33.329  6980  6980 D Mms/MmsApp: [end]    onCreate() consume time = 1.547865
,08-18 14:08:33.329  6999  7144 D OpenGLRenderer: Render dirty regions requested: true
,08-18 14:08:33.329  6980  7142 D Mms/MessagingNotification: [start]    init() consume time = 3.453542
,08-18 14:08:33.339  1018  1385 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-18 14:08:33.339  1018  1385 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-18 14:08:33.339  1018  1385 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-18 14:08:33.339  6980  7142 D Mms/MessagingNotification: [end]    init consume time = 4.348646
08-18 14:08:33.339  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
08-18 14:08:33.339  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-18 14:08:33.339  6980  7145 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 2.191458
,08-18 14:08:33.339  6999  6999 V ActivityThread: updateVisibility : ActivityRecord{24f66ce4 token=android.os.BinderProxy@2ea49a76 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-18 14:08:33.339  6999  7099 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-18 14:08:33.349  1471  1486 D TP/MmsSmsProvider: query,matched:0, calling pid = 6980
08-18 14:08:33.349  1471  1486 V TP/MmsSmsProvider: getSimpleConversations entered.
,08-18 14:08:33.349  6980  7146 D Mms/Synchronizer: [start]    doSync consume time = 6.229323
,08-18 14:08:33.349  1471  1486 D TP/MmsSmsProvider: match 0:Elapsed time : 2.794 ms
,08-18 14:08:33.349  1471  2483 D TP/MmsSmsProvider: query,matched:400, calling pid = 6980
,08-18 14:08:33.349  6999  6999 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-18 14:08:33.349  6999  6999 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-18 14:08:33.349  1471  1733 D TP/MmsSmsProvider: update, matched:300, calling pid = 6980
08-18 14:08:33.349  1471  1733 V TP/MmsSmsProvider: syncDBData start
,08-18 14:08:33.349  1471  1733 V TP/MmsSmsProvider: syncDBData sms end
,08-18 14:08:33.349  6980  6980 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
,08-18 14:08:33.359  1471  1733 V TP/MmsSmsProvider: syncDBData mms end
08-18 14:08:33.359  1471  1733 V TP/MmsSmsProvider: syncDBData end
,08-18 14:08:33.359  6980  7145 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 9.82875
,08-18 14:08:33.359  6980  6980 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,08-18 14:08:33.359  1018  4320 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,08-18 14:08:33.359  1018  4320 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:33.359  1018  4320 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:33.359  1018  4320 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:33.359  1018  4320 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:33.359  6980  6980 D Mms/MethodReflector: getSubId is called
,08-18 14:08:33.369  6980  6980 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,08-18 14:08:33.369  6980  6980 D Mms/MethodReflector: getTelephonyProperty is called
,08-18 14:08:33.369  6980  6980 D Mms/DownloadManager: roaming -> false (slotId = 0)
,08-18 14:08:33.369  6980  6980 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
,08-18 14:08:33.369  6980  6980 D Mms/DownloadManager: auto download without roaming -> true
08-18 14:08:33.369  6980  6980 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-18 14:08:33.369  6980  6980 D Mms/DownloadManager: mAutoDownload ------> true
,08-18 14:08:33.379   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-18 14:08:33.379  6980  6980 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
08-18 14:08:33.379  7149  7149 E Zygote  : MountEmulatedStorage()
08-18 14:08:33.379  7149  7149 I libpersona: KNOX_SDCARD checking this for 10068
08-18 14:08:33.379  7149  7149 E Zygote  : v2
08-18 14:08:33.379  7149  7149 I libpersona: KNOX_SDCARD not a persona
08-18 14:08:33.379  7149  7149 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-18 14:08:33.389  7149  7149 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-18 14:08:33.389  1018  4320 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7149 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-18 14:08:33.389  1018  4318 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-18 14:08:33.389  7149  7149 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-18 14:08:33.389  1018  4318 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
08-18 14:08:33.389  1018  4318 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:33.389  1018  4318 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-18 14:08:33.389  1018  4318 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,08-18 14:08:33.389  1018  1212 D InputDispatcher: Focus entered window: 6999
,08-18 14:08:33.399  6980  7146 D Mms/Synchronizer: [end]    doSync consume time = 32.589114,
,08-18 14:08:33.399  1018  4317 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast,
08-18 14:08:33.399  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-18 14:08:33.399  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-18 14:08:33.399  6999  6999 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
08-18 14:08:33.399  6999  7144 I OpenGLRenderer: Initialized EGL, version 1.4
08-18 14:08:33.409  1018  4317 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:33.409  1018  4317 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:33.409  1018  4317 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-18 14:08:33.409  1018  4317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:33.409  6999  7144 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-18 14:08:33.409  6999  7144 D OpenGLRenderer: Enabling debug mode 0
,08-18 14:08:33.419  7165  7165 E Zygote  : MountEmulatedStorage(),
08-18 14:08:33.419  7165  7165 E Zygote  : v2
,08-18 14:08:33.419  7165  7165 I libpersona: KNOX_SDCARD checking this for 10042
,08-18 14:08:33.429  7165  7165 I libpersona: KNOX_SDCARD not a persona
,08-18 14:08:33.429  1018  4317 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7165 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a,
,08-18 14:08:33.429  7165  7165 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-18 14:08:33.429  7149  7149 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-18 14:08:33.439  7149  7149 D ActivityThread: Added TimaKeyStore provider
,08-18 14:08:33.439  7165  7165 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-18 14:08:33.439  7165  7165 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
,08-18 14:08:33.449  1018  1212 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-18 14:08:33.449   309   309 I art     : Explicit concurrent mark sweep GC freed 8687(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 615us total 23.027ms
,08-18 14:08:33.459  1018  7173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-18 14:08:33.469  1018  4318 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
,08-18 14:08:33.469   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 614us total 18.271ms
,08-18 14:08:33.469  1173  1173 D PanelView: There is/are notification(s) 
,08-18 14:08:33.469  1018  4318 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:33.469  1018  4318 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:33.469  1018  4318 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:33.469  1018  4318 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:33.469  6999  6999 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-18 14:08:33.479  6999  6999 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2ea49a76 time:96211
,08-18 14:08:33.479  7165  7165 D TimaKeyStoreProvider: TimaSignature is unavailable
08-18 14:08:33.479  7165  7165 D ActivityThread: Added TimaKeyStore provider
,08-18 14:08:33.489   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 17.159ms
,08-18 14:08:33.499  6980  7185 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
08-18 14:08:33.499  6980  7185 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
08-18 14:08:33.509  7188  7188 E Zygote  : MountEmulatedStorage()
08-18 14:08:33.509  7188  7188 E Zygote  : v2,
08-18 14:08:33.509  7188  7188 I libpersona: KNOX_SDCARD checking this for 1000
08-18 14:08:33.509  1018  4318 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7188 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-18 14:08:33.509  7188  7188 I libpersona: KNOX_SDCARD not a persona
,08-18 14:08:33.509  1018  4318 I ActivityManager: Killing 6661:com.qualcomm.timeservice/1000 (adj 15): empty #21,
,08-18 14:08:33.509  7188  7188 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-18 14:08:33.519  7188  7188 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-18 14:08:33.519  7188  7188 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-18 14:08:33.519  1018  1048 I ActivityManager: Displayed Component not be shown by security: +1s372ms (total +1s484ms)
08-18 14:08:33.519  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{446d081 u0 com.test.thalitest/.MainActivity t163} time:96258
08-18 14:08:33.519  1018  1048 W ActivityManager: mDVFSHelper.release()
,08-18 14:08:33.529   259  1162 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-18 14:08:33.529   259   453 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
08-18 14:08:33.529  1018  1385 I ActivityManager: Killing 6683:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
,08-18 14:08:33.529  7149  7149 D BadgeProvider: onCreate
,08-18 14:08:33.529  7149  7149 D BadgeProvider: DatabaseHelper
,08-18 14:08:33.539  1018  1385 I ActivityManager: Killing 6610:com.android.providers.calendar/u0a37 (adj 15): empty #22
,08-18 14:08:33.549  7165  7165 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-18 14:08:33.549  7165  7165 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-18 14:08:33.549  7165  7165 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-18 14:08:33.549  7188  7188 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-18 14:08:33.549  7188  7188 D ActivityThread: Added TimaKeyStore provider
,08-18 14:08:33.569  6980  7142 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-18 14:08:33.569  1471  1486 D TP/SmsProvider: query,matched:26, calling pid = 6980
,08-18 14:08:33.569  1471  1486 D TP/SmsProvider: match 26:Elapsed time : 1.146 ms
,08-18 14:08:33.579  1471  2483 D TP/MmsSmsProvider: query,matched:6, calling pid = 6980
,08-18 14:08:33.579  1471  2483 D TP/MmsSmsProvider: match 6:Elapsed time : 0.916 ms
,08-18 14:08:33.599  1881  1881 I SamsungIME: getCurrentCandidateView
,08-18 14:08:33.669  7188  7188 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
,08-18 14:08:33.679  7188  7188 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,08-18 14:08:33.729  6909  7175 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-18 14:08:33.729  6909  7175 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-18 14:08:33.729  1018  1031 I art     : Explicit concurrent mark sweep GC freed 18732(1006KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.585ms total 137.475ms
,08-18 14:08:33.729  1018  1487 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
08-18 14:08:33.729  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
,08-18 14:08:33.729  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
,08-18 14:08:33.729  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-18 14:08:33.729  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,08-18 14:08:33.739  1018  1453 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,08-18 14:08:33.739  1018  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:33.739  1018  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:33.739  1018  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:33.739  1018  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:33.749  7188  7188 I FilterInstaller: FilterPackageService : ACTION_CHANGED
,08-18 14:08:33.749  7207  7207 E Zygote  : MountEmulatedStorage(),
08-18 14:08:33.749  7207  7207 E Zygote  : v2
08-18 14:08:33.749  7207  7207 I libpersona: KNOX_SDCARD checking this for 10023
08-18 14:08:33.749  7207  7207 I libpersona: KNOX_SDCARD not a persona
,08-18 14:08:33.749  7207  7207 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-18 14:08:33.759  7207  7207 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-18 14:08:33.759  7207  7207 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-18 14:08:33.759  1018  1453 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7207 uid=10023 gids={50023, 9997} abi=armeabi-v7a
08-18 14:08:33.759  7188  7206 E FilterInstaller: installFilters
,08-18 14:08:33.769  7188  7206 E FilterInstaller: There is no requred permission
08-18 14:08:33.769  1018  1031 I ActivityManager: Killing 6704:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
,08-18 14:08:33.799  7207  7207 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-18 14:08:33.799  7207  7207 D ActivityThread: Added TimaKeyStore provider
,08-18 14:08:33.809  6999  6999 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6999
,08-18 14:08:33.809  1018  1031 I ActivityManager: Killing 5045:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
,08-18 14:08:33.819  6909  7175 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-18 14:08:33.829  7165  7165 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,08-18 14:08:33.829  1018  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
08-18 14:08:33.829  1018  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-18 14:08:33.829  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:33.829  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:33.829  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:33.829  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:33.849  7223  7223 E Zygote  : MountEmulatedStorage(),
08-18 14:08:33.849  7223  7223 E Zygote  : v2
08-18 14:08:33.849  7223  7223 I libpersona: KNOX_SDCARD checking this for 10003
08-18 14:08:33.849  7223  7223 I libpersona: KNOX_SDCARD not a persona
,08-18 14:08:33.849  7223  7223 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-18 14:08:33.849  1018  1058 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7223 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-18 14:08:33.849  1018  1502 I splitIntent: Queue : backgroundsplit_0 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-18 14:08:33.849  7223  7223 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-18 14:08:33.849  1018  1502 I ActivityManager: Killing 6740:com.sec.spp.push/u0a32 (adj 15): empty #21
,08-18 14:08:33.849  7223  7223 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-18 14:08:33.849  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
08-18 14:08:33.849  1918  4311 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
,08-18 14:08:33.859  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:33.859  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:33.859  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-18 14:08:33.859  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:33.859  1881  1881 D SamsungIME: Dismiss ExpandCandiate
,08-18 14:08:33.879  7238  7238 E Zygote  : MountEmulatedStorage()
08-18 14:08:33.879  7238  7238 E Zygote  : v2
08-18 14:08:33.879  7238  7238 I libpersona: KNOX_SDCARD checking this for 10130
08-18 14:08:33.879  7238  7238 I libpersona: KNOX_SDCARD not a persona
08-18 14:08:33.879  7238  7238 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-18 14:08:33.879  7238  7238 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-18 14:08:33.879  7238  7238 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-18 14:08:33.879  1018  1043 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7238 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,08-18 14:08:33.899  7223  7223 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-18 14:08:33.899  7223  7223 D ActivityThread: Added TimaKeyStore provider
,08-18 14:08:33.899  7238  7238 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-18 14:08:33.909  7238  7238 D ActivityThread: Added TimaKeyStore provider
,08-18 14:08:33.919  7207  7207 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,08-18 14:08:33.949  6980  7142 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-18 14:08:33.949   285   285 E installd: system dir 0 : /system/app/
08-18 14:08:33.949   285   285 E installd: system dir 1 : /system/priv-app/
08-18 14:08:33.949   285   285 E installd: system dir 2 : /vendor/app/
08-18 14:08:33.949   285   285 E installd: system dir 3 : /oem/app/
,08-18 14:08:33.959  7238  7238 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-18 14:08:33.959  7238  7238 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-18 14:08:33.979  6909  7175 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-18 14:08:33.979  6909  7175 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2837ce41: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-18 14:08:33.979  6909  7175 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-18 14:08:33.979  7207  7207 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,08-18 14:08:33.989  1018  1058 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,08-18 14:08:33.999  7207  7207 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,08-18 14:08:33.999  7207  7207 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-18 14:08:33.999  7207  7207 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,08-18 14:08:33.999  7207  7207 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,08-18 14:08:33.999  7207  7207 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-18 14:08:33.999  7207  7207 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-18 14:08:33.999  7207  7207 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-18 14:08:34.009  7207  7207 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-18 14:08:34.009  7207  7207 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-18 14:08:34.009  7207  7207 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-18 14:08:34.009  7207  7207 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-18 14:08:34.009  7207  7207 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-18 14:08:34.019  1918  4311 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-18 14:08:34.029  1018  1453 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,08-18 14:08:34.029  1018  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:34.029  1018  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:34.029  1018  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:34.029  1018  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:34.039  7259  7259 E Zygote  : MountEmulatedStorage(),
,08-18 14:08:34.049  7259  7259 E Zygote  : v2
08-18 14:08:34.049  7259  7259 I libpersona: KNOX_SDCARD checking this for 10131
08-18 14:08:34.049  7259  7259 I libpersona: KNOX_SDCARD not a persona
,08-18 14:08:34.049  7259  7259 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-18 14:08:34.049  7259  7259 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-18 14:08:34.049  1018  1453 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7259 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-18 14:08:34.049  7259  7259 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-18 14:08:34.059  1018  4319 I ActivityManager: Killing 6749:com.samsung.helphub/1000 (adj 15): empty #21
,08-18 14:08:34.069  6999  6999 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-18 14:08:34.089  7259  7259 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-18 14:08:34.089  7259  7259 D ActivityThread: Added TimaKeyStore provider
,08-18 14:08:34.099  1881  1881 I SamsungIME: getDebugLevel  : 0x4f4c
,08-18 14:08:34.109  1918  4311 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
,08-18 14:08:34.119  7259  7259 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-18 14:08:34.119  7259  7259 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-18 14:08:34.119  7259  7259 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-18 14:08:34.129  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-18 14:08:34.129  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:34.129  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-18 14:08:34.129  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-18 14:08:34.139  1881  1881 I SamsungIME: getDebugLevel  : 0x4f4c
,08-18 14:08:34.149  1836  1844 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-18 14:08:34.159  1881  1881 I SamsungIME: KeybaordView init() : load resources
,08-18 14:08:34.169  6999  7203 D jxcore_app_log: JniHelper::setJavaVM(0xb77602b0), pthread_self() = -1211187232
,08-18 14:08:34.169  1018  4320 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-18 14:08:34.169  1018  4320 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-18 14:08:34.169  1018  4320 W ActivityManager: userId = 0, bbcId = -10000
,08-18 14:08:34.169  1018  4320 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-18 14:08:34.169  1018  4320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-18 14:08:34.169  6999  7203 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-18 14:08:34.169  6999  7203 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-18 14:08:34.169  6999  7203 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-18 14:08:34.169  6999  7203 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-18 14:08:34.169  6999  7203 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-18 14:08:34.179  6999  7203 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@113d938b added. We now have 1 listener(s)
,08-18 14:08:34.189  1881  1881 I SamsungIME: getCurrentKeyboard
08-18 14:08:34.189  6999  7203 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
08-18 14:08:34.189  1881  1881 I SamsungIME: getTextKeyboard
,08-18 14:08:34.189  6999  7203 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-18 14:08:34.189  6999  7203 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-18 14:08:34.189  6999  7203 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-18 14:08:34.189  1018  1307 I ActivityManager: Killing 6717:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,08-18 14:08:34.189  6999  7203 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-18 14:08:34.189  6999  7203 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-18 14:08:34.189  6999  7203 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-18 14:08:34.189  6999  7203 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-18 14:08:34.189  6999  7203 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-18 14:08:34.189  6999  7203 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-18 14:08:34.189  6999  7203 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-18 14:08:34.189  6999  7203 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-18 14:08:34.189  6999  7203 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-18 14:08:34.189  6999  7203 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-18 14:08:34.189  6999  7203 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-18 14:08:34.189  6999  7203 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-18 14:08:34.189  6999  7203 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-18 14:08:34.189  6999  7203 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-18 14:08:34.189  6999  7203 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ac68d26 added. We now have 1 listener(s)
,08-18 14:08:34.189  6999  7203 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 14:08:34.199  1018  1453 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-18 14:08:34.199  1018  1453 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-18 14:08:34.199  1018  1453 W ActivityManager: userId = 0, bbcId = -10000
,08-18 14:08:34.199  1018  1453 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-18 14:08:34.199  1018  1453 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
08-18 14:08:34.199  6999  7203 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-18 14:08:34.199  6999  7203 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-18 14:08:34.199  6999  7203 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-18 14:08:34.199  6999  7203 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-18 14:08:34.199  6999  7203 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-18 14:08:34.209  6999  7203 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 14:08:34.209  1881  1881 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-18 14:08:34.209  6999  7203 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
08-18 14:08:34.209  1018  1307 I ActivityManager: Killing 6805:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,08-18 14:08:34.219  6999  7203 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-18 14:08:34.219  6999  7203 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 14:08:34.219  6999  7203 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:08:34.219  6999  7203 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:08:34.219  6999  7203 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:08:34.219  6999  7203 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:08:34.219  6999  7203 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:08:34.219  6999  7203 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:08:34.219  6999  7203 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 14:08:34.219  6999  7203 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-18 14:08:34.219  6999  7203 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 14:08:34.219  6999  6999 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:08:34.229  6999  7203 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-18 14:08:34.229  6999  6999 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:08:34.259  6999  6999 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-18 14:08:34.469   274   274 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7f8c7c8
08-18 14:08:34.469   274   274 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-18 14:08:34.469   274   274 I rmt_storage: wakelock acquired: 1, error no: 42
08-18 14:08:34.469   274   319 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1208432504)
,08-18 14:08:34.519   274   319 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-18 14:08:34.519   274   319 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-18 14:08:34.519   274   319 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1208432504) wakelock released: 1, error no: 0
08-18 14:08:34.519   274   319 I rmt_storage: 
,08-18 14:08:34.519   274   274 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7f8c7c8
,08-18 14:08:34.859  6999  7281 W jxcore-log: Initializing JXcore engine
08-18 14:08:34.859  6999  7281 W jxcore-log: JXcore engine is ready
,08-18 14:08:34.919  2001  2001 E audit   : type=1400 msg=audit(1471522114.919:205): avc:  denied  { ioctl } for  pid=7281 comm="Thread-1320" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-18 14:08:34.919  2001  2001 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-18 14:08:34.919  2001  2001 E audit   : type=1300 msg=audit(1471522114.919:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e6fd8f8 items=0 ppid=309 ppcomm=main pid=7281 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1320" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-18 14:08:34.919  2001  2001 E audit   : type=1320 msg=audit(1471522114.919:205): 
,08-18 14:08:34.939  6999  7281 W jxcore-log: Starting JXcore engine
,08-18 14:08:35.029  1018  3358 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-18 14:08:35.039  6999  7281 W jxcore-log: Platform android
08-18 14:08:35.039  6999  7281 W jxcore-log: 
,08-18 14:08:35.039  6999  7281 W jxcore-log: Process ARCH arm
08-18 14:08:35.039  6999  7281 W jxcore-log: 
,08-18 14:08:35.239  6999  7281 I jxcore-log: JXcore Cordova bridge is ready!
08-18 14:08:35.239  6999  7281 I jxcore-log: 
,08-18 14:08:35.239  6999  7281 W jxcore-log: JXcore engine is started
,08-18 14:08:35.259  6999  7203 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-18 14:08:35.259  6999  6999 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41),
,08-18 14:08:35.259   289   289 E SMD     : DCD OFF
,08-18 14:08:35.269  6999  7281 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
08-18 14:08:35.269  6999  7281 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,08-18 14:08:35.289  6999  6999 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,08-18 14:08:35.289  6999  6999 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,08-18 14:08:35.289  1018  4319 D FocusedStackFrame: Set to : 0
08-18 14:08:35.289  1018  4319 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-18 14:08:35.289  1018  4319 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-18 14:08:35.299  1018  4319 D InputDispatcher: Focused application set to: xxxx
08-18 14:08:35.299  1018  4319 D InputDispatcher: Focus left window: 6999
,08-18 14:08:35.299  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-18 14:08:35.299  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-18 14:08:35.309  1018  4319 I ActivityManager: Killing 6775:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-18 14:08:35.309  6999  7203 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 24ms. Plugin should use CordovaInterface.getThreadPool().
,08-18 14:08:35.309  6999  6999 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-18 14:08:35.319  6999  6999 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,08-18 14:08:35.319  6999  6999 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:08:35.319  6999  6999 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:35.319  6999  6999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:35.319  6999  6999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 14:08:35.319  6999  6999 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@113d938b removed from the list
08-18 14:08:35.319  6999  6999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:35.319  6999  6999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ac68d26 removed from the list
08-18 14:08:35.319  6999  6999 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:08:35.319  6999  6999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,08-18 14:08:35.319  6999  6999 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-18 14:08:35.339  6980  6980 I Mms/MmsApp:  start initViewCache mms
,08-18 14:08:35.339   259  1162 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,08-18 14:08:35.339   259   453 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,08-18 14:08:35.339  6980  6980 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1952.687135
,08-18 14:08:35.339  6980  6980 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-18 14:08:35.349  1018  4319 W ActivityManager: mDVFSHelper.acquire()
,08-18 14:08:35.359  1018  4319 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-18 14:08:35.389  1495  1495 D Launcher: onRestart, Launcher: 414366960
,08-18 14:08:35.389  1495  1495 D Launcher: onStart, Launcher: 414366960
,08-18 14:08:35.389  1495  1495 D Launcher.HomeView: onStart
,08-18 14:08:35.389  1495  1495 D Launcher: onResume, Launcher: 414366960
,08-18 14:08:35.389  1018  1385 D SettingsProvider: name = kids_home_mode
,08-18 14:08:35.389  1018  1385 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-18 14:08:35.389  1018  1385 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-18 14:08:35.389  1018  1385 D SettingsProvider: selectionArgs: false
,08-18 14:08:35.389  1018  1385 D SettingsProvider: selectionArgs: 10006
08-18 14:08:35.389  1018  1385 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-18 14:08:35.389  1018  1385 D SettingsProvider: ret = -1
,08-18 14:08:35.389  1495  1495 D Launcher.HomeView: onResume
,08-18 14:08:35.399  1495  1495 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-18 14:08:35.409  1495  1495 D MenuAppsGridFragment: onResume
,08-18 14:08:35.409  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:35.409  1495  1495 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-18 14:08:35.409  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-18 14:08:35.409  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
08-18 14:08:35.409  1495  1495 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-18 14:08:35.409  1018  1488 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
08-18 14:08:35.409  1018  1488 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,08-18 14:08:35.409  1018  1488 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:35.409  1018  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-18 14:08:35.409  1018  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
08-18 14:08:35.409  1018  1488 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,08-18 14:08:35.419  1018  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:35.419  1018  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:35.419  1018  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:35.419  1018  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:35.429  7285  7285 E Zygote  : MountEmulatedStorage()
,08-18 14:08:35.429  7285  7285 E Zygote  : v2
08-18 14:08:35.429  7285  7285 I libpersona: KNOX_SDCARD checking this for 10039
08-18 14:08:35.429  7285  7285 I libpersona: KNOX_SDCARD not a persona
,08-18 14:08:35.429  7285  7285 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-18 14:08:35.439  7285  7285 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-18 14:08:35.439  7285  7285 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-18 14:08:35.439  1018  1488 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=7285 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-18 14:08:35.449  1018  1487 D ActivityManager: handle home activity for 0
,08-18 14:08:35.449  1018  1487 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-18 14:08:35.449  1018  1487 D KnoxTimeoutHandler: post home show event for user 0
08-18 14:08:35.449  1018  1487 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-18 14:08:35.449  1018  1487 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-18 14:08:35.449  1018  1487 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-18 14:08:35.449  1018  1018 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-18 14:08:35.449  1018  1018 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-18 14:08:35.449  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-18 14:08:35.449  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,08-18 14:08:35.459  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:35.459  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-18 14:08:35.459  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
08-18 14:08:35.459  1495  1495 D Launcher.HomeView: onPause
08-18 14:08:35.459  1495  1495 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-18 14:08:35.459  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:35.459  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
08-18 14:08:35.459  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-18 14:08:35.459  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
,08-18 14:08:35.459  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:35.459  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:35.459  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:35.459  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:35.469  7285  7285 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-18 14:08:35.469  7285  7285 D ActivityThread: Added TimaKeyStore provider
,08-18 14:08:35.479  7300  7300 E Zygote  : MountEmulatedStorage()
08-18 14:08:35.479  1018  1043 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=7300 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
08-18 14:08:35.479  7300  7300 E Zygote  : v2
08-18 14:08:35.479  7300  7300 I libpersona: KNOX_SDCARD checking this for 10089
08-18 14:08:35.479  7300  7300 I libpersona: KNOX_SDCARD not a persona
,08-18 14:08:35.489  7300  7300 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-18 14:08:35.489  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:35.489  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-18 14:08:35.489  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
08-18 14:08:35.489  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,08-18 14:08:35.489  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-18 14:08:35.499  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:35.499  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:35.499  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:35.499  7300  7300 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-18 14:08:35.499  7300  7300 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-18 14:08:35.509  7314  7314 E Zygote  : MountEmulatedStorage()
08-18 14:08:35.509  7314  7314 I libpersona: KNOX_SDCARD checking this for 10139
08-18 14:08:35.509  7314  7314 E Zygote  : v2
08-18 14:08:35.509  7314  7314 I libpersona: KNOX_SDCARD not a persona
,08-18 14:08:35.509  7314  7314 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-18 14:08:35.509  7314  7314 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-18 14:08:35.509  1018  1043 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=7314 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
08-18 14:08:35.519  7314  7314 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-18 14:08:35.529  7300  7300 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-18 14:08:35.529  7300  7300 D ActivityThread: Added TimaKeyStore provider
,08-18 14:08:35.529   259   259 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
08-18 14:08:35.529  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-18 14:08:35.539  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-18 14:08:35.539  1018  1212 D InputDispatcher: Focus entered window: 1495
,08-18 14:08:35.549  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-18 14:08:35.549  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-18 14:08:35.549  1495  1495 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-18 14:08:35.549  7314  7314 D TimaKeyStoreProvider: TimaSignature is unavailable
08-18 14:08:35.549  7314  7314 D ActivityThread: Added TimaKeyStore provider
08-18 14:08:35.549  7300  7300 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-18 14:08:35.549  1495  1495 D Launcher.HomeView: onStop
08-18 14:08:35.549  1495  1495 V ActivityThread: updateVisibility : ActivityRecord{260b177c token=android.os.BinderProxy@23a4b0f4 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-18 14:08:35.559  1018  1030 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-18 14:08:35.559  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:35.559  1018  1487 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1495, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
08-18 14:08:35.559  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-18 14:08:35.559  1018  7331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-18 14:08:35.559  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,08-18 14:08:35.559  7300  7300 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,08-18 14:08:35.569  6999  6999 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-18 14:08:35.569  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:35.569  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-18 14:08:35.569  1881  1881 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
08-18 14:08:35.569  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,08-18 14:08:35.569  7282  7282 D AndroidRuntime: 
08-18 14:08:35.569  7282  7282 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-18 14:08:35.569  1173  1173 D PanelView: There is/are notification(s) 
,08-18 14:08:35.569  7282  7282 D AndroidRuntime: CheckJNI is OFF
08-18 14:08:35.569  7282  7282 D AndroidRuntime: readGMSProperty: start
08-18 14:08:35.569  7282  7282 D AndroidRuntime: readGMSProperty: already setted!!
08-18 14:08:35.569  7282  7282 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-18 14:08:35.569  7282  7282 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-18 14:08:35.569  7282  7282 D AndroidRuntime: readGMSProperty: end
08-18 14:08:35.569  7282  7282 D AndroidRuntime: addProductProperty: start
,08-18 14:08:35.579  6980  6980 D AbsListView: Get MotionRecognitionManager
,08-18 14:08:35.579  7285  7285 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-18 14:08:35.579  1018  1502 D MotionRecognitionService:  ssp status : false
08-18 14:08:35.579  7285  7285 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-18 14:08:35.579  7285  7285 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-18 14:08:35.579  7285  7285 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-18 14:08:35.579  7285  7285 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-18 14:08:35.579  7285  7285 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-18 14:08:35.579  7285  7285 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-18 14:08:35.589  2617  2617 D Recents_RecreateReceiver: onReceive by home
,08-18 14:08:35.589  6980  6980 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 250.529687
08-18 14:08:35.599  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:35.599  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-18 14:08:35.599  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,08-18 14:08:35.599  1018  1487 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
,08-18 14:08:35.599  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:35.599  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:35.599  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:35.599  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:35.609  1495  1495 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@23a4b0f4 time:98344
,08-18 14:08:35.619  7333  7333 E Zygote  : MountEmulatedStorage(),
08-18 14:08:35.619  7333  7333 I libpersona: KNOX_SDCARD checking this for 10084
08-18 14:08:35.619  7333  7333 E Zygote  : v2,
,08-18 14:08:35.619  7333  7333 I libpersona: KNOX_SDCARD not a persona
08-18 14:08:35.619  7333  7333 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-18 14:08:35.629  1018  1487 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=7333 uid=10084 gids={50084, 9997} abi=armeabi-v7a
08-18 14:08:35.629  7314  7314 V TaskCloserActivity: TaskCloserActivity enter()
08-18 14:08:35.629  7333  7333 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-18 14:08:35.629  7333  7333 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
08-18 14:08:35.639  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
08-18 14:08:35.639  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{869828 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t162} time:98378
08-18 14:08:35.639  1018  1048 W ActivityManager: mDVFSHelper.release()
,08-18 14:08:35.659  7314  7314 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
08-18 14:08:35.659  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
08-18 14:08:35.659  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:35.659  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:35.659  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-18 14:08:35.659  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:35.659  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
08-18 14:08:35.659  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:35.659  7333  7333 D TimaKeyStoreProvider: TimaSignature is unavailable
08-18 14:08:35.659  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:35.659  7333  7333 D ActivityThread: Added TimaKeyStore provider
,08-18 14:08:35.679  1018  1031 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=7357 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,08-18 14:08:35.679  1018  1031 I ActivityManager: Killing 6214:com.samsung.android.sm/1000 (adj 15): empty #21
,08-18 14:08:35.679  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:35.679  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-18 14:08:35.679  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
08-18 14:08:35.679  7357  7357 E Zygote  : MountEmulatedStorage()
08-18 14:08:35.679  7357  7357 I libpersona: KNOX_SDCARD checking this for 10135
08-18 14:08:35.679  7357  7357 E Zygote  : v2
08-18 14:08:35.679  7357  7357 I libpersona: KNOX_SDCARD not a persona
,08-18 14:08:35.679  7357  7357 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-18 14:08:35.679  1018  1031 I ActivityManager: Killing 6845:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,08-18 14:08:35.689  7357  7357 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-18 14:08:35.689  7357  7357 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-18 14:08:35.709  7357  7357 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-18 14:08:35.709  7357  7357 D ActivityThread: Added TimaKeyStore provider
,08-18 14:08:35.729  6980  6980 D Mms/BubbleViewCache: fillCache bubble = 1
08-18 14:08:35.729  7333  7333 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-18 14:08:35.729  7357  7357 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
08-18 14:08:35.729  7357  7357 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-18 14:08:35.729  7357  7357 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,08-18 14:08:35.729  7357  7357 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
08-18 14:08:35.729  7357  7357 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-18 14:08:35.739  7282  7282 E AffinityControl: AffinityControl: registerfunction enter
,08-18 14:08:35.749  1018  1487 D PersonaManager: isKioskContainerExistOnDevice
,08-18 14:08:35.759  1018  1212 I ActivityManager: Killing 6856:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,08-18 14:08:35.769  7282  7282 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-18 14:08:35.789  1018  1453 I ActivityManager: Killing 6888:com.sec.pcw.device/1000 (adj 15): empty #21
,08-18 14:08:35.799  1018  4318 D PackageManager: START PACKAGE DELETE: observer{34651407}
08-18 14:08:35.799  1018  4318 D PackageManager: pkg{<packageName>}
08-18 14:08:35.799  1018  4318 D PackageManager: user{0}
08-18 14:08:35.799  1018  4318 D PackageManager: caller{2000}
08-18 14:08:35.799  1018  4318 D PackageManager: flags{2}
,08-18 14:08:35.799  1018  4318 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-18 14:08:35.799  1018  4318 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-18 14:08:35.799  1018  4318 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-18 14:08:35.799  1018  4318 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-18 14:08:35.799  1018  4318 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-18 14:08:35.799  1018  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-18 14:08:35.799  1018  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,08-18 14:08:35.799  1018  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-18 14:08:35.799  1018  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
08-18 14:08:35.799  1018  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-18 14:08:35.809  1018  1058 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,08-18 14:08:35.809  1018  1043 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,08-18 14:08:35.809  1018  1043 I ActivityManager: Killing 6999:com.test.thalitest/u0a170 (adj 15): stop com.test.thalitest cause uninstall pkg
,08-18 14:08:35.829  7285  7285 D NearbySource: Nearby Source Create!
,08-18 14:08:35.829  7285  7285 D NearbyContext: Nearby Context Create!
,08-18 14:08:35.869   258   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-18 14:08:35.869   258   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-18 14:08:35.869  7285  7285 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache,
08-18 14:08:35.879  7285  7285 D SLinkSource: Samsung link source created
,08-18 14:08:35.959  1018  1058 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-18 14:08:35.989  1018  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-18 14:08:36.019  1018  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-18 14:08:36.029  1018  1212 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-18 14:08:36.039  1881  1881 E SamsungIME: mOCRHelper is null
,08-18 14:08:36.039  2804  2804 I art     : Explicit concurrent mark sweep GC freed 24425(1323KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 1.170ms total 60.472ms
,08-18 14:08:36.049  1740  1986 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-18 14:08:36.069  1018  1018 D RCPManagerService: PackageReceiver onReceive()
,08-18 14:08:36.069  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-18 14:08:36.069  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-18 14:08:36.069  1018  1018 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-18 14:08:36.069  1018  1018 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-18 14:08:36.079  1018  1018 I OTPFW   : ProvisionData::getAllEntries Enter
,08-18 14:08:36.089  1457  1457 D PersonaManager: isKioskContainerExistOnDevice
,08-18 14:08:36.099  1018  1018 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-18 14:08:36.119  1457  1457 D RegisteredServicesCache: empty dynamic service
,08-18 14:08:36.119  1018  1124 V NetworkStats: removeUidsLocked() for UIDs [10170]
,08-18 14:08:36.119  1018  1124 V NetworkStats: performPollLocked(flags=0x3)
08-18 14:08:36.119  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-18 14:08:36.119  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-18 14:08:36.119  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-18 14:08:36.129  1018  4319 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-18 14:08:36.129  1018  1124 V NetworkStats: performPollLocked() took 14ms
08-18 14:08:36.129  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-18 14:08:36.139  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-18 14:08:36.139  7285  7285 D GalleryCacheReady: Receive : home resume
,08-18 14:08:36.139  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-18 14:08:36.139  1018  1453 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:36.139  1018  1453 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-18 14:08:36.139  1018  1453 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,08-18 14:08:36.149  6980  6980 D Mms/UIEventReceiver: ui event
,08-18 14:08:36.159  1018  4319 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,08-18 14:08:36.159  1018  4319 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:36.159  1018  4319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-18 14:08:36.159  1018  4319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,08-18 14:08:36.159  1018  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
08-18 14:08:36.159  1018  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-18 14:08:36.169  1018  1042 W TextServicesManagerService: no available spell checker services found
,08-18 14:08:36.169  7314  7314 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,08-18 14:08:36.179  7285  7376 D ContactProvider: getAllContactInfoList Start
08-18 14:08:36.179  1018  1381 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-18 14:08:36.179  1018  1381 D SecContentProvider2: mCursor = null
,08-18 14:08:36.179  1457  1457 D RegisteredComponentCache: Collect Tech packages for Knox
,08-18 14:08:36.179  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-18 14:08:36.179  1457  1457 D PersonaManager: isKioskContainerExistOnDevice
,08-18 14:08:36.209  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-18 14:08:36.209  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-18 14:08:36.209  2788  2788 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Aug 18 14:08:36 GMT+02:00 2016
,08-18 14:08:36.209  1018  1487 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-18 14:08:36.209  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-18 14:08:36.209  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:36.209  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-18 14:08:36.209  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-18 14:08:36.219  2788  2788 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-18 14:08:36.219  1018  4318 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
08-18 14:08:36.219  1018  4318 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-18 14:08:36.219  1018  4318 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-18 14:08:36.229  1018  4318 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.229  1018  4318 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.229  1018  4318 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.229  1018  4318 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:36.229  2788  2788 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-18 14:08:36.229  2788  2788 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-18 14:08:36.229  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-18 14:08:36.239  7379  7379 E Zygote  : MountEmulatedStorage()
08-18 14:08:36.239  7379  7379 E Zygote  : v2
,08-18 14:08:36.239  7379  7379 I libpersona: KNOX_SDCARD checking this for 10090
08-18 14:08:36.239  7379  7379 I libpersona: KNOX_SDCARD not a persona
08-18 14:08:36.239  7379  7379 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-18 14:08:36.239  1018  4318 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7379 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,08-18 14:08:36.239  2788  2788 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-18 14:08:36.249  7379  7379 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-18 14:08:36.249  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
08-18 14:08:36.249  7379  7379 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-18 14:08:36.259  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-18 14:08:36.259  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-18 14:08:36.259  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-18 14:08:36.259  1018  1018 V EnterpriseBillingPolicy: uID is 10170
08-18 14:08:36.259  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-18 14:08:36.259  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-18 14:08:36.259  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-18 14:08:36.259  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-18 14:08:36.259  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-18 14:08:36.259  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-18 14:08:36.259  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-18 14:08:36.269   309   309 I art     : Explicit concurrent mark sweep GC freed 8677(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 934us total 24.263ms
,08-18 14:08:36.269  7379  7379 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-18 14:08:36.269  7379  7379 D ActivityThread: Added TimaKeyStore provider
,08-18 14:08:36.269  2788  7378 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-18 14:08:36.279  2788  7378 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-18 14:08:36.279  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:36.279  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:36.279  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:36.279  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:36.279   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 18.024ms
,08-18 14:08:36.299  1018  1058 I art     : Explicit concurrent mark sweep GC freed 32899(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/34MB, paused 4.196ms total 216.775ms
,08-18 14:08:36.299  2788  7378 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-18 14:08:36.299  2788  7378 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-18 14:08:36.299   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 606us total 16.727ms
,08-18 14:08:36.309  7394  7394 E Zygote  : MountEmulatedStorage()
,08-18 14:08:36.309  7394  7394 E Zygote  : v2
08-18 14:08:36.309  7394  7394 I libpersona: KNOX_SDCARD checking this for 10032
08-18 14:08:36.309  7394  7394 I libpersona: KNOX_SDCARD not a persona
08-18 14:08:36.319  7394  7394 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-18 14:08:36.319  1018  1043 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=7394 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-18 14:08:36.319  7394  7394 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-18 14:08:36.319  7394  7394 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-18 14:08:36.329  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,08-18 14:08:36.329  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.329  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.329  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.329  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:36.339  7403  7403 E Zygote  : MountEmulatedStorage()
,08-18 14:08:36.339  7403  7403 I libpersona: KNOX_SDCARD checking this for 10052
08-18 14:08:36.339  7403  7403 E Zygote  : v2
08-18 14:08:36.339  7403  7403 I libpersona: KNOX_SDCARD not a persona
,08-18 14:08:36.349  7403  7403 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-18 14:08:36.349  1018  1043 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7403 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
08-18 14:08:36.349  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
08-18 14:08:36.349  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.349  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-18 14:08:36.349  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.349  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:36.349  7403  7403 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-18 14:08:36.359  7403  7403 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-18 14:08:36.369  7394  7394 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-18 14:08:36.369  7394  7394 D ActivityThread: Added TimaKeyStore provider
,08-18 14:08:36.379  7419  7419 E Zygote  : MountEmulatedStorage()
08-18 14:08:36.379  7419  7419 E Zygote  : v2
08-18 14:08:36.379  7419  7419 I libpersona: KNOX_SDCARD checking this for 10098
08-18 14:08:36.379  7419  7419 I libpersona: KNOX_SDCARD not a persona
,08-18 14:08:36.379  7419  7419 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-18 14:08:36.379  7419  7419 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-18 14:08:36.379  7419  7419 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-18 14:08:36.379  2788  7378 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-18 14:08:36.389  1018  1043 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7419 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-18 14:08:36.389  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-18 14:08:36.389  1018  1018 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,08-18 14:08:36.389  1018  3345 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-18 14:08:36.389  1018  1163 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,08-18 14:08:36.399  7403  7403 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-18 14:08:36.399  7403  7403 D ActivityThread: Added TimaKeyStore provider
,08-18 14:08:36.409  7419  7419 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-18 14:08:36.419  7419  7419 D ActivityThread: Added TimaKeyStore provider
,08-18 14:08:36.419  2788  7378 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
08-18 14:08:36.419  7285  7376 D ContactProvider: getAllContactInfoList End
,08-18 14:08:36.419  1018  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-18 14:08:36.419  7285  7376 I syncContacts: thread: 1358, sync time = 416
,08-18 14:08:36.419  2788  7378 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-18 14:08:36.429  2788  2788 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-18 14:08:36.439  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-18 14:08:36.439  1018  1018 V EnterpriseBillingPolicy: uID is 10170
08-18 14:08:36.439  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-18 14:08:36.439  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-18 14:08:36.439  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-18 14:08:36.439  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-18 14:08:36.439  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-18 14:08:36.439  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-18 14:08:36.439  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-18 14:08:36.459  7379  7379 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-18 14:08:36.459  7379  7379 D elm:15121: ELMEngine.ELMEngine( context ).
,08-18 14:08:36.459  7379  7379 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-18 14:08:36.459  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-18 14:08:36.469  1018  4319 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,08-18 14:08:36.469  1018  4319 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.469  1018  4319 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.469  1018  4319 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.469  1018  4319 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:36.479  1018  1058 D PackageManager: delete codoeFile: 
,08-18 14:08:36.479  7439  7439 E Zygote  : MountEmulatedStorage()
08-18 14:08:36.479  7439  7439 I libpersona: KNOX_SDCARD checking this for 1000
08-18 14:08:36.479  7439  7439 E Zygote  : v2
08-18 14:08:36.479  7439  7439 I libpersona: KNOX_SDCARD not a persona
08-18 14:08:36.489  7439  7439 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-18 14:08:36.489  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-18 14:08:36.489  7439  7439 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-18 14:08:36.489  7439  7439 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-18 14:08:36.489  1018  1058 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
08-18 14:08:36.489  1018  1058 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,08-18 14:08:36.489  1018  1058 D PackageManager: result of delete: 1{34651407}
08-18 14:08:36.489  1018  4319 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7439 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-18 14:08:36.499  1018  4319 I ActivityManager: Killing 6909:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-18 14:08:36.499  1018  1488 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:36.499  1018  1488 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-18 14:08:36.499  1018  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-18 14:08:36.499  1018  1488 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
08-18 14:08:36.499  1018  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-18 14:08:36.509  7379  7379 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-18 14:08:36.509  7282  7282 D AndroidRuntime: Shutting down VM
,08-18 14:08:36.509  7394  7447 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-18 14:08:36.509  7394  7447 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-18 14:08:36.519  7379  7379 D elm:15121: ElmAgentService : onCreate()
,08-18 14:08:36.519  7379  7451 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-18 14:08:36.519  7379  7451 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-18 14:08:36.519  7379  7451 D elm:15121: MDMBridge.getInstance()
08-18 14:08:36.519  7379  7451 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-18 14:08:36.529  7394  7447 D SPPClientService: PushLog.txt file is not deleted.
08-18 14:08:36.529  7394  7447 D SPPClientService: PushLog.txt file is not deleted.
08-18 14:08:36.529  7394  7447 D SPPClientService: ============PushLog. stop!
,08-18 14:08:36.529  1018  1385 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-18 14:08:36.529  7379  7451 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-18 14:08:36.529  7439  7439 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-18 14:08:36.529  7439  7439 D ActivityThread: Added TimaKeyStore provider
,08-18 14:08:36.539  1018  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.539  1018  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.539  1018  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.539  1018  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:36.539  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-18 14:08:36.539  1018  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-18 14:08:36.539  1018  1058 D PackageManager: userId{-1}
08-18 14:08:36.539  1018  1058 D PackageManager: andCode{true}
,08-18 14:08:36.549  1018  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-18 14:08:36.549  1018  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-18 14:08:36.549  1018  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-18 14:08:36.559  7459  7459 E Zygote  : MountEmulatedStorage()
08-18 14:08:36.559  7459  7459 I libpersona: KNOX_SDCARD checking this for 10032
08-18 14:08:36.559  7459  7459 E Zygote  : v2
08-18 14:08:36.559  7459  7459 I libpersona: KNOX_SDCARD not a persona
08-18 14:08:36.559  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
08-18 14:08:36.559  7459  7459 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-18 14:08:36.559  7459  7459 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-18 14:08:36.559  1018  1385 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7459 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-18 14:08:36.559  1018  1385 I ActivityManager: Killing 6822:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-18 14:08:36.559  7459  7459 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-18 14:08:36.569  1018  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-18 14:08:36.569  7379  7379 D elm:15121: ElmAgentService : onDestroy().
,08-18 14:08:36.579  1655  1655 E NetworkScheduler.SchedulerReceiver: Invalid parameter app,
08-18 14:08:36.579  1655  1655 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-18 14:08:36.579  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-18 14:08:36.589  1018  1212 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-18 14:08:36.589  1018  1212 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-18 14:08:36.589  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-18 14:08:36.589  1018  1212 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:36.589  1018  1212 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-18 14:08:36.589  1018  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-18 14:08:36.589  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-18 14:08:36.589  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-18 14:08:36.589  1018  1548 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-18 14:08:36.589  1018  1548 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
08-18 14:08:36.589  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-18 14:08:36.599  1018  1548 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:36.599  1018  1548 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-18 14:08:36.599  1018  1548 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-18 14:08:36.599  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-18 14:08:36.599  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-18 14:08:36.599  1018  1031 I ActivityManager: Killing 7019:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,08-18 14:08:36.599  7459  7459 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-18 14:08:36.599  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-18 14:08:36.599  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-18 14:08:36.599  7459  7459 D ActivityThread: Added TimaKeyStore provider
,08-18 14:08:36.609  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-18 14:08:36.619  1018  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-18 14:08:36.619  1018  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-18 14:08:36.629  1018  1212 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-18 14:08:36.629  1018  1212 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,08-18 14:08:36.629  1018  1212 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:36.629  1018  1212 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-18 14:08:36.629  1018  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-18 14:08:36.639  1918  7475 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-18 14:08:36.639  1918  7475 D AccountUtils: Clearing selected account for com.test.thalitest
,08-18 14:08:36.649  1018  4319 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,08-18 14:08:36.649  1018  4319 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.649  1018  4319 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:36.649  1018  4319 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.649  1018  4319 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:36.659  7479  7479 E Zygote  : MountEmulatedStorage()
,08-18 14:08:36.659  7479  7479 E Zygote  : v2
08-18 14:08:36.659  7479  7479 I libpersona: KNOX_SDCARD checking this for 1000
08-18 14:08:36.659  7479  7479 I libpersona: KNOX_SDCARD not a persona
,08-18 14:08:36.659  7479  7479 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-18 14:08:36.669  1018  4319 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7479 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-18 14:08:36.669  1018  1385 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-18 14:08:36.669  7479  7479 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-18 14:08:36.669  1018  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-18 14:08:36.669  1018  1385 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:36.669  1018  1385 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-18 14:08:36.669  1018  1385 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-18 14:08:36.669  7479  7479 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-18 14:08:36.669  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:36.669  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-18 14:08:36.669  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-18 14:08:36.679  1018  4319 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-18 14:08:36.679  1018  4319 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:36.679  1018  4319 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:36.679  1018  4319 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.679  1018  4319 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:36.699  7459  7492 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-18 14:08:36.699  7459  7492 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
08-18 14:08:36.699  7493  7493 E Zygote  : MountEmulatedStorage()
08-18 14:08:36.699  7493  7493 I libpersona: KNOX_SDCARD checking this for 10055
08-18 14:08:36.699  7493  7493 E Zygote  : v2
08-18 14:08:36.699  7493  7493 I libpersona: KNOX_SDCARD not a persona
,08-18 14:08:36.699  7493  7493 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-18 14:08:36.699  7479  7479 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-18 14:08:36.699  7479  7479 D ActivityThread: Added TimaKeyStore provider
,08-18 14:08:36.709  1018  4319 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7493 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-18 14:08:36.709  7493  7493 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-18 14:08:36.709  1018  4319 I ActivityManager: Killing 7044:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,08-18 14:08:36.709  7493  7493 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-18 14:08:36.719  7282  7282 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-18 14:08:36.729  1018  4317 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-18 14:08:36.729  1018  4317 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0,
08-18 14:08:36.729  1018  4317 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:36.729  1018  1488 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
08-18 14:08:36.729  1018  4317 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-18 14:08:36.729  1018  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
08-18 14:08:36.729  1018  4317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
08-18 14:08:36.729  1018  1488 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:36.729  1018  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-18 14:08:36.729  1018  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,08-18 14:08:36.739  7459  7492 D SPPClientService: PushLog.txt file is not deleted.
08-18 14:08:36.739  7459  7492 D SPPClientService: PushLog.txt file is not deleted.
08-18 14:08:36.739  7459  7492 D SPPClientService: ============PushLog. stop!
,08-18 14:08:36.749  7285  7285 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,08-18 14:08:36.749  7479  7479 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,08-18 14:08:36.749  1018  1307 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
08-18 14:08:36.749  1018  1307 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,08-18 14:08:36.759  1018  1307 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:36.759  1018  1307 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-18 14:08:36.759  1018  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,08-18 14:08:36.759  7493  7493 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-18 14:08:36.759  1918  1918 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-18 14:08:36.759  1918  1918 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-18 14:08:36.759  7493  7493 D ActivityThread: Added TimaKeyStore provider
08-18 14:08:36.759  1918  7475 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-18 14:08:36.769  1018  4317 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-18 14:08:36.769  1018  4317 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:36.769  1018  4317 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-18 14:08:36.769  1018  4317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-18 14:08:36.769  1918  1918 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-18 14:08:36.769  1918  1918 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-18 14:08:36.769  1018  1385 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,08-18 14:08:36.769  1018  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.779  1018  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.779  1018  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.779  1018  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:36.789  7520  7520 E Zygote  : MountEmulatedStorage()
,08-18 14:08:36.789  7520  7520 E Zygote  : v2
08-18 14:08:36.789  7520  7520 I libpersona: KNOX_SDCARD checking this for 1000
08-18 14:08:36.789  7520  7520 I libpersona: KNOX_SDCARD not a persona,
,08-18 14:08:36.789  7520  7520 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-18 14:08:36.789  1018  1385 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7520 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-18 14:08:36.789  7493  7493 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-18 14:08:36.799  1018  1385 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-18 14:08:36.799  1018  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:36.799  1018  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.799  1018  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.799  1018  1385 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.799  7520  7520 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-18 14:08:36.799  7520  7520 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-18 14:08:36.799  1918  7508 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
08-18 14:08:36.799  1918  7508 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,08-18 14:08:36.819  7533  7533 E Zygote  : MountEmulatedStorage()
08-18 14:08:36.819  7533  7533 I libpersona: KNOX_SDCARD checking this for 1000
08-18 14:08:36.819  7533  7533 E Zygote  : v2
08-18 14:08:36.819  7533  7533 I libpersona: KNOX_SDCARD not a persona
,08-18 14:08:36.819  1018  1385 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7533 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-18 14:08:36.829  7493  7493 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-18 14:08:36.829  7493  7493 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-18 14:08:36.829  7493  7493 D UserAnalysis: Create SecureDbHelper
,08-18 14:08:36.829  1018  1488 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-18 14:08:36.829  1018  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,08-18 14:08:36.829  1018  1488 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:36.829  1018  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-18 14:08:36.829  1018  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-18 14:08:36.839  7533  7533 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-18 14:08:36.839  7533  7533 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-18 14:08:36.839  1018  4318 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-18 14:08:36.839  7533  7533 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-18 14:08:36.839  7493  7493 D IntelligenceServiceApplication: onCreate()
08-18 14:08:36.839  7520  7520 D TimaKeyStoreProvider: TimaSignature is unavailable
08-18 14:08:36.839  1918  7508 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
08-18 14:08:36.839  1918  7508 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
08-18 14:08:36.849  7493  7493 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
08-18 14:08:36.849  7520  7520 D ActivityThread: Added TimaKeyStore provider
08-18 14:08:36.849  1018  4318 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:36.849  1018  4318 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-18 14:08:36.849  1018  4318 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-18 14:08:36.859  1018  4317 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
08-18 14:08:36.859  7493  7493 D IntelligenceServiceApplication: no applications having user consent for prediction
08-18 14:08:36.859  1018  4317 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.859  1018  4317 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.859  1018  4317 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.859  1018  4317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:36.869  1918  7508 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
08-18 14:08:36.869  1918  7508 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,08-18 14:08:36.869  1918  7508 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,08-18 14:08:36.879  7551  7551 E Zygote  : MountEmulatedStorage()
,08-18 14:08:36.879  7551  7551 E Zygote  : v2
08-18 14:08:36.879  7551  7551 I libpersona: KNOX_SDCARD checking this for 1000
08-18 14:08:36.879  7551  7551 I libpersona: KNOX_SDCARD not a persona
,08-18 14:08:36.879  7551  7551 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-18 14:08:36.879  1018  4317 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=7551 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-18 14:08:36.879  7551  7551 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-18 14:08:36.879  7533  7533 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-18 14:08:36.879  7533  7533 D ActivityThread: Added TimaKeyStore provider
,08-18 14:08:36.879  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-18 14:08:36.879  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
08-18 14:08:36.889  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:36.889  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-18 14:08:36.889  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-18 14:08:36.889  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.889  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.889  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.889  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-18 14:08:36.889  7551  7551 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-18 14:08:36.889  1918  7508 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
08-18 14:08:36.889  1918  7508 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,08-18 14:08:36.889  1918  7508 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
08-18 14:08:36.889  1918  7508 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,08-18 14:08:36.889  1918  7508 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
08-18 14:08:36.889  1918  7508 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,08-18 14:08:36.909  7565  7565 E Zygote  : MountEmulatedStorage(),
08-18 14:08:36.909  7565  7565 I libpersona: KNOX_SDCARD checking this for 10011
08-18 14:08:36.909  7565  7565 E Zygote  : v2
08-18 14:08:36.909  7565  7565 I libpersona: KNOX_SDCARD not a persona
08-18 14:08:36.909  7565  7565 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-18 14:08:36.909  7565  7565 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-18 14:08:36.909  1018  1030 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=7565 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
08-18 14:08:36.909  7565  7565 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-18 14:08:36.909  1018  4320 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0,
08-18 14:08:36.909  1018  1488 I ActivityManager: Killing 7063:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
08-18 14:08:36.919  7493  7493 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-18 14:08:36.919  7551  7551 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-18 14:08:36.919  7551  7551 D ActivityThread: Added TimaKeyStore provider
,08-18 14:08:36.929  1018  1030 D LocationManagerService: getProviders()=[passive, gps]
08-18 14:08:36.929   309   309 I art     : Explicit concurrent mark sweep GC freed 8750(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 640us total 22.625ms
,08-18 14:08:36.939  7565  7565 D TimaKeyStoreProvider: TimaSignature is unavailable
08-18 14:08:36.939  7493  7493 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
08-18 14:08:36.939  7565  7565 D ActivityThread: Added TimaKeyStore provider
,08-18 14:08:36.949  7520  7584 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
08-18 14:08:36.949   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 17.607ms
,08-18 14:08:36.949  6980  6980 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,08-18 14:08:36.959  7493  7493 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-18 14:08:36.959  7493  7493 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM place_privacy WHERE package_name = ?] disk I/O error
,08-18 14:08:36.959  7493  7493 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/predictor.db" with flag (131138) and mode_t (0) due to error (30)
,08-18 14:08:36.959  7520  7584 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,08-18 14:08:36.969  1018  1031 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,08-18 14:08:36.969  1918  7475 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/databases/phenotype.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,08-18 14:08:36.969   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.922ms
,08-18 14:08:36.969  7493  7493 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/predictor.db'.
08-18 14:08:36.969  7493  7493 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 14:08:36.969  7493  7493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 14:08:36.969  7493  7493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-18 14:08:36.969  7493  7493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-18 14:08:36.969  7493  7493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-18 14:08:36.969  7493  7493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-18 14:08:36.969  7493  7493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-18 14:08:36.969  7493  7493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-18 14:08:36.969  7493  7493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-18 14:08:36.969  7493  7493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-18 14:08:36.969  7493  7493 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-18 14:08:36.969  7493  7493 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-18 14:08:36.969  7493  7493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 14:08:36.969  7493  7493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-18 14:08:36.969  7493  7493 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlaceCategoryManager.removePlaceCategories(PlaceCategoryManager.java:65)
08-18 14:08:36.969  7493  7493 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removePlaceCategories(PlacePredictor.java:150)
08-18 14:08:36.969  7493  7493 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removeAllPlaceCategories(PlacePredictor.java:145)
08-18 14:08:36.969  7493  7493 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:79)
08-18 14:08:36.969  7493  7493 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-18 14:08:36.969  7493  7493 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-18 14:08:36.969  7493  7493 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-18 14:08:36.969  7493  7493 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-18 14:08:36.969  7493  7493 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 14:08:36.969  7493  7493 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-18 14:08:36.969  7493  7493 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-18 14:08:36.969  7493  7493 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-18 14:08:36.969  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.969  7493  7493 D AndroidRuntime: Shutting down VM
08-18 14:08:36.969  1559  1574 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-18 14:08:36.969  1559  1574 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-18 14:08:36.969  7493  7493 E AndroidRuntime: FATAL EXCEPTION: main
08-18 14:08:36.969  7493  7493 E Andr,oidRuntime: Process: com.samsung.android.intelligenceservice, PID: 7493
08-18 14:08:36.969  7493  7493 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 14:08:36.969  7493  7493 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 14:08:36.969  7493  7493 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-18 14:08:36.969  7493  7493 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-18 14:08:36.969  7493  7493 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-18 14:08:36.969  7493  7493 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-18 14:08:36.969  7493  7493 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-18 14:08:36.969  7493  7493 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-18 14:08:36.969  7493  7493 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-18 14:08:36.969  7493  7493 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-18 14:08:36.969  7493  7493 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-18 14:08:36.969  7493  7493 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-18 14:08:36.969  7493  7493 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 14:08:36.969  7493  7493 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-18 14:08:36.969  7493  7493 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlaceCategoryManager.removePlaceCategories(PlaceCategoryManager.java:65)
08-18 14:08:36.969  7493  7493 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removePlaceCategories(PlacePredictor.java:150)
08-18 14:08:36.969  7493  7493 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removeAllPlaceCategories(PlacePredictor.java:145)
08-18 14:08:36.969  7493  7493 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:79)
08-18 14:08:36.969  7493  7493 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-18 14:08:36.969  7493  7493 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-18 14:08:36.969  7493  7493 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-18 14:08:36.969  7493  7493 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-18 14:08:36.969  7493  7493 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 14:08:36.969  7493  7493 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-18 14:08:36.969  7493  7493 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-18 14:08:36.969  7493  7493 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-18 14:08:36.979  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.979  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.979  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:36.979  1559  1574 E DatabaseUtils: Writing exception to parcel
08-18 14:08:36.979  1559  1574 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-18 14:08:36.979  1559  1574 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-18 14:08:36.979  1559  1574 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
08-18 14:08:36.979  1559  1574 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-18 14:08:36.979  1559  1574 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-18 14:08:36.979  1559  1574 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
08-18 14:08:36.979  1559  1574 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
08-18 14:08:36.979  1559  1574 E DatabaseUtils: 	at com.sec.android.provider.logsprovider.LogsProvider.delete(LogsProvider.java:3550)
08-18 14:08:36.979  1559  1574 E DatabaseUtils: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:324)
08-18 14:08:36.979  1559  1574 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:206)
08-18 14:08:36.979  1559  1574 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:446)
08-18 14:08:36.989  7551  7551 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-18 14:08:36.999  7587  7587 E Zygote  : MountEmulatedStorage()
08-18 14:08:36.999  7587  7587 E Zygote  : v2
08-18 14:08:36.999  7587  7587 I libpersona: KNOX_SDCARD checking this for 10014
08-18 14:08:36.999  7587  7587 I libpersona: KNOX_SDCARD not a persona
08-18 14:08:36.999  1018  1031 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7587 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
08-18 14:08:37.009  1018  1381 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-18 14:08:37.009  1018  1381 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,08-18 14:08:37.009  1018  1381 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:37.009  1018  1381 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-18 14:08:37.009  1018  1381 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
08-18 14:08:37.019  1018  1307 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
08-18 14:08:37.019  1018  1307 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
08-18 14:08:37.019  1018  1307 W ActivityManager: userId = 0, bbcId = -10000
08-18 14:08:37.019  1018  1307 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-18 14:08:37.019  1018  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
08-18 14:08:37.019  7533  7533 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-18 14:08:37.019  7533  7533 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-18 14:08:37.019  7533  7533 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
08-18 14:08:37.019  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.intelligenceservice
08-18 14:08:37.019  1018  1212 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
08-18 14:08:37.019  7520  7520 D AcmsService: Enter Oncreate
08-18 14:08:37.029  7520  7520 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-18 14:08:37.029  7520  7520 D AcmsService: creating AcmsCore
08-18 14:08:37.029  7533  7533 E SQLiteLog: (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
08-18 14:08:37.029  7520  7520 D AcmsCore: AcmsCore.getAcmsCore() - Enter
08-18 14:08:37.029  7520  7520 D AcmsCore: AcmsCore
08-18 14:08:37.029  1764  7515 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-18 14:08:37.029  1764  7515 E AndroidRuntime: Process: android.process.acore, PID: 1764
08-18 14:08:37.029  1764  7515 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-18 14:08:37.029  1764  7515 E AndroidRuntime: 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:179)
08-18 14:08:37.029  1764  7515 E AndroidRuntime: 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
08-18 14:08:37.029  1764  7515 E AndroidRuntime: 	at android.content.ContentProviderProxy.delete(ContentProviderNative.java:543)
08-18 14:08:37.029  1764  7515 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1352)
08-18 14:08:37.029  1764  7515 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:476)
08-18 14:08:37.029  1764  7515 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:130)
08-18 14:08:37.029  1764  7515 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:324)
08-18 14:08:37.029  1764  7515 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1352)
08-18 14:08:37.029  1764  7515 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-18 14:08:37.029  1764  7515 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-18 14:08:37.029  1764  7515 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-18 14:08:37.029  1764  7515 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 14:08:37.029  1764  7515 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-18 14:08:37.029  1764  7515 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-18 14:08:37.029  1018  1212 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:37.029  1018  1212 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:37.029  1018  1212 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:37.029  1018  1212 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-18 14:08:37.029  7533  7533 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-18 14:08:37.029  7533  7533 D AndroidRuntime: Shutting down VM
08-18 14:08:37.029  7533  7533 E AndroidRuntime: FATAL EXCEPTION: main
08-18 14:08:37.029  7533  7533 E AndroidRuntime: Process: com.sec.pcw.device, PID: 7533
08-18 14:08:37.029  7533  7533 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-18 14:08:37.029  7533  7533 E AndroidRuntime: 	... 11 more
08-18 14:08:37.039  7551  7551 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/lowpowercontext-system-db" with flag (131138) and mode_t (0) due to error (30)
08-18 14:08:37.039  7520  7520 D AcmsCore: init
08-18 14:08:37.039  7520  7520 D AcmsCore: Looper handler is not null
08-18 14:08:37.039  7520  7520 D AcmsCore: Post to AcmsCoreHandler
08-18 14:08:37.039  7520  7520 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-18 14:08:37.039  7520  7520 D AcmsServiceMonitor: Incrementing - Counter value: 1
08-18 14:08:37.039  7520  7520 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
08-18 14:08:37.039  7520  7520 D AcmsService: onStartCommand
08-18 14:08:37.039  7520  7520 D AcmsService: Action: android.intent.action.PACKAGE_REMOVED
08-18 14:08:37.039  7520  7520 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
08-18 14:08:37.039  7520  7520 D AcmsServiceMonitor: Incrementing - Counter value: 2
08-18 14:08:37.039  7520  7520 D AcmsService: Incremented Counter Value : onStartCommand
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/lowpowercontext-system-db'.
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f$b.a(DataStore.java:2443)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(DataStore.java:85)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextProvider.onCreate(LowpowerContextProvider.java:303)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-18 14:08:37.039  7551  7551 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)

```
