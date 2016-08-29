#### Test 79763830f89c62d_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
08-29 14:20:41.781  1932  6862 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-29 14:20:41.791  6789  6860 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
--------- beginning of system
08-29 14:20:41.791  1014  1487 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 14:20:41.791  1014  3867 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
08-29 14:20:41.791  1014  3867 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
08-29 14:20:41.801  1014  3867 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:41.801  1932  6862 I qtaguid : Tagging socket 101 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1932, getuid(): 10011
08-29 14:20:41.801  1014  3867 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:41.801  1014  3867 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
08-29 14:20:41.801  6843  6843 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
08-29 14:20:41.801  6973  6973 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 14:20:41.801  6973  6973 D ActivityThread: Added TimaKeyStore provider
08-29 14:20:41.801  1932  6879 W BaseAppContext: Using Auth Proxy for data requests.
08-29 14:20:41.811  1932  6879 W BaseAppContext: Using Auth Proxy for data requests.
08-29 14:20:41.811  6843  6972 D ContactProvider: getAllContactInfoList Start
08-29 14:20:41.821  1014  1027 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-29 14:20:41.831  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:41.831  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:41.831  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
08-29 14:20:41.831  1014  1027 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
08-29 14:20:41.831  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
08-29 14:20:41.861   287   287 E SMD     : DCD OFF
,08-29 14:20:41.881  6843  6972 D ContactProvider: getAllContactInfoList End
08-29 14:20:41.881  6843  6972 I syncContacts: thread: 1268, sync time = 149
08-29 14:20:41.901  1014  1486 E EdmStorageProvider: Admin not in database, something went wrong
08-29 14:20:41.951  1932  6862 I qtaguid : Tagging socket 105 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1932, getuid(): 10011
08-29 14:20:41.961  1014  1484 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
08-29 14:20:41.961  6973  6973 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 14:20:41.971  1014  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:41.971  1014  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:41.971  1014  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:41.971  1014  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:41.971  6973  6973 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 14:20:41.981  1014  1484 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7004 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
08-29 14:20:41.991  7004  7004 E Zygote  : MountEmulatedStorage()
08-29 14:20:41.991  7004  7004 E Zygote  : v2
08-29 14:20:41.991  7004  7004 I libpersona: KNOX_SDCARD checking this for 10148
08-29 14:20:41.991  7004  7004 I libpersona: KNOX_SDCARD not a persona
08-29 14:20:41.991  7004  7004 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 14:20:41.991  7004  7004 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 14:20:41.991  7004  7004 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 14:20:42.001  1014  1484 I ActivityManager: Killing 6557:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
08-29 14:20:42.021  7004  7004 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 14:20:42.021  7004  7004 D ActivityThread: Added TimaKeyStore provider
08-29 14:20:42.041  1014  1253 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
08-29 14:20:42.051  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:42.051  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:42.051  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:42.051  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:42.071  1014  1510 I art     : Explicit concurrent mark sweep GC freed 20725(1229KB) AllocSpace objects, 1(22KB) LOS objects, 33% free, 23MB/34MB, paused 2.771ms total 150.376ms
08-29 14:20:42.071  7021  7021 E Zygote  : MountEmulatedStorage()
08-29 14:20:42.071  7021  7021 E Zygote  : v2
08-29 14:20:42.071  7021  7021 I libpersona: KNOX_SDCARD checking this for 10041
08-29 14:20:42.071  7021  7021 I libpersona: KNOX_SDCARD not a persona
08-29 14:20:42.071  7021  7021 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 14:20:42.071  7021  7021 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 14:20:42.071  7021  7021 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-29 14:20:42.081  1014  1253 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=7021 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
08-29 14:20:42.081  1014  1253 I ActivityManager: Killing 6575:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
08-29 14:20:42.081  1014  3867 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-29 14:20:42.091  1014  3867 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:42.091  1014  3867 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:42.091  1014  3867 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
08-29 14:20:42.101  7021  7021 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 14:20:42.101  7021  7021 D ActivityThread: Added TimaKeyStore provider
08-29 14:20:42.111  7004  7004 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
08-29 14:20:42.121  7021  7021 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-29 14:20:42.121  7021  7021 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 14:20:42.121  7021  7021 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 14:20:42.121  7021  7021 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-29 14:20:42.121  7021  7021 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
08-29 14:20:42.121  1014  1485 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
08-29 14:20:42.121  1014  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:42.121  1014  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:42.121  1014  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:42.121  1014  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:42.161  6999  6999 D AndroidRuntime: 
08-29 14:20:42.161  6999  6999 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-29 14:20:42.161  1014  3396 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-29 14:20:42.171  7036  7036 E Zygote  : MountEmulatedStorage()
08-29 14:20:42.171  7036  7036 I libpersona: KNOX_SDCARD checking this for 1000
08-29 14:20:42.171  7036  7036 E Zygote  : v2
08-29 14:20:42.171  7036  7036 I libpersona: KNOX_SDCARD not a persona
08-29 14:20:42.171  6999  6999 D AndroidRuntime: CheckJNI is OFF
08-29 14:20:42.171  1014  1485 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=7036 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-29 14:20:42.171  6999  6999 D AndroidRuntime: readGMSProperty: start
08-29 14:20:42.171  6999  6999 D AndroidRuntime: readGMSProperty: already setted!!
08-29 14:20:42.171  6999  6999 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-29 14:20:42.171  7036  7036 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 14:20:42.171  6999  6999 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-29 14:20:42.171  6999  6999 D AndroidRuntime: readGMSProperty: end
08-29 14:20:42.171  6999  6999 D AndroidRuntime: addProductProperty: start
08-29 14:20:42.171  7036  7036 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 14:20:42.171  1014  1485 I ActivityManager: Killing 6591:com.wsomacp/u0a23 (adj 15): empty #21
08-29 14:20:42.171  7036  7036 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 14:20:42.171  1014  1482 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 14:20:42.171  1014  1482 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-29 14:20:42.181  1014  1482 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:42.181  1014  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:42.181  1014  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-29 14:20:42.191  7021  7021 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
08-29 14:20:42.201  7036  7036 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 14:20:42.201  7036  7036 D ActivityThread: Added TimaKeyStore provider
08-29 14:20:42.211  1014  1510 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-29 14:20:42.211  1014  1510 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:42.211  1014  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:42.211  1014  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-29 14:20:42.231  6973  6973 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
08-29 14:20:42.241  7036  7036 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
08-29 14:20:42.251  6973  6973 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 14:20:42.261  1014  1486 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 14:20:42.261  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-29 14:20:42.261  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:42.261  1014  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:42.261  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-29 14:20:42.291  1014  3867 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
08-29 14:20:42.291  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:42.291  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:42.291  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:42.291  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:42.311  7062  7062 E Zygote  : MountEmulatedStorage()
08-29 14:20:42.311  1014  3867 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7062 uid=10152 gids={50152, 9997} abi=armeabi-v7a
08-29 14:20:42.311  7062  7062 E Zygote  : v2
08-29 14:20:42.311  7062  7062 I libpersona: KNOX_SDCARD checking this for 10152
08-29 14:20:42.311  7062  7062 I libpersona: KNOX_SDCARD not a persona
08-29 14:20:42.311  7062  7062 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 14:20:42.311  1014  3867 I ActivityManager: Killing 6607:com.sec.esdk.elm/u0a90 (adj 15): empty #21
08-29 14:20:42.321  7062  7062 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 14:20:42.321  7062  7062 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 14:20:42.321  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-29 14:20:42.321  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:42.321  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:42.321  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-29 14:20:42.331  1014  1487 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-29 14:20:42.341  1014  1487 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:42.341  1014  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:42.341  1014  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-29 14:20:42.341  6999  6999 E AffinityControl: AffinityControl: registerfunction enter
08-29 14:20:42.351  7062  7062 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 14:20:42.351  7062  7062 D ActivityThread: Added TimaKeyStore provider
08-29 14:20:42.371  6999  6999 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-29 14:20:42.371  1932  6879 W BaseAppContext: Using Auth Proxy for data requests.
08-29 14:20:42.371  6789  6860 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 577 ms] updated apps [took 577 ms] 
08-29 14:20:42.381  1014  1486 I ActivityManager: Killing 6626:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
08-29 14:20:42.391  1014  1510 E PersonaManagerService: inState():  stateMachine is null !!
08-29 14:20:42.391  1014  1510 I PersonaManagerService: PersonaId don't exist
08-29 14:20:42.391  1014  1510 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-29 14:20:42.391  1014  1510 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-29 14:20:42.411  7062  7062 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
08-29 14:20:42.411  7062  7062 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
08-29 14:20:42.411  1014  1510 W ActivityManager: mDVFSHelper.acquire()
08-29 14:20:42.421  7062  7062 I TapandpayWidget:Utils: Clear T&P info.
08-29 14:20:42.421  1014  1510 D FocusedStackFrame: Set to : 0
08-29 14:20:42.431  7062  7062 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
08-29 14:20:42.431  1014  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:42.431  1014  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:42.431  1014  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:42.431  1014  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:42.431  1014  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-29 14:20:42.431  1014  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-29 14:20:42.451  7083  7083 E Zygote  : MountEmulatedStorage()
08-29 14:20:42.451  7083  7083 E Zygote  : v2
08-29 14:20:42.451  7083  7083 I libpersona: KNOX_SDCARD checking this for 10170
08-29 14:20:42.451  7083  7083 I libpersona: KNOX_SDCARD not a persona
08-29 14:20:42.451  1014  1510 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7083 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-29 14:20:42.451  1014  1510 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-29 14:20:42.451  1014  1510 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-29 14:20:42.451  1014  1510 D InputDispatcher: Focused application set to: xxxx
08-29 14:20:42.451  1014  1510 D InputDispatcher: Focus left window: 1488
08-29 14:20:42.451  7083  7083 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 14:20:42.461  1014  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-29 14:20:42.461  1014  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-29 14:20:42.461  7083  7083 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 14:20:42.461  7083  7083 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-29 14:20:42.461   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-29 14:20:42.461  6999  6999 D AndroidRuntime: Shutting down VM
08-29 14:20:42.481  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 14:20:42.491  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
08-29 14:20:42.491  7021  7021 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 209.211ms
08-29 14:20:42.491  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
08-29 14:20:42.491  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:42.491  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:42.491  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:42.491  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:42.501  6973  6973 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 14:20:42.511  1014  1026 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7099 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-29 14:20:42.511  1014  1026 I ActivityManager: Killing 6657:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
08-29 14:20:42.521  7099  7099 E Zygote  : MountEmulatedStorage()
08-29 14:20:42.521  7099  7099 E Zygote  : v2
08-29 14:20:42.521  7083  7083 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 14:20:42.521  7099  7099 I libpersona: KNOX_SDCARD checking this for 10009
08-29 14:20:42.521  7083  7083 D ActivityThread: Added TimaKeyStore provider
08-29 14:20:42.521  6973  6973 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 14:20:42.521  7099  7099 I libpersona: KNOX_SDCARD not a persona
08-29 14:20:42.531  7099  7099 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 14:20:42.531  7099  7099 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 14:20:42.531  7099  7099 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-29 14:20:42.541  6973  6973 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 14:20:42.551   305   305 I art     : Explicit concurrent mark sweep GC freed 8701(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 626us total 37.537ms
08-29 14:20:42.561  1014  1253 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-29 14:20:42.561  6973  6973 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 14:20:42.561  1014  1014 V ActivityManager: Display changed displayId=0
08-29 14:20:42.571  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-29 14:20:42.581   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 691us total 25.983ms
08-29 14:20:42.591  1932  6862 I qtaguid : Untagging socket 101
08-29 14:20:42.591  7099  7099 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 14:20:42.591  7099  7099 D ActivityThread: Added TimaKeyStore provider
08-29 14:20:42.601  6973  6973 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 14:20:42.601  7021  7021 W art     : Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 104.402ms
08-29 14:20:42.601  6973  6973 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 14:20:42.601  6973  6973 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 14:20:42.601  6973  6973 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 14:20:42.601  6973  6973 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 14:20:42.601   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 2.237ms total 23.053ms
08-29 14:20:42.601  7021  7021 D Mms/TelephonyPermission: start operation mode monitor
08-29 14:20:42.601  6973  6973 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 14:20:42.601  6973  6973 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 14:20:42.601  6973  6973 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 14:20:42.611  6973  6973 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 14:20:42.611  6973  6973 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 14:20:42.611  6973  6973 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 14:20:42.611  6973  6973 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 14:20:42.611  6973  6973 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-29 14:20:42.611  1932  1932 I ConfigFetchService: fetch service done; releasing wakelock
08-29 14:20:42.621  7021  7021 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-29 14:20:42.621  7021  7122 D Mms/ArtClassLoader: init before art
08-29 14:20:42.631  1932  1932 I ConfigFetchService: stopping self
08-29 14:20:42.631  1014  1253 D PersonaManager: isKioskContainerExistOnDevice
08-29 14:20:42.631   257   449 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
08-29 14:20:42.641   257  1036 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-29 14:20:42.651  1932  6879 W BaseAppContext: Using Auth Proxy for data requests.
08-29 14:20:42.651  1488  1488 V ActivityThread: updateVisibility : ActivityRecord{3f58385e token=android.os.BinderProxy@3c067f45 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-29 14:20:42.651  7021  7021 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-29 14:20:42.651  7021  7021 D Mms/TelephonyPermission: isDefault true
08-29 14:20:42.651  1488  1488 D Launcher: onTrimMemory. Level: 20
08-29 14:20:42.661  7021  7021 D Mms/MmsApp: onCreate() com.android.mms
08-29 14:20:42.661  1932  6879 W BaseAppContext: Using Auth Proxy for data requests.
08-29 14:20:42.671  6999  6999 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-29 14:20:42.671  6973  6973 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-29 14:20:42.691  1014  1014 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-29 14:20:42.691  6973  6973 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-29 14:20:42.701  1932  6879 W BaseAppContext: Using Auth Proxy for data requests.
08-29 14:20:42.761  7021  7021 D Mms/MmsApp: [start]    initCountryIso consume time = 573.446094
08-29 14:20:42.771  1014  1026 D CountryDetector: The first listener is added
08-29 14:20:42.771  6973  6973 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 14:20:42.781  6973  6973 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 14:20:42.781  6973  6973 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-29 14:20:42.791  7083  7083 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-29 14:20:42.801  7021  7021 D Mms/MmsApp: [end]    initCountryIso consume time = 33.593385
08-29 14:20:42.801  7021  7021 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 1.117865
08-29 14:20:42.811  1014  1026 I ActivityManager: Killing 6674:com.qualcomm.timeservice/1000 (adj 15): empty #21
08-29 14:20:42.821  1014  1027 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-29 14:20:42.831  7083  7083 I cr.library_loader: Time to load native libraries: 4 ms (timestamps 9017-9021)
08-29 14:20:42.831  7083  7083 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-29 14:20:42.831  7021  7021 D Mms/MmsConfig: before partial update
08-29 14:20:42.851  7021  7021 D Mms/MmsConfig: Load Resize quality : 80
08-29 14:20:42.851  7021  7021 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
08-29 14:20:42.861  7021  7021 D EasySignUpManager_1.0.1: isAuth is false
08-29 14:20:42.861  7021  7021 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
08-29 14:20:42.861  1014  1487 I ActivityManager: Killing 6638:com.android.providers.calendar/u0a37 (adj 15): empty #21
08-29 14:20:42.871  1456  1476 D TP/MmsSmsProvider: query,matched:2117, calling pid = 7021
08-29 14:20:42.871  1456  1476 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.730 ms
08-29 14:20:42.891  7021  7021 D EasySignUpManager_1.0.1: isAuth is false
08-29 14:20:42.891  7021  7021 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
08-29 14:20:42.901  7021  7021 E CscParser: mps_code.dat does not exist
08-29 14:20:42.901  7021  7021 E CscParser: customer_path =/system/csc/customer.xml
08-29 14:20:42.901  7021  7021 E CscParser: fileName + /system/csc/customer.xml
08-29 14:20:42.911  7021  7021 E CscParser: mps_code.dat does not exist
08-29 14:20:42.911  7021  7021 E CscParser: customer_path =/system/csc/customer.xml
08-29 14:20:42.911  7021  7021 E CscParser: fileName + /system/csc/customer.xml
08-29 14:20:42.911  7083  7083 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {36ac3a11}
08-29 14:20:42.911  7021  7021 D CscParser: getInstance fileName =/system/csc/customer.xml
08-29 14:20:42.911  7083  7083 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-29 14:20:42.921  7083  7083 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 14:20:42.931  7021  7021 D Mms/MmsConfig:  enable multiwindow = false
08-29 14:20:42.941  6973  6973 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-29 14:20:42.941  1014  1487 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
08-29 14:20:42.941  1014  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
08-29 14:20:42.941  1014  1487 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:42.941  1014  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:42.941  1014  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
08-29 14:20:42.951  7021  7021 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-29 14:20:42.951  7021  7021 E Mms/MessageUtils: updateCountryIso : update country iso info 
08-29 14:20:42.971  7021  7021 D Mms/MmsConfig: [end]    init() consume time = 169.707083
08-29 14:20:42.971  7021  7021 D Mms/Contact: [start]    init() consume time = 1.54526
08-29 14:20:42.991  1456  1476 D TP/MmsSmsProvider: query,matched:13, calling pid = 7021
08-29 14:20:42.991  6973  6973 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-29 14:20:42.991  7083  7083 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-29 14:20:43.001  1456  1476 D TP/MmsSmsProvider: match 13:Elapsed time : 3.966 ms
08-29 14:20:43.001  7021  7021 D Mms/Contact: [end]    init consume time = 25.393907
08-29 14:20:43.001  6905  6998 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-29 14:20:43.001  6905  6998 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 14:20:43.001  6905  6998 I GAv4    :   adb logcat -s GAv4
08-29 14:20:43.001  6973  7135 D Ads     : Skipping gmscore version check
08-29 14:20:43.021  7083  7083 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 14:20:43.021  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-29 14:20:43.021  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:43.021  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:43.021  6905  6998 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-29 14:20:43.021  1014  1208 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-29 14:20:43.021  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
08-29 14:20:43.031  7083  7083 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 14:20:43.051  7021  7140 D Mms/DraftCache: [start]    rebuildCache consume time = 49.431458
08-29 14:20:43.051  7021  7122 W art     : Verification of boolean com.android.mms.ui.ConversationListFragment.onOptionsItemSelected(android.view.MenuItem) took 115.116ms
08-29 14:20:43.051  7021  7021 D Mms/MethodReflector: getSubId is called
08-29 14:20:43.051  7021  7021 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-29 14:20:43.051  6905  6998 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-29 14:20:43.051  1456  1483 D TP/MmsSmsProvider: query,matched:12, calling pid = 7021
08-29 14:20:43.051  1456  1483 D TP/MmsSmsProvider: match 12:Elapsed time : 2.036 ms
08-29 14:20:43.061  7021  7021 D Mms/MethodReflector: getTelephonyProperty is called
08-29 14:20:43.061  7021  7021 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-29 14:20:43.061  7021  7021 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-29 14:20:43.061  7021  7021 D Mms/DownloadManager: auto download without roaming -> true
08-29 14:20:43.061  7021  7021 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-29 14:20:43.061  7021  7021 D Mms/MethodReflector: getSubId is called
08-29 14:20:43.061  7021  7021 D Mms/MethodReflector: getDefaultSmsSubId is called
08-29 14:20:43.061  7021  7021 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
08-29 14:20:43.061  7021  7021 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
08-29 14:20:43.061  7021  7021 D Mms/MethodReflector: getTelephonyProperty is called
08-29 14:20:43.061  7021  7021 D Mms/DownloadManager: roaming -> false (slotId = 1)
08-29 14:20:43.061  7021  7021 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-29 14:20:43.061  7021  7021 D Mms/DownloadManager: auto download without roaming -> true
08-29 14:20:43.061  7021  7021 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-29 14:20:43.061  7021  7021 D Mms/DownloadManager: auto download during roaming secondary -> false
08-29 14:20:43.061  7021  7021 D Mms/DownloadManager: mAutoDownload ------> true
08-29 14:20:43.061  7021  7140 D Mms/DraftCache: [end]    rebuildCache consume time = 18.136094
08-29 14:20:43.071  6973  6973 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-29 14:20:43.071  7083  7083 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-29 14:20:43.071  7083  7083 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-29 14:20:43.071  7083  7083 I Adreno-EGL: Build Date: 04/06/15 Mon
08-29 14:20:43.071  7083  7083 I Adreno-EGL: Local Branch: 
08-29 14:20:43.071  7083  7083 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-29 14:20:43.071  7083  7083 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-29 14:20:43.071  7083  7083 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-29 14:20:43.121  6905  6998 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
08-29 14:20:43.121  7021  7021 D ComposerPerformance: 1472473243138 ms / [DONE] Composer constructor
08-29 14:20:43.121  7021  7021 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
08-29 14:20:43.121  7021  7021 I Mms/ReservationManager: ReservationManager()
08-29 14:20:43.121  7021  7021 I Mms/ReservationManager: resetAfterConnected()
08-29 14:20:43.131  1456  1727 D TP/MmsSmsProvider: query,matched:7, calling pid = 7021
08-29 14:20:43.141  1456  1727 D TP/MmsSmsProvider: match 7:Elapsed time : 5.849 ms
08-29 14:20:43.141  1014  1040 W ActivityManager: Activity pause timeout for ActivityRecord{1eef85e3 u0 com.test.thalitest/.MainActivity t163}
08-29 14:20:43.141  6905  7142 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
08-29 14:20:43.151  7021  7021 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
08-29 14:20:43.151  7021  7147 D Mms/Conversation: [start]    init() consume time = 87.490989
08-29 14:20:43.151  7021  7021 D Mms/MmsApp: [end]    onCreate() consume time = 3.840834
08-29 14:20:43.161  1456  1476 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-29 14:20:43.161  1456  1476 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-29 14:20:43.161  1456  1476 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
08-29 14:20:43.161  1456  1476 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
08-29 14:20:43.161  1456  1476 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-29 14:20:43.161  1456  1476 D TP/MmsSmsProvider: need read changed broadcast:false
08-29 14:20:43.171  7021  7147 D Mms/Conversation: [end]    init consume time = 10.308906
08-29 14:20:43.171  7021  7147 D Mms/MessagingNotification: [start]    init() consume time = 3.335208
08-29 14:20:43.171  7021  7147 D Mms/MessagingNotification: [end]    init consume time = 4.702552
08-29 14:20:43.181  1456  1483 D TP/MmsSmsProvider: query,matched:0, calling pid = 7021
08-29 14:20:43.181  1456  1483 V TP/MmsSmsProvider: getSimpleConversations entered.
08-29 14:20:43.181  1456  1483 D TP/MmsSmsProvider: match 0:Elapsed time : 1.623 ms
08-29 14:20:43.191  7021  7153 D Mms/Synchronizer: [start]    doSync consume time = 15.49724
08-29 14:20:43.191  1014  1487 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
08-29 14:20:43.191  1014  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:43.191  1014  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:43.191  1014  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:43.191  1014  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:43.201  7021  7150 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 6.636406
08-29 14:20:43.211  7159  7159 E Zygote  : MountEmulatedStorage()
08-29 14:20:43.211  7159  7159 E Zygote  : v2
08-29 14:20:43.211  7159  7159 I libpersona: KNOX_SDCARD checking this for 10068
08-29 14:20:43.211  7159  7159 I libpersona: KNOX_SDCARD not a persona
08-29 14:20:43.211  1014  1487 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7159 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-29 14:20:43.211  7159  7159 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 14:20:43.211  7021  7021 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
08-29 14:20:43.221  7159  7159 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 14:20:43.221  7159  7159 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-29 14:20:43.231  7021  7021 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
08-29 14:20:43.231  1456  1727 D TP/MmsSmsProvider: update, matched:300, calling pid = 7021
08-29 14:20:43.231  1456  1727 V TP/MmsSmsProvider: syncDBData start
08-29 14:20:43.231  1456  1727 V TP/MmsSmsProvider: syncDBData sms end
08-29 14:20:43.231  1456  2488 D TP/MmsSmsProvider: query,matched:400, calling pid = 7021
08-29 14:20:43.231  7021  7021 D Mms/MethodReflector: getSubId is called
08-29 14:20:43.231  7021  7021 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-29 14:20:43.231  7021  7021 D Mms/MethodReflector: getTelephonyProperty is called
08-29 14:20:43.231  7021  7021 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-29 14:20:43.231  7021  7021 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-29 14:20:43.231  7021  7021 D Mms/DownloadManager: auto download without roaming -> true
08-29 14:20:43.231  7021  7021 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-29 14:20:43.231  7021  7021 D Mms/DownloadManager: mAutoDownload ------> true
08-29 14:20:43.241  1456  1727 V TP/MmsSmsProvider: syncDBData mms end
08-29 14:20:43.241  7021  7150 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 44.299167
08-29 14:20:43.241  6798  6857 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
08-29 14:20:43.241  7021  7021 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
08-29 14:20:43.241  1456  1727 V TP/MmsSmsProvider: syncDBData end
08-29 14:20:43.251  1014  1484 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-29 14:20:43.251  1014  1484 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
08-29 14:20:43.251  1014  1484 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:43.251  1014  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:20:43.251  1014  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
08-29 14:20:43.251  7083  7083 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 14:20:43.251  1932  6879 W art     : Verification of void com.google.android.gms.games.broker.GameAgent.addGameBadgeOps(com.google.android.gms.common.internal.ClientContext, com.google.android.gms.games.server.api.MarketInstance, java.lang.String, java.util.ArrayList, int) took 107.602ms
08-29 14:20:43.261  7021  7153 D Mms/Synchronizer: [end]    doSync consume time = 15.488281
08-29 14:20:43.261  7083  7083 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-29 14:20:43.261  7083  7083 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-29 14:20:43.271  7159  7159 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 14:20:43.271  7159  7159 D ActivityThread: Added TimaKeyStore provider
08-29 14:20:43.271  1014  1510 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
08-29 14:20:43.271  1014  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:43.271  1014  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:43.271  1014  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:43.271  1014  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:43.281  7083  7083 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-29 14:20:43.281  7083  7083 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-29 14:20:43.291  7178  7178 E Zygote  : MountEmulatedStorage()
08-29 14:20:43.291  1014  1510 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7178 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
08-29 14:20:43.291  7178  7178 E Zygote  : v2
08-29 14:20:43.291  7178  7178 I libpersona: KNOX_SDCARD checking this for 10042
08-29 14:20:43.291  7178  7178 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 14:20:43.291  7178  7178 I libpersona: KNOX_SDCARD not a persona
08-29 14:20:43.301  7178  7178 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 14:20:43.301  7178  7178 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
08-29 14:20:43.311  7021  7177 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
08-29 14:20:43.311  7021  7177 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
08-29 14:20:43.311  1014  1484 I ActivityManager: Killing 6344:com.android.calendar/u0a131 (adj 15): empty #21
08-29 14:20:43.311  1014  1484 I ActivityManager: Killing 6325:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #22
08-29 14:20:43.341  6798  6857 I AcmsKeyStoreHelper: Key Store exist
08-29 14:20:43.341  6798  6857 I AcmsKeyStoreHelper: Hence loading the keystore file
08-29 14:20:43.361  7021  7122 D Mms/ArtClassLoader: init [DONE] art
08-29 14:20:43.361  7178  7178 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 14:20:43.361  7178  7178 D ActivityThread: Added TimaKeyStore provider
08-29 14:20:43.371  7159  7159 D BadgeProvider: onCreate
08-29 14:20:43.371  7159  7159 D BadgeProvider: DatabaseHelper
,08-29 14:20:43.381  7178  7178 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 14:20:43.381  7178  7178 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-29 14:20:43.381  7178  7178 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-29 14:20:43.391  7021  7147 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-29 14:20:43.401  1456  1476 D TP/SmsProvider: query,matched:26, calling pid = 7021
,08-29 14:20:43.401  1456  1476 D TP/SmsProvider: match 26:Elapsed time : 2.868 ms
,08-29 14:20:43.411  1456  2488 D TP/MmsSmsProvider: query,matched:6, calling pid = 7021
,08-29 14:20:43.411  1456  2488 D TP/MmsSmsProvider: match 6:Elapsed time : 0.973 ms
,08-29 14:20:43.431  1014  1253 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,08-29 14:20:43.431  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:20:43.431  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:20:43.431  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:43.431  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:20:43.431  6798  6857 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit,
08-29 14:20:43.431  6798  6857 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-29 14:20:43.431  6798  6857 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-29 14:20:43.431  6798  6857 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,08-29 14:20:43.431  6798  6857 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-29 14:20:43.431  6798  6857 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
08-29 14:20:43.431  6798  6857 D AcmsCore: This is NOT a valid MirrorLink app
08-29 14:20:43.431  6798  6857 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
,08-29 14:20:43.431  6798  6857 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-29 14:20:43.431  6798  6857 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-29 14:20:43.431  6798  6857 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,08-29 14:20:43.451  7196  7196 E Zygote  : MountEmulatedStorage(),
,08-29 14:20:43.451  1014  1253 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7196 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,08-29 14:20:43.451  7196  7196 E Zygote  : v2
08-29 14:20:43.451  7196  7196 I libpersona: KNOX_SDCARD checking this for 10023
08-29 14:20:43.451  6798  6798 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-29 14:20:43.451  7196  7196 I libpersona: KNOX_SDCARD not a persona
08-29 14:20:43.451  6798  6798 D AcmsService: Enter onDestroy
08-29 14:20:43.451  6798  6798 I AcmsService: cleanUp(): inside service clean up
08-29 14:20:43.451  6798  6798 D AcmsCore: AcmsCore: inside DeInit
08-29 14:20:43.451  6798  6798 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
08-29 14:20:43.451  6798  6798 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
08-29 14:20:43.451  6798  6798 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-29 14:20:43.451  6798  6798 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-29 14:20:43.451  6798  6798 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
08-29 14:20:43.451  7196  7196 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 14:20:43.451  6798  6798 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-29 14:20:43.451  6798  6798 D AcmsService: killing acms process
08-29 14:20:43.451  6798  6798 I Process : Sending signal. PID: 6798 SIG: 9
08-29 14:20:43.451  7196  7196 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 14:20:43.461  7196  7196 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 14:20:43.471  7178  7178 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,08-29 14:20:43.471  7196  7196 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 14:20:43.471  1014  1026 I ActivityManager: Killing 6440:com.android.defcontainer/u0a3 (adj 15): empty #21
08-29 14:20:43.471  7196  7196 D ActivityThread: Added TimaKeyStore provider
,08-29 14:20:43.481  1014  1484 I ActivityManager: Killing 6703:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
,08-29 14:20:43.491  1014  1054 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
08-29 14:20:43.491  1014  1054 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-29 14:20:43.491  1014  1054 W ActivityManager: Application dead when creating service ServiceRecord{d7186e9 u0 com.android.defcontainer/.DefaultContainerService}
,08-29 14:20:43.491  1014  1054 W ActivityManager: Scheduling restart of crashed service com.android.defcontainer/.DefaultContainerService in 18104ms
,08-29 14:20:43.491  1932  4291 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
08-29 14:20:43.491  1014  1054 W ActivityManager: Scheduling restart of crashed service com.android.defcontainer/.DefaultContainerService in 72416ms
,08-29 14:20:43.491  1014  1487 W ActivityManager: Spurious death for ProcessRecord{11a79f6e 0:com.android.defcontainer/u0a3}, curProc for 6440: null
,08-29 14:20:43.511  1014  1336 I ActivityManager: Process ACMS.Process (pid 6798)(adj 0) has died(52,772)
,08-29 14:20:43.551  7083  7083 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 14:20:43.551  7196  7196 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,08-29 14:20:43.571  1014  1482 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
,08-29 14:20:43.571  1014  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:43.571  1014  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:43.571  1014  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:43.571  1014  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:20:43.571  7083  7083 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 14:20:43.581  1932  4291 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-29 14:20:43.591  7215  7215 E Zygote  : MountEmulatedStorage()
,08-29 14:20:43.591  7215  7215 E Zygote  : v2
08-29 14:20:43.591  7215  7215 I libpersona: KNOX_SDCARD checking this for 1000
,08-29 14:20:43.591  7215  7215 I libpersona: KNOX_SDCARD not a persona
08-29 14:20:43.591  7215  7215 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 14:20:43.591  1014  1482 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7215 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-29 14:20:43.601  7215  7215 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 14:20:43.601  7196  7196 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false,
,08-29 14:20:43.601  7021  7147 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
08-29 14:20:43.601  7083  7083 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-29 14:20:43.601  7083  7083 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-29 14:20:43.601  7196  7196 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-29 14:20:43.601  7196  7196 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-29 14:20:43.611  7196  7196 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,08-29 14:20:43.611  7196  7196 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,08-29 14:20:43.611  7196  7196 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-29 14:20:43.611  7196  7196 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false,
,08-29 14:20:43.611  7083  7083 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-29 14:20:43.611  7196  7196 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-29 14:20:43.611  7196  7196 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-29 14:20:43.621  7215  7215 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 14:20:43.621  7196  7196 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-29 14:20:43.621  7196  7196 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-29 14:20:43.621  7196  7196 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-29 14:20:43.621  7196  7196 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
08-29 14:20:43.621  7083  7083 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 14:20:43.621  7083  7083 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 14:20:43.631  1014  1484 I ActivityManager: Killing 6716:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
,08-29 14:20:43.651  7215  7215 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 14:20:43.651  7215  7215 D ActivityThread: Added TimaKeyStore provider
,08-29 14:20:43.671  1932  4291 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
,08-29 14:20:43.681  1014  1208 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-29 14:20:43.681  1014  1208 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:43.681  1014  1208 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:43.681  1014  1208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:20:43.681  7215  7215 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
,08-29 14:20:43.681  7215  7215 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,08-29 14:20:43.681  1014  1510 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
08-29 14:20:43.681  1014  1510 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
08-29 14:20:43.681  1014  1510 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:43.681  1014  1510 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:20:43.681  1014  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
08-29 14:20:43.691  1014  1026 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-29 14:20:43.691  7215  7215 I FilterInstaller: FilterPackageService : ACTION_CHANGED
,08-29 14:20:43.691  6905  7213 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-29 14:20:43.691  6905  7213 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-29 14:20:43.711  7083  7236 D OpenGLRenderer: Render dirty regions requested: true
,08-29 14:20:43.711  1014  1484 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-29 14:20:43.711  1014  1484 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-29 14:20:43.711  1014  1484 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-29 14:20:43.711  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-29 14:20:43.711  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,08-29 14:20:43.721  7215  7234 E FilterInstaller: installFilters
,08-29 14:20:43.721  7215  7234 E FilterInstaller: There is no requred permission
,08-29 14:20:43.721  7083  7083 V ActivityThread: updateVisibility : ActivityRecord{261e2498 token=android.os.BinderProxy@372b160a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-29 14:20:43.721  7083  7156 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-29 14:20:43.721  1014  1336 I ActivityManager: Killing 6755:com.samsung.helphub/1000 (adj 15): empty #21
,08-29 14:20:43.731  7083  7083 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,08-29 14:20:43.731  7083  7083 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-29 14:20:43.741   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-29 14:20:43.751  6905  7213 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-29 14:20:43.761  1014  1026 D InputDispatcher: Focus entered window: 7083
,08-29 14:20:43.761  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-29 14:20:43.761  7083  7083 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-29 14:20:43.761  7083  7236 I OpenGLRenderer: Initialized EGL, version 1.4
08-29 14:20:43.761  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 14:20:43.771  7083  7236 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-29 14:20:43.771  7083  7236 D OpenGLRenderer: Enabling debug mode 0
,08-29 14:20:43.791  1014  1208 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-29 14:20:43.801  1170  1170 D PanelView: There is/are notification(s) 
,08-29 14:20:43.801  1014  7241 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 14:20:43.811  6905  7213 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-29 14:20:43.811  6905  7213 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@e6e3e0f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-29 14:20:43.811  6905  7213 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-29 14:20:43.811  1014  1045 I ActivityManager: Displayed Component not be shown by security: +1s178ms (total +1s385ms)
,08-29 14:20:43.821  1868  1868 I SamsungIME: getCurrentCandidateView
,08-29 14:20:43.821  1014  1045 W ActivityManager: mDVFSHelper.release()
08-29 14:20:43.821  1014  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1eef85e3 u0 com.test.thalitest/.MainActivity t163} time:100010
,08-29 14:20:43.821   257   453 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-29 14:20:43.821   257   453 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-29 14:20:43.831  7083  7083 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-29 14:20:43.831  7083  7083 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@372b160a time:100024,
,08-29 14:20:43.961  1868  1868 D SamsungIME: Dismiss ExpandCandiate
,08-29 14:20:43.991  7083  7083 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7083
,08-29 14:20:44.101  1868  1868 I SamsungIME: getDebugLevel  : 0x4f4c
,08-29 14:20:44.141  1868  1868 I SamsungIME: getDebugLevel  : 0x4f4c
,08-29 14:20:44.151  1868  1868 I SamsungIME: KeybaordView init() : load resources
,08-29 14:20:44.151  1014  1486 I ActivityManager: Killing 6772:com.sec.spp.push/u0a32 (adj 15): empty #21
,08-29 14:20:44.181  1868  1868 I SamsungIME: getCurrentKeyboard
,08-29 14:20:44.181  1868  1868 I SamsungIME: getTextKeyboard
,08-29 14:20:44.191  7083  7083 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 14:20:44.211  1868  1868 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-29 14:20:44.281  7083  7244 D jxcore_app_log: JniHelper::setJavaVM(0xb849b2b0), pthread_self() = -1197296096
,08-29 14:20:44.281  7083  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 14:20:44.281  7083  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 14:20:44.281  7083  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 14:20:44.281  7083  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 14:20:44.281  7083  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 14:20:44.281  7083  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde2a4f added. We now have 1 listener(s)
,08-29 14:20:44.291  7083  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,08-29 14:20:44.291  7083  7244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-29 14:20:44.291  7083  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 14:20:44.291  7083  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 14:20:44.301  7083  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 14:20:44.301  7083  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 14:20:44.301  7083  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 14:20:44.301  7083  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-29 14:20:44.301  7083  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 14:20:44.301  7083  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 14:20:44.301  7083  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 14:20:44.301  7083  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 14:20:44.301  7083  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 14:20:44.301  7083  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 14:20:44.301  7083  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 14:20:44.301  7083  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 14:20:44.301  7083  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 14:20:44.301  7083  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-29 14:20:44.301  7083  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3abd15ba added. We now have 1 listener(s)
,08-29 14:20:44.301  7083  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:20:44.301  7083  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 14:20:44.301  7083  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 14:20:44.301  7083  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-29 14:20:44.301  7083  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 14:20:44.301  7083  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 14:20:44.311  7083  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:20:44.311  7083  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,08-29 14:20:44.321  7083  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-29 14:20:44.321  7083  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:20:44.321  7083  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:20:44.321  7083  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:20:44.321  7083  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:20:44.321  7083  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:20:44.321  7083  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:20:44.321  7083  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:20:44.321  7083  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:20:44.321  7083  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 14:20:44.321  7083  7244 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 14:20:44.321  7083  7244 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 14:20:44.321  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:20:44.331  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:20:44.351  7083  7083 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 14:20:44.831  7083  7251 W jxcore-log: Initializing JXcore engine
08-29 14:20:44.831  7083  7251 W jxcore-log: JXcore engine is ready
,08-29 14:20:44.861   287   287 E SMD     : DCD OFF
,08-29 14:20:44.881  2018  2018 E audit   : type=1400 msg=audit(1472473244.881:205): avc:  denied  { ioctl } for  pid=7251 comm="Thread-1346" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-29 14:20:44.881  2018  2018 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-29 14:20:44.881  2018  2018 E audit   : type=1300 msg=audit(1472473244.881:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e0fb8f8 items=0 ppid=305 ppcomm=main pid=7251 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1346" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-29 14:20:44.891  2018  2018 E audit   : type=1320 msg=audit(1472473244.881:205): 
,08-29 14:20:44.901  7083  7251 W jxcore-log: Starting JXcore engine,
,08-29 14:20:45.001  7083  7251 W jxcore-log: Platform android
08-29 14:20:45.001  7083  7251 W jxcore-log: 
08-29 14:20:45.001  7083  7251 W jxcore-log: Process ARCH arm
08-29 14:20:45.001  7083  7251 W jxcore-log: 
,08-29 14:20:45.151  7021  7021 I Mms/MmsApp:  start initViewCache mms
,08-29 14:20:45.151  7021  7021 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1899.682135
,08-29 14:20:45.161  7021  7021 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-29 14:20:45.221  7083  7251 I jxcore-log: JXcore Cordova bridge is ready!
08-29 14:20:45.221  7083  7251 I jxcore-log: 
,08-29 14:20:45.221  7083  7251 W jxcore-log: JXcore engine is started
,08-29 14:20:45.231  7083  7244 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 14:20:45.231  7083  7083 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 14:20:45.261  7021  7021 D AbsListView: Get MotionRecognitionManager
,08-29 14:20:45.261  1014  1253 D MotionRecognitionService:  ssp status : false
,08-29 14:20:45.271  7021  7021 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 112.220364
,08-29 14:20:45.351  7021  7021 D Mms/BubbleViewCache: fillCache bubble = 1
,08-29 14:20:46.671  1014  3374 D SSRM:n  : SIOP:: AP = 420
,08-29 14:20:47.181  1014  3396 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 14:20:47.661  2635  2635 I ConfigService: onDestroy
,08-29 14:20:47.861   287   287 E SMD     : DCD OFF
,08-29 14:20:49.771  1014  1510 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 14:20:49.771  1014  1510 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4255, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-29 14:20:49.771  1014  1510 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 14:20:49.771  1014  1510 D BatteryService: stay LED for charging
08-29 14:20:49.771  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 14:20:49.771  1170  1170 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 14:20:49.771  1170  1170 D KeyguardUpdateMonitor: handleBatteryUpdate,
08-29 14:20:49.771  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 14:20:49.771  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 14:20:49.781  1014  1014 I MotionRecognitionService: Plugged
08-29 14:20:49.781  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
08-29 14:20:49.791  3235  3235 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-29 14:20:49.791  3235  3375 D HeadsetStateMachine: Disconnected process message: 10
08-29 14:20:49.801  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-29 14:20:49.801  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-29 14:20:49.801  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-29 14:20:50.861   287   287 E SMD     : DCD OFF
,08-29 14:20:51.601  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-29 14:20:51.601  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:51.601  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:51.601  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:20:51.611  1014  1040 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=7255 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
,08-29 14:20:51.611  7255  7255 E Zygote  : MountEmulatedStorage(),
08-29 14:20:51.611  7255  7255 E Zygote  : v2
08-29 14:20:51.611  7255  7255 I libpersona: KNOX_SDCARD checking this for 10011
08-29 14:20:51.611  7255  7255 I libpersona: KNOX_SDCARD not a persona
,08-29 14:20:51.611  7255  7255 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 14:20:51.621  7255  7255 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 14:20:51.621  7255  7255 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-29 14:20:51.641  7255  7255 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 14:20:51.641  7255  7255 D ActivityThread: Added TimaKeyStore provider
,08-29 14:20:51.661  7255  7255 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-29 14:20:51.661  7255  7255 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-29 14:20:51.701  7255  7255 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>,
08-29 14:20:51.701  7255  7255 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-29 14:20:51.711  7255  7255 I MultiDex: VM with version 2.1.0 has multidex support,
08-29 14:20:51.711  7255  7255 I MultiDex: install
08-29 14:20:51.711  7255  7255 I MultiDex: VM has multidex support, MultiDex support library is disabled.,
,08-29 14:20:51.731  7255  7255 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-29 14:20:51.791  7255  7255 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-29 14:20:51.791  7255  7255 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@fec1d9d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-29 14:20:51.791  7255  7255 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-29 14:20:51.791  1014  1040 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:20:51.801  1014  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:51.801  1014  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:20:51.801  1014  1486 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 14:20:51.801  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-29 14:20:51.801  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:51.801  1014  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:51.801  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:20:51.801  1014  1336 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,08-29 14:20:51.801  1014  1336 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
08-29 14:20:51.801  1014  1336 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
,08-29 14:20:51.801  2635  5107 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-29 14:20:51.801  1014  1336 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,08-29 14:20:51.801  1014  1336 W ActivityManager: userId = 0, bbcId = -10000,
08-29 14:20:51.801  1014  1336 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:51.801  1014  1336 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:20:51.811  1014  1484 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:20:51.811  1014  1484 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:51.811  1014  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:20:51.811  2635  2635 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-29 14:20:51.821  1014  1482 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:20:51.821  1014  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:51.821  1014  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:20:51.821  1014  3867 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 14:20:51.821  1014  3867 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,08-29 14:20:51.821  1014  3867 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:51.821  1014  3867 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:51.821  1014  3867 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:20:51.831  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:20:51.831  1014  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:51.831  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:20:51.831  2635  2635 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:20:51.841  2635  2635 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:20:51.841  1014  1487 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:20:51.841  1014  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:51.841  1014  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:20:51.841  1014  1320 E Watchdog: !@Sync 3
,08-29 14:20:51.841  1932  1932 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-29 14:20:51.851  1014  1336 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 14:20:51.851  1014  1336 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,08-29 14:20:51.851  1014  1336 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:51.851  1014  1336 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 14:20:51.851  1014  1336 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:20:51.851  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:20:51.851  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:51.851  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:20:51.861  7255  7274 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0
08-29 14:20:51.861  1014  1486 I ActivityManager: Killing 6734:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,08-29 14:20:51.861  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:20:51.861  1014  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:51.861  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:20:51.871  1014  1336 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:20:51.871  1014  1336 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 14:20:51.871  1014  1336 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:20:51.881  1014  1336 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:20:51.881  1014  1336 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:51.881  1014  1336 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:20:51.881  1014  1482 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-29 14:20:51.881  1014  1482 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:51.881  1014  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:51.881  1014  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:20:51.891  7255  7255 D WearableService: callingUid 10011, callindPid: 7255
,08-29 14:20:51.901  1014  1336 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:20:51.901  1014  1336 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:51.901  1014  1336 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:20:51.921  1014  1484 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:20:51.921  1014  1484 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:51.921  1014  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:20:51.921  1014  3867 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:20:51.921  1014  3867 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:51.921  1014  3867 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:20:51.931  1014  1482 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 14:20:51.931  1014  1482 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:20:51.931  1014  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 14:20:51.931  1014  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:20:51.941  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:51.941  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:51.941  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:20:51.951  1014  1487 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 14:20:51.951  1014  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,08-29 14:20:51.951  1014  1487 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:51.951  1014  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 14:20:51.951  1014  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:20:51.951  1729  3179 E MDM     : [182] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-29 14:20:51.951  1932  7277 D LocationInitializer: Restart initialization of location
,08-29 14:20:51.951  1014  3867 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 14:20:51.951  1014  3867 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,08-29 14:20:51.951  1014  3867 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:51.951  1014  3867 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 14:20:51.951  1014  3867 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:20:51.971  1014  1484 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 14:20:51.971  1014  1484 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:20:51.971  1014  1484 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:51.971  1014  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:20:52.471  1014  1054 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-29 14:20:52.871   317   317 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-29 14:20:52.871   317   317 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 14:20:53.861   287   287 E SMD     : DCD OFF
,08-29 14:20:56.571  1014  1047 I PowerManagerService: [PWL] Off : 50s ago
,08-29 14:20:56.701  1014  3374 D SSRM:n  : SIOP:: AP = 400,
,08-29 14:20:56.861   287   287 E SMD     : DCD OFF
,08-29 14:20:57.781  1014  1094 V AlarmManager: waitForAlarm result :4
,08-29 14:20:57.781  1014  1094 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,08-29 14:20:57.871   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 14:20:57.901  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-29 14:20:57.901  7083  7251 I jxcore-log: 
,08-29 14:20:57.911  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-29 14:20:57.911  7083  7251 I jxcore-log: 
,08-29 14:20:57.911  7083  7251 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:20:57.911  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:20:57.911  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:20:57.911  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:20:57.911  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:20:57.911  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:20:57.911  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:20:57.911  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:20:57.911  7083  7251 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 14:20:57.921  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 14:20:57.921  7083  7251 I jxcore-log: 
,08-29 14:20:57.921  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 14:20:57.921  7083  7251 I jxcore-log: 
,08-29 14:20:57.941  1014  3867 I art     : Explicit concurrent mark sweep GC freed 24763(1449KB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 23MB/34MB, paused 2.500ms total 138.099ms
,08-29 14:20:58.141  6973  7123 D Finsky  : [1314] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,08-29 14:20:58.141  6973  6973 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-29 14:20:58.601  7083  7251 D executeNativeTests: Running unit tests
,08-29 14:20:58.691  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:20:58.691  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e34f5f added. We now have 2 listener(s)
,08-29 14:20:58.691  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-29 14:20:58.691  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:20:58.691  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 14:20:58.691  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:20:58.691  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac added. We now have 2 listener(s)
08-29 14:20:58.691  7083  7251 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:20:58.691  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 14:20:58.691  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:20:58.701  7083  7251 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:20:58.701  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:20:58.701  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:20:58.701  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:20:58.701  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:20:58.701  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:20:58.701  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:20:58.701  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:20:58.701  7083  7251 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 14:20:58.701  7083  7251 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 14:20:58.701  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:20:58.701  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:20:58.701  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 14:20:58.701  7083  7251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
,08-29 14:20:58.701  7083  7251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 14:20:58.711  7083  7251 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 14:20:58.711  7083  7251 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-29 14:20:58.711  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 14:20:58.711  7083  7251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 14:20:58.711  7083  7251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 14:20:58.711  7083  7251 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:20:58.711  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:20:58.711  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:20:58.711  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:20:58.711  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:58.711  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:20:58.711  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 14:20:58.711  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e34f5f removed from the list
,08-29 14:20:58.711  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:58.711  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac removed from the list
08-29 14:20:58.711  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 14:20:58.711  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:58.711  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:58.711  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:58.711  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:20:58.711  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 14:20:58.711  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:58.711  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
,08-29 14:20:58.711  7083  7251 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported,
08-29 14:20:58.711  7083  7251 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:20:58.711  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:20:58.711  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:20:58.711  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:20:58.711  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:58.711  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:58.711  7083  7251 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e34f5f not in the list
08-29 14:20:58.711  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:20:58.711  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:58.711  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:20:58.711  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:58.711  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:58.711  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 14:20:58.711  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:58.711  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:20:58.711  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 14:20:58.711  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:58.711  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
,08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310],
08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010],
08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 14:20:58.721  7083  7251 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:20:58.721  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:20:58.721  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:20:58.721  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:20:58.721  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:58.721  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:58.721  7083  7251 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e34f5f not in the list
08-29 14:20:58.721  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:58.721  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:58.721  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:20:58.721  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:58.721  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:58.721  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:58.721  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:58.721  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:20:58.721  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:20:58.721  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:58.721  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:58.721  7083  7251 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 14:20:58.721  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:20:58.731  7083  7251 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:20:58.731  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:20:58.731  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:20:58.731  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:20:58.731  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:20:58.731  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:20:58.731  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:20:58.731  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 14:20:58.731  7083  7251 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 14:20:58.731  7083  7251 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 14:20:58.731  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 14:20:58.731  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 14:20:58.731  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 14:20:58.731  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:20:58.731  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 14:20:58.731  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 14:20:58.731  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:20:58.741  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:20:58.741  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 14:20:58.741  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 14:20:58.751  7083  7251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-29 14:20:58.751  7083  7251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-29 14:20:58.751  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 14:20:58.751  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 14:20:58.751  7083  7251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 14:20:58.751  3235  3248 D BtGatt.GattService: registerClient() - UUID=e847ea4d-3cb0-4ade-bdca-aa229648f417
,08-29 14:20:58.801  3235  3317 D BtGatt.GattService: onClientRegistered() - UUID=e847ea4d-3cb0-4ade-bdca-aa229648f417, clientIf=6
,08-29 14:20:58.811  7083  7242 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 14:20:58.811  3235  3318 D BtGatt.GattService: start scan with filters
,08-29 14:20:58.811  3235  3373 D BtGatt.ScanManager: handling starting scan
,08-29 14:20:58.811  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 14:20:58.811  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 14:20:58.811  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 14:20:58.821  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 14:20:58.821  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 14:20:58.821  3235  3373 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
,08-29 14:20:58.821  7083  7083 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 14:20:58.821  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
,08-29 14:20:58.831  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 14:20:58.831  3235  3317 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 14:20:58.831  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 14:20:58.831  3235  3373 D BtGatt.ScanManager: allow scan with filters
08-29 14:20:58.831  3235  3373 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-29 14:20:58.831  3235  3373 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-29 14:20:58.841  7083  7251 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 14:20:58.841  3235  3317 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-29 14:20:58.841  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 14:20:58.841  3235  3373 D BtGatt.ScanManager: Starting BLE batch scan
08-29 14:20:58.841  3235  3373 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 14:20:58.841  7083  7251 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 14:20:58.841  7083  7251 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 14:20:58.841  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
08-29 14:20:58.841  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 14:20:58.841  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:58.841  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 14:20:58.851  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 14:20:58.851  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 14:20:58.851  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 14:20:58.851  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 14:20:58.851  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 14:20:58.851  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 14:20:58.851  3235  3248 D BtGatt.GattService: stopScan() - queue size =1
,08-29 14:20:58.851  3235  3394 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 14:20:58.851  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:20:58.851  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 14:20:58.851  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 14:20:58.851  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 14:20:58.851  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 14:20:58.851  3235  3317 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-29 14:20:58.851  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 14:20:58.851  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 14:20:58.851  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 14:20:58.851  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 14:20:58.861  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 14:20:58.861  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:20:58.861  7083  7083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:20:58.861  7083  7083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:20:58.861  7083  7083 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 14:20:58.861  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:20:58.861  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:58.861  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:20:58.861  7083  7251 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e34f5f not in the list
08-29 14:20:58.861  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:58.861  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:58.861  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:20:58.861  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:20:58.861  7083  7251 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 14:20:58.861  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:20:58.861  3235  3317 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-29 14:20:58.861  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 14:20:58.871  3235  3373 D BtGatt.ScanManager: filter size is 1
08-29 14:20:58.871  3235  3373 D BtGatt.ScanManager: delete FilterIndex - 3
,08-29 14:20:58.871   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 14:20:58.871  7083  7251 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:20:58.871  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:20:58.871  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:20:58.871  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:20:58.871  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:20:58.871  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:20:58.871  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:20:58.871  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:20:58.871  3235  3317 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-29 14:20:58.871  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 14:20:58.871  3235  3373 D BtGatt.ScanManager: stopping BLe Batch
,08-29 14:20:58.881  7083  7251 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 14:20:58.881  7083  7251 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 14:20:58.881  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 14:20:58.881  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 14:20:58.881  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 14:20:58.881  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:20:58.881  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 14:20:58.881  3235  3317 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 14:20:58.881  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 14:20:58.881  3235  3373 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 14:20:58.881  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 14:20:58.881  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:20:58.891  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:20:58.891  3235  3317 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-29 14:20:58.891  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 14:20:58.891  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 14:20:58.891  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 14:20:58.901  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 14:20:58.901  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 14:20:58.901  7083  7251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 14:20:58.901  3235  3394 D BtGatt.GattService: registerClient() - UUID=8769fe62-83c2-43a7-89c5-a5889a9abfa2
,08-29 14:20:58.951  3235  3317 D BtGatt.GattService: onClientRegistered() - UUID=8769fe62-83c2-43a7-89c5-a5889a9abfa2, clientIf=6
,08-29 14:20:58.951  7083  7094 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 14:20:58.951  3235  3244 D BtGatt.GattService: start scan with filters
,08-29 14:20:58.951  3235  3373 D BtGatt.ScanManager: handling starting scan
,08-29 14:20:58.951  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 14:20:58.951  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 14:20:58.951  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 14:20:58.951  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 14:20:58.951  3235  3317 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 14:20:58.961  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 14:20:58.961  3235  3373 D BtGatt.ScanManager: allow scan with filters
,08-29 14:20:58.961  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 14:20:58.961  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 14:20:58.961  7083  7083 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 14:20:58.961  3235  3373 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-29 14:20:58.961  3235  3373 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-29 14:20:58.961  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 14:20:58.971  3235  3317 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-29 14:20:58.971  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 14:20:58.971  3235  3373 D BtGatt.ScanManager: Starting BLE batch scan
08-29 14:20:58.971  3235  3373 D BtGatt.ScanManager: configuring batch scan storage, appIf 6,
08-29 14:20:58.971  7083  7251 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 14:20:58.971  3235  3317 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-29 14:20:58.971  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 14:20:58.971  7083  7251 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:20:58.971  7083  7251 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 14:20:58.971  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 14:20:58.971  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 14:20:58.971  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:58.971  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 14:20:58.971  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 14:20:58.971  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 14:20:58.971  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 14:20:58.971  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 14:20:58.971  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 14:20:58.971  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 14:20:58.971  3235  3248 D BtGatt.GattService: stopScan() - queue size =1
,08-29 14:20:58.981  3235  3394 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 14:20:58.981  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 14:20:58.981  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 14:20:58.981  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 14:20:58.981  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 14:20:58.981  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 14:20:58.981  3235  3317 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-29 14:20:58.981  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 14:20:58.991  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 14:20:58.991  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 14:20:58.991  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 14:20:58.991  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 14:20:58.991  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:20:58.991  3235  3373 D BtGatt.ScanManager: filter size is 1
,08-29 14:20:58.991  3235  3373 D BtGatt.ScanManager: delete FilterIndex - 4
,08-29 14:20:58.991  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:20:58.991  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:58.991  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:20:58.991  7083  7251 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e34f5f not in the list
08-29 14:20:58.991  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:58.991  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:58.991  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:20:58.991  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:20:58.991  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:58.991  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:20:58.991  7083  7083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 14:20:58.991  7083  7083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:20:58.991  7083  7083 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 14:20:58.991  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 14:20:59.001  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:20:59.001  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.001  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
,08-29 14:20:59.001  3235  3317 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-29 14:20:59.001  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 14:20:59.001  7083  7251 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 14:20:59.001  3235  3373 D BtGatt.ScanManager: stopping BLe Batch
,08-29 14:20:59.001  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:20:59.001  3235  3317 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 14:20:59.001  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 14:20:59.011  3235  3373 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-29 14:20:59.011  7083  7251 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:20:59.011  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:20:59.011  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:20:59.011  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,08-29 14:20:59.011  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:20:59.011  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:20:59.011  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:20:59.011  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:20:59.011  3235  3317 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-29 14:20:59.011  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 14:20:59.011  7083  7251 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 14:20:59.011  7083  7251 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 14:20:59.021  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 14:20:59.021  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 14:20:59.021  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 14:20:59.021  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:20:59.021  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 14:20:59.021  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:20:59.021  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 14:20:59.021  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:20:59.021  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 14:20:59.031  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 14:20:59.031  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 14:20:59.031  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 14:20:59.031  7083  7251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 14:20:59.031  3235  3394 D BtGatt.GattService: registerClient() - UUID=0bfe1aba-c682-4f77-a0d8-dbdda4f061b8
,08-29 14:20:59.081  3235  3317 D BtGatt.GattService: onClientRegistered() - UUID=0bfe1aba-c682-4f77-a0d8-dbdda4f061b8, clientIf=6
,08-29 14:20:59.081  7083  7094 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 14:20:59.081  3235  3318 D BtGatt.GattService: start scan with filters
,08-29 14:20:59.081  3235  3373 D BtGatt.ScanManager: handling starting scan
,08-29 14:20:59.081  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 14:20:59.081  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 14:20:59.081  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 14:20:59.081  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 14:20:59.081  3235  3317 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 14:20:59.081  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 14:20:59.081  3235  3373 D BtGatt.ScanManager: allow scan with filters
08-29 14:20:59.081  3235  3373 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-29 14:20:59.081  3235  3373 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
08-29 14:20:59.091  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 14:20:59.091  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 14:20:59.091  7083  7083 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 14:20:59.091  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 14:20:59.091  3235  3317 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-29 14:20:59.091  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 14:20:59.091  3235  3373 D BtGatt.ScanManager: Starting BLE batch scan
08-29 14:20:59.091  3235  3373 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 14:20:59.091  7083  7251 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 14:20:59.101  7083  7251 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:20:59.101  7083  7251 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 14:20:59.101  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 14:20:59.101  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 14:20:59.101  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.101  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 14:20:59.101  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 14:20:59.101  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 14:20:59.101  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 14:20:59.101  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 14:20:59.101  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 14:20:59.101  3235  3317 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-29 14:20:59.101  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 14:20:59.101  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 14:20:59.101  3235  3394 D BtGatt.GattService: stopScan() - queue size =1
,08-29 14:20:59.111  3235  3318 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 14:20:59.111  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 14:20:59.111  3235  3317 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-29 14:20:59.111  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 14:20:59.111  3235  3373 D BtGatt.ScanManager: filter size is 1
,08-29 14:20:59.111  3235  3373 D BtGatt.ScanManager: delete FilterIndex - 5
,08-29 14:20:59.111  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 14:20:59.111  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 14:20:59.111  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 14:20:59.111  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 14:20:59.121  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 14:20:59.121  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 14:20:59.121  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 14:20:59.121  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 14:20:59.121  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:20:59.121  3235  3317 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-29 14:20:59.121  7083  7083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:20:59.121  7083  7251 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:20:59.121  7083  7251 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 14:20:59.121  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:20:59.121  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:20:59.121  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:20:59.121  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.121  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:20:59.121  7083  7251 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e34f5f not in the list
08-29 14:20:59.121  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.121  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
,08-29 14:20:59.121  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:20:59.121  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.121  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 14:20:59.121  7083  7083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 14:20:59.121  7083  7083 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 14:20:59.121  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.121  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:20:59.121  3235  3373 D BtGatt.ScanManager: stopping BLe Batch
,08-29 14:20:59.121  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 14:20:59.121  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:20:59.121  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.121  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
,08-29 14:20:59.121  7083  7251 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 14:20:59.131  7083  7251 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 14:20:59.131  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:20:59.131  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:20:59.131  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:20:59.131  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.131  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.131  7083  7251 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e34f5f not in the list
08-29 14:20:59.131  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.131  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.131  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:20:59.131  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.131  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.131  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.131  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:20:59.131  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:20:59.131  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:20:59.131  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:20:59.131  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
,08-29 14:20:59.131  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 14:20:59.131  7083  7251 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 14:20:59.131  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:20:59.131  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 14:20:59.131  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:20:59.131  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.131  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.131  7083  7251 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e34f5f not in the list
,08-29 14:20:59.131  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.131  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.131  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:20:59.131  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.131  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:20:59.131  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.131  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.131  3235  3317 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 14:20:59.131  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 14:20:59.131  3235  3373 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-29 14:20:59.131  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:20:59.131  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 14:20:59.131  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.131  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.131  7083  7251 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-29 14:20:59.131  7083  7251 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:20:59.131  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:20:59.131  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:20:59.131  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:20:59.131  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 14:20:59.131  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:20:59.131  7083  7251 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e34f5f not in the list,
08-29 14:20:59.131  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:20:59.131  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.131  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:20:59.131  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.131  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.131  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.131  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.131  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:20:59.131  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 14:20:59.131  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.131  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.141  7083  7251 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 14:20:59.141  7083  7251 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 14:20:59.141  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:20:59.141  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:20:59.141  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:20:59.141  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:20:59.141  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.141  7083  7251 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e34f5f not in the list
08-29 14:20:59.141  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.141  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:20:59.141  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.141  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.141  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 14:20:59.141  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.141  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:20:59.141  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:20:59.141  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.141  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.141  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 14:20:59.141  7083  7251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 14:20:59.141  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 14:20:59.141  3235  3317 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-29 14:20:59.141  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 14:20:59.141  7083  7251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 14:20:59.141  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 14:20:59.141  7083  7251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 14:20:59.141  7083  7251 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:20:59.141  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:20:59.141  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:20:59.141  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:20:59.141  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.141  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:20:59.141  7083  7251 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e34f5f not in the list
08-29 14:20:59.141  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:20:59.141  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop,
,08-29 14:20:59.141  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:20:59.141  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.141  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:20:59.141  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.141  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:20:59.141  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:20:59.141  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:20:59.141  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.141  7083  7251 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 14:20:59.141  7083  7251 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 14:20:59.141  7083  7251 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 14:20:59.141  7083  7251 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 14:20:59.141  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 14:20:59.151  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 14:20:59.151  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 14:20:59.151  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 14:20:59.151  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 14:20:59.151  7083  7251 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 14:20:59.151  7083  7251 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 14:20:59.151  7083  7251 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 14:20:59.151  7083  7251 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 14:20:59.151  7083  7251 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 14:20:59.151  7083  7251 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 14:20:59.151  7083  7251 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 14:20:59.151  7083  7251 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 14:20:59.151  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 14:20:59.151  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 14:20:59.151  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 14:20:59.151  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 14:20:59.151  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 14:20:59.151  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 14:20:59.151  7083  7251 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 14:20:59.151  7083  7251 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 14:20:59.151  7083  7251 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 14:20:59.151  7083  7251 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:20:59.151  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:20:59.151  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:20:59.151  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:20:59.151  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.151  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.151  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 14:20:59.151  7083  7284 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1410)
08-29 14:20:59.151  7083  7251 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e34f5f not in the list
08-29 14:20:59.151  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.151  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.151  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:20:59.151  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.151  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.151  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.151  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.151  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:20:59.151  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:20:59.151  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.151  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.151  7083  7251 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 14:20:59.151  7083  7251 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:20:59.151  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:20:59.151  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:20:59.151  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:20:59.151  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.151  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.151  7083  7251 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e34f5f not in the list
08-29 14:20:59.151  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.151  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.151  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:20:59.151  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.151  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.151  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.151  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.161  7083  7285 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1410
08-29 14:20:59.161  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:20:59.161  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:20:59.161  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.161  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.161  7083  7251 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 14:20:59.161  7083  7251 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:20:59.161  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:20:59.161  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:20:59.161  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:20:59.161  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.161  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.161  7083  7251 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e34f5f not in the list
08-29 14:20:59.161  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.161  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.161  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:20:59.161  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.161  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.161  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.161  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.161  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:20:59.161  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:20:59.161  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.161  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.161  7083  7251 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 14:20:59.161  7083  7251 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 14:20:59.161  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 14:20:59.161  7083  7251 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 14:20:59.161  7083  7251 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 14:20:59.161  7083  7251 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 14:20:59.161  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 14:20:59.161  7083  7251 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 14:20:59.161  7083  7251 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 14:20:59.161  7083  7251 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 14:20:59.161  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 14:20:59.161  7083  7251 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 14:20:59.161  7083  7251 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:20:59.161  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:20:59.161  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:20:59.161  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:20:59.161  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.161  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.161  7083  7251 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e34f5f not in the list
08-29 14:20:59.161  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.161  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.161  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:20:59.161  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.161  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.161  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.161  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.161  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:20:59.161  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:20:59.161  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.161  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.161  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:20:59.161  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.161  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.161  7083  7251 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e34f5f not in the list
08-29 14:20:59.161  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.161  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.161  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:20:59.161  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.161  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.161  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.161  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.161  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:20:59.161  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.161  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.161  7083  7251 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e34f5f not in the list
08-29 14:20:59.161  7083  7251 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:20:59.161  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:20:59.161  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:20:59.161  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:20:59.161  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.161  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.161  7083  7251 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e34f5f not in the list
08-29 14:20:59.161  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.161  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.161  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:20:59.161  7083  7284 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-29 14:20:59.161  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.161  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.161  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.161  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.161  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:20:59.161  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:20:59.161  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.161  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.161  7083  7284 D BluetoothSocket: connect(): myUserId = 0
08-29 14:20:59.161  7083  7284 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 14:20:59.161  7083  7251 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 14:20:59.161  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:20:59.161  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 14:20:59.171  7083  7251 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 14:20:59.171  7083  7251 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 14:20:59.171  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 14:20:59.171  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 14:20:59.171  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:20:59.171  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 14:20:59.171  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 14:20:59.171  3235  3248 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:20:59.171  7083  7083 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 14:20:59.171  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 14:20:59.171  7083  7284 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
08-29 14:20:59.171  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.171  7083  7251 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 14:20:59.171  7083  7251 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e34f5f not in the list
08-29 14:20:59.171  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.171  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 14:20:59.171  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 14:20:59.171  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 14:20:59.171  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.171  7083  7083 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 14:20:59.171  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.171  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 14:20:59.171  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.171  7083  7251 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:20:59.171  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:20:59.171  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:20:59.171  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:20:59.171  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.171  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.171  7083  7251 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e34f5f not in the list
08-29 14:20:59.171  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.171  7083  7083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:20:59.171  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.171  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:20:59.171  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.171  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.171  7083  7083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:20:59.171  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.171  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.171  7083  7083 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 14:20:59.171  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:20:59.171  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:20:59.171  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.171  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.171  7083  7251 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 14:20:59.171  7083  7251 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 14:20:59.171  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 14:20:59.171  7083  7251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 14:20:59.171  7083  7251 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:20:59.171  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:20:59.171  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:20:59.171  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:20:59.171  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.171  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.171  7083  7251 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e34f5f not in the list
08-29 14:20:59.171  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.171  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.171  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:20:59.171  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.171  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.171  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.171  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.171  7083  7286 D BluetoothSocket: bindListen(): myUserId = 0
08-29 14:20:59.171  7083  7286 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 14:20:59.171  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:20:59.171  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:20:59.171  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.171  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.181  7083  7251 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:20:59.181  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:20:59.181  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:20:59.181  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:20:59.181  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.181  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.181  7083  7251 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e34f5f not in the list
08-29 14:20:59.181  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.181  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.181  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:20:59.181  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.181  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.181  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.181  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.181  7083  7286 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[107]}
08-29 14:20:59.181  7083  7286 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 14:20:59.181  7083  7286 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 14:20:59.181  7083  7286 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@257690ae
,08-29 14:20:59.181  7083  7286 D BluetoothSocket: channel: 6
08-29 14:20:59.181  7083  7286 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2824ce4f, channel: 6, state: LISTENING
08-29 14:20:59.181  7083  7286 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2824ce4f, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@257690ae, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2ea219dcmSocket: android.net.LocalSocket@1b0e3ae5 impl:android.net.LocalSocketImpl@d1f09ba fd:FileDescriptor[107]
08-29 14:20:59.181  7083  7286 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1b0e3ae5 impl:android.net.LocalSocketImpl@d1f09ba fd:FileDescriptor[107]
08-29 14:20:59.181  7083  7286 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 14:20:59.181  7083  7286 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 14:20:59.181  7083  7286 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 14:20:59.181  7083  7083 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 14:20:59.181  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:20:59.181  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:20:59.181  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.181  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.181  7083  7251 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:20:59.181  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:20:59.181  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:20:59.181  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:20:59.181  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.181  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.181  7083  7251 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e34f5f not in the list
08-29 14:20:59.181  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.181  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.181  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:20:59.181  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.181  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.181  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:20:59.181  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:20:59.181  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:20:59.181  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:20:59.181  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:20:59.181  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c71edac not in the list
08-29 14:20:59.181  7083  7251 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 14:20:59.181  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 14:20:59.181  7083  7251 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 14:20:59.181  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 14:20:59.181  7083  7251 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 14:20:59.181  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 14:20:59.181  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 14:20:59.181  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 14:20:59.191  7083  7251 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 14:20:59.191  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 14:20:59.191  7083  7251 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 14:20:59.191  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 14:20:59.191  7083  7251 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 14:20:59.191  7083  7251 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 14:20:59.191  7083  7251 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 14:20:59.191  7083  7251 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 14:20:59.191  7083  7251 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 14:20:59.191  7083  7251 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 14:20:59.191  7083  7251 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 14:20:59.191  7083  7251 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 14:20:59.191  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:20:59.191  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b0a006b added. We now have 2 listener(s)
08-29 14:20:59.191  7083  7251 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:20:59.191  7083  7251 D BluetoothAdapter: enable()
08-29 14:20:59.191  7083  7251 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 14:20:59.191  1014  1026 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-29 14:20:59.191  1014  1026 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 14:20:59.191  1014  1026 D SecContentProvider2: mCursor = null
08-29 14:20:59.191  1014  1026 D WifiService: setWifiEnabled: true pid=7083, uid=10170
08-29 14:20:59.201  1014  1026 W ActivityManager: Permission Denial: getCurrentUser() from pid=7083, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-29 14:20:59.201  1014  1026 W WifiService: Failed getting userId using ActivityManagerNative
08-29 14:20:59.201  1014  1026 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7083, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-29 14:20:59.201  1014  1026 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 14:20:59.201  1014  1026 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-29 14:20:59.201  1014  1026 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-29 14:20:59.201  1014  1026 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-29 14:20:59.201  1014  1026 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-29 14:20:59.201  1014  1026 D SettingsProvider: name = wifi_on
08-29 14:20:59.201  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:20:59.201  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d24f7c8 added. We now have 3 listener(s)
08-29 14:20:59.201  7083  7251 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:20:59.211  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:20:59.211  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38eca061 added. We now have 4 listener(s)
08-29 14:20:59.211  7083  7251 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:20:59.211  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:20:59.211  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a40786 added. We now have 5 listener(s)
08-29 14:20:59.211  7083  7251 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:20:59.211  1014  1336 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-29 14:20:59.211  1014  1336 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 14:20:59.211  1014  1336 D SecContentProvider2: mCursor = null
08-29 14:20:59.211  1014  1336 D WifiService: setWifiEnabled: false pid=7083, uid=10170
08-29 14:20:59.211  1014  1336 D SettingsProvider: name = wifi_on
08-29 14:20:59.221  1014  1124 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 14:20:59.221  1377  1377 I wpa_supplicant: reset timer : RESET_TIMER 0
08-29 14:20:59.221  1377  1377 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-29 14:20:59.221  1377  1377 I wpa_supplicant: P2P: Current p2p state = IDLE
08-29 14:20:59.221  1377  1377 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-29 14:20:59.221  7083  7251 D BluetoothAdapter: disable()
,08-29 14:20:59.231  1014  3867 D SettingsProvider: name = bluetooth_on
,08-29 14:20:59.231  1014  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 14:20:59.241  3235  3311 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-29 14:20:59.241  3235  3311 D BluetoothAdapterProperties: Setting state to 13
,08-29 14:20:59.241  3235  3311 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 14:20:59.241  3235  3311 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 14:20:59.241  3235  3311 D BluetoothAdapterService: updateAdapterState state is 13
,08-29 14:20:59.251  1014  1482 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 14:20:59.251  1014  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 14:20:59.251  1377  1377 I wpa_supplicant: Scan aborted because the firmware maybe busy.
08-29 14:20:59.251  1377  1377 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
08-29 14:20:59.251  1377  1377 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
,08-29 14:20:59.251  1014  1124 E WifiNative-wlan0: do suspend true
,08-29 14:20:59.251  1014  1482 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:20:59.251  1014  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:20:59.251  1014  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:20:59.251  3235  3311 D BluetoothAdapterService: Autoconnection is available 
08-29 14:20:59.251  3235  3311 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-29 14:20:59.251  3235  3311 D BluetoothAdapterService: terminating service from this receiver
,08-29 14:20:59.251  1014  1484 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-29 14:20:59.251  1014  1484 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:59.251  1014  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 14:20:59.251  1014  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:20:59.251  3235  3235 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-29 14:20:59.251  3235  3235 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@f87cef8, channel: 19, state: LISTENING
08-29 14:20:59.251  3235  3235 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@f87cef8, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@45d63e0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@9b2dfd1mSocket: android.net.LocalSocket@e012a36 impl:android.net.LocalSocketImpl@2d1f9d37 fd:FileDescriptor[80]
08-29 14:20:59.251  3235  3235 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@e012a36 impl:android.net.LocalSocketImpl@2d1f9d37 fd:FileDescriptor[80]
08-29 14:20:59.251  3235  3311 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 14:20:59.251  3235  3311 D BluetoothAdapterProperties: mDiscovering is false
,08-29 14:20:59.261  1014  1027 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-29 14:20:59.261  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:20:59.261  3235  3311 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-29 14:20:59.261  4739  4739 D BluetoothPbap: Proxy object disconnected
,08-29 14:20:59.261  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:20:59.261  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,08-29 14:20:59.271  4739  4739 D PbapServerProfile: Bluetooth service disconnected
,08-29 14:20:59.271  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:20:59.271  7083  7251 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:20:59.271  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:20:59.271  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:20:59.271  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:20:59.271  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:20:59.271  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:20:59.271  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:20:59.271  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:20:59.271  3235  3317 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-29 14:20:59.271  3235  3317 D BluetoothAdapterProperties: Scan Mode:20
,08-29 14:20:59.271  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:20:59.271  7083  7251 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 14:20:59.271  7083  7251 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 14:20:59.281  1170  1170 D BluetoothTile:  onBluetoothStateChange:
,08-29 14:20:59.281  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:20:59.281  1170  1170 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:20:59.281  1170  1170 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-29 14:20:59.281  1170  1170 D BluetoothTile:  getBluetoothState : 13
,08-29 14:20:59.281  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:20:59.281  1868  1868 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 14:20:59.291  1014  3867 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 14:20:59.291  1014  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 14:20:59.291  1170  1170 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 14:20:59.291  1170  1768 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 14:20:59.291  4739  4739 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:20:59.291  1170  1768 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 14:20:59.301  1170  1768 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-29 14:20:59.301  3235  3311 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-29 14:20:59.301  3235  3311 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-29 14:20:59.301  3235  3311 E bt-btif : cmd socket is not created
,08-29 14:20:59.301  3235  5285 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 14:20:59.301  3235  3311 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-29 14:20:59.301  7083  7083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:20:59.301  3235  3319 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
08-29 14:20:59.301  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:20:59.301  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:20:59.301  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:20:59.301  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:20:59.301  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:20:59.301  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:20:59.301  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:20:59.301  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:20:59.311  7083  7284 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3b75c874, channel: -1, state: INIT
,08-29 14:20:59.311  7083  7284 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3b75c874, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31f1e19d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@13291612mSocket: android.net.LocalSocket@112411e3 impl:android.net.LocalSocketImpl@260f7e0 fd:FileDescriptor[105]
08-29 14:20:59.311  7083  7284 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@112411e3 impl:android.net.LocalSocketImpl@260f7e0 fd:FileDescriptor[105]
08-29 14:20:59.311  7083  7284 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1410)
,08-29 14:20:59.311  3235  3235 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@534a80d, channel: 5, state: LISTENING
08-29 14:20:59.311  3235  3235 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@534a80d, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f71f699, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@9adb3c2mSocket: android.net.LocalSocket@15c6d5d3 impl:android.net.LocalSocketImpl@f018510 fd:FileDescriptor[82]
08-29 14:20:59.311  3235  3235 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@15c6d5d3 impl:android.net.LocalSocketImpl@f018510 fd:FileDescriptor[82]
,08-29 14:20:59.311  7083  7083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:20:59.311  7083  7083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 14:20:59.311  4739  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 14:20:59.311  1014  1485 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 14:20:59.311  1014  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 14:20:59.311  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:59.311  1014  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:20:59.311  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 14:20:59.311  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:20:59.321  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:20:59.321  2635  2635 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 14:20:59.321  3235  3235 I BtOppRfcommListener: stopping Accept Thread
,08-29 14:20:59.321  3235  3319 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
08-29 14:20:59.321  3235  3319 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
08-29 14:20:59.321  3235  3319 W bt-btif : invalid rfc slot id: 4
,08-29 14:20:59.321  4739  4739 D DockEventReceiver: finishStartingService: stopping service
,08-29 14:20:59.321  3235  3235 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1490b809, channel: 12, state: LISTENING
,08-29 14:20:59.321  3235  3235 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1490b809, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2941f65b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@39a74a0emSocket: android.net.LocalSocket@199efc2f impl:android.net.LocalSocketImpl@14e1e23c fd:FileDescriptor[86]
08-29 14:20:59.321  3235  3235 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@199efc2f impl:android.net.LocalSocketImpl@14e1e23c fd:FileDescriptor[86]
08-29 14:20:59.321  3235  3319 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 14:20:59.321  3235  3319 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 14:20:59.321  3235  3319 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 14:20:59.321  3235  3319 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 14:20:59.321  3235  3319 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 14:20:59.321  3235  3319 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-29 14:20:59.321  3235  5285 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-29 14:20:59.321  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:20:59.331  3235  3235 V BluetoothOppManager: cleanUp...
,08-29 14:20:59.331  4739  4739 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 14:20:59.331  1170  1170 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:20:59.331  1170  1170 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-29 14:20:59.331  1014  3867 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-29 14:20:59.341  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:20:59.341  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:20:59.341  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:20:59.341  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:20:59.351  7292  7292 E Zygote  : MountEmulatedStorage(),
,08-29 14:20:59.351  1014  1123 D WifiP2pService: InactiveState{ what=143375 }
08-29 14:20:59.351  7292  7292 E Zygote  : v2
08-29 14:20:59.351  1014  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
08-29 14:20:59.351  7292  7292 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 14:20:59.351  7292  7292 I libpersona: KNOX_SDCARD checking this for 10055
08-29 14:20:59.351  7292  7292 I libpersona: KNOX_SDCARD not a persona
08-29 14:20:59.351  1014  3867 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7292 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-29 14:20:59.351   277  1010 D CommandListener: Clearing all IP addresses on wlan0
08-29 14:20:59.351  7292  7292 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 14:20:59.361  7292  7292 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 14:20:59.361  2635  2673 V NativeCrypto: Read error: ssl=0xb89aebe8: I/O error during system call, Connection timed out
,08-29 14:20:59.361  2635  2673 V NativeCrypto: SSL shutdown failed: ssl=0xb89aebe8: I/O error during system call, Broken pipe
,08-29 14:20:59.361  1170  1170 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-29 14:20:59.361  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-29 14:20:59.361  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 14:20:59.361  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:20:59.361  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:20:59.361  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:20:59.361  1014  1485 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
08-29 14:20:59.361  1014  1762 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:20:59.361  1014  1762 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:20:59.361  1014  1762 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-29 14:20:59.361  1014  1762 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:20:59.361  1014  1762 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-29 14:20:59.361  1014  1762 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 14:20:59.371  1014  1126 E ConnectivityService: updateNetworkInfo()
08-29 14:20:59.371  1014  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 14:20:59.371  1014  1126 E ConnectivityService: updateNetworkInfo()
08-29 14:20:59.371  1014  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,08-29 14:20:59.371  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-29 14:20:59.371  1014  1124 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 14:20:59.371  1014  1123 D WifiP2pService: InactiveState{ what=131204 }
08-29 14:20:59.371  1014  1123 D WifiP2pService: P2pEnabledState{ what=131204 }
08-29 14:20:59.371  1014  1123 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-29 14:20:59.381  1014  1762 I qtaguid : Tagging socket 355 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1014, getuid(): 1000
,08-29 14:20:59.381  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 14:20:59.381  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 14:20:59.381  1014  1014 D RttService: SCAN_AVAILABLE : 1
,08-29 14:20:59.381  1014  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 14:20:59.391  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:20:59.391  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
,08-29 14:20:59.391  1014  1762 I qtaguid : Untagging socket 355
08-29 14:20:59.391  1014  1762 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 14:20:59.391  1014  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED,
08-29 14:20:59.391  7292  7292 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 14:20:59.391  1014  1123 D WifiP2pService: P2pDisablingState
08-29 14:20:59.391  7292  7292 D ActivityThread: Added TimaKeyStore provider
08-29 14:20:59.391  1014  1123 D WifiP2pService: P2pDisablingState{ what=147458 }
08-29 14:20:59.391  1014  1123 D WifiP2pService: p2p socket connection lost
08-29 14:20:59.391  1170  1170 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 14:20:59.391  1014  1123 D WifiP2pService: P2pDisabledState
,08-29 14:20:59.391  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 14:20:59.391  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 14:20:59.391  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 14:20:59.391  1014  1124 E WifiNative-wlan0: do suspend true
08-29 14:20:59.391  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:20:59.391  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:20:59.391  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 14:20:59.401  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-29 14:20:59.401  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-29 14:20:59.401  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-29 14:20:59.401  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-29 14:20:59.401  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 14:20:59.401  1014  1045 D WifiDisplayController: disconnect
08-29 14:20:59.401  1014  1045 D WifiDisplayController: updateConnection
08-29 14:20:59.401  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 14:20:59.401  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-29 14:20:59.401  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 14:20:59.401  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
08-29 14:20:59.401  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 14:20:59.401  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-29 14:20:59.411  1170  1170 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-29 14:20:59.421  1014  1027 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-29 14:20:59.421  1170  1170 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-29 14:20:59.431  7292  7292 D UserAnalysis.PlaceProvider: PlaceProvider onCreate(),
,08-29 14:20:59.431  1014  1123 D WifiP2pService: P2pDisabledState{ what=143375 }
08-29 14:20:59.431  1014  1123 D WifiP2pService: DefaultState{ what=143375 }
,08-29 14:20:59.431  1170  1170 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 14:20:59.431  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 14:20:59.431  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-29 14:20:59.441  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-29 14:20:59.441  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:20:59.441  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-29 14:20:59.441  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 14:20:59.461   277  1006 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
08-29 14:20:59.461   277  1006 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-29 14:20:59.461  1014  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:20:59.461  1014  1126 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-29 14:20:59.461  1014  1126 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-29 14:20:59.461  1014  1126 V NetworkStats: updateIfacesLocked()
08-29 14:20:59.461  7292  7292 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-29 14:20:59.461  1014  1126 V NetworkStats: performPollLocked(flags=0x1),
08-29 14:20:59.461  1014  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 14:20:59.461  7292  7292 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-29 14:20:59.461  7292  7292 D UserAnalysis: Create SecureDbHelper
08-29 14:20:59.461   277  1010 D CommandListener: Clearing all IP addresses on wlan0
08-29 14:20:59.461  1014  1762 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,08-29 14:20:59.461  1014  1762 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-29 14:20:59.471  7292  7292 D IntelligenceServiceApplication: onCreate()
,08-29 14:20:59.471  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-29 14:20:59.481  1014  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
08-29 14:20:59.481  1014  1126 V NetworkStats: performPollLocked() took 19ms
,08-29 14:20:59.481  1377  1377 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-29 14:20:59.481  1170  1170 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 14:20:59.481  1014  1484 I ActivityManager: Killing 6843:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
08-29 14:20:59.481  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 14:20:59.481  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 14:20:59.481  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:20:59.481  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:20:59.481  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:20:59.481  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 14:20:59.491  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:20:59.491  1014  1126 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-29 14:20:59.491  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:20:59.491  1014  1484 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
08-29 14:20:59.491  1014  1126 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-29 14:20:59.491  1014  1762 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:20:59.491  1014  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-29 14:20:59.491  1170  1759 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-29 14:20:59.491  1014  1126 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-29 14:20:59.491  1014  1126 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-29 14:20:59.491  1014  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-29 14:20:59.501  7292  7292 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-29 14:20:59.501  1456  1456 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-29 14:20:59.501  1456  1456 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 14:20:59.501  1014  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:59.501  1014  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:59.501  1014  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:59.501  1014  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:59.501  1014  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-29 14:20:59.511  7313  7313 E Zygote  : MountEmulatedStorage()
08-29 14:20:59.511  7313  7313 E Zygote  : v2
08-29 14:20:59.511  7313  7313 I libpersona: KNOX_SDCARD checking this for 10105
08-29 14:20:59.511  7313  7313 I libpersona: KNOX_SDCARD not a persona
,08-29 14:20:59.521  1014  1484 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7313 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-29 14:20:59.521  7313  7313 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 14:20:59.521  7313  7313 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-29 14:20:59.521  1014  1336 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-29 14:20:59.521  3235  3311 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-29 14:20:59.521  3235  3311 D BtConfig.SecureMode: isSecureModeOn:false
08-29 14:20:59.521  3235  3311 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-29 14:20:59.521  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-29 14:20:59.521  3235  3311 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-29 14:20:59.521  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-29 14:20:59.521  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 14:20:59.521  7292  7292 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-29 14:20:59.521  3235  3311 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-29 14:20:59.521  1014  1126 D ConnectivityService: nai.networkMonitor.doQuit()
08-29 14:20:59.521  1014  1126 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-29 14:20:59.521  1014  1126 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 14:20:59.521  1014  1126 E ConnectivityService: updateNetworkInfo()
08-29 14:20:59.521  1014  1126 E ConnectivityService: updateNetworkInfo()
,08-29 14:20:59.521  1014  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-29 14:20:59.521  7313  7313 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 14:20:59.521  1014  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-29 14:20:59.531  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 14:20:59.531  1014  1124 D SecContentProvider2: mCursor = null
,08-29 14:20:59.531  4739  4739 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-29 14:20:59.531  7292  7292 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-29 14:20:59.531  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-29 14:20:59.531  1014  1128 D Tethering: MasterInitialState.processMessage what=3
,08-29 14:20:59.531  1170  1170 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 14:20:59.541  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 14:20:59.541  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 14:20:59.541  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:20:59.541  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 14:20:59.541  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:20:59.541  1014  1121 V NetworkStats: updateIfacesLocked()
08-29 14:20:59.541  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:20:59.541  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
08-29 14:20:59.541  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:20:59.541  1170  1170 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 14:20:59.541  1170  1170 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 14:20:59.541  1170  1170 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-29 14:20:59.541  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 14:20:59.541  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 14:20:59.541  1170  1768 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 14:20:59.541  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:20:59.541  1014  1121 V NetworkStats: performPollLocked() took 3ms
,08-29 14:20:59.541  1170  1170 D HotspotTile: onReceive : 0, 0
,08-29 14:20:59.541  7083  7083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:20:59.541  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:20:59.541  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:20:59.541  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:20:59.541  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:20:59.541  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:20:59.541  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:20:59.541  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:20:59.541  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:20:59.541  7083  7083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:20:59.541  7083  7083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:20:59.551  1014  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-29 14:20:59.541  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:20:59.551  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:20:59.551  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:20:59.551  1014  3867 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 14:20:59.551  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 14:20:59.551  1014  3867 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-29 14:20:59.551  1014  3867 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:59.551  1014  3867 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:20:59.551  1014  3867 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 14:20:59.551  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-29 14:20:59.551  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-29 14:20:59.551  3235  3311 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-29 14:20:59.551  7083  7083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:20:59.551  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:20:59.551  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:20:59.551  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:20:59.551  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:20:59.551  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:20:59.551  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:20:59.551  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:20:59.551  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:20:59.551  3235  3235 D HeadsetService: Received stop request...Stopping profile...
,08-29 14:20:59.551  7083  7083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:20:59.551  7083  7083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:20:59.551  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:20:59.551  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:20:59.551  1014  1510 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 14:20:59.551  1014  1510 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 14:20:59.551  1014  1510 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:59.551  1014  1510 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:20:59.551  1014  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:20:59.561  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,08-29 14:20:59.561  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 14:20:59.561  7313  7313 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 14:20:59.561  1170  1170 D StatusBar.NetworkController: EthernetConnected: false
08-29 14:20:59.561  1170  1170 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-29 14:20:59.561  1170  1170 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-29 14:20:59.561  1170  1170 D StatusBar.NetworkController: updateDataNetType()
08-29 14:20:59.561  7313  7313 D ActivityThread: Added TimaKeyStore provider
,08-29 14:20:59.561  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
08-29 14:20:59.561  3235  3311 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-29 14:20:59.571  1170  1170 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 14:20:59.571  1170  1170 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-29 14:20:59.571  1014  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 14:20:59.571  1014  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-29 14:20:59.571  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-29 14:20:59.571  1014  1487 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:59.571  1014  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:20:59.571  1014  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 14:20:59.571  3235  3235 D A2dpService: Received stop request...Stopping profile...
08-29 14:20:59.571  3235  3381 D A2dpStateMachine: Exit Disconnected: -1
08-29 14:20:59.571  4739  4739 D HeadsetProfile: Bluetooth service disconnected
08-29 14:20:59.571  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-29 14:20:59.571  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-29 14:20:59.571  3235  3311 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-29 14:20:59.571  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 14:20:59.571  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-29 14:20:59.571  1170  1170 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-29 14:20:59.571  1170  1170 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 19 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-29 14:20:59.571  1170  1170 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-29 14:20:59.571  1170  1170 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-29 14:20:59.571  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:59.571  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:20:59.571  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:20:59.581  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
,08-29 14:20:59.581  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-29 14:20:59.581  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-29 14:20:59.581  1014  1014 D BluetoothA2dp: Proxy object disconnected
08-29 14:20:59.581  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-29 14:20:59.581  3235  3311 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-29 14:20:59.581  4739  4739 D BluetoothA2dp: Proxy object disconnected
08-29 14:20:59.581  4739  4739 D A2dpProfile: Bluetooth service disconnected
,08-29 14:20:59.591  1014  1482 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 14:20:59.591  1014  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 14:20:59.591  1170  1170 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 14:20:59.591  1014  1482 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:59.591  1014  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:20:59.591  1014  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 14:20:59.591  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 14:20:59.591  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 14:20:59.591  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:20:59.591  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:20:59.591  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:20:59.591  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 14:20:59.591  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-29 14:20:59.591  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 14:20:59.591  3235  3311 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-29 14:20:59.591  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 14:20:59.591  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 14:20:59.591  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:20:59.591  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 14:20:59.591  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:20:59.601  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-29 14:20:59.601  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-29 14:20:59.601  3235  3311 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService,
08-29 14:20:59.601  1014  1253 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 14:20:59.601  1014  1253 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 14:20:59.601  1014  1253 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:20:59.601  1014  1253 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 14:20:59.601  1014  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:20:59.601  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-29 14:20:59.601  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 14:20:59.601  3235  3311 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-29 14:20:59.601  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-29 14:20:59.601  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-29 14:20:59.601  3235  3311 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-29 14:20:59.601  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
,08-29 14:20:59.601  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 14:20:59.611  3235  3311 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-29 14:20:59.611  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-29 14:20:59.611  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 14:20:59.611  3235  3311 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-29 14:20:59.611  3235  3311 D BluetoothAdapterState: Stopping profile services that were post enabled
08-29 14:20:59.611  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-29 14:20:59.611  3235  3235 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 14:20:59.611  3235  3235 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-29 14:20:59.611  3235  3235 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-29 14:20:59.611  3235  3235 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-29 14:20:59.611  3235  3235 D HidService: Received stop request...Stopping profile...
08-29 14:20:59.611  3235  3235 D HidService: Stopping Bluetooth HidService,
,08-29 14:20:59.611  3235  3235 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 14:20:59.611  3235  3235 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-29 14:20:59.611  3235  3235 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-29 14:20:59.611  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
08-29 14:20:59.621  3235  3235 D HealthService: Received stop request...Stopping profile...
08-29 14:20:59.621  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
,08-29 14:20:59.621  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true,
08-29 14:20:59.621  3235  3235 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 14:20:59.621  3235  3235 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-29 14:20:59.621  3235  3235 D BluetoothA2dp: Proxy object disconnected
08-29 14:20:59.621  3235  3235 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-29 14:20:59.621  3235  3382 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 14:20:59.621  3235  3235 I GKI_LINUX: GKI_exit_task 2 done
,08-29 14:20:59.621  3235  3235 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-29 14:20:59.621  4739  4739 D BluetoothInputDevice: Proxy object disconnected
08-29 14:20:59.621  4739  4739 D HidProfile: Bluetooth service disconnected
,08-29 14:20:59.621  3235  3235 D PanService: Received stop request...Stopping profile...
08-29 14:20:59.621  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38,
,08-29 14:20:59.621  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 14:20:59.621  4739  4739 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 14:20:59.621  3235  3235 D BluetoothMapService: Received stop request...Stopping profile...
,08-29 14:20:59.631  4739  4739 D PanProfile: Bluetooth service disconnected
08-29 14:20:59.631  1377  1377 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 14:20:59.631  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
,08-29 14:20:59.631  3235  3235 D SapService: Received stop request...Stopping profile...
08-29 14:20:59.631  3235  3235 D SapService: Stopping Bluetooth SapService
08-29 14:20:59.631  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
,08-29 14:20:59.631  4739  4739 D BluetoothMap: Proxy object disconnected
08-29 14:20:59.631  4739  4739 D MapProfile: Bluetooth service disconnected
,08-29 14:20:59.631  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-29 14:20:59.631  3235  3235 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 14:20:59.631  3235  3235 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 14:20:59.631  3235  3235 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 14:20:59.631  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-29 14:20:59.631  3235  3235 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 14:20:59.631  3235  3235 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 14:20:59.631  3235  3235 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 14:20:59.631  3235  3235 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 14:20:59.641  3235  3235 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-29 14:20:59.641  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-29 14:20:59.641  3235  3235 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 14:20:59.641  3235  3235 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 14:20:59.641  3235  3235 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 14:20:59.641  3235  3235 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 14:20:59.641  3235  3235 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 14:20:59.641  4739  4739 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-29 14:20:59.641  4739  4739 D SapProfile: Bluetooth service disconnected
08-29 14:20:59.641  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-29 14:20:59.641  3235  3235 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 14:20:59.641  3235  3235 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 14:20:59.641  3235  3235 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-29 14:20:59.641  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-29 14:20:59.641  3235  3235 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 14:20:59.641  3235  3235 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-29 14:20:59.641  3235  3235 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-29 14:20:59.641  3235  3311 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-29 14:20:59.641  3235  3311 D BluetoothAdapterProperties: Setting state to 10
,08-29 14:20:59.641  3235  3311 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 14:20:59.641  3235  3311 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 14:20:59.641  3235  3311 D BluetoothAdapterService: updateAdapterState state is 10,
08-29 14:20:59.641  3235  3311 D BluetoothAdapterService: Autoconnection is available 
08-29 14:20:59.641  3235  3311 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-29 14:20:59.641  3235  3311 I BluetoothAdapterState: Entering OffState
08-29 14:20:59.641  4739  4747 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 14:20:59.651  2635  2648 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 14:20:59.651  2635  2648 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 14:20:59.651  4739  7289 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 14:20:59.651  1440  1459 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 14:20:59.651  1440  1459 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 14:20:59.651  4739  4746 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 14:20:59.651  3235  3318 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 14:20:59.651  3235  3318 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 14:20:59.661  1170  1188 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 14:20:59.661  1170  1188 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 14:20:59.661  1729  1741 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 14:20:59.661  1729  1741 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 14:20:59.661  4739  7289 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 14:20:59.661  4739  4746 D Bluetoothsap: onBluetoothStateChange: up=false,
08-29 14:20:59.661  4739  4746 D Bluetoothsap: Unbinding service...
,08-29 14:20:59.661  1456  2019 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 14:20:59.661  1456  2019 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan,
,08-29 14:20:59.671  7083  7242 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 14:20:59.671  7083  7242 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 14:20:59.671  7083  7242 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-29 14:20:59.671  7083  7242 D BluetoothLeAdvertiser: Exit stop advertising
08-29 14:20:59.671  7083  7242 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-29 14:20:59.671  7083  7242 D BluetoothLeScanner: Exiting stopAllScan
08-29 14:20:59.671  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 14:20:59.671  1430  1466 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 14:20:59.671  1430  1466 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 14:20:59.671  7083  7083 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-29 14:20:59.671  3235  3248 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 14:20:59.671  4739  7289 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 14:20:59.671  4739  7289 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 14:20:59.671  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 14:20:59.671  1014  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 14:20:59.671  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 14:20:59.681  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 14:20:59.681  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 14:20:59.681  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 14:20:59.681  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-29 14:20:59.681  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
08-29 14:20:59.681  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-29 14:20:59.681  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 14:20:59.681  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 14:20:59.681  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 14:20:59.691  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 14:20:59.691  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 14:20:59.691  1170  1170 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-29 14:20:59.691  1170  1170 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:20:59.691  1170  1170 D BluetoothTile:  getBluetoothState : 10
,08-29 14:20:59.691  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 14:20:59.691  1868  1868 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 14:20:59.691  4739  4739 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:20:59.691  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 14:20:59.701  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 14:20:59.701  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 14:20:59.701  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:20:59.701  1014  1208 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 14:20:59.701  1014  1482 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 14:20:59.701  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:20:59.701  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
,08-29 14:20:59.701  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 14:20:59.701  1170  1170 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-29 14:20:59.701  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 14:20:59.701  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 14:20:59.701  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 14:20:59.701  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 14:20:59.711  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 14:20:59.711  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 14:20:59.711  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 14:20:59.711  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 14:20:59.711  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 14:20:59.711  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 14:20:59.711  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 14:20:59.711  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 14:20:59.721  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 14:20:59.721   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-29 14:20:59.721  7313  7336 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
08-29 14:20:59.721   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 14:20:59.721  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 14:20:59.721  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 14:20:59.721   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-29 14:20:59.721   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 14:20:59.721  7313  7336 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-29 14:20:59.731  1377  1377 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-29 14:20:59.731  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 14:20:59.731  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-29 14:20:59.731  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 14:20:59.751  1377  1377 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-29 14:20:59.751  1377  1377 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-29 14:20:59.751  1377  1377 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-29 14:20:59.751  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 14:20:59.751  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 14:20:59.751  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-29 14:20:59.751  1377  1377 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-29 14:20:59.751  1377  1377 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-29 14:20:59.751  1014  1128 D Tethering: InitialState.processMessage what=4
,08-29 14:20:59.751  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,08-29 14:20:59.751  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-29 14:20:59.761  1014  1128 E Tethering: No numeric data
,08-29 14:20:59.761  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 14:20:59.761  1014  1128 D Tethering: clearTetheredNotification()
,08-29 14:20:59.761  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 14:20:59.761  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 14:20:59.761  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 14:20:59.761  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-29 14:20:59.761  1170  1170 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 14:20:59.761  1170  1170 D HotspotTile: updateTetherState():false, false
08-29 14:20:59.771  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:20:59.771  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
08-29 14:20:59.771  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 14:20:59.771  1014  1121 V NetworkStats: performPollLocked() took 4ms
08-29 14:20:59.771  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 14:20:59.771  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:20:59.771  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:20:59.771  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 14:20:59.821  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 14:20:59.821  1014  1026 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4233, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 14:20:59.821  1014  1026 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 14:20:59.821  1014  1026 D BatteryService: stay LED for charging
08-29 14:20:59.821  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 14:20:59.821  1014  1014 I MotionRecognitionService: Plugged
,08-29 14:20:59.821  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 14:20:59.821  1170  1170 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 14:20:59.821  1170  1170 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 14:20:59.821  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 14:20:59.821  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 14:20:59.851  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-29 14:20:59.851  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-29 14:20:59.851  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-29 14:20:59.871   287   287 E SMD     : DCD OFF
,08-29 14:20:59.871   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 14:20:59.891  7313  7313 D StrictMode: StrictMode policy violation; ~duration=160 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-29 14:20:59.891  7313  7313 D StrictMode: StrictMode policy violation; ~duration=159 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-29 14:20:59.891  7313  7313 D StrictMode: StrictMode policy violation; ~duration=158 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 14:20:59.891  7313  7313 D StrictMode: StrictMode policy violation; ~duration=157 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.q.v.a(PG,:1161)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.q.e.b(PG:170)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 14:20:59.891  7313  7313 D StrictMode: StrictMode policy violation; ~duration=155 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.q.k.d(PG:583)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.q.e.b(PG:170)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a,(PG:48)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 14:20:59.891  7313  7313 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 14:20:59.891  7313  7313 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 14:20:59.891  7313  7313 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 14:20:59.891  7313  7313 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 14:20:59.901  1014  1208 I ActivityManager: Killing 6789:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
08-29 14:20:59.911  1014  1510 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 14:20:59.911  1014  1510 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 14:20:59.911  1014  1510 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:59.911  1014  1510 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:20:59.911  1014  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 14:20:59.911  1603  1603 I Hs20UtilService: Starting #8
08-29 14:20:59.911  1603  1624 I Hs20UtilService: Message received 5007
08-29 14:20:59.921  1377  1377 I wpa_supplicant: Blacklist: Clear (all) 
08-29 14:20:59.921  4739  4739 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-29 14:20:59.921  4739  4739 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 14:20:59.921  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-29 14:20:59.921  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 14:20:59.921  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 14:20:59.921  4739  4739 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 14:20:59.921  4739  4815 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-29 14:20:59.931  4739  4739 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-29 14:20:59.931  4739  4739 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 14:20:59.931  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-29 14:20:59.941  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 14:20:59.941  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 14:20:59.941  4739  4739 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 14:20:59.941  4739  4815 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-29 14:20:59.941  1014  1510 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-29 14:20:59.941  1014  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:59.941  1014  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:59.941  1014  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:59.941  1014  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:20:59.951  7358  7358 E Zygote  : MountEmulatedStorage()
08-29 14:20:59.951  7358  7358 E Zygote  : v2
08-29 14:20:59.951  7358  7358 I libpersona: KNOX_SDCARD checking this for 10064
08-29 14:20:59.951  7313  7351 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-29 14:20:59.951  7358  7358 I libpersona: KNOX_SDCARD not a persona
08-29 14:20:59.951  7358  7358 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 14:20:59.951  7358  7358 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 14:20:59.951  1014  1510 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7358 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 14:20:59.961  7358  7358 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 14:20:59.971  1377  1377 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-29 14:20:59.971  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 14:20:59.971  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-29 14:20:59.971  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 14:20:59.981  7358  7358 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 14:20:59.981  7358  7358 D ActivityThread: Added TimaKeyStore provider
,08-29 14:20:59.981  1014  1510 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 14:20:59.981  1014  1094 V AlarmManager: waitForAlarm result :8
,08-29 14:20:59.981  1014  1510 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:20:59.981  1014  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:20:59.981  1014  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-29 14:21:00.001  7358  7358 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-29 14:21:00.011  7358  7358 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 14:21:00.021  7358  7358 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-29 14:21:00.021  1014  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:21:00.021  1014  1014 I ApplicationPolicy: updateDataUsageMap
,08-29 14:21:00.031  1014  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:21:00.041  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:00.041  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:00.051  7358  7358 D FileShare-Client: Outbound.stopDelayTimer - 
,08-29 14:21:00.051  1014  1486 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-29 14:21:00.051  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:00.051  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:00.051  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:00.051  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:00.071  7375  7375 E Zygote  : MountEmulatedStorage(),
08-29 14:21:00.071  7375  7375 E Zygote  : v2
,08-29 14:21:00.071  7375  7375 I libpersona: KNOX_SDCARD checking this for 10065
08-29 14:21:00.071  7375  7375 I libpersona: KNOX_SDCARD not a persona
,08-29 14:21:00.071  1014  1486 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7375 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 14:21:00.071  7375  7375 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 14:21:00.071  1014  1486 I ActivityManager: Killing 6229:com.samsung.android.sm/1000 (adj 15): empty #21
,08-29 14:21:00.071  7375  7375 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 14:21:00.071  7375  7375 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 14:21:00.071  1014  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-29 14:21:00.071  1014  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-29 14:21:00.081  1170  1170 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 14:21:00.081  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 14:21:00.081  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 14:21:00.081  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:00.081  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:00.081  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:00.081  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:00.081  1170  1170 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 14:21:00.081  1170  1170 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 14:21:00.081  1170  1170 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-29 14:21:00.081  1170  1768 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 14:21:00.081  4739  4739 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 14:21:00.091  1170  1170 D HotspotTile: onReceive : 1, 0
,08-29 14:21:00.091  1729  2203 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 14:21:00.091  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:00.091  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:00.101  7375  7375 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 14:21:00.101  7375  7375 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:00.121  7375  7375 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 14:21:00.131  1014  1208 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:00.131  1014  1208 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 14:21:00.131  1014  1208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-29 14:21:00.131  1014  1208 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-29 14:21:00.131  1014  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:00.131  1014  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:00.131  1014  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:00.131  1014  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:00.141  7390  7390 E Zygote  : MountEmulatedStorage(),
08-29 14:21:00.141  7390  7390 E Zygote  : v2
08-29 14:21:00.141  7390  7390 I libpersona: KNOX_SDCARD checking this for 10102
08-29 14:21:00.141  7390  7390 I libpersona: KNOX_SDCARD not a persona
08-29 14:21:00.141  7390  7390 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 14:21:00.151  1014  1208 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7390 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
08-29 14:21:00.151  7390  7390 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 14:21:00.151  1014  1208 I ActivityManager: Killing 6868:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,08-29 14:21:00.151  7390  7390 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 14:21:00.171  7390  7390 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 14:21:00.171  7390  7390 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:00.191  7390  7390 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-29 14:21:00.401  7390  7410 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-29 14:21:00.401  7390  7410 I Babel_SMS: MmsConfig.loadMmsSettings
08-29 14:21:00.401  7390  7410 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-29 14:21:00.401  7390  7410 I Babel_SMS: MmsConfig.loadFromDatabase
,08-29 14:21:00.411  7390  7410 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-29 14:21:00.411  7390  7410 I Babel_SMS: MmsConfig.loadFromResources
,08-29 14:21:00.411  7390  7410 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-29 14:21:00.411  7390  7410 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-29 14:21:00.421  1014  1253 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-29 14:21:00.421  1014  1253 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-29 14:21:00.421  1014  1253 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:00.421  1014  1253 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:21:00.421  1014  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-29 14:21:00.441  7390  7390 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 14:21:00.441  7390  7390 I Babel_Crash: startup - clean
,08-29 14:21:00.471  1014  1253 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 14:21:00.471  1014  1253 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 14:21:00.471  1014  1253 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:00.471  1014  1253 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:00.471  1014  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 14:21:00.471  1603  1603 I Hs20UtilService: Starting #9
,08-29 14:21:00.471  1603  1624 I Hs20UtilService: Message received 5007
,08-29 14:21:00.471  4739  4739 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 14:21:00.481  4739  4739 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 14:21:00.481  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 14:21:00.481  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-29 14:21:00.481  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 14:21:00.481  4739  4739 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 14:21:00.481  4739  4815 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 14:21:00.481  1014  1208 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 14:21:00.491  1014  1208 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 14:21:00.491  1014  1208 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:00.491  1014  1208 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:00.491  1014  1208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 14:21:00.491  7390  7390 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 14:21:00.491  1014  3867 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-29 14:21:00.491  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:00.491  7390  7390 W AudioCapabilities: Unsupported mime audio/evrc
08-29 14:21:00.491  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:00.491  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:00.491  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:00.491  1603  1603 I Hs20UtilService: Starting #10
08-29 14:21:00.491  1603  1624 I Hs20UtilService: Message received 5011
,08-29 14:21:00.491  7390  7390 W AudioCapabilities: Unsupported mime audio/qcelp
,08-29 14:21:00.501  7390  7390 W AudioCapabilities: Unsupported mime audio/mpeg-L1,
08-29 14:21:00.501  7390  7390 W AudioCapabilities: Unsupported mime audio/mpeg-L2
08-29 14:21:00.501  7390  7390 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-29 14:21:00.501  7390  7390 W AudioCapabilities: Unsupported mime audio/x-ima
08-29 14:21:00.501  7390  7390 W AudioCapabilities: Unsupported mime audio/qcelp
,08-29 14:21:00.511  7390  7390 W AudioCapabilities: Unsupported mime audio/evrc,
,08-29 14:21:00.521  7413  7413 E Zygote  : MountEmulatedStorage()
08-29 14:21:00.521  7413  7413 E Zygote  : v2
08-29 14:21:00.521  7413  7413 I libpersona: KNOX_SDCARD checking this for 1000
08-29 14:21:00.521  7413  7413 I libpersona: KNOX_SDCARD not a persona
,08-29 14:21:00.521  7413  7413 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 14:21:00.521  1014  3867 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7413 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-29 14:21:00.521  7413  7413 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 14:21:00.521  7413  7413 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 14:21:00.551  7390  7390 W VideoCapabilities: Unsupported mime video/wvc1,
08-29 14:21:00.551   305   305 I art     : Explicit concurrent mark sweep GC freed 8696(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 28.908ms
08-29 14:21:00.551  7390  7390 W VideoCapabilities: Unsupported mime video/x-ms-wmv,
08-29 14:21:00.551  7413  7413 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 14:21:00.551  7413  7413 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:00.561  7390  7390 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-29 14:21:00.571  7390  7390 W VideoCapabilities: Unsupported mime video/wvc1
08-29 14:21:00.571   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 16.807ms
,08-29 14:21:00.571  7390  7390 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-29 14:21:00.571  7390  7390 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-29 14:21:00.571  7390  7390 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
08-29 14:21:00.571  7390  7390 W VideoCapabilities: Unsupported mime video/mp43
,08-29 14:21:00.581  7390  7390 W VideoCapabilities: Unsupported mime video/sorenson
,08-29 14:21:00.581  7390  7390 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-29 14:21:00.581   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.732ms
,08-29 14:21:00.591  7413  7413 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 14:21:00.591  7413  7413 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 14:21:00.591  7413  7413 D SecurityLogAgent: StateMachine : Current State = 1
,08-29 14:21:00.591  7413  7413 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 14:21:00.591  1014  1027 I ActivityManager: Killing 6905:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-29 14:21:00.601  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:00.601  1014  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:00.601  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 14:21:00.611  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:00.611  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:00.611  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 14:21:00.611  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:00.611  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:00.611  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
08-29 14:21:00.611  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:00.621  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:00.621  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 14:21:00.621  7390  7390 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-29 14:21:00.621  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:00.621  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:00.621  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
08-29 14:21:00.621  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:00.621  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:00.621  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 14:21:00.631  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:00.631  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:00.631  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 14:21:00.631  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:00.631  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:00.631  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 14:21:00.641  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:00.641  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:00.641  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 14:21:00.641  1014  1014 W ActivityManager: userId = 0, bbcId = -10000,
08-29 14:21:00.641  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 14:21:00.641  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 14:21:00.651  1014  1014 W ActivityManager: userId = 0, bbcId = -10000,
08-29 14:21:00.651  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:00.651  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 14:21:00.651  7390  7390 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 14:21:00.651  7390  7390 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,08-29 14:21:00.651  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:00.651  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:00.651  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
08-29 14:21:00.651  7390  7390 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 14:21:00.651  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:00.651  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:00.651  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 14:21:00.651  1014  1014 W ActivityManager: userId = 0, bbcId = -10000,
08-29 14:21:00.651  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:00.651  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 14:21:00.661  1014  1014 W ActivityManager: userId = 0, bbcId = -10000,
08-29 14:21:00.661  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:00.661  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 14:21:00.661  7390  7390 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 14:21:00.661  1014  1208 I ActivityManager: Killing 6886:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,08-29 14:21:00.661  1014  1042 D Tethering: interfaceRemoved wlan0
08-29 14:21:00.661  1014  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-29 14:21:00.661  7390  7390 I vclib   : onServiceConnected
08-29 14:21:00.661  4739  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 14:21:00.671  1014  3867 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-29 14:21:00.671  1014  3867 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-29 14:21:00.671  1014  3867 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:00.671  1014  3867 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:00.671  1014  3867 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 14:21:00.671  2635  2635 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 14:21:00.681  4739  4739 D DockEventReceiver: finishStartingService: stopping service
,08-29 14:21:00.681  4739  4739 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 14:21:00.681  1170  1170 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:21:00.681  1170  1170 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-29 14:21:00.691  6928  6928 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-29 14:21:00.691  6928  6928 I PCWCLIENTTRACE_PushUtil: sales region : global
08-29 14:21:00.691  6928  6928 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-29 14:21:00.691  6928  6928 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:21:00.691  1014  1486 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
08-29 14:21:00.691  1014  1486 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-29 14:21:00.691  1014  1486 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-29 14:21:00.691  1014  1486 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-29 14:21:00.701  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-29 14:21:00.701  6928  7431 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-29 14:21:00.701  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:00.701  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:00.701  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:00.701  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:00.711  7433  7433 E Zygote  : MountEmulatedStorage()
08-29 14:21:00.711  7433  7433 I libpersona: KNOX_SDCARD checking this for 10001
08-29 14:21:00.711  7433  7433 E Zygote  : v2
08-29 14:21:00.711  7433  7433 I libpersona: KNOX_SDCARD not a persona
,08-29 14:21:00.711  7433  7433 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 14:21:00.721  7433  7433 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 14:21:00.721  1014  1014 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7433 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 14:21:00.721  7433  7433 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 14:21:00.731  7433  7433 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 14:21:00.731  7433  7433 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:00.811  1014  1253 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-29 14:21:00.811  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:00.811  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:00.811  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:00.811  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-29 14:21:00.821  7450  7450 E Zygote  : MountEmulatedStorage(),
08-29 14:21:00.821  7450  7450 E Zygote  : v2
08-29 14:21:00.821  7450  7450 I libpersona: KNOX_SDCARD checking this for 1000,
08-29 14:21:00.821  7450  7450 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 14:21:00.821  7450  7450 I libpersona: KNOX_SDCARD not a persona
,08-29 14:21:00.831  1014  1253 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7450 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-29 14:21:00.831  1014  1042 D Tethering: interfaceRemoved p2p0
,08-29 14:21:00.831  1014  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
08-29 14:21:00.831  7450  7450 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 14:21:00.831  1014  1253 I ActivityManager: Killing 6822:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-29 14:21:00.831  7450  7450 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 14:21:00.861  7450  7450 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 14:21:00.861  7450  7450 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:00.871   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 14:21:00.901  7450  7450 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-29 14:21:01.041  7450  7450 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-29 14:21:01.051  7450  7450 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-29 14:21:01.051  7450  7450 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:21:01.051  7450  7450 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-29 14:21:01.051  7450  7450 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-29 14:21:01.051  7450  7450 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-29 14:21:01.051  1014  1336 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-29 14:21:01.051  1014  1336 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:01.051  1014  1336 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:01.051  1014  1336 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:01.051  1014  1336 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:01.071  1014  1336 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7467 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-29 14:21:01.071  1014  1336 I ActivityManager: Killing 7004:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21,
,08-29 14:21:01.071  7467  7467 E Zygote  : MountEmulatedStorage()
08-29 14:21:01.071  7467  7467 I libpersona: KNOX_SDCARD checking this for 10008
08-29 14:21:01.071  7467  7467 E Zygote  : v2
08-29 14:21:01.071  7467  7467 I libpersona: KNOX_SDCARD not a persona
,08-29 14:21:01.071  7467  7467 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 14:21:01.071  7467  7467 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 14:21:01.081  7467  7467 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-29 14:21:01.091  7467  7467 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 14:21:01.091  7467  7467 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:01.171  1014  1485 I ActivityManager: Killing 7036:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,08-29 14:21:01.171  1014  1482 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 14:21:01.171  1014  1482 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-29 14:21:01.171  1014  1482 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:01.171  1014  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:21:01.171  1014  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:21:01.191  1932  1932 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 14:21:01.191  1932  2827 I iu.UploadsManager: num queued entries: 0
,08-29 14:21:01.201  1932  2827 I iu.UploadsManager: num updated entries: 0
,08-29 14:21:01.201  1932  2827 I iu.SyncManager: NEXT; no task
,08-29 14:21:01.201  1014  1253 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 14:21:01.201  1014  1253 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,08-29 14:21:01.201  1014  1253 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:01.201  1014  1253 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:21:01.201  1014  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:21:01.211  1932  1932 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 14:21:01.211  1932  1932 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,08-29 14:21:01.221  2831  2831 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Aug 29 14:21:01 GMT+02:00 2016
,08-29 14:21:01.221  1014  1486 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-29 14:21:01.221  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-29 14:21:01.221  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:01.221  1014  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:01.221  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-29 14:21:01.231  2831  2831 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-29 14:21:01.231  1014  3867 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-29 14:21:01.241  2831  2831 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-29 14:21:01.241  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:01.241  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:01.241  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:01.241  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:01.251  2831  2831 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-29 14:21:01.251  7484  7484 E Zygote  : MountEmulatedStorage(),
08-29 14:21:01.251  7484  7484 E Zygote  : v2
08-29 14:21:01.251  7484  7484 I libpersona: KNOX_SDCARD checking this for 10031
08-29 14:21:01.251  7484  7484 I libpersona: KNOX_SDCARD not a persona
,08-29 14:21:01.251  7484  7484 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 14:21:01.261  1014  3867 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7484 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-29 14:21:01.261  2831  2831 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-29 14:21:01.261  7484  7484 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 14:21:01.261  7484  7484 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 14:21:01.261  2831  7483 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-29 14:21:01.271  2831  7483 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-29 14:21:01.271  2831  7483 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-29 14:21:01.281  2831  7483 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-29 14:21:01.281  2831  2831 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-29 14:21:01.281  7484  7484 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 14:21:01.281  7484  7484 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:01.321  7484  7484 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-29 14:21:01.321  1014  1487 I ActivityManager: Killing 7062:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-29 14:21:01.331  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-29 14:21:01.331  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:01.331  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:01.331  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:01.331  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:01.351  2769  7499 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-29 14:21:01.351  7500  7500 E Zygote  : MountEmulatedStorage()
,08-29 14:21:01.351  7500  7500 E Zygote  : v2
08-29 14:21:01.351  7500  7500 I libpersona: KNOX_SDCARD checking this for 10032
08-29 14:21:01.351  7500  7500 I libpersona: KNOX_SDCARD not a persona
,08-29 14:21:01.351  2769  7499 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-29 14:21:01.351  7500  7500 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 14:21:01.351  2769  7499 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable,
,08-29 14:21:01.351  2769  7499 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0,
,08-29 14:21:01.351  2769  7499 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... ,
,08-29 14:21:01.361  7500  7500 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 14:21:01.361  7500  7500 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,08-29 14:21:01.361  1014  1026 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7500 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 14:21:01.391  7500  7500 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 14:21:01.391  7500  7500 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:01.441  7500  7515 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-29 14:21:01.441  7500  7515 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-29 14:21:01.451  7500  7500 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-29 14:21:01.451  1014  1487 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-29 14:21:01.451  1014  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:01.451  1014  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:01.451  1014  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:01.461  7500  7515 D SPPClientService: PushLog.txt file is not deleted.
08-29 14:21:01.461  7500  7515 D SPPClientService: PushLog.txt file is not deleted.
08-29 14:21:01.461  7500  7515 D SPPClientService: ============PushLog. stop!
08-29 14:21:01.461  1014  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:01.471  1014  1487 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7517 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 14:21:01.471  1014  1208 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-29 14:21:01.471  1014  1208 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-29 14:21:01.471  7517  7517 E Zygote  : MountEmulatedStorage()
08-29 14:21:01.471  7517  7517 E Zygote  : v2
08-29 14:21:01.471  7517  7517 I libpersona: KNOX_SDCARD checking this for 10036
08-29 14:21:01.471  7517  7517 I libpersona: KNOX_SDCARD not a persona
,08-29 14:21:01.471  1014  1208 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:01.471  1014  1208 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-29 14:21:01.471  1014  1208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
08-29 14:21:01.471  7517  7517 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 14:21:01.481  7517  7517 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 14:21:01.481  7517  7517 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-29 14:21:01.501  7517  7517 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 14:21:01.501  7517  7517 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:01.501  7500  7523 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-29 14:21:01.531  1014  1482 I ActivityManager: Killing 7099:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-29 14:21:01.551  7517  7517 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@1f5b48d9
,08-29 14:21:01.561  7517  7517 I SA      : [SSP] onCreated
,08-29 14:21:01.571  7517  7517 I SA      : [TPM] There is no property file
,08-29 14:21:01.571  7517  7517 I SA      : [SCU] isHaveSA() - false
,08-29 14:21:01.581  7517  7517 I SA      : [TPM] getModelProperty : null
,08-29 14:21:01.581  7517  7517 I SA      : [TPM] getCSCProperty : null
,08-29 14:21:01.581  7517  7517 I SA      : [DM] FLOATING AMOLED FEATURE: true
,08-29 14:21:01.581  7517  7517 I SA      : [DM] PRODUCT AMOLED FEATURE: false
,08-29 14:21:01.581  7517  7517 I SA      : [DM] TFT FEATURE: false
,08-29 14:21:01.581  7517  7517 I SA      : [DM] init START
,08-29 14:21:01.591  7517  7517 I SA      : [DM] This device is not a Vodafone
,08-29 14:21:01.591  7517  7517 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-29 14:21:01.591  7517  7517 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-29 14:21:01.601  7517  7517 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-29 14:21:01.601  7517  7517 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-29 14:21:01.601  7517  7517 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-29 14:21:01.601  7517  7517 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-29 14:21:01.601  7517  7517 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-29 14:21:01.601  7517  7517 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-29 14:21:01.601  7517  7517 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-29 14:21:01.601  7517  7517 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-29 14:21:01.601  7517  7517 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-29 14:21:01.611  7517  7517 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-29 14:21:01.611  7517  7517 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-29 14:21:01.611  7517  7517 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-29 14:21:01.611  7517  7517 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-29 14:21:01.611  7517  7517 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-29 14:21:01.611  7517  7517 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,08-29 14:21:01.611  7517  7517 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-29 14:21:01.611  7517  7517 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-29 14:21:01.611  7517  7517 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-29 14:21:01.611  7517  7517 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-29 14:21:01.621  7517  7517 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-29 14:21:01.621  7517  7517 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-29 14:21:01.621  7517  7517 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-29 14:21:01.621  7517  7517 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-29 14:21:01.621  7517  7517 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-29 14:21:01.621  7517  7517 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,08-29 14:21:01.621  7517  7517 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-29 14:21:01.621  7517  7517 I SA      : [SCU] isHaveSA() - false
,08-29 14:21:01.621  7517  7517 I SA      : support phone number id : false
08-29 14:21:01.621  7517  7517 I SA      : [DM] Supports Ref Jpn : true
,08-29 14:21:01.621  7517  7517 I SA      : [DM] init END
08-29 14:21:01.621  7517  7517 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-29 14:21:01.631  7517  7517 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,08-29 14:21:01.631  7517  7517 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-29 14:21:01.631  7517  7517 I SA      : [SLFUCHKMGR] constructor called
,08-29 14:21:01.641  1014  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-29 14:21:01.641  7517  7517 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-29 14:21:01.641  7517  7517 I SA      : [OR] == isSIMCardReady false ==
,08-29 14:21:01.641  7517  7517 I SA      : [SCU] == networkStateCheck == false
,08-29 14:21:01.651  7517  7517 I SA      : [OR] onReceive END
,08-29 14:21:01.651  1014  1486 I ActivityManager: Killing 7021:com.android.mms/u0a41 (adj 15): empty #21
,08-29 14:21:01.651  1230  1230 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:21:01.661  1788  1788 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-29 14:21:01.671  2688  2700 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,08-29 14:21:01.671  1788  1788 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-29 14:21:01.671  1788  1788 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,08-29 14:21:01.671  1788  1788 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-29 14:21:01.681  1788  1788 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-29 14:21:01.681  1788  1788 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-29 14:21:01.691  1788  1788 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-29 14:21:01.691  1014  1208 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-29 14:21:01.691  1014  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:01.691  1014  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:01.691  1014  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:01.691  1014  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:01.711  1014  1208 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7539 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 14:21:01.711  7539  7539 E Zygote  : MountEmulatedStorage()
08-29 14:21:01.711  7539  7539 I libpersona: KNOX_SDCARD checking this for 10077
08-29 14:21:01.711  7539  7539 E Zygote  : v2
08-29 14:21:01.711  7539  7539 I libpersona: KNOX_SDCARD not a persona
,08-29 14:21:01.711  7539  7539 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 14:21:01.711  7539  7539 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 14:21:01.711  7539  7539 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-29 14:21:01.731  7539  7539 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 14:21:01.731  7539  7539 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:01.841  1014  1484 D CountryDetector: No listener is left
,08-29 14:21:01.871   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 14:21:01.921  1014  1482 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-29 14:21:01.921  1014  1482 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-29 14:21:01.921  1014  1482 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:01.921  1014  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:21:01.921  1014  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-29 14:21:01.931  1014  1487 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast,
08-29 14:21:01.931  1014  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:01.931  1014  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:01.931  1014  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:01.931  1014  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:01.941  1014  1487 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7557 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-29 14:21:01.941  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:01.941  1014  1027 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-29 14:21:01.941  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:21:01.941  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
08-29 14:21:01.941  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-29 14:21:01.941  7557  7557 E Zygote  : MountEmulatedStorage()
08-29 14:21:01.941  7557  7557 I libpersona: KNOX_SDCARD checking this for 10110
08-29 14:21:01.941  7557  7557 E Zygote  : v2
08-29 14:21:01.941  7557  7557 I libpersona: KNOX_SDCARD not a persona
,08-29 14:21:01.951  7557  7557 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 14:21:01.951  7390  7556 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-29 14:21:01.951  7557  7557 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 14:21:01.951  7557  7557 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 14:21:01.951  1014  3867 I ActivityManager: Killing 7159:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-29 14:21:01.981  7557  7557 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 14:21:01.981  7557  7557 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:02.151  1014  1253 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 14:21:02.271  7557  7557 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-29 14:21:02.271  7557  7557 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 14:21:02.271  7557  7557 I GAv4    :   adb logcat -s GAv4
,08-29 14:21:02.281  1014  3867 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-29 14:21:02.281  1014  3867 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 14:21:02.281  1014  3867 D SecContentProvider2: mCursor = null
,08-29 14:21:02.281  1014  3867 D WifiService: setWifiEnabled: true pid=7083, uid=10170
08-29 14:21:02.281  1014  3867 W ActivityManager: Permission Denial: getCurrentUser() from pid=7083, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-29 14:21:02.281  1014  3867 W WifiService: Failed getting userId using ActivityManagerNative
08-29 14:21:02.281  1014  3867 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7083, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-29 14:21:02.281  1014  3867 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 14:21:02.281  1014  3867 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-29 14:21:02.281  1014  3867 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-29 14:21:02.281  1014  3867 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-29 14:21:02.281  1014  3867 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-29 14:21:02.281  1014  3867 D SettingsProvider: name = wifi_on
,08-29 14:21:02.281   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-29 14:21:02.281   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 14:21:02.281  7557  7575 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-29 14:21:02.291  1014  1124 E WifiHW  : ##################### set firmware type 0 #####################
,08-29 14:21:02.291   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-29 14:21:02.291   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 14:21:02.291  7557  7575 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-29 14:21:02.301  7557  7557 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 14:21:02.301  1014  1253 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 14:21:02.301   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-29 14:21:02.301   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 14:21:02.301  7557  7578 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-29 14:21:02.311   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-29 14:21:02.311   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 14:21:02.311  7557  7578 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-29 14:21:02.321  7557  7557 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-29 14:21:02.331  7557  7579 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-29 14:21:02.361  5935  5935 D FactoryTest: Not factory mode
,08-29 14:21:02.361  5935  5935 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-29 14:21:02.371  5935  5935 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-29 14:21:02.371  5935  5935 D MTPRx   : still no open session command from host, so toast
,08-29 14:21:02.371  5935  5935 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-29 14:21:02.371  5935  5935 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-29 14:21:02.371  5935  5935 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:118569
,08-29 14:21:02.381  1014  1485 E PersonaManagerService: inState():  stateMachine is null !!
08-29 14:21:02.381  1014  1485 I PersonaManagerService: PersonaId don't exist
08-29 14:21:02.381  1014  1485 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-29 14:21:02.381  1014  1485 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-29 14:21:02.391  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:02.391  1014  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:02.391  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-29 14:21:02.401  1014  1485 W ActivityManager: mDVFSHelper.acquire()
,08-29 14:21:02.411  1014  1485 D PersonaManager: isKioskContainerExistOnDevice
,08-29 14:21:02.421  1014  1485 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-29 14:21:02.421  1014  1485 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-29 14:21:02.421  1014  1485 D InputDispatcher: Focused application set to: xxxx
,08-29 14:21:02.421  1014  1485 D InputDispatcher: Focus left window: 7083
,08-29 14:21:02.431  5935  5935 E MTPRx   : started activity for popup
,08-29 14:21:02.431  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-29 14:21:02.431  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 14:21:02.461  5935  5935 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-29 14:21:02.461  5935  5935 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-29 14:21:02.461  5935  5935 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-29 14:21:02.461  5935  5935 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 14:21:02.461  5935  5935 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 14:21:02.461  5935  5935 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 14:21:02.501  5935  5935 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-29 14:21:02.511  1014  1510 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-29 14:21:02.511  1014  1510 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-29 14:21:02.511  1014  1510 D InputDispatcher: Focused application set to: xxxx
,08-29 14:21:02.511  1014  1510 D InputDispatcher: Focus entered window: 7083
,08-29 14:21:02.511  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-29 14:21:02.511  1014  1487 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-29 14:21:02.521  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 14:21:02.521  1014  1487 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@113ba8f9 attribute=null, token = android.os.BinderProxy@2212d34
,08-29 14:21:02.591  5935  5935 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-29 14:21:02.601  5935  5935 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-29 14:21:02.601  5935  5935 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-29 14:21:02.631  7083  7083 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 14:21:02.631  7083  7083 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-29 14:21:02.631  7083  7083 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-29 14:21:02.631  7083  7083 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-29 14:21:02.641  1014  1026 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-29 14:21:02.641  1014  1026 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-29 14:21:02.641  1014  1026 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-29 14:21:02.641  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-29 14:21:02.641  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,08-29 14:21:02.651  7083  7083 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 14:21:02.651  7083  7083 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-29 14:21:02.661  7083  7083 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3aa74a26 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@260ffa99, 16908290=android.view.AbsSavedState$1@260ffa99}, android:focusedViewId=100}]}]
08-29 14:21:02.661  7083  7083 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-29 14:21:02.661  7083  7083 V ActivityThread: updateVisibility : ActivityRecord{261e2498 token=android.os.BinderProxy@372b160a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-29 14:21:02.661  7083  7083 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 14:21:02.661  7083  7083 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-29 14:21:02.661  7083  7083 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@372b160a time:118853
,08-29 14:21:02.671  1014  1027 D PersonaManager: isKioskContainerExistOnDevice
,08-29 14:21:02.681  1014  1486 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 14:21:02.681  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:02.691  1014  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 14:21:02.691  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-29 14:21:02.701  7557  7557 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-29 14:21:02.711  1014  1042 D Tethering: interfaceAdded wlan0
,08-29 14:21:02.721  1014  1128 E Tethering: No numeric data
,08-29 14:21:02.721  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 14:21:02.721  1014  1128 D Tethering: clearTetheredNotification()
,08-29 14:21:02.721  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,08-29 14:21:02.721  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-29 14:21:02.721  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 14:21:02.721  1014  1128 D Tethering: InitialState.processMessage what=4
,08-29 14:21:02.721  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
08-29 14:21:02.721  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 14:21:02.721  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-29 14:21:02.731  1014  1128 E Tethering: No numeric data
08-29 14:21:02.731  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 14:21:02.731  1014  1128 D Tethering: clearTetheredNotification()
08-29 14:21:02.731  1170  1170 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 14:21:02.731  1170  1170 D HotspotTile: updateTetherState():false, false
,08-29 14:21:02.731  1014  1042 D Tethering: interfaceAdded p2p0
,08-29 14:21:02.731  1014  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
08-29 14:21:02.731  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 14:21:02.731  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 14:21:02.731  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
08-29 14:21:02.731  1170  1170 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 14:21:02.731  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
08-29 14:21:02.731  1170  1170 D HotspotTile: updateTetherState():false, false
,08-29 14:21:02.741   277  1010 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-29 14:21:02.741  1014  1121 V NetworkStats: performPollLocked() took 14ms
08-29 14:21:02.741  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:21:02.741   277  1010 D SoftapController: Softap fwReload - Ok
,08-29 14:21:02.741  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:21:02.741  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
08-29 14:21:02.741  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:21:02.741  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 14:21:02.741  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 14:21:02.741  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 14:21:02.741   277  1010 D CommandListener: Setting iface cfg
08-29 14:21:02.741   277  1010 D CommandListener: Trying to bring down wlan0
08-29 14:21:02.741   277  1010 D CommandListener: Clearing all IP addresses on wlan0
,08-29 14:21:02.741  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:21:02.741  1014  1121 V NetworkStats: performPollLocked() took 3ms
,08-29 14:21:02.741  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:21:02.741  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 14:21:02.741  1014  1124 E WifiHW  : supplicant_name : p2p_supplicant
,08-29 14:21:02.741  7557  7557 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 8936-8939),
08-29 14:21:02.741  7557  7557 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-29 14:21:02.751  1014  1124 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 14:21:02.751  1014  1124 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-29 14:21:02.751  1170  1170 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-29 14:21:02.751  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 14:21:02.751  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 14:21:02.761  1170  1170 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 14:21:02.761  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:02.761  1170  1768 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-29 14:21:02.761  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:02.761  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:02.761  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:02.761  1170  1170 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 14:21:02.761  1170  1170 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-29 14:21:02.761  1170  1170 D HotspotTile: onReceive : 2, 0
,08-29 14:21:02.761  4739  4739 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-29 14:21:02.761  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:02.771  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-29 14:21:02.771  7557  7557 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f87cef8}
08-29 14:21:02.771  7557  7557 I cr.library_loader: Expected native library version number "", actual native library version number "",
08-29 14:21:02.771  7557  7557 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 14:21:02.791  7557  7557 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-29 14:21:02.791  7557  7557 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,08-29 14:21:02.801  7557  7557 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-29 14:21:02.821  7557  7557 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-29 14:21:02.821  7557  7557 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-29 14:21:02.821  7557  7557 I Adreno-EGL: Build Date: 04/06/15 Mon
08-29 14:21:02.821  7557  7557 I Adreno-EGL: Local Branch: 
08-29 14:21:02.821  7557  7557 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-29 14:21:02.821  7557  7557 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-29 14:21:02.821  7557  7557 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-29 14:21:02.821  7604  7604 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-29 14:21:02.821  7604  7604 I wpa_supplicant: Successfully initialized wpa_supplicant
08-29 14:21:02.821  7604  7604 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-29 14:21:02.841  7604  7604 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-29 14:21:02.841   403   403 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7604
,08-29 14:21:02.841   403   403 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-29 14:21:02.841  7604  7604 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-29 14:21:02.841  7604  7604 I wpa_supplicant: ssSupport state is = 1,
08-29 14:21:02.841  7604  7604 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-29 14:21:02.841  7604  7604 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-29 14:21:02.841   403   403 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7604
,08-29 14:21:02.841   403   403 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-29 14:21:02.871   287   287 E SMD     : DCD OFF
,08-29 14:21:02.871   317   317 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 14:21:02.881  7557  7618 W cr.media: Requires BLUETOOTH permission
,08-29 14:21:02.891  7557  7557 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 14:21:02.901  7557  7557 I NSApplication: Starting up...
,08-29 14:21:02.901  1014  1486 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 14:21:02.901  1014  1208 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 14:21:02.911  1014  1253 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-29 14:21:02.911  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:02.911  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:02.911  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:02.911  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:02.931  1014  1253 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7623 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
08-29 14:21:02.931  1014  1253 I ActivityManager: Killing 7178:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,08-29 14:21:02.931  7623  7623 E Zygote  : MountEmulatedStorage()
08-29 14:21:02.931  7623  7623 I libpersona: KNOX_SDCARD checking this for 10117
08-29 14:21:02.931  7623  7623 E Zygote  : v2
08-29 14:21:02.931  7623  7623 I libpersona: KNOX_SDCARD not a persona
,08-29 14:21:02.931  7623  7623 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 14:21:02.931  7623  7623 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 14:21:02.941  7623  7623 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 14:21:02.951  7623  7623 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 14:21:02.951  7623  7623 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:02.971  7623  7623 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 14:21:03.071   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-29 14:21:03.071  7604  7604 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-29 14:21:03.121  7604  7604 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-29 14:21:03.121  7604  7604 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-29 14:21:03.131  7604  7604 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-29 14:21:03.131   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7604,
08-29 14:21:03.131   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-29 14:21:03.131  7604  7604 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running,
08-29 14:21:03.131  7604  7604 I wpa_supplicant: ssSupport state is = 1,
08-29 14:21:03.131  7604  7604 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-29 14:21:03.141  7604  7604 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 14:21:03.141  7604  7604 E wpa_supplicant: SIM READ ERROR
,08-29 14:21:03.141  7604  7604 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 14:21:03.141  7604  7604 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 14:21:03.141  7604  7604 E wpa_supplicant: SIM READ ERROR
08-29 14:21:03.141  7604  7604 I wpa_supplicant: Blacklist: Clear (all) ,
08-29 14:21:03.141  7604  7604 I wpa_supplicant: wpa_default_ap_write_once
08-29 14:21:03.141  7604  7604 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-29 14:21:03.141  7604  7604 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-29 14:21:03.141  7604  7604 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-29 14:21:03.141  7604  7604 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 14:21:03.141  7604  7604 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 14:21:03.141  7604  7604 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-29 14:21:03.151  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 14:21:03.151  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-29 14:21:03.151  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 14:21:03.191  7604  7604 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-29 14:21:03.321  1014  1253 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-29 14:21:03.321  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:03.321  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:03.321  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:03.321  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:03.331  7645  7645 E Zygote  : MountEmulatedStorage(),
,08-29 14:21:03.331  7645  7645 E Zygote  : v2
,08-29 14:21:03.331  7645  7645 I libpersona: KNOX_SDCARD checking this for 10121
08-29 14:21:03.331  7645  7645 I libpersona: KNOX_SDCARD not a persona
,08-29 14:21:03.341  7645  7645 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 14:21:03.341  1014  1253 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7645 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-29 14:21:03.341  1014  1253 I ActivityManager: Killing 7196:com.wsomacp/u0a23 (adj 15): empty #21
,08-29 14:21:03.341  7645  7645 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 14:21:03.341  7645  7645 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 14:21:03.361  7645  7645 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 14:21:03.361  7645  7645 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:03.381  7645  7645 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 14:21:03.381  7645  7645 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-29 14:21:03.381  7645  7645 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 14:21:03.391  7645  7645 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:21:03.391  7645  7645 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-29 14:21:03.391  7645  7645 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-29 14:21:03.401  1014  3867 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-29 14:21:03.401  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:03.401  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:03.401  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:03.401  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:03.401  7604  7604 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-29 14:21:03.401  7604  7604 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage,
,08-29 14:21:03.411  7604  7604 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-29 14:21:03.411   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7604
08-29 14:21:03.411   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-29 14:21:03.411  7604  7604 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-29 14:21:03.411  7604  7604 I wpa_supplicant: ssSupport state is = 1
,08-29 14:21:03.411  7663  7663 E Zygote  : MountEmulatedStorage(),
08-29 14:21:03.411  7663  7663 E Zygote  : v2
08-29 14:21:03.411  7663  7663 I libpersona: KNOX_SDCARD checking this for 10141
08-29 14:21:03.411  7663  7663 I libpersona: KNOX_SDCARD not a persona,
08-29 14:21:03.411  7663  7663 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 14:21:03.421  7663  7663 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-29 14:21:03.421  1014  3867 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7663 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-29 14:21:03.421  7663  7663 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 14:21:03.421  1014  3867 I ActivityManager: Killing 7215:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
08-29 14:21:03.421  7604  7604 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-29 14:21:03.421  7604  7604 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-29 14:21:03.431  7604  7604 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-29 14:21:03.431   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7604
08-29 14:21:03.431   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-29 14:21:03.431  7604  7604 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-29 14:21:03.431  7604  7604 I wpa_supplicant: ssSupport state is = 1
08-29 14:21:03.431  7604  7604 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 14:21:03.431  7604  7604 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 14:21:03.431  7604  7604 E wpa_supplicant: SIM READ ERROR
08-29 14:21:03.431  7604  7604 I wpa_supplicant: wpa_default_ap_write_once
08-29 14:21:03.431  7604  7604 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-29 14:21:03.431  7604  7604 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 14:21:03.431  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 14:21:03.431  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 14:21:03.431  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
08-29 14:21:03.431  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 14:21:03.431  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
08-29 14:21:03.431  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 14:21:03.441  7663  7663 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 14:21:03.441  7663  7663 D ActivityThread: Added TimaKeyStore provider,
,08-29 14:21:03.451   305   305 I art     : Explicit concurrent mark sweep GC freed 8699(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 710us total 30.972ms
,08-29 14:21:03.461  7663  7663 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-29 14:21:03.461  7663  7663 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 14:21:03.461  7663  7663 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 14:21:03.461  7663  7663 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-29 14:21:03.461   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 16.745ms
,08-29 14:21:03.481   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 16.407ms
,08-29 14:21:03.511  1014  1486 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 14:21:03.521  1014  1510 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 14:21:03.541  7604  7604 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-29 14:21:03.541  7604  7604 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-29 14:21:03.551  1014  3867 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 14:21:03.561  1014  1336 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 14:21:03.591  1014  1510 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-29 14:21:03.591  1014  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:03.591  1014  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:03.591  1014  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:03.601  1014  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:03.601  1014  1482 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 14:21:03.611  7687  7687 E Zygote  : MountEmulatedStorage()
,08-29 14:21:03.611  7687  7687 E Zygote  : v2
08-29 14:21:03.611  7687  7687 I libpersona: KNOX_SDCARD checking this for 10068
08-29 14:21:03.611  7687  7687 I libpersona: KNOX_SDCARD not a persona
,08-29 14:21:03.611  7687  7687 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 14:21:03.611  1014  1510 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7687 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-29 14:21:03.611  7687  7687 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 14:21:03.611  1014  1208 D RCPManagerService: exchangeData() failure , invalid userId
08-29 14:21:03.611  7687  7687 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-29 14:21:03.611  7604  7604 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-29 14:21:03.611  7604  7604 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-29 14:21:03.611  7604  7604 I wpa_supplicant: Skip scan - bUseNetwork false
,08-29 14:21:03.631  7687  7687 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 14:21:03.631  7687  7687 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:03.651  1014  1486 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 14:21:03.651  1014  1484 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-29 14:21:03.651  1014  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:03.651  1014  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:03.651  1014  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:03.651  1014  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:03.661  7687  7687 D BadgeProvider: onCreate
08-29 14:21:03.661  7687  7687 D BadgeProvider: DatabaseHelper
08-29 14:21:03.661  7702  7702 E Zygote  : MountEmulatedStorage()
08-29 14:21:03.661  7702  7702 E Zygote  : v2
08-29 14:21:03.661  7702  7702 I libpersona: KNOX_SDCARD checking this for 10009
08-29 14:21:03.661  7702  7702 I libpersona: KNOX_SDCARD not a persona
08-29 14:21:03.661  7702  7702 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 14:21:03.661  7702  7702 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 14:21:03.671  1014  1484 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7702 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,08-29 14:21:03.671  1014  1484 I ActivityManager: Killing 6973:com.android.vending/u0a26 (adj 15): empty #21,
,08-29 14:21:03.671  1014  1484 I ActivityManager: Killing 7255:com.google.android.gms.wearable/u0a11 (adj 15): empty #22
,08-29 14:21:03.671  7702  7702 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-29 14:21:03.701  7702  7702 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 14:21:03.701  7702  7702 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:03.721  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 14:21:03.721  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 14:21:03.721  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-29 14:21:03.751  1014  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-29 14:21:03.751  1014  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-29 14:21:03.751  7604  7604 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-29 14:21:03.751  7604  7604 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 14:21:03.751  7604  7604 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-29 14:21:03.751  7604  7604 E wpa_supplicant: SIM READ ERROR
08-29 14:21:03.751  7604  7604 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 14:21:03.791  1014  1482 I ActivityManager: Killing 7358:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-29 14:21:03.801  7604  7604 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-29 14:21:03.801  1014  1487 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 14:21:03.801  1014  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 14:21:03.801  1014  1487 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:03.801  1014  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 14:21:03.811  1014  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 14:21:03.811  7604  7604 I wpa_supplicant: Skip scan - bUseNetwork false
,08-29 14:21:03.811  1014  1124 D WifiConfigStore: Loading config and enabling all networks 
,08-29 14:21:03.821  1603  1603 I Hs20UtilService: Starting #11
,08-29 14:21:03.821  1603  1624 I Hs20UtilService: Message received 5011
,08-29 14:21:03.821  1014  1094 V AlarmManager: waitForAlarm result :4
,08-29 14:21:03.831  1014  1124 E WifiConfigStore: Not a HS20
,08-29 14:21:03.831  1170  1170 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 14:21:03.831  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 14:21:03.831  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 14:21:03.831  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 14:21:03.831  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:03.831  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:03.831  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:03.831  1170  1170 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 14:21:03.831  1170  1170 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-29 14:21:03.831  1170  1170 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-29 14:21:03.831  1170  1768 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 14:21:03.831  1170  1170 D HotspotTile: onReceive : 3, 0
,08-29 14:21:03.841  4739  4739 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 14:21:03.841  1014  1510 I art     : Explicit concurrent mark sweep GC freed 58233(3MB) AllocSpace objects, 1(64KB) LOS objects, 33% free, 23MB/34MB, paused 2.825ms total 166.132ms
,08-29 14:21:03.841  7413  7413 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 14:21:03.841  7413  7413 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 14:21:03.841  7413  7413 D SecurityLogAgent: StateMachine : Current State = 1
08-29 14:21:03.841  7413  7413 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 14:21:03.851  7083  7083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:21:03.851  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:03.851  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:03.851  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:03.851  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:03.851  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:03.851  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:03.851  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:03.851  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:03.851  7083  7083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:21:03.851  7083  7083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:21:03.851  1014  1124 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-29 14:21:03.851  7083  7083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:21:03.851  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:03.851  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:03.851  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:03.851  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:03.851  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:03.851  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:03.851  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:03.851  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:03.851  7083  7083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:03.851  7083  7083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:21:03.861  1014  1124 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,08-29 14:21:03.861  7604  7604 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-29 14:21:03.861  7604  7604 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-29 14:21:03.861  7604  7604 I wpa_supplicant: reset timer : RESET_TIMER 0
08-29 14:21:03.861  7604  7604 I wpa_supplicant: P2P: Current p2p state = IDLE
08-29 14:21:03.861  7604  7604 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
,08-29 14:21:03.861  7604  7604 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-29 14:21:03.861  7604  7604 I wpa_supplicant: First Scan Start
08-29 14:21:03.861  7604  7604 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-29 14:21:03.861  1014  1124 D WifiNative-wlan0: Setting external_sim to 1
,08-29 14:21:03.861  7687  7695 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-29 14:21:03.871  1014  1124 D WifiStateMachine: Setting OUI to DA-A1-19
,08-29 14:21:03.871  1014  1124 I WifiNative-HAL: startHal
08-29 14:21:03.871  7390  7390 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 14:21:03.871  1014  1124 E wifi    : getStaticLongField sWifiHalHandle 0x9f2ae88c
08-29 14:21:03.871  1014  1124 I WifiNative-HAL: Could not start hal
,08-29 14:21:03.871  1014  3867 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 14:21:03.871  1014  3867 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 14:21:03.871  1014  1124 E WifiNative-wlan0: do suspend true
,08-29 14:21:03.871  1014  1123 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-29 14:21:03.871  1014  1014 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-29 14:21:03.881  1014  3867 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:03.881  1014  3867 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:03.881  1014  3867 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 14:21:03.881   277  1010 D CommandListener: Setting iface cfg
08-29 14:21:03.881  1014  1014 V AlarmManagerEXT: <AppSync3 Whitelist>
08-29 14:21:03.881   277  1010 D CommandListener: Trying to bring up p2p0
08-29 14:21:03.881  1014  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-29 14:21:03.881  1014  1014 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-29 14:21:03.881  1014  1123 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 14:21:03.881  1014  1123 D WifiP2pService: P2pEnablingState
,08-29 14:21:03.881  1014  1123 D WifiP2pService: P2pEnablingState{ what=147457 }
08-29 14:21:03.881  1014  1123 D WifiP2pService: P2p socket connection successful
,08-29 14:21:03.881  1014  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-29 14:21:03.881  1014  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-29 14:21:03.881  1014  1123 D WifiP2pService: P2pEnabledState
08-29 14:21:03.881  1014  1124 E WifiNative-wlan0: invaild command id : 215
08-29 14:21:03.881  1603  1603 I Hs20UtilService: Starting #12
,08-29 14:21:03.881  1603  1624 I Hs20UtilService: Message received 5011
,08-29 14:21:03.881  1170  1170 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-29 14:21:03.881  1170  1170 D KeyguardUpdateMonitor: handleTimeUpdate
08-29 14:21:03.881  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 14:21:03.881  1014  1014 D RttService: SCAN_AVAILABLE : 3
,08-29 14:21:03.881  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:03.881  1014  1148 I WifiNative-HAL: startHal
08-29 14:21:03.881  1014  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9e26e9bc
08-29 14:21:03.881  1014  1148 I WifiNative-HAL: Could not start hal
08-29 14:21:03.881  1014  1148 E WifiScanningService: could not start HAL
08-29 14:21:03.881  1014  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 14:21:03.881  7604  7604 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-29 14:21:03.891  7604  7604 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-29 14:21:03.891  7604  7604 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-29 14:21:03.891  1014  1124 E WifiStateMachine: Failed to set frequency band 0
,08-29 14:21:03.891  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 14:21:03.891  1014  1124 D SecContentProvider2: mCursor = null
,08-29 14:21:03.891  1170  1170 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-29 14:21:03.891  1170  1170 D SecKeyguardClockView: HomeTimezone(): 1
,08-29 14:21:03.891  7413  7413 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 14:21:03.891  7413  7413 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 14:21:03.891  7413  7413 D SecurityLogAgent: StateMachine : Current State = 1
08-29 14:21:03.891  7413  7413 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 14:21:03.901  1014  1253 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-29 14:21:03.901  1014  1253 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
08-29 14:21:03.901  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 14:21:03.901  1014  1124 D SecContentProvider2: mCursor = null
,08-29 14:21:03.901  1170  1170 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 14:21:03.901  1014  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-29 14:21:03.901  1014  1126 E ConnectivityService: updateNetworkInfo()
,08-29 14:21:03.901  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED,
08-29 14:21:03.901  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-29 14:21:03.901  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 14:21:03.901  1014  1045 D WifiDisplayController: disconnect
08-29 14:21:03.901  1014  1045 D WifiDisplayController: updateConnection
08-29 14:21:03.901  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 14:21:03.901  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-29 14:21:03.901  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-29 14:21:03.911  1170  1170 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-29 14:21:03.911  1014  3867 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 14:21:03.911  1014  1123 D WifiNative-p2p0: p2pGetDeviceAddress
08-29 14:21:03.911  7687  7696 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-29 14:21:03.911  7687  7696 D BadgeProvider: sendNotify, [notify] : null
,08-29 14:21:03.911  7687  7696 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-29 14:21:03.911  1014  1123 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
08-29 14:21:03.911  7687  7696 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-29 14:21:03.911  7687  7696 D BadgeProvider: update, [UpdateCount] : 1
08-29 14:21:03.911  1170  1170 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-29 14:21:03.911  1488  1488 D Launcher.Model: reloadBadges entered.
,08-29 14:21:03.911  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 14:21:03.911  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
,08-29 14:21:03.911  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 14:21:03.911  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-29 14:21:03.911  1014  1123 D WifiP2pService: DeviceAddress: 0a:75:42
,08-29 14:21:03.921  1170  1170 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-29 14:21:03.921  1170  1170 I KeyguardEffectViewController: *** don't update sliding image ***
,08-29 14:21:03.921  1014  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-29 14:21:03.921  1014  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-29 14:21:03.921  1014  1045 D WifiDisplayController:  primary type: 10-0050F204-5
08-29 14:21:03.921  1014  1045 D WifiDisplayController:  secondary type: null
08-29 14:21:03.921  1014  1045 D WifiDisplayController:  wps: 0
08-29 14:21:03.921  1014  1045 D WifiDisplayController:  grpcapab: 0
08-29 14:21:03.921  1014  1045 D WifiDisplayController:  devcapab: 0
08-29 14:21:03.921  1014  1045 D WifiDisplayController:  status: 3
08-29 14:21:03.921  1014  1045 D WifiDisplayController:  wfdInfo: null
08-29 14:21:03.921  1014  1045 D WifiDisplayController:  groupownerAddress: null
08-29 14:21:03.921  1014  1045 D WifiDisplayController:  GOdeviceName: null
08-29 14:21:03.921  1014  1045 D WifiDisplayController:  interfaceAddress: 
08-29 14:21:03.921  1014  1045 D WifiDisplayController:  SConnectInfo : null
08-29 14:21:03.921  1014  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-29 14:21:03.931  1014  1485 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 14:21:03.931  1014  1485 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 14:21:03.931  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:03.931  1014  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:03.931  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 14:21:03.931  1603  1603 I Hs20UtilService: Starting #13
,08-29 14:21:03.931  1603  1624 I Hs20UtilService: Message received 5011
,08-29 14:21:03.941  1014  1123 D WifiP2pService: sending p2p persistent groups changed broadcast
08-29 14:21:03.941  1014  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-29 14:21:03.941  1014  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-29 14:21:03.941  1014  1124 E WifiNative-wlan0: invaild command id : 215
,08-29 14:21:03.941  1014  1123 D WifiP2pService: InactiveState
08-29 14:21:03.941  7413  7413 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 14:21:03.941  7413  7413 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 14:21:03.941  7413  7413 D SecurityLogAgent: StateMachine : Current State = 1
08-29 14:21:03.941  7413  7413 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-29 14:21:03.941  1014  1123 D WifiP2pService: InactiveState{ what=143376 }
,08-29 14:21:03.941  1014  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-29 14:21:03.941  7604  7604 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-29 14:21:03.941  1014  1123 D WifiP2pService: InactiveState{ what=143376 }
08-29 14:21:03.941  1014  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-29 14:21:03.951  4739  4739 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-29 14:21:03.951  4739  4739 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 14:21:03.951   277  1006 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 14:21:03.951   277  1006 D Netd    : getNetworkForDns: using netid 0 for uid 10011
08-29 14:21:03.951  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 14:21:03.961  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-29 14:21:03.961  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 14:21:03.961  4739  4739 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 14:21:03.961  1170  1170 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 14:21:03.961  4739  4815 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 14:21:03.961  1170  1170 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 14:21:03.961  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-29 14:21:03.971  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:03.971  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:03.971  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:03.971  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:03.981  7727  7727 E Zygote  : MountEmulatedStorage(),
08-29 14:21:03.981  7727  7727 I libpersona: KNOX_SDCARD checking this for 10064
08-29 14:21:03.981  7727  7727 E Zygote  : v2
08-29 14:21:03.981  7727  7727 I libpersona: KNOX_SDCARD not a persona
,08-29 14:21:03.981  7727  7727 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 14:21:03.981  1014  1026 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7727 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 14:21:03.991  1170  1170 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 14:21:03.991  7727  7727 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 14:21:03.991  7727  7727 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 14:21:04.001  1170  1170 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,08-29 14:21:04.011  7727  7727 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 14:21:04.011  7727  7727 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:04.021  7727  7727 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-29 14:21:04.031  7727  7727 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 14:21:04.031  7727  7727 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-29 14:21:04.061  7727  7727 D FileShare-Client: Outbound.stopDelayTimer - 
,08-29 14:21:04.061  7375  7375 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 14:21:04.071  1014  3867 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:04.071  1014  3867 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:21:04.071  1014  3867 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-29 14:21:04.071  1014  1484 I ActivityManager: Killing 7292:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-29 14:21:05.191  7604  7604 I wpa_supplicant: nl80211: Received scan results (25 BSSes),
,08-29 14:21:05.191  7604  7604 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-29 14:21:05.191  7604  7604 I wpa_supplicant: Trying to associate with SSID '4E47373030',
08-29 14:21:05.191  7604  7604 I wpa_supplicant: Trying to associate with  'G700'
08-29 14:21:05.191  7604  7604 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-29 14:21:05.191  7604  7604 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-29 14:21:05.191  1014  7718 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-29 14:21:05.211  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 14:21:05.221  1014  1124 D SecContentProvider2: mCursor = null
,08-29 14:21:05.301  1014  3867 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 14:21:05.301  1014  3867 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 14:21:05.301  1014  3867 D SecContentProvider2: mCursor = null
,08-29 14:21:05.301  1014  3867 D WifiService: setWifiEnabled: false pid=7083, uid=10170
,08-29 14:21:05.301  1014  3867 D SettingsProvider: name = wifi_on
,08-29 14:21:05.301  7604  7604 E wpa_supplicant: Cmd 35605 not handled
,08-29 14:21:05.301  7604  7604 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-29 14:21:05.301  7604  7604 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-29 14:21:05.301  7604  7604 I wpa_supplicant: Associated with F4.99.3E
08-29 14:21:05.301  7604  7604 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-29 14:21:05.301  7604  7604 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-29 14:21:05.301  7604  7604 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-29 14:21:05.311  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 14:21:05.311  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-29 14:21:05.311  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 14:21:05.311  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 14:21:05.311  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-29 14:21:05.311  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 14:21:05.311  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 14:21:05.311  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 14:21:05.311  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-29 14:21:05.311  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-29 14:21:05.311  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, true
,08-29 14:21:05.311  1014  1042 D Tethering: interfaceStatusChanged wlan0, true
08-29 14:21:05.321  1014  1123 D WifiP2pService: InactiveState{ what=131204 }
08-29 14:21:05.311  7604  7604 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 14:21:05.321  1014  1123 D WifiP2pService: P2pEnabledState{ what=131204 }
08-29 14:21:05.321  7604  7604 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-29 14:21:05.321  7604  7604 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-29 14:21:05.321  7604  7604 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-29 14:21:05.321  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 14:21:05.321  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:05.321  7604  7604 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 14:21:05.321  7604  7604 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-29 14:21:05.321  7604  7604 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-29 14:21:05.321  7604  7604 I wpa_supplicant: Blacklist: Clear (temp) 
,08-29 14:21:05.321  7604  7604 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-29 14:21:05.321  1014  1014 D RttService: SCAN_AVAILABLE : 1
08-29 14:21:05.321  1014  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 14:21:05.321  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-29 14:21:05.321  1014  1123 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-29 14:21:05.321  1014  1042 D Tethering: interfaceStatusChanged wlan0, true
08-29 14:21:05.321  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 14:21:05.321  1014  1124 D SecContentProvider2: mCursor = null
08-29 14:21:05.321  1014  1126 E ConnectivityService: updateNetworkInfo()
08-29 14:21:05.331  1014  1128 E Tethering: No numeric data
,08-29 14:21:05.331  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true,
,08-29 14:21:05.331  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:05.331  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
08-29 14:21:05.331  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 14:21:05.331  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-29 14:21:05.331  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 14:21:05.331  1014  1128 D Tethering: clearTetheredNotification()
,08-29 14:21:05.341  4739  4739 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-29 14:21:05.341  4739  4739 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 14:21:05.341  1014  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-29 14:21:05.341  1014  1126 E ConnectivityService: updateNetworkInfo()
,08-29 14:21:05.341  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
08-29 14:21:05.341  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 14:21:05.341  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 14:21:05.341  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 14:21:05.341  1170  1170 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 14:21:05.341  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-29 14:21:05.341  1170  1170 D HotspotTile: updateTetherState():false, false
,08-29 14:21:05.341  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-29 14:21:05.341  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-29 14:21:05.341  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 14:21:05.341  1014  1045 D WifiDisplayController: disconnect
08-29 14:21:05.341  1014  1045 D WifiDisplayController: updateConnection
08-29 14:21:05.341  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 14:21:05.341  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 14:21:05.341  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 14:21:05.341  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 14:21:05.341  4739  4739 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 14:21:05.341  4739  4815 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-29 14:21:05.341  1014  1121 V NetworkStats: performPollLocked() took 6ms
08-29 14:21:05.341  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 14:21:05.351  1014  1123 D WifiP2pService: P2pDisablingState
,08-29 14:21:05.351  1014  1123 D WifiP2pService: P2pDisablingState{ what=147458 },
08-29 14:21:05.351  1014  1123 D WifiP2pService: p2p socket connection lost
,08-29 14:21:05.351  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 14:21:05.351   277  1010 D CommandListener: Clearing all IP addresses on wlan0
08-29 14:21:05.351  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
08-29 14:21:05.351  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 14:21:05.351  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-29 14:21:05.351  1014  1123 D WifiP2pService: P2pDisabledState
,08-29 14:21:05.351  1170  1170 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-29 14:21:05.351  1014  1336 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-29 14:21:05.351  1170  1170 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-29 14:21:05.361  7727  7727 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 14:21:05.361  7727  7727 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-29 14:21:05.361  7727  7727 D FileShare-Client: Outbound.stopDelayTimer - 
,08-29 14:21:05.361  7604  7604 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-29 14:21:05.361  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-29 14:21:05.371  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:21:05.371  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-29 14:21:05.371  1170  1170 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 14:21:05.371  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 14:21:05.371  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-29 14:21:05.371  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:05.371  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 14:21:05.381  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:05.381  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 14:21:05.391  7375  7375 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 14:21:05.391  1170  1170 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 14:21:05.391  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 14:21:05.391  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-29 14:21:05.391  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 14:21:05.391  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 14:21:05.391  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:05.391  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:05.391  1170  1170 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 14:21:05.391  1170  1170 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-29 14:21:05.401  1170  1170 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-29 14:21:05.401  1170  1768 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 14:21:05.401  1170  1170 D HotspotTile: onReceive : 0, 0
,08-29 14:21:05.401  4739  4739 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 14:21:05.401  1014  1040 W ActivityManager: mDVFSHelper.release(),
,08-29 14:21:05.401  7083  7083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:05.401  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:05.401  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:05.401  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:05.401  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:05.401  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:05.401  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:05.401  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:05.401  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:05.401  7083  7083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:21:05.401  7083  7083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:21:05.411  4739  4739 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-29 14:21:05.411  4739  4739 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 14:21:05.411  7083  7083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:05.411  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:05.411  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:05.411  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:05.411  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:05.411  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:05.411  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:05.411  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:05.411  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:05.411  7083  7083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:21:05.411  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-29 14:21:05.411  7083  7083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:21:05.411  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-29 14:21:05.411  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 14:21:05.411  4739  4739 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 14:21:05.411  4739  4815 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 14:21:05.421  7727  7727 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 14:21:05.421  7727  7727 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-29 14:21:05.421  7727  7727 D FileShare-Client: Outbound.stopDelayTimer - 
,08-29 14:21:05.421  7375  7375 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 14:21:05.431  1014  3867 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 14:21:05.431  1014  3867 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 14:21:05.431  1014  3867 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:05.431  1014  3867 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:05.431  1014  3867 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 14:21:05.441  1603  1603 I Hs20UtilService: Starting #14
,08-29 14:21:05.441  1603  1624 I Hs20UtilService: Message received 5007
,08-29 14:21:05.441  4739  4739 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-29 14:21:05.441  4739  4739 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 14:21:05.441  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 14:21:05.441  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 14:21:05.441  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 14:21:05.441  4739  4739 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 14:21:05.441  4739  4815 V NearbySettings: MountReceiver.mPrefHandler - 7002,
,08-29 14:21:05.451  1014  1485 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 14:21:05.451  1014  1485 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 14:21:05.451  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:05.451  1014  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:05.451  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 14:21:05.451  7413  7413 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 14:21:05.451  7413  7413 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 14:21:05.451  7413  7413 D SecurityLogAgent: StateMachine : Current State = 1
,08-29 14:21:05.451  7413  7413 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 14:21:05.451  1603  1603 I Hs20UtilService: Starting #15
,08-29 14:21:05.451  1603  1624 I Hs20UtilService: Message received 5011
,08-29 14:21:05.501  7604  7604 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 14:21:05.561  7604  7604 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-29 14:21:05.561  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 14:21:05.561  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
08-29 14:21:05.561  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 14:21:05.581  7604  7604 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-29 14:21:05.581  7604  7604 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-29 14:21:05.581  7604  7604 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-29 14:21:05.581  7604  7604 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-29 14:21:05.581  7604  7604 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-29 14:21:05.591  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 14:21:05.591  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-29 14:21:05.591  1014  1128 D Tethering: InitialState.processMessage what=4
08-29 14:21:05.591  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 14:21:05.591  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,08-29 14:21:05.591  1014  1042 D Tethering: interfaceStatusChanged wlan0, false,
08-29 14:21:05.591  1014  1128 E Tethering: No numeric data
,08-29 14:21:05.591  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 14:21:05.591  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 14:21:05.591  1014  1128 D Tethering: clearTetheredNotification()
08-29 14:21:05.591  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
,08-29 14:21:05.591  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-29 14:21:05.591  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 14:21:05.591  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 14:21:05.591  1170  1170 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 14:21:05.591  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-29 14:21:05.591  1170  1170 D HotspotTile: updateTetherState():false, false
,08-29 14:21:05.591  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 14:21:05.601  1014  1121 V NetworkStats: performPollLocked() took 6ms
08-29 14:21:05.591  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 14:21:05.601  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:21:05.601  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:21:05.601  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 14:21:05.871   287   287 E SMD     : DCD OFF
,08-29 14:21:05.911  7604  7604 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 14:21:05.971  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-29 14:21:05.971  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 14:21:05.971  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-29 14:21:05.971  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 14:21:05.971  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 14:21:05.971  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-29 14:21:05.971  7604  7604 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 14:21:06.091  1014  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0,
08-29 14:21:06.091  1014  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21],
08-29 14:21:06.091  7390  7390 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 14:21:06.091  1170  1170 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 14:21:06.091  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 14:21:06.091  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 14:21:06.091  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:06.091  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:06.091  1170  1170 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 14:21:06.091  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:06.091  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:06.091  1170  1170 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 14:21:06.091  1170  1170 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-29 14:21:06.091  1170  1768 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 14:21:06.091  1170  1170 D HotspotTile: onReceive : 1, 0
,08-29 14:21:06.091  1729  2203 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:21:06.101  4739  4739 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 14:21:06.101  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:06.101  1014  1208 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 14:21:06.101  1014  1208 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 14:21:06.101  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:06.101  1014  1208 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:06.101  1014  1208 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:06.101  1014  1208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 14:21:06.111  1603  1603 I Hs20UtilService: Starting #16
,08-29 14:21:06.121  1603  1624 I Hs20UtilService: Message received 5011
,08-29 14:21:06.121  7413  7413 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 14:21:06.121  7413  7413 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 14:21:06.121  7413  7413 D SecurityLogAgent: StateMachine : Current State = 1
08-29 14:21:06.121  7413  7413 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 14:21:06.611  1014  1042 D Tethering: interfaceRemoved wlan0
,08-29 14:21:06.611  1014  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-29 14:21:06.721  1014  3374 D SSRM:n  : SIOP:: AP = 400
,08-29 14:21:06.761  1014  1042 D Tethering: interfaceRemoved p2p0
,08-29 14:21:06.761  1014  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-29 14:21:07.191  1014  3396 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 14:21:07.511  1014  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-29 14:21:07.881   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 14:21:08.321  7083  7251 D BluetoothAdapter: enable()
,08-29 14:21:08.321  1014  1026 W ActivityManager: Permission Denial: getCurrentUser() from pid=7083, uid=10170 requires android.permission.INTERACT_ACROSS_USERS,
,08-29 14:21:08.321  1014  1026 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-29 14:21:08.321  1014  1026 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7083, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-29 14:21:08.321  1014  1026 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 14:21:08.321  1014  1026 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-29 14:21:08.321  1014  1026 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688),
08-29 14:21:08.321  1014  1026 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-29 14:21:08.321  1014  1026 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-29 14:21:08.321  1014  1026 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 14:21:08.321  1014  1026 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 14:21:08.321  1014  1026 D SettingsProvider: name = bluetooth_on,
,08-29 14:21:08.331  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-29 14:21:08.331  1014  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
08-29 14:21:08.331  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 14:21:08.341  3235  3311 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-29 14:21:08.341  3235  3311 D BluetoothAdapterProperties: Setting state to 11
08-29 14:21:08.341  3235  3311 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-29 14:21:08.341  3235  3311 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 14:21:08.341  3235  3311 D BluetoothAdapterService: updateAdapterState state is 11
,08-29 14:21:08.341  3235  3311 D BluetoothAdapterService: Autoconnection is available 
,08-29 14:21:08.341  3235  3311 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-29 14:21:08.341  3235  3311 D BtConfig.SecureMode: isSecureModeOn:false
08-29 14:21:08.341  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-29 14:21:08.341  3235  3311 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,08-29 14:21:08.341  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 14:21:08.341  3235  3311 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-29 14:21:08.341  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService,
08-29 14:21:08.341  3235  3311 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-29 14:21:08.341  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-29 14:21:08.351  3235  3311 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-29 14:21:08.351  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-29 14:21:08.351  3235  3311 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-29 14:21:08.351  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 14:21:08.351  3235  3311 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-29 14:21:08.351  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 14:21:08.351  3235  3311 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-29 14:21:08.351  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-29 14:21:08.351  3235  3311 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-29 14:21:08.351  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 14:21:08.351  3235  3311 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 14:21:08.351  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 14:21:08.351  3235  3311 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-29 14:21:08.351  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 14:21:08.351  3235  3311 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-29 14:21:08.351  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 14:21:08.351  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:21:08.351  3235  3311 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-29 14:21:08.351  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
08-29 14:21:08.351  3235  3311 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-29 14:21:08.351  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-29 14:21:08.351  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 14:21:08.351  3235  3311 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-29 14:21:08.361  1170  1170 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 14:21:08.361  1170  1170 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:21:08.361  1170  1170 D BluetoothTile:  getBluetoothState : 11
,08-29 14:21:08.361  1014  1027 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 14:21:08.371  1014  1336 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-29 14:21:08.371  1170  1768 D BluetoothTile:  handleUpdatestate:false name:null
08-29 14:21:08.371  1170  1768 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-29 14:21:08.371  1868  1868 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 14:21:08.371  1170  1170 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 14:21:08.371  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:08.371  4739  4739 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:21:08.371  1014  1253 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 14:21:08.371  1014  1253 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-29 14:21:08.371  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:08.371  1014  1253 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:08.371  1014  1253 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:08.371  1014  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:08.381  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-29 14:21:08.381  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-29 14:21:08.381  3235  3311 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-29 14:21:08.381  1014  1484 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 14:21:08.381  1014  1484 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 14:21:08.381  1014  1484 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:08.381  1014  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:08.381  1014  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:08.381  3235  3235 D HeadsetService: Received start request. Starting profile...
08-29 14:21:08.381  3235  3235 D HeadsetService: start()
08-29 14:21:08.381  3235  3235 D HeadsetStateMachine: make
,08-29 14:21:08.381  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,08-29 14:21:08.381  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 14:21:08.381  3235  3311 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-29 14:21:08.391  3235  3235 E HeadsetStateMachine: # of Max HF connection is 2
,08-29 14:21:08.391  2635  2635 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 14:21:08.391  1014  1482 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 14:21:08.391  1014  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 14:21:08.391  1014  1482 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:08.391  1014  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:08.391  1014  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:08.401  1014  1486 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-29 14:21:08.401  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
08-29 14:21:08.401  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-29 14:21:08.401  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-29 14:21:08.401  3235  3311 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-29 14:21:08.401  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:08.401  1014  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:08.401  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-29 14:21:08.401  1014  1336 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 14:21:08.401  1014  1336 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-29 14:21:08.401  1014  1336 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:08.401  1014  1336 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 14:21:08.401  1014  1336 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:08.411  4739  4739 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 14:21:08.411  1014  1484 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-29 14:21:08.411  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-29 14:21:08.411  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 14:21:08.411  1014  1484 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-29 14:21:08.411  3235  3311 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-29 14:21:08.411  1014  1484 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:08.411  1014  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:08.411  1014  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-29 14:21:08.411  1014  3867 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 14:21:08.411  3235  3235 I bluedroid: get_profile_interface handsfree
,08-29 14:21:08.411  1014  3867 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 14:21:08.411  1014  3867 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:08.411  1014  3867 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:08.411  1014  3867 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:08.411  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-29 14:21:08.411  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 14:21:08.411  3235  3311 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-29 14:21:08.411  1014  1482 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 14:21:08.411  1014  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 14:21:08.421  1014  1482 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:08.421  1014  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:08.421  1014  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:08.421  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-29 14:21:08.421  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 14:21:08.421  3235  3311 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-29 14:21:08.421  1014  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 14:21:08.421  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-29 14:21:08.421  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:08.421  1014  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:08.421  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:08.421  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 14:21:08.421  3235  3235 E DualScoManager: Dual Sco Manager already instantiated
08-29 14:21:08.421  3235  3235 I DualScoManager: Set HeadsetServiceHelper
08-29 14:21:08.421  3235  3235 D BluetoothAtMessage: createCMTIContentObservers
08-29 14:21:08.421  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 14:21:08.421  1014  1027 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-29 14:21:08.421  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 14:21:08.421  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 14:21:08.421  1014  1027 D SettingsProvider: selectionArgs: false
08-29 14:21:08.421  1014  1027 D SettingsProvider: selectionArgs: 1002
08-29 14:21:08.421  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 14:21:08.421  1014  1027 D SettingsProvider: ret = -1
08-29 14:21:08.421  3235  3311 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-29 14:21:08.421  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-29 14:21:08.421  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 14:21:08.421  3235  3311 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-29 14:21:08.421  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-29 14:21:08.421  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 14:21:08.421  3235  3311 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-29 14:21:08.421  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-29 14:21:08.421  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 14:21:08.421  3235  3311 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-29 14:21:08.421  3235  3311 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-29 14:21:08.421  3235  7746 D HeadsetStateMachine: Enter Disconnected: -2
08-29 14:21:08.431  1170  1170 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:08.431  1170  1170 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
08-29 14:21:08.431  3235  3235 D HeadsetService: mStartError = false
08-29 14:21:08.431  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
,08-29 14:21:08.431  3235  3235 D A2dpService: Received start request. Starting profile...
,08-29 14:21:08.431  1014  1484 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
08-29 14:21:08.431  3235  3235 D A2dpService: start()
08-29 14:21:08.431  3235  3235 I bluedroid: get_profile_interface avrcp
,08-29 14:21:08.431  3235  7746 D HeadsetStateMachine: Clear mHeadsetBrsf
08-29 14:21:08.431  1014  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:08.431  3235  7746 D HeadsetStateMachine: map size, before remove : 0
08-29 14:21:08.431  3235  7746 D HeadsetStateMachine: map size, after remove: 0
08-29 14:21:08.431  1014  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:08.431  1014  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:08.431  1014  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:08.441  3235  3235 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 14:21:08.441  3235  3235 D Avrcp   : Initialize Media Controller
08-29 14:21:08.441  3235  3235 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-29 14:21:08.441  3235  3235 E Avrcp   : getActiveSessions
,08-29 14:21:08.441  3235  3235 D Avrcp   : pick active media Controller
,08-29 14:21:08.441  3235  3235 D Avrcp   : Get the active Media Controller 
,08-29 14:21:08.451  7748  7748 E Zygote  : MountEmulatedStorage()
08-29 14:21:08.451  7748  7748 E Zygote  : v2
08-29 14:21:08.451  7748  7748 I libpersona: KNOX_SDCARD checking this for 10055
08-29 14:21:08.451  7748  7748 I libpersona: KNOX_SDCARD not a persona
,08-29 14:21:08.451  1014  1484 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7748 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-29 14:21:08.451  7748  7748 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 14:21:08.451  7748  7748 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 14:21:08.461  7748  7748 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 14:21:08.461  3235  3235 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-29 14:21:08.461  3235  7747 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-29 14:21:08.461  3235  3235 D A2dpStateMachine: make
,08-29 14:21:08.461  3235  3235 I bluedroid: get_profile_interface a2dp
08-29 14:21:08.461  3235  7757 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-29 14:21:08.461  3235  3235 E bt-btif : warning : media task started media_task_refcnt 1 
,08-29 14:21:08.461  3235  3235 D A2dpService: mStartError = false
08-29 14:21:08.461  3235  7755 D A2dpStateMachine: Enter Disconnected: -2
08-29 14:21:08.461  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
,08-29 14:21:08.471  3235  3235 D HidService: Received start request. Starting profile...
08-29 14:21:08.471  3235  3235 D HidService: start()
08-29 14:21:08.471  3235  3235 I bluedroid: get_profile_interface hidhost
08-29 14:21:08.471  3235  3235 D HidService: setHidService(): set to: null
08-29 14:21:08.471  3235  3235 D HidService: mStartError = false
08-29 14:21:08.471  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
08-29 14:21:08.471  3235  3235 D HeadsetStateMachine: Try to query the phonestate on bind
,08-29 14:21:08.471  1430  1466 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 14:21:08.471  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-29 14:21:08.471  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-29 14:21:08.471  1430  1466 I Telecom : BluetoothPhoneService: Result of Message : true
,08-29 14:21:08.471  3235  7747 D BluetoothMediaBrowser: no now playing list
08-29 14:21:08.471  3235  3235 D HealthService: Received start request. Starting profile...
08-29 14:21:08.471  3235  3235 D HealthService: start()
,08-29 14:21:08.471  3235  7747 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-29 14:21:08.471  3235  3235 I bluedroid: get_profile_interface health
,08-29 14:21:08.471  3235  3235 D HealthService: mStartError = false
08-29 14:21:08.471  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
08-29 14:21:08.471  3235  3235 D HeadsetStateMachine: Proxy object connected
08-29 14:21:08.471  3235  3235 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-29 14:21:08.471  3235  7746 D HeadsetStateMachine: Disconnected process message: 11
08-29 14:21:08.471  3235  3235 D PanService: Received start request. Starting profile...
,08-29 14:21:08.481  3235  3235 D PanService: start()
08-29 14:21:08.481  3235  3235 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 14:21:08.481  3235  3235 I bluedroid: get_profile_interface pan
08-29 14:21:08.481  3235  3235 D PanService: mStartError = false
08-29 14:21:08.481  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
08-29 14:21:08.481  3235  3235 D BluetoothMapService: Received start request. Starting profile...
,08-29 14:21:08.481  3235  3235 D BluetoothMapService: start()
,08-29 14:21:08.481  7748  7748 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 14:21:08.481  3235  3235 D BluetoothMapService: mStartError = false
08-29 14:21:08.481  7748  7748 D ActivityThread: Added TimaKeyStore provider
08-29 14:21:08.481  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
08-29 14:21:08.481  3235  3235 D HeadsetPhoneState: sendDeviceDataStateChanged
08-29 14:21:08.481  3235  3235 D HeadsetPhoneState: Signal level : previous=0 curr=4
,08-29 14:21:08.481  3235  7746 D HeadsetStateMachine: Disconnected process message: 18
08-29 14:21:08.481  3235  3235 D SapService: Received start request. Starting profile...
08-29 14:21:08.481  3235  3235 D SapService: start()
08-29 14:21:08.481  3235  3235 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-29 14:21:08.481  3235  3235 I bluedroid: get_profile_interface sap
08-29 14:21:08.481  3235  3235 D SapService: mStartError = false
08-29 14:21:08.481  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
08-29 14:21:08.481  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-29 14:21:08.481  3235  3235 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-29 14:21:08.481  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-29 14:21:08.481  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-29 14:21:08.481  3235  7746 D HeadsetStateMachine: Disconnected process message: 10
,08-29 14:21:08.481  3235  7746 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-29 14:21:08.481  3235  7746 D HeadsetStateMachine: Disconnected process message: 11
,08-29 14:21:08.491  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true,
08-29 14:21:08.491  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-29 14:21:08.501  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-29 14:21:08.501  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-29 14:21:08.511  3235  3311 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-29 14:21:08.511  3235  3311 I bluedroid: enable
,08-29 14:21:08.511  3235  3317 E bt-btif : Calling BTA_HhEnable
,08-29 14:21:08.511  3235  3317 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-29 14:21:08.511  3235  3317 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-29 14:21:08.511  3235  3317 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-29 14:21:08.511  3235  3317 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
,08-29 14:21:08.511  3235  3317 E BluetoothServiceJni: populateRssiValuesNative
08-29 14:21:08.511  3235  3317 I bluedroid: getModelRssiValues
,08-29 14:21:08.511  3235  3317 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-29 14:21:08.511  3235  3317 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-29 14:21:08.521  7748  7748 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-29 14:21:08.521  1014  1014 D SettingsProvider: name = bluetooth_name
,08-29 14:21:08.521  3235  3317 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-29 14:21:08.521  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:08.531  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:08.531  3235  3317 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-29 14:21:08.531  3235  3317 D BluetoothAdapterProperties: Scan Mode:20
,08-29 14:21:08.531  3235  3317 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 14:21:08.531  3235  3317 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
,08-29 14:21:08.531  3235  3317 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-29 14:21:08.531  3235  3317 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-29 14:21:08.531  3235  3317 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-29 14:21:08.531  3235  3317 E bt-btif : JVenable fails
,08-29 14:21:08.531  3235  3317 D bte_conf: Device ID record 1 : primary
,08-29 14:21:08.531  3235  3317 D bte_conf:   vendorId            = 0075
08-29 14:21:08.531  3235  3317 D bte_conf:   vendorIdSource      = 0001
08-29 14:21:08.531  3235  3317 D bte_conf:   product             = 0100
08-29 14:21:08.531  3235  3317 D bte_conf:   version             = 0200
08-29 14:21:08.531  3235  3317 D bte_conf:   clientExecutableURL = 
08-29 14:21:08.531  3235  3317 D bte_conf:   serviceDescription  = 
08-29 14:21:08.531  3235  3317 D bte_conf:   documentationURL    = 
,08-29 14:21:08.531  3235  3317 D bte_conf: bte_load_did_conf no section named DID2.
08-29 14:21:08.531  3235  3317 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-29 14:21:08.531  3235  3317 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 14:21:08.531  3235  3311 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-29 14:21:08.531  3235  3311 D BluetoothAdapterProperties: ScanMode =  20
08-29 14:21:08.531  3235  3311 D BluetoothAdapterProperties: State =  11
,08-29 14:21:08.541  1014  1253 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-29 14:21:08.541  3235  3311 D BluetoothAdapterProperties: Setting state to 12
,08-29 14:21:08.541  3235  3311 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 14:21:08.541  3235  3317 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-29 14:21:08.541  3235  3317 D BluetoothAdapterProperties: Scan Mode:21
08-29 14:21:08.541  3235  3317 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 14:21:08.541  1014  1484 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-29 14:21:08.541  1014  1484 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 14:21:08.541  1014  1484 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 14:21:08.541  1014  1484 D SettingsProvider: selectionArgs: false
08-29 14:21:08.541  1014  1484 D SettingsProvider: selectionArgs: 1002
08-29 14:21:08.541  1014  1484 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 14:21:08.541  1014  1484 D SettingsProvider: ret = -1
,08-29 14:21:08.541  3235  3311 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-29 14:21:08.541  3235  3311 D BluetoothAdapterService: updateAdapterState state is 12
,08-29 14:21:08.541  1014  1482 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 14:21:08.551  1014  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 14:21:08.551  1014  1482 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:08.551  1014  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:08.551  1014  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:08.551  7748  7748 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-29 14:21:08.551  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:08.551  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:08.551  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:08.551  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:08.551  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:08.551  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:08.551  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:08.551  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:08.551  7748  7748 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-29 14:21:08.551  7748  7748 D UserAnalysis: Create SecureDbHelper
,08-29 14:21:08.551  3235  3311 D BluetoothAdapterService: Autoconnection is available 
08-29 14:21:08.551  4739  7289 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 14:21:08.551  3235  3311 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-29 14:21:08.551  3235  3311 D BluetoothAdapterService: starting service from this receiver
,08-29 14:21:08.551  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 14:21:08.551  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-29 14:21:08.551  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:08.551  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:08.551  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:08.561  3235  3311 I BluetoothAdapterState: Entering On State from state = 11
,08-29 14:21:08.561  7748  7748 D IntelligenceServiceApplication: onCreate()
08-29 14:21:08.561  7083  7083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:21:08.561  4739  7289 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 14:21:08.561  3235  3235 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-29 14:21:08.561  1014  1485 I ActivityManager: Killing 7313:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-29 14:21:08.561  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:08.561  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:08.561  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:08.561  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:08.561  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:08.561  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:08.561  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:08.561  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:08.571  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 14:21:08.571  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 14:21:08.571  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:08.571  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:08.571  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:08.571  7748  7748 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-29 14:21:08.571  7083  7083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:21:08.571  2635  4336 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 14:21:08.571  2635  4336 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 14:21:08.571  1014  1336 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-29 14:21:08.571  4739  4746 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 14:21:08.571  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-29 14:21:08.571  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-29 14:21:08.571  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 14:21:08.571  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:08.571  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:08.571  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:08.571  3235  3235 I BluetoothPbapService: Handler(): got msg=1
,08-29 14:21:08.581  1014  3867 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-29 14:21:08.581  1440  1459 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 14:21:08.581  1440  1459 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 14:21:08.581  1014  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 14:21:08.581  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 14:21:08.581  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-29 14:21:08.581  1014  1044 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 14:21:08.581  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-29 14:21:08.581  1430  1450 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 14:21:08.581  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 14:21:08.581  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 14:21:08.581  4739  4739 D BluetoothA2dp: Proxy object connected
08-29 14:21:08.581  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:08.591  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:08.591  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-29 14:21:08.591  4739  4739 D A2dpProfile: Bluetooth service connected
,08-29 14:21:08.591  3235  7771 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-29 14:21:08.591  1430  1450 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 14:21:08.591  1014  1044 D BluetoothPan: Binding service...
,08-29 14:21:08.591  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-29 14:21:08.591  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 14:21:08.591  4739  4746 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 14:21:08.591  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 14:21:08.591  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-29 14:21:08.591  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-29 14:21:08.591  4739  4739 D BluetoothInputDevice: Proxy object connected
08-29 14:21:08.591  4739  4739 D HidProfile: Bluetooth service connected
08-29 14:21:08.591  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:08.591  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:08.591  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:08.601  3235  7771 D BluetoothSocket: bindListen(): myUserId = 0
08-29 14:21:08.601  3235  7771 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 14:21:08.601  3235  3318 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 14:21:08.601  3235  3318 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 14:21:08.601  1430  1466 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 14:21:08.601  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-29 14:21:08.601  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-29 14:21:08.601  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:08.601  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:08.601  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-29 14:21:08.601  3235  7771 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-29 14:21:08.601  3235  7771 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 14:21:08.601  3235  7771 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 14:21:08.601  3235  7771 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f472f5d
08-29 14:21:08.601  3235  7771 D BluetoothSocket: channel: 19
08-29 14:21:08.601  3235  7771 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-29 14:21:08.601  1430  1466 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 14:21:08.611  4739  4739 D BluetoothPbap: Proxy object connected
08-29 14:21:08.611  4739  4739 D PbapServerProfile: Bluetooth service connected
,08-29 14:21:08.611  1170  2086 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 14:21:08.611  1170  2086 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 14:21:08.611  1729  1961 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 14:21:08.611  1729  1961 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 14:21:08.621  1014  1044 E BluetoothManagerService: Unable to call onBluetoothStateChange() on callback #12
08-29 14:21:08.621  1014  1044 E BluetoothManagerService: android.os.DeadObjectException
08-29 14:21:08.621  1014  1044 E BluetoothManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 14:21:08.621  1014  1044 E BluetoothManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 14:21:08.621  1014  1044 E BluetoothManagerService: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub$Proxy.onBluetoothStateChange(IBluetoothStateChangeCallback.java:84)
08-29 14:21:08.621  1014  1044 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:1053)
08-29 14:21:08.621  1014  1044 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2007)
08-29 14:21:08.621  1014  1044 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
08-29 14:21:08.621  1014  1044 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1576)
08-29 14:21:08.621  1014  1044 E BluetoothManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:21:08.621  1014  1044 E BluetoothManagerService: 	at android.os.Looper.loop(Looper.java:145)
08-29 14:21:08.621  1014  1044 E BluetoothManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 14:21:08.621  1014  1044 E BluetoothManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-29 14:21:08.621  4739  4747 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 14:21:08.621  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-29 14:21:08.621  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 14:21:08.621  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:08.621  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:08.621  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:08.621  4739  4747 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 14:21:08.631  4739  4739 D HeadsetProfile: Bluetooth service connected
,08-29 14:21:08.631  1430  7772 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 14:21:08.631  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-29 14:21:08.631  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 14:21:08.631  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:08.631  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:08.631  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:08.631  1430  7772 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 14:21:08.631  4739  4746 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 14:21:08.631  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-29 14:21:08.631  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 14:21:08.631  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:08.631  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:08.631  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:08.641  4739  4747 D Bluetoothsap: onBluetoothStateChange: up=true
,08-29 14:21:08.641  4739  4747 D Bluetoothsap: Binding service...
,08-29 14:21:08.641  4739  4739 D BluetoothMap: Proxy object connected
,08-29 14:21:08.641  4739  4739 D MapProfile: Bluetooth service connected
,08-29 14:21:08.641  4739  4739 D BluetoothMap: getConnectedDevices()
,08-29 14:21:08.641  4739  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-29 14:21:08.641  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-29 14:21:08.641  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 14:21:08.641  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:08.641  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:08.641  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-29 14:21:08.641  4739  4747 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-29 14:21:08.641  1456  1476 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 14:21:08.641  4739  4739 D Bluetoothsap: BluetoothSAP Proxy object connected
08-29 14:21:08.641  1456  1476 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 14:21:08.641  4739  4739 D SapProfile: Bluetooth service connected
08-29 14:21:08.641  4739  4739 D Bluetoothsap: getConnectedDevices()
08-29 14:21:08.641  4739  7289 D BluetoothPan: Binding service...
,08-29 14:21:08.651  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-29 14:21:08.651  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 14:21:08.651  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:08.651  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:08.651  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:08.651  7083  7242 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 14:21:08.651  7083  7242 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 14:21:08.651  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 14:21:08.651  4739  4739 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 14:21:08.651  4739  4739 D PanProfile: Bluetooth service connected
08-29 14:21:08.651  1014  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 14:21:08.651  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 14:21:08.651  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-29 14:21:08.651  1014  1014 D BluetoothA2dp: Proxy object connected
08-29 14:21:08.651  1430  1466 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 14:21:08.651  1430  1466 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 14:21:08.651  1456  2019 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 14:21:08.651  1014  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-29 14:21:08.651  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 14:21:08.651  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:08.651  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:08.651  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:08.651  1456  2019 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 14:21:08.651  3235  3394 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 14:21:08.651  3235  3394 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 14:21:08.651  1014  1044 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 14:21:08.651  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 14:21:08.651  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:08.651  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:08.651  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:08.661  4739  7722 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 14:21:08.661  3235  3235 D BluetoothA2dp: Proxy object connected
08-29 14:21:08.661  3235  3235 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-29 14:21:08.661  4739  7722 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 14:21:08.661  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 14:21:08.661  1014  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 14:21:08.661  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-29 14:21:08.661  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-29 14:21:08.661  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:21:08.661  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
08-29 14:21:08.661  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-29 14:21:08.671  1430  1430 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2bde2a4f, true
,08-29 14:21:08.671  1170  1170 D BluetoothTile:  onBluetoothStateChange:
,08-29 14:21:08.671  1170  1170 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 14:21:08.671  1170  1768 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 14:21:08.671  1170  1170 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:08.671  1170  1170 D BluetoothTile:  getBluetoothState : 12,
08-29 14:21:08.671  1430  1430 D BluetoothHeadset: registerMessageListener
08-29 14:21:08.671  1170  1768 D BluetoothTile:  handleUpdatestate:false name:null
08-29 14:21:08.671  1868  1868 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
08-29 14:21:08.671  4739  4739 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:21:08.681  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:08.681  3235  3244 D HeadsetService: registerMessageListener
,08-29 14:21:08.681  3235  3244 D HeadsetService: registerMessageListener
08-29 14:21:08.681  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:08.681  1014  1487 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-29 14:21:08.681  4739  4739 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-29 14:21:08.681  4739  4739 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-29 14:21:08.681  4739  4739 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-29 14:21:08.681  4739  4739 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-29 14:21:08.681  3235  7746 D HeadsetStateMachine: Disconnected process message: 70
08-29 14:21:08.681  3235  7746 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@abb0d2
,08-29 14:21:08.681  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-29 14:21:08.681  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-29 14:21:08.681  1014  1253 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-29 14:21:08.691  1170  1170 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 14:21:08.691  1170  1768 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 14:21:08.691  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-29 14:21:08.691  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-29 14:21:08.691  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-29 14:21:08.691  3235  7774 D BluetoothMapMasInstance: set MAP SDP message type : 1,
08-29 14:21:08.691  3235  7746 D HeadsetStateMachine: Disconnected process message: 9
08-29 14:21:08.691  3235  7746 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-29 14:21:08.701   282   282 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-29 14:21:08.701   282   282 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-29 14:21:08.701   282   282 V voice   : voice_set_parameters: exit with code(-2)
,08-29 14:21:08.701   282   282 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-29 14:21:08.701   282   282 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-29 14:21:08.701   282   282 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-29 14:21:08.701   282   282 V audio_hw_primary: adev_set_parameters: exit
08-29 14:21:08.701  3235  7746 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-29 14:21:08.701  3235  7774 D BluetoothSocket: bindListen(): myUserId = 0
08-29 14:21:08.701  4739  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 14:21:08.701  3235  7774 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 14:21:08.701  1014  1510 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 14:21:08.701  1014  1510 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 14:21:08.701  1014  1510 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:08.701  3235  7774 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-29 14:21:08.701  3235  7774 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 14:21:08.701  3235  7774 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 14:21:08.701  3235  7774 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d6675a3
,08-29 14:21:08.701  1014  1510 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 14:21:08.701  1014  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 14:21:08.701  3235  7774 D BluetoothSocket: channel: 5
,08-29 14:21:08.711  2635  2635 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 14:21:08.711  4739  4739 D DockEventReceiver: finishStartingService: stopping service
,08-29 14:21:08.721  4739  4739 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 14:21:08.721  1170  1170 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:08.721  1170  1170 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-29 14:21:08.731  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
,08-29 14:21:08.731  3235  3235 D BtConfig.SecureMode: isSecureModeOn:false
,08-29 14:21:08.731  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 14:21:08.731  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-29 14:21:08.731  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:08.731  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:08.731  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:08.741  1014  1253 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-29 14:21:08.741  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:08.741  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:08.741  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:08.741  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-29 14:21:08.751  1014  1253 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7777 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-29 14:21:08.751  7777  7777 E Zygote  : MountEmulatedStorage()
08-29 14:21:08.751  7777  7777 E Zygote  : v2
08-29 14:21:08.751  7777  7777 I libpersona: KNOX_SDCARD checking this for 10105
08-29 14:21:08.751  7777  7777 I libpersona: KNOX_SDCARD not a persona
,08-29 14:21:08.761  7777  7777 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 14:21:08.761  1014  1253 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-29 14:21:08.761  7777  7777 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-29 14:21:08.761  7777  7777 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 14:21:08.771  3235  7785 D BluetoothSocket: bindListen(): myUserId = 0
08-29 14:21:08.771  3235  7785 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 14:21:08.771  3235  7785 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
08-29 14:21:08.771  3235  7785 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 14:21:08.771  3235  7785 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 14:21:08.771  3235  7785 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3a60c8ff
,08-29 14:21:08.781  3235  7785 D BluetoothSocket: channel: 12
08-29 14:21:08.781  3235  7785 I BtOppRfcommListener: Accept thread started.
,08-29 14:21:08.791  7777  7777 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 14:21:08.791  7777  7777 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:08.871   287   287 E SMD     : DCD OFF
,08-29 14:21:08.881   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 14:21:08.921   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-29 14:21:08.921   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 14:21:08.921  7777  7797 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-29 14:21:08.921   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-29 14:21:08.921   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 14:21:08.931  7777  7797 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-29 14:21:09.071  7777  7777 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-29 14:21:09.071  7777  7777 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 14:21:09.071  7777  7777 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 14:21:09.071  7777  7777 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.q.e.b(PG:170)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08,-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 14:21:09.071  7777  7777 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.q.k.d(PG:583)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.q.e.b(PG:170)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 14:21:09.071  7777  7777 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 14:21:09.071  7777  7777 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 14:21:09.071  7777  7777 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 14:21:09.071  7777  7777 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 14:21:09.081  1014  1486 I ActivityManager: Killing 6928:com.sec.pcw.device/1000 (adj 15): empty #21
,08-29 14:21:09.121  7777  7808 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-29 14:21:09.151  1014  1208 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-29 14:21:09.151  1014  1208 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:09.151  1014  1208 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:21:09.151  1014  1208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-29 14:21:09.871  1014  1486 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 14:21:09.871  1014  1486 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4290, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-29 14:21:09.871  1014  1486 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 14:21:09.871  1014  1486 D BatteryService: stay LED for charging
,08-29 14:21:09.871  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 14:21:09.871  1014  1014 I MotionRecognitionService: Plugged
,08-29 14:21:09.881  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 14:21:09.881   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 14:21:09.881  1170  1170 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 14:21:09.881  1170  1170 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 14:21:09.881  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 14:21:09.881  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 14:21:09.891  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-29 14:21:09.891  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-29 14:21:09.891  3235  3235 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 14:21:09.891  3235  7746 D HeadsetStateMachine: Disconnected process message: 10
,08-29 14:21:09.901  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-29 14:21:10.891   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 14:21:11.341  7083  7251 D BluetoothAdapter: disable()
,08-29 14:21:11.341  1014  1026 D SettingsProvider: name = bluetooth_on
,08-29 14:21:11.361  3235  3311 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-29 14:21:11.361  3235  3311 D BluetoothAdapterProperties: Setting state to 13
,08-29 14:21:11.361  3235  3311 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 14:21:11.361  1014  1482 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 14:21:11.361  3235  3311 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 14:21:11.361  1014  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-29 14:21:11.361  3235  3311 D BluetoothAdapterService: updateAdapterState state is 13
08-29 14:21:11.361  1014  1482 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:11.361  1014  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:11.361  1014  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 14:21:11.361  3235  3235 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-29 14:21:11.361  3235  3311 D BluetoothAdapterService: Autoconnection is available 
08-29 14:21:11.361  3235  3311 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-29 14:21:11.361  3235  3311 D BluetoothAdapterService: terminating service from this receiver
,08-29 14:21:11.371  3235  3235 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@cad76cc, channel: 19, state: LISTENING
08-29 14:21:11.371  3235  3235 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@cad76cc, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f472f5d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2dd5ed15mSocket: android.net.LocalSocket@2590882a impl:android.net.LocalSocketImpl@282f61b fd:FileDescriptor[80]
08-29 14:21:11.371  3235  3235 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2590882a impl:android.net.LocalSocketImpl@282f61b fd:FileDescriptor[80]
,08-29 14:21:11.371  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:11.371  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,08-29 14:21:11.371  1170  1170 D BluetoothTile:  onBluetoothStateChange:
,08-29 14:21:11.371  1170  1170 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 14:21:11.371  1170  1170 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:11.371  1170  1170 D BluetoothTile:  getBluetoothState : 13
,08-29 14:21:11.381  1170  1768 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 14:21:11.381  4739  4739 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:21:11.381  1868  1868 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 14:21:11.381  1014  1510 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 14:21:11.381  1014  1336 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 14:21:11.381  1170  1170 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 14:21:11.391  1170  1170 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-29 14:21:11.391  1170  1768 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 14:21:11.391  1170  1768 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-29 14:21:11.391  7083  7083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:21:11.391  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:11.391  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:11.391  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:11.391  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:11.391  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:11.391  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:11.391  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:11.391  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:11.391  1014  1253 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-29 14:21:11.391  1014  1253 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:11.391  1014  1253 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:11.391  1014  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:11.401  3235  3311 D BluetoothAdapterProperties: onBluetoothDisable(),
,08-29 14:21:11.401  3235  3311 D BluetoothAdapterProperties: mDiscovering is false
08-29 14:21:11.401  1014  1485 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-29 14:21:11.401  7083  7083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:11.401  7083  7083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:21:11.401  3235  3311 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-29 14:21:11.411  3235  3317 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-29 14:21:11.411  7083  7083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:21:11.411  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:11.411  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:11.411  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:11.411  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:11.411  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:21:11.411  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:11.411  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:11.411  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:11.411  7083  7083 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:21:11.411  7083  7083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:21:11.411  3235  3317 D BluetoothAdapterProperties: Scan Mode:20
,08-29 14:21:11.411  3235  3235 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2ca133b8, channel: 5, state: LISTENING
,08-29 14:21:11.411  3235  3235 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2ca133b8, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d6675a3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@16b54591mSocket: android.net.LocalSocket@586fcf6 impl:android.net.LocalSocketImpl@17d0d8f7 fd:FileDescriptor[82]
08-29 14:21:11.411  3235  3235 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@586fcf6 impl:android.net.LocalSocketImpl@17d0d8f7 fd:FileDescriptor[82]
,08-29 14:21:11.411  3235  3235 I BtOppRfcommListener: stopping Accept Thread
08-29 14:21:11.411  3235  3235 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@c11d364, channel: 12, state: LISTENING
08-29 14:21:11.411  3235  3235 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@c11d364, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3a60c8ff, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3557a9cdmSocket: android.net.LocalSocket@d9df282 impl:android.net.LocalSocketImpl@3eb00d93 fd:FileDescriptor[86]
08-29 14:21:11.411  3235  3235 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@d9df282 impl:android.net.LocalSocketImpl@3eb00d93 fd:FileDescriptor[86]
,08-29 14:21:11.411  3235  7785 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 14:21:11.411  3235  7785 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-29 14:21:11.411  4739  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 14:21:11.411  3235  3311 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-29 14:21:11.411  3235  3311 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-29 14:21:11.411  3235  3311 E bt-btif : btif_dm_generic_evt: even
,08-29 14:21:11.411  3235  3319 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
08-29 14:21:11.411  3235  3311 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-29 14:21:11.421  1014  1482 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 14:21:11.421  1014  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 14:21:11.421  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:11.421  1014  1482 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:11.421  1014  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 14:21:11.421  1014  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 14:21:11.421  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:11.421  4739  4739 D BluetoothPbap: Proxy object disconnected
,08-29 14:21:11.421  4739  4739 D PbapServerProfile: Bluetooth service disconnected
,08-29 14:21:11.421  3235  3235 V BluetoothOppManager: cleanUp...
,08-29 14:21:11.431  3235  3319 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 14:21:11.431  3235  3319 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 14:21:11.431  3235  3319 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 14:21:11.431  3235  3319 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 14:21:11.431  3235  3319 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 14:21:11.431  3235  3319 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-29 14:21:11.431  2635  2635 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 14:21:11.441  4739  4739 D DockEventReceiver: finishStartingService: stopping service
,08-29 14:21:11.441  4739  4739 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 14:21:11.441  1170  1170 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:21:11.441  1170  1170 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-29 14:21:11.621  3235  3311 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-29 14:21:11.621  3235  3311 D BtConfig.SecureMode: isSecureModeOn:false
08-29 14:21:11.621  3235  3311 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-29 14:21:11.621  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-29 14:21:11.621  3235  3311 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-29 14:21:11.621  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-29 14:21:11.621  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 14:21:11.621  1014  1253 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 14:21:11.621  3235  3311 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-29 14:21:11.621  1014  1253 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-29 14:21:11.621  1014  1253 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:11.621  1014  1253 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:11.621  1014  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:11.621  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-29 14:21:11.621  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-29 14:21:11.621  3235  3311 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-29 14:21:11.621  1014  1510 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 14:21:11.621  1014  1510 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-29 14:21:11.621  1014  1510 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:11.621  1014  1510 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:11.621  1014  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:11.621  3235  3235 D HeadsetService: Received stop request...Stopping profile...
08-29 14:21:11.621  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,08-29 14:21:11.621  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 14:21:11.621  3235  3311 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-29 14:21:11.631  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
,08-29 14:21:11.631  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-29 14:21:11.631  4739  4739 D HeadsetProfile: Bluetooth service disconnected
,08-29 14:21:11.631  1014  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 14:21:11.631  1014  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 14:21:11.631  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:11.631  1014  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:11.631  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:11.631  3235  3235 D A2dpService: Received stop request...Stopping profile...
08-29 14:21:11.631  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-29 14:21:11.631  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-29 14:21:11.631  3235  3311 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-29 14:21:11.631  3235  7755 D A2dpStateMachine: Exit Disconnected: -1
08-29 14:21:11.631  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 14:21:11.631  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-29 14:21:11.641  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:11.641  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:11.641  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 14:21:11.641  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-29 14:21:11.641  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 14:21:11.641  3235  3311 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-29 14:21:11.641  1014  1510 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 14:21:11.641  1014  1510 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 14:21:11.641  1014  1510 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:11.641  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
08-29 14:21:11.641  1014  1510 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:11.641  1014  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:11.641  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-29 14:21:11.641  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 14:21:11.641  3235  3311 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-29 14:21:11.641  1014  1208 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 14:21:11.641  1014  1208 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 14:21:11.641  4739  4739 D BluetoothA2dp: Proxy object disconnected
08-29 14:21:11.641  1014  1208 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:11.641  1014  1208 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:11.641  1014  1208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:11.641  1014  1014 D BluetoothA2dp: Proxy object disconnected
08-29 14:21:11.641  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-29 14:21:11.641  4739  4739 D A2dpProfile: Bluetooth service disconnected
,08-29 14:21:11.641  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 14:21:11.641  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-29 14:21:11.641  3235  3311 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-29 14:21:11.641  1014  1336 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 14:21:11.641  1014  1336 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 14:21:11.651  1014  1336 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:11.651  1014  1336 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:11.651  1014  1336 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:11.651  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 14:21:11.651  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 14:21:11.651  3235  3311 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 14:21:11.651  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-29 14:21:11.651  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 14:21:11.651  3235  3311 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-29 14:21:11.651  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-29 14:21:11.651  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 14:21:11.651  3235  3311 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-29 14:21:11.651  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
,08-29 14:21:11.651  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 14:21:11.651  3235  3311 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-29 14:21:11.651  3235  3311 D BluetoothAdapterState: Stopping profile services that were post enabled
08-29 14:21:11.651  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-29 14:21:11.651  3235  3235 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService,
08-29 14:21:11.651  3235  3235 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-29 14:21:11.651  3235  3235 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-29 14:21:11.661  3235  3235 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-29 14:21:11.661  3235  3235 D HidService: Received stop request...Stopping profile...
,08-29 14:21:11.661  3235  3235 D HidService: Stopping Bluetooth HidService
08-29 14:21:11.661  3235  3235 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 14:21:11.661  3235  3235 W bt-btif : cleanup: HH disabling or disabled already, status = 0
,08-29 14:21:11.661  3235  3235 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-29 14:21:11.661  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
,08-29 14:21:11.661  3235  3235 D HealthService: Received stop request...Stopping profile...
,08-29 14:21:11.661  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
08-29 14:21:11.661  4739  4739 D BluetoothInputDevice: Proxy object disconnected
08-29 14:21:11.661  4739  4739 D HidProfile: Bluetooth service disconnected
,08-29 14:21:11.661  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-29 14:21:11.661  3235  3235 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-29 14:21:11.661  3235  3235 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-29 14:21:11.661  3235  3235 D PanService: Received stop request...Stopping profile...
08-29 14:21:11.661  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
,08-29 14:21:11.671  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 14:21:11.671  3235  3235 D BluetoothA2dp: Proxy object disconnected
,08-29 14:21:11.671  3235  3235 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-29 14:21:11.671  3235  7757 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 14:21:11.671  3235  3235 I GKI_LINUX: GKI_exit_task 2 done
08-29 14:21:11.671  3235  3235 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-29 14:21:11.671  4739  4739 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 14:21:11.671  4739  4739 D PanProfile: Bluetooth service disconnected
08-29 14:21:11.671  3235  3235 D BluetoothMapService: Received stop request...Stopping profile...
,08-29 14:21:11.671  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
,08-29 14:21:11.671  3235  3235 D SapService: Received stop request...Stopping profile...
,08-29 14:21:11.671  3235  3235 D SapService: Stopping Bluetooth SapService
08-29 14:21:11.671  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
,08-29 14:21:11.671  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-29 14:21:11.671  3235  3235 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 14:21:11.671  3235  3235 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 14:21:11.671  3235  3235 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 14:21:11.671  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-29 14:21:11.671  3235  3235 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 14:21:11.671  3235  3235 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 14:21:11.671  3235  3235 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 14:21:11.671  3235  3235 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-29 14:21:11.671  4739  4739 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-29 14:21:11.681  4739  4739 D SapProfile: Bluetooth service disconnected
08-29 14:21:11.681  3235  3235 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 14:21:11.681  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
,08-29 14:21:11.681  3235  3235 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 14:21:11.681  4739  4739 D BluetoothMap: Proxy object disconnected
08-29 14:21:11.681  4739  4739 D MapProfile: Bluetooth service disconnected
08-29 14:21:11.681  3235  3235 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 14:21:11.681  3235  3235 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-29 14:21:11.681  3235  3235 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 14:21:11.681  3235  3235 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 14:21:11.681  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-29 14:21:11.681  3235  3235 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 14:21:11.681  3235  3235 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 14:21:11.681  3235  3235 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-29 14:21:11.681  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-29 14:21:11.681  3235  3235 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 14:21:11.681  3235  3235 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-29 14:21:11.681  3235  3235 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-29 14:21:11.681  3235  3311 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-29 14:21:11.681  3235  3311 D BluetoothAdapterProperties: Setting state to 10
08-29 14:21:11.681  3235  3311 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 14:21:11.681  3235  3311 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 14:21:11.681  3235  3311 D BluetoothAdapterService: updateAdapterState state is 10
,08-29 14:21:11.681  3235  3311 D BluetoothAdapterService: Autoconnection is available 
08-29 14:21:11.681  3235  3311 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-29 14:21:11.681  3235  3311 I BluetoothAdapterState: Entering OffState
08-29 14:21:11.681  4739  4747 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 14:21:11.681  2635  2677 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 14:21:11.681  2635  2677 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 14:21:11.681  4739  7722 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 14:21:11.681  1440  1459 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 14:21:11.691  1440  1459 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 14:21:11.691  4739  4746 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 14:21:11.691  3235  3244 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 14:21:11.691  3235  3244 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 14:21:11.691  1170  1188 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 14:21:11.691  1170  1188 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 14:21:11.691  1729  1748 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 14:21:11.691  1729  1748 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 14:21:11.691  4739  4747 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 14:21:11.691  4739  7722 D Bluetoothsap: onBluetoothStateChange: up=false
,08-29 14:21:11.691  4739  7722 D Bluetoothsap: Unbinding service...
,08-29 14:21:11.691  1456  1483 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 14:21:11.691  1456  1483 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 14:21:11.701  7083  7093 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 14:21:11.701  7083  7093 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 14:21:11.701  7083  7093 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-29 14:21:11.701  7083  7093 D BluetoothLeAdvertiser: Exit stop advertising
,08-29 14:21:11.701  7083  7093 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-29 14:21:11.701  7083  7093 D BluetoothLeScanner: Exiting stopAllScan
,08-29 14:21:11.701  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 14:21:11.701  1430  7816 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 14:21:11.701  1430  7816 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 14:21:11.701  7777  7788 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 14:21:11.701  7777  7788 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 14:21:11.701  3235  3248 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 14:21:11.701  4739  7289 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 14:21:11.701  4739  7289 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 14:21:11.701  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 14:21:11.701  1014  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 14:21:11.711  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:21:11.711  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
08-29 14:21:11.711  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-29 14:21:11.711  1170  1170 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-29 14:21:11.711  1170  1170 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:11.711  1170  1170 D BluetoothTile:  getBluetoothState : 10
,08-29 14:21:11.711  1868  1868 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 14:21:11.711  1014  1487 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 14:21:11.711  4739  4739 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:21:11.711  1014  1484 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 14:21:11.711  1170  1170 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 14:21:11.721  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:11.721  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:11.721  4739  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 14:21:11.721  1014  1482 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-29 14:21:11.721  1014  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 14:21:11.721  1014  1482 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:11.721  1014  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:11.721  1014  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 14:21:11.731  2635  2635 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 14:21:11.731  4739  4739 D DockEventReceiver: finishStartingService: stopping service
,08-29 14:21:11.731  4739  4739 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 14:21:11.741  1170  1170 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:21:11.741  1170  1170 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-29 14:21:11.871   287   287 E SMD     : DCD OFF
,08-29 14:21:11.881   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 14:21:12.881  1014  1094 V AlarmManager: waitForAlarm result :4
,08-29 14:21:12.881   317   317 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 14:21:12.891   277  1006 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 14:21:12.891   277  1006 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-29 14:21:12.911  1014  1040 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:12.911  1014  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:21:12.911  1014  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-29 14:21:14.371  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 14:21:14.371  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:14.881   287   287 E SMD     : DCD OFF
,08-29 14:21:16.741  1014  3374 D SSRM:n  : SIOP:: AP = 350,
,08-29 14:21:17.371  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 14:21:17.371  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e7e815e added. We now have 6 listener(s)
,08-29 14:21:17.371  7083  7251 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:17.371  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:17.371  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13fbe93f added. We now have 7 listener(s)
,08-29 14:21:17.371  7083  7251 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:17.371  7083  7251 I System.out: IsBluetoothEnabled
08-29 14:21:17.371  7083  7251 D BluetoothAdapter: disable()
,08-29 14:21:17.371  1014  1487 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.,
,08-29 14:21:17.381  7083  7251 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:17.381  7083  7251 D BluetoothAdapter: enable()
,08-29 14:21:17.381  1014  1336 W ActivityManager: Permission Denial: getCurrentUser() from pid=7083, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-29 14:21:17.381  1014  1336 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-29 14:21:17.381  1014  1336 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7083, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-29 14:21:17.381  1014  1336 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 14:21:17.381  1014  1336 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-29 14:21:17.381  1014  1336 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-29 14:21:17.381  1014  1336 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-29 14:21:17.381  1014  1336 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 14:21:17.381  1014  1336 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-29 14:21:17.381  1014  1336 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 14:21:17.381  1014  1336 D SettingsProvider: name = bluetooth_on
,08-29 14:21:17.391  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-29 14:21:17.391  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 14:21:17.401  1014  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-29 14:21:17.401  3235  3311 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-29 14:21:17.401  3235  3311 D BluetoothAdapterProperties: Setting state to 11
08-29 14:21:17.401  3235  3311 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-29 14:21:17.401  3235  3311 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 14:21:17.401  3235  3311 D BluetoothAdapterService: updateAdapterState state is 11
,08-29 14:21:17.401  3235  3311 D BluetoothAdapterService: Autoconnection is available 
,08-29 14:21:17.401  3235  3311 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-29 14:21:17.401  3235  3311 D BtConfig.SecureMode: isSecureModeOn:false
08-29 14:21:17.401  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-29 14:21:17.401  3235  3311 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-29 14:21:17.401  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 14:21:17.401  3235  3311 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
,08-29 14:21:17.401  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-29 14:21:17.401  3235  3311 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-29 14:21:17.401  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-29 14:21:17.411  3235  3311 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-29 14:21:17.411  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-29 14:21:17.411  3235  3311 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-29 14:21:17.411  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 14:21:17.411  3235  3311 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
,08-29 14:21:17.411  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 14:21:17.411  3235  3311 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-29 14:21:17.411  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 14:21:17.411  3235  3311 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-29 14:21:17.411  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 14:21:17.411  3235  3311 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 14:21:17.411  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-29 14:21:17.411  3235  3311 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-29 14:21:17.411  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 14:21:17.411  3235  3311 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService,
08-29 14:21:17.411  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 14:21:17.411  3235  3311 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-29 14:21:17.411  3235  3311 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-29 14:21:17.411  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-29 14:21:17.411  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 14:21:17.411  3235  3311 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-29 14:21:17.411  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
08-29 14:21:17.411  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
08-29 14:21:17.411  1170  1170 D BluetoothTile:  onBluetoothPairedDevicesChanged:,
08-29 14:21:17.421  1170  1170 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:21:17.421  1170  1170 D BluetoothTile:  getBluetoothState : 11
,08-29 14:21:17.421  1868  1868 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 14:21:17.421  4739  4739 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:21:17.431  1014  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 14:21:17.431  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-29 14:21:17.431  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:17.431  1014  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:17.431  1014  1026 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-29 14:21:17.431  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:17.431  1014  1487 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 14:21:17.431  1170  1170 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 14:21:17.431  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-29 14:21:17.431  1170  1768 D BluetoothTile:  handleUpdatestate:false name:null
08-29 14:21:17.431  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-29 14:21:17.431  1170  1768 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-29 14:21:17.431  3235  3311 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-29 14:21:17.441  2635  2635 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 14:21:17.441  3235  3235 D HeadsetService: Received start request. Starting profile...
08-29 14:21:17.441  3235  3235 D HeadsetService: start()
08-29 14:21:17.441  3235  3235 D HeadsetStateMachine: make
,08-29 14:21:17.441  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:17.441  1014  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 14:21:17.441  3235  3235 E HeadsetStateMachine: # of Max HF connection is 2
08-29 14:21:17.441  1014  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 14:21:17.441  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:17.441  1014  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:17.441  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:17.441  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-29 14:21:17.441  1014  3867 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 14:21:17.441  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 14:21:17.441  1014  3867 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-29 14:21:17.441  3235  3311 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-29 14:21:17.441  1014  3867 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:17.441  1014  3867 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:17.441  1014  3867 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:17.451  1014  1510 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-29 14:21:17.451  1014  1510 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-29 14:21:17.451  1014  1510 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:17.451  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-29 14:21:17.451  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-29 14:21:17.451  1014  1510 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:17.451  3235  3311 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-29 14:21:17.451  1014  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-29 14:21:17.451  1014  1484 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 14:21:17.451  1014  1484 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-29 14:21:17.451  1014  1484 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:17.451  1014  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:17.451  1014  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:17.451  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-29 14:21:17.451  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 14:21:17.451  3235  3311 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-29 14:21:17.461  4739  4739 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 14:21:17.461  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 14:21:17.461  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 14:21:17.461  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:17.461  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:17.461  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:17.461  1014  1208 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-29 14:21:17.461  1014  1208 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-29 14:21:17.461  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-29 14:21:17.461  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 14:21:17.461  3235  3311 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-29 14:21:17.461  1014  1208 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:17.461  1014  1208 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:17.461  1014  1208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-29 14:21:17.461  3235  3235 I bluedroid: get_profile_interface handsfree
,08-29 14:21:17.471  1170  1170 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:21:17.471  1170  1170 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-29 14:21:17.471  1014  1253 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 14:21:17.471  1014  1253 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 14:21:17.471  1014  1253 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:17.471  1014  1253 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 14:21:17.471  1014  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:17.481  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-29 14:21:17.481  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 14:21:17.481  3235  3311 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-29 14:21:17.491  1014  3867 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 14:21:17.491  1014  3867 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 14:21:17.491  1014  3867 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:17.491  1014  3867 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 14:21:17.491  1014  3867 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:17.491  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 14:21:17.491  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 14:21:17.491  3235  3311 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 14:21:17.491  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-29 14:21:17.491  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 14:21:17.491  3235  3311 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-29 14:21:17.491  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-29 14:21:17.491  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 14:21:17.491  3235  3311 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-29 14:21:17.491  3235  3311 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-29 14:21:17.491  3235  3311 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 14:21:17.491  3235  3311 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-29 14:21:17.491  3235  3311 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-29 14:21:17.491  3235  3235 E DualScoManager: Dual Sco Manager already instantiated
08-29 14:21:17.491  3235  3235 I DualScoManager: Set HeadsetServiceHelper
08-29 14:21:17.491  3235  3235 D BluetoothAtMessage: createCMTIContentObservers
,08-29 14:21:17.501  1014  1486 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-29 14:21:17.501  1014  1486 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 14:21:17.501  1014  1486 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 14:21:17.501  1014  1486 D SettingsProvider: selectionArgs: false
08-29 14:21:17.501  1014  1486 D SettingsProvider: selectionArgs: 1002
08-29 14:21:17.501  1014  1486 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 14:21:17.501  1014  1486 D SettingsProvider: ret = -1
,08-29 14:21:17.501  3235  7826 D HeadsetStateMachine: Enter Disconnected: -2
,08-29 14:21:17.501  3235  3235 D HeadsetService: mStartError = false
,08-29 14:21:17.501  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
,08-29 14:21:17.501  3235  3235 D A2dpService: Received start request. Starting profile...
,08-29 14:21:17.501  3235  3235 D A2dpService: start()
08-29 14:21:17.501  3235  3235 I bluedroid: get_profile_interface avrcp
,08-29 14:21:17.511  3235  3235 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 14:21:17.511  3235  3235 D Avrcp   : Initialize Media Controller
08-29 14:21:17.511  3235  3235 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-29 14:21:17.511  3235  3235 E Avrcp   : getActiveSessions
,08-29 14:21:17.511  3235  3235 D Avrcp   : pick active media Controller
08-29 14:21:17.511  3235  3235 D Avrcp   : Get the active Media Controller 
,08-29 14:21:17.511  3235  7826 D HeadsetStateMachine: Clear mHeadsetBrsf
08-29 14:21:17.511  3235  7826 D HeadsetStateMachine: map size, before remove : 0
08-29 14:21:17.511  3235  7826 D HeadsetStateMachine: map size, after remove: 0
,08-29 14:21:17.511  3235  3235 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-29 14:21:17.521  3235  7827 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-29 14:21:17.521  3235  3235 D A2dpStateMachine: make
,08-29 14:21:17.521  3235  3235 I bluedroid: get_profile_interface a2dp
,08-29 14:21:17.521  3235  7829 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-29 14:21:17.521  3235  3235 E bt-btif : warning : media task started media_task_refcnt 1 
,08-29 14:21:17.521  3235  3235 D A2dpService: mStartError = false
08-29 14:21:17.521  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
08-29 14:21:17.521  3235  3235 D HidService: Received start request. Starting profile...
08-29 14:21:17.521  3235  3235 D HidService: start()
08-29 14:21:17.521  3235  3235 I bluedroid: get_profile_interface hidhost
08-29 14:21:17.521  3235  3235 D HidService: setHidService(): set to: null
08-29 14:21:17.521  3235  3235 D HidService: mStartError = false
08-29 14:21:17.521  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
08-29 14:21:17.521  3235  3235 D HeadsetStateMachine: Try to query the phonestate on bind
,08-29 14:21:17.521  3235  7828 D A2dpStateMachine: Enter Disconnected: -2
08-29 14:21:17.521  1430  1450 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 14:21:17.521  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-29 14:21:17.521  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-29 14:21:17.521  1430  1450 I Telecom : BluetoothPhoneService: Result of Message : true
,08-29 14:21:17.531  3235  3235 D HealthService: Received start request. Starting profile...
08-29 14:21:17.531  3235  3235 D HealthService: start()
,08-29 14:21:17.531  3235  3235 I bluedroid: get_profile_interface health
08-29 14:21:17.531  3235  3235 D HealthService: mStartError = false
08-29 14:21:17.531  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
,08-29 14:21:17.531  3235  3235 D HeadsetStateMachine: Proxy object connected
08-29 14:21:17.531  3235  3235 D PanService: Received start request. Starting profile...
08-29 14:21:17.531  3235  3235 D PanService: start()
08-29 14:21:17.531  3235  3235 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 14:21:17.531  3235  3235 I bluedroid: get_profile_interface pan
08-29 14:21:17.531  3235  3235 D PanService: mStartError = false
08-29 14:21:17.531  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
08-29 14:21:17.531  3235  3235 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-29 14:21:17.531  3235  7826 D HeadsetStateMachine: Disconnected process message: 11
,08-29 14:21:17.531  3235  3235 D BluetoothMapService: Received start request. Starting profile...
08-29 14:21:17.531  3235  3235 D BluetoothMapService: start()
,08-29 14:21:17.531  3235  7827 D BluetoothMediaBrowser: no now playing list
08-29 14:21:17.531  3235  7827 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-29 14:21:17.531  3235  3235 D BluetoothMapService: mStartError = false
,08-29 14:21:17.531  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
08-29 14:21:17.531  3235  3235 D HeadsetPhoneState: sendDeviceDataStateChanged
08-29 14:21:17.531  3235  3235 D HeadsetPhoneState: Signal level : previous=0 curr=4
,08-29 14:21:17.531  3235  7826 D HeadsetStateMachine: Disconnected process message: 18
08-29 14:21:17.531  3235  3235 D SapService: Received start request. Starting profile...
08-29 14:21:17.531  3235  3235 D SapService: start()
08-29 14:21:17.531  3235  3235 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-29 14:21:17.531  3235  3235 I bluedroid: get_profile_interface sap
08-29 14:21:17.531  3235  3235 D SapService: mStartError = false
08-29 14:21:17.531  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
08-29 14:21:17.531  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-29 14:21:17.531  3235  3235 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-29 14:21:17.531  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-29 14:21:17.531  3235  7826 D HeadsetStateMachine: Disconnected process message: 10
08-29 14:21:17.531  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-29 14:21:17.531  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-29 14:21:17.531  3235  7826 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 14:21:17.531  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
08-29 14:21:17.531  3235  7826 D HeadsetStateMachine: Disconnected process message: 11
,08-29 14:21:17.551  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-29 14:21:17.551  3235  3235 E BluetoothAdapterService(738273848): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-29 14:21:17.551  3235  3311 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-29 14:21:17.551  3235  3311 I bluedroid: enable
,08-29 14:21:17.561  3235  3317 E bt-btif : Calling BTA_HhEnable
08-29 14:21:17.561  3235  3317 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-29 14:21:17.561  3235  3317 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-29 14:21:17.561  3235  3317 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
08-29 14:21:17.561  3235  3317 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-29 14:21:17.561  3235  3317 E BluetoothServiceJni: populateRssiValuesNative
08-29 14:21:17.561  3235  3317 I bluedroid: getModelRssiValues
08-29 14:21:17.561  3235  3317 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-29 14:21:17.561  3235  3317 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
08-29 14:21:17.561  3235  3317 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-29 14:21:17.561  1014  1014 D SettingsProvider: name = bluetooth_name
,08-29 14:21:17.561  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:17.571  3235  3317 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-29 14:21:17.571  3235  3317 D BluetoothAdapterProperties: Scan Mode:20
08-29 14:21:17.571  3235  3317 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 14:21:17.571  3235  3317 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-29 14:21:17.571  3235  3317 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-29 14:21:17.571  3235  3317 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
08-29 14:21:17.571  3235  3317 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-29 14:21:17.571  3235  3317 E bt-btif : JVenable fails
,08-29 14:21:17.571  3235  3317 D bte_conf: Device ID record 1 : primary
08-29 14:21:17.571  3235  3317 D bte_conf:   vendorId            = 0075
08-29 14:21:17.571  3235  3317 D bte_conf:   vendorIdSource      = 0001
08-29 14:21:17.571  3235  3317 D bte_conf:   product             = 0100
08-29 14:21:17.571  3235  3317 D bte_conf:   version             = 0200
08-29 14:21:17.571  3235  3317 D bte_conf:   clientExecutableURL = 
08-29 14:21:17.571  3235  3317 D bte_conf:   serviceDescription  = 
08-29 14:21:17.571  3235  3317 D bte_conf:   documentationURL    = 
08-29 14:21:17.571  3235  3317 D bte_conf: bte_load_did_conf no section named DID2.
08-29 14:21:17.571  3235  3317 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-29 14:21:17.571  3235  3317 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 14:21:17.571  3235  3311 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-29 14:21:17.571  3235  3311 D BluetoothAdapterProperties: ScanMode =  20
08-29 14:21:17.571  3235  3311 D BluetoothAdapterProperties: State =  11
,08-29 14:21:17.571  1014  1487 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-29 14:21:17.571  3235  3311 D BluetoothAdapterProperties: Setting state to 12
,08-29 14:21:17.571  3235  3311 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 14:21:17.571  3235  3317 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
,08-29 14:21:17.571  3235  3317 D BluetoothAdapterProperties: Scan Mode:21
08-29 14:21:17.571  3235  3317 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 14:21:17.571  1014  1027 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-29 14:21:17.571  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-29 14:21:17.571  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 14:21:17.571  1014  1027 D SettingsProvider: selectionArgs: false
08-29 14:21:17.571  1014  1027 D SettingsProvider: selectionArgs: 1002,
08-29 14:21:17.571  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 14:21:17.571  1014  1027 D SettingsProvider: ret = -1
08-29 14:21:17.571  3235  3311 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-29 14:21:17.571  3235  3311 D BluetoothAdapterService: updateAdapterState state is 12,
08-29 14:21:17.581  1014  3867 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 14:21:17.581  1014  3867 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-29 14:21:17.581  1014  3867 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:17.581  1014  3867 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:17.581  1014  3867 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:17.581  3235  3311 D BluetoothAdapterService: Autoconnection is available ,
08-29 14:21:17.581  3235  3311 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-29 14:21:17.581  3235  3311 D BluetoothAdapterService: starting service from this receiver
08-29 14:21:17.581  4739  7722 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 14:21:17.581  1014  1510 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 14:21:17.581  1014  1510 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-29 14:21:17.581  4739  7722 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 14:21:17.591  1014  1510 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:17.591  1014  1510 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 14:21:17.591  1014  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:17.591  3235  3311 I BluetoothAdapterState: Entering On State from state = 11
,08-29 14:21:17.601  3235  3235 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-29 14:21:17.601  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:17.601  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:17.601  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:17.601  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:17.601  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:17.601  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:17.601  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:17.601  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:17.601  7083  7083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:21:17.731  1014  1044 I art     : Explicit concurrent mark sweep GC freed 49916(2MB) AllocSpace objects, 10(161KB) LOS objects, 33% free, 22MB/34MB, paused 2.342ms total 142.611ms,
08-29 14:21:17.731  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 14:21:17.731  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 14:21:17.731  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:17.731  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:17.731  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:17.741  2635  2643 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 14:21:17.741  2635  2643 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 14:21:17.741  4739  4746 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 14:21:17.741  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-29 14:21:17.741  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 14:21:17.741  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:17.741  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:17.741  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:17.741  3235  3235 I BluetoothPbapService: Handler(): got msg=1
,08-29 14:21:17.741  1440  1459 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 14:21:17.741  1440  1459 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 14:21:17.741  1014  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-29 14:21:17.741  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 14:21:17.741  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 14:21:17.741  1014  1044 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 14:21:17.751  1014  1486 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-29 14:21:17.751  1430  1450 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 14:21:17.751  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 14:21:17.751  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 14:21:17.751  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:17.751  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:17.751  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:17.751  1430  1450 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 14:21:17.751  1014  1044 D BluetoothPan: Binding service...
,08-29 14:21:17.751  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-29 14:21:17.751  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 14:21:17.751  4739  4739 D BluetoothA2dp: Proxy object connected
08-29 14:21:17.751  4739  4739 D A2dpProfile: Bluetooth service connected
,08-29 14:21:17.751  3235  7834 V BluetoothPbapService: PBAP Service initSocket try: 0
08-29 14:21:17.751  4739  7722 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 14:21:17.761  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-29 14:21:17.761  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 14:21:17.761  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:17.761  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:17.761  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-29 14:21:17.761  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 14:21:17.761  3235  3318 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 14:21:17.761  3235  3318 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 14:21:17.761  4739  4739 D BluetoothInputDevice: Proxy object connected
08-29 14:21:17.761  4739  4739 D HidProfile: Bluetooth service connected
,08-29 14:21:17.761  1430  1466 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 14:21:17.761  4739  4739 D BluetoothPbap: Proxy object connected
,08-29 14:21:17.761  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 14:21:17.761  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 14:21:17.761  4739  4739 D PbapServerProfile: Bluetooth service connected
08-29 14:21:17.761  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:17.761  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:17.761  3235  7834 D BluetoothSocket: bindListen(): myUserId = 0
08-29 14:21:17.761  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-29 14:21:17.761  3235  7834 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 14:21:17.761  1430  1466 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 14:21:17.761  1170  1612 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 14:21:17.761  1170  1612 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 14:21:17.761  1729  1748 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 14:21:17.761  3235  7834 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-29 14:21:17.761  3235  7834 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 14:21:17.761  3235  7834 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 14:21:17.761  3235  7834 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35980d48
,08-29 14:21:17.771  1729  1748 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 14:21:17.771  3235  7834 D BluetoothSocket: channel: 19
08-29 14:21:17.771  3235  7834 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-29 14:21:17.771  4739  7289 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0,
,08-29 14:21:17.771  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 14:21:17.771  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 14:21:17.771  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:17.771  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:17.771  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:17.771  4739  7289 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 14:21:17.771  4739  4739 D HeadsetProfile: Bluetooth service connected
,08-29 14:21:17.771  1430  1450 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 14:21:17.771  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset,
08-29 14:21:17.771  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 14:21:17.771  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:17.771  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:17.771  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-29 14:21:17.771  1430  1450 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 14:21:17.771  4739  4746 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 14:21:17.781  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-29 14:21:17.781  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 14:21:17.781  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:17.781  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 14:21:17.781  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:17.781  4739  4747 D Bluetoothsap: onBluetoothStateChange: up=true
,08-29 14:21:17.781  4739  4747 D Bluetoothsap: Binding service...
08-29 14:21:17.781  4739  4739 D BluetoothMap: Proxy object connected
08-29 14:21:17.781  4739  4739 D MapProfile: Bluetooth service connected
08-29 14:21:17.781  4739  4739 D BluetoothMap: getConnectedDevices()
,08-29 14:21:17.781  4739  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-29 14:21:17.781  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-29 14:21:17.781  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 14:21:17.781  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:17.781  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:17.781  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:17.781  4739  4747 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-29 14:21:17.781  1456  2488 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 14:21:17.791  1456  2488 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 14:21:17.791  4739  7722 D BluetoothPan: Binding service...
,08-29 14:21:17.791  4739  4739 D Bluetoothsap: BluetoothSAP Proxy object connected
08-29 14:21:17.791  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-29 14:21:17.791  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 14:21:17.791  4739  4739 D SapProfile: Bluetooth service connected
08-29 14:21:17.791  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:17.791  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:17.791  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:17.791  4739  4739 D Bluetoothsap: getConnectedDevices()
,08-29 14:21:17.791  7083  7242 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 14:21:17.791  7083  7242 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 14:21:17.791  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 14:21:17.791  1014  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-29 14:21:17.791  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 14:21:17.791  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0,
,08-29 14:21:17.791  1014  1014 D BluetoothA2dp: Proxy object connected
08-29 14:21:17.791  4739  4739 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 14:21:17.791  4739  4739 D PanProfile: Bluetooth service connected
08-29 14:21:17.791  1430  7816 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 14:21:17.791  1430  7816 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 14:21:17.791  7777  7789 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 14:21:17.791  7777  7789 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 14:21:17.801  1456  1476 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 14:21:17.801  1014  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 14:21:17.801  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 14:21:17.801  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:17.801  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:17.801  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
08-29 14:21:17.801  1456  1476 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 14:21:17.801  3235  7773 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 14:21:17.801  3235  7773 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 14:21:17.801  1014  1044 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-29 14:21:17.801  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 14:21:17.801  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:17.801  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:17.801  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:17.801  3235  3235 D BluetoothA2dp: Proxy object connected
,08-29 14:21:17.801  3235  3235 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-29 14:21:17.811  4739  4747 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 14:21:17.811  4739  4747 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 14:21:17.811  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 14:21:17.811  1014  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 14:21:17.811  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-29 14:21:17.811  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-29 14:21:17.811  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:21:17.811  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
08-29 14:21:17.811  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-29 14:21:17.811  1430  1430 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@269645dc, true
,08-29 14:21:17.811  1430  1430 D BluetoothHeadset: registerMessageListener
,08-29 14:21:17.821  1170  1170 D BluetoothTile:  onBluetoothStateChange:
,08-29 14:21:17.821  1170  1170 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 14:21:17.821  1170  1170 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:21:17.821  1170  1170 D BluetoothTile:  getBluetoothState : 12
,08-29 14:21:17.821  1868  1868 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 14:21:17.821  4739  4739 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:21:17.831  1170  1768 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 14:21:17.831  4739  4739 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-29 14:21:17.831  4739  4739 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-29 14:21:17.831  4739  4739 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-29 14:21:17.831  4739  4739 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-29 14:21:17.831  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:17.831  3235  3318 D HeadsetService: registerMessageListener
,08-29 14:21:17.831  3235  3318 D HeadsetService: registerMessageListener
08-29 14:21:17.831  3235  7826 D HeadsetStateMachine: Disconnected process message: 70
08-29 14:21:17.831  3235  7826 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3379c7e1
,08-29 14:21:17.831  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-29 14:21:17.831  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-29 14:21:17.831  1014  1027 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 14:21:17.831  1014  1510 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-29 14:21:17.831  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-29 14:21:17.831  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-29 14:21:17.831  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-29 14:21:17.841  3235  7835 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-29 14:21:17.841  1170  1170 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 14:21:17.841  1170  1768 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 14:21:17.841  3235  7826 D HeadsetStateMachine: Disconnected process message: 9
,08-29 14:21:17.841  3235  7826 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-29 14:21:17.841  3235  7835 D BluetoothSocket: bindListen(): myUserId = 0
08-29 14:21:17.841  3235  7835 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 14:21:17.841  1170  1768 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 14:21:17.841   282   682 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-29 14:21:17.841  3235  7835 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-29 14:21:17.841  3235  7835 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 14:21:17.841  3235  7835 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-29 14:21:17.841   282   682 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-29 14:21:17.841  3235  7835 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3ec6d906
08-29 14:21:17.841   282   682 V voice   : voice_set_parameters: exit with code(-2)
,08-29 14:21:17.851   282   682 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-29 14:21:17.851   282   682 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-29 14:21:17.851   282   682 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-29 14:21:17.851   282   682 V audio_hw_primary: adev_set_parameters: exit
08-29 14:21:17.851  3235  7835 D BluetoothSocket: channel: 5
08-29 14:21:17.851  3235  7826 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-29 14:21:17.851  4739  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 ,
08-29 14:21:17.851  1014  1484 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 14:21:17.851  1014  1484 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 14:21:17.851  1014  1484 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:17.851  1014  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 14:21:17.851  1014  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 14:21:17.851  2635  2635 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 14:21:17.861  4739  4739 D DockEventReceiver: finishStartingService: stopping service
,08-29 14:21:17.861  4739  4739 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 14:21:17.861  1170  1170 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:21:17.861  1170  1170 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-29 14:21:17.871  3235  3235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c012a38
,08-29 14:21:17.871  3235  3235 D BtConfig.SecureMode: isSecureModeOn:false
,08-29 14:21:17.871  1014  1482 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 14:21:17.871  1014  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-29 14:21:17.871  1014  1482 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:17.871  1014  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:17.871  1014  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 14:21:17.881   287   287 E SMD     : DCD OFF
,08-29 14:21:17.891  1014  1510 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-29 14:21:17.891  3235  7840 D BluetoothSocket: bindListen(): myUserId = 0
08-29 14:21:17.891  3235  7840 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 14:21:17.901  3235  7840 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[85]}
,08-29 14:21:17.901  3235  7840 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 14:21:17.901  3235  7840 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 14:21:17.901  3235  7840 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11677f92
08-29 14:21:17.901  3235  7840 D BluetoothSocket: channel: 12
08-29 14:21:17.901  3235  7840 I BtOppRfcommListener: Accept thread started.
,08-29 14:21:18.401  7083  7251 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:18.401  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:18.401  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:18.401  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:21:18.401  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:18.401  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:18.401  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:18.401  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:18.401  7083  7251 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:21:18.401  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 14:21:18.401  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@290db20c added. We now have 8 listener(s)
08-29 14:21:18.401  7083  7251 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:21:18.411  1014  1484 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 14:21:18.411  1014  1484 D WifiService: setWifiEnabled: false pid=7083, uid=10170
,08-29 14:21:18.411  1014  1484 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 14:21:18.411  1014  1484 D SecContentProvider2: mCursor = null
,08-29 14:21:18.411  1014  1484 D SettingsProvider: name = wifi_on
,08-29 14:21:18.421  7083  7251 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:18.421  1014  1027 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 14:21:18.421  1014  1027 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 14:21:18.421  1014  1027 D SecContentProvider2: mCursor = null
,08-29 14:21:18.421  1014  1027 D WifiService: setWifiEnabled: true pid=7083, uid=10170
,08-29 14:21:18.421  1014  1027 W ActivityManager: Permission Denial: getCurrentUser() from pid=7083, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-29 14:21:18.421  1014  1027 W WifiService: Failed getting userId using ActivityManagerNative
08-29 14:21:18.421  1014  1027 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7083, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-29 14:21:18.421  1014  1027 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 14:21:18.421  1014  1027 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-29 14:21:18.421  1014  1027 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-29 14:21:18.421  1014  1027 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-29 14:21:18.421  1014  1027 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-29 14:21:18.421  1014  1027 D SettingsProvider: name = wifi_on
,08-29 14:21:18.431  1014  1124 E WifiHW  : ##################### set firmware type 0 #####################
,08-29 14:21:18.771  1014  1042 D Tethering: interfaceAdded wlan0
,08-29 14:21:18.781  1014  1128 E Tethering: No numeric data
,08-29 14:21:18.781  1014  1121 V NetworkStats: performPollLocked(flags=0x1),
08-29 14:21:18.781  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit,
08-29 14:21:18.781  1170  1170 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 14:21:18.781  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 14:21:18.781  1170  1170 D HotspotTile: updateTetherState():false, false,
08-29 14:21:18.781  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 14:21:18.791  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 14:21:18.791  1014  1128 D Tethering: clearTetheredNotification()
,08-29 14:21:18.791  1014  1121 V NetworkStats: performPollLocked() took 7ms,
08-29 14:21:18.791  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 14:21:18.791  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 14:21:18.791  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-29 14:21:18.791  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 14:21:18.791  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:21:18.791  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 14:21:18.791  1014  1128 D Tethering: InitialState.processMessage what=4
,08-29 14:21:18.801  1014  1042 D Tethering: interfaceAdded p2p0,
08-29 14:21:18.801  1014  1128 E Tethering: No numeric data
08-29 14:21:18.801  1014  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
08-29 14:21:18.801  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 14:21:18.801  1170  1170 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 14:21:18.801  1014  1128 D Tethering: clearTetheredNotification()
08-29 14:21:18.801  1170  1170 D HotspotTile: updateTetherState():false, false
,08-29 14:21:18.801  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:21:18.801  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
08-29 14:21:18.801  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-29 14:21:18.801  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 14:21:18.811  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 14:21:18.811  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-29 14:21:18.811  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 14:21:18.811  1014  1121 V NetworkStats: performPollLocked() took 11ms
08-29 14:21:18.811  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 14:21:18.821   277  1010 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-29 14:21:18.821  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:21:18.821  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 14:21:18.821   277  1010 D SoftapController: Softap fwReload - Ok
,08-29 14:21:18.821   277  1010 D CommandListener: Setting iface cfg,
08-29 14:21:18.821   277  1010 D CommandListener: Trying to bring down wlan0
08-29 14:21:18.821   277  1010 D CommandListener: Clearing all IP addresses on wlan0
,08-29 14:21:18.831  1014  1124 E WifiHW  : supplicant_name : p2p_supplicant
,08-29 14:21:18.831  1014  1124 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
08-29 14:21:18.831  1014  1124 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-29 14:21:18.841  4739  4739 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 14:21:18.851  1170  1170 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 14:21:18.851  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 14:21:18.851  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 14:21:18.851  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:18.851  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:18.851  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:18.851  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:18.851  1170  1170 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 14:21:18.851  1170  1170 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-29 14:21:18.851  1170  1170 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 14:21:18.851  1170  1768 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 14:21:18.851  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:18.851  1014  3867 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 14:21:18.851  1014  3867 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:18.851  1014  3867 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 14:21:18.851  1014  3867 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:18.851  1014  3867 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 14:21:18.851  1603  1603 I Hs20UtilService: Starting #17
08-29 14:21:18.851  1603  1624 I Hs20UtilService: Message received 5011
,08-29 14:21:18.861  1170  1170 D HotspotTile: onReceive : 2, 0
08-29 14:21:18.861  7413  7413 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 14:21:18.861  7413  7413 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 14:21:18.861  7413  7413 D SecurityLogAgent: StateMachine : Current State = 1
08-29 14:21:18.861  7413  7413 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 14:21:18.881  7851  7851 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-29 14:21:18.881  7851  7851 I wpa_supplicant: Successfully initialized wpa_supplicant,
08-29 14:21:18.881  7851  7851 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-29 14:21:18.891  7851  7851 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-29 14:21:18.891   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7851
08-29 14:21:18.891   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-29 14:21:18.891  7851  7851 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-29 14:21:18.891  7851  7851 I wpa_supplicant: ssSupport state is = 1
08-29 14:21:18.891  7851  7851 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-29 14:21:18.891  7851  7851 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-29 14:21:18.901   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7851
08-29 14:21:18.901   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-29 14:21:19.051   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-29 14:21:19.051  7851  7851 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-29 14:21:19.101  7851  7851 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-29 14:21:19.101  7851  7851 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-29 14:21:19.111  7851  7851 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-29 14:21:19.111   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7851
08-29 14:21:19.111   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-29 14:21:19.111  7851  7851 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-29 14:21:19.111  7851  7851 I wpa_supplicant: ssSupport state is = 1
08-29 14:21:19.111  7851  7851 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-29 14:21:19.111  7851  7851 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 14:21:19.111  7851  7851 E wpa_supplicant: SIM READ ERROR
08-29 14:21:19.111  7851  7851 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 14:21:19.111  7851  7851 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 14:21:19.111  7851  7851 E wpa_supplicant: SIM READ ERROR,
08-29 14:21:19.111  7851  7851 I wpa_supplicant: Blacklist: Clear (all) 
08-29 14:21:19.111  7851  7851 I wpa_supplicant: wpa_default_ap_write_once
08-29 14:21:19.111  7851  7851 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-29 14:21:19.111  7851  7851 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 14:21:19.111  7851  7851 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
,08-29 14:21:19.111  7851  7851 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 14:21:19.111  7851  7851 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-29 14:21:19.111  7851  7851 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-29 14:21:19.121  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-29 14:21:19.121  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-29 14:21:19.121  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 14:21:19.281  7851  7851 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-29 14:21:19.411  7851  7851 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-29 14:21:19.411  7851  7851 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-29 14:21:19.421  7851  7851 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-29 14:21:19.421   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7851
08-29 14:21:19.421   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-29 14:21:19.431  7851  7851 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-29 14:21:19.431  7851  7851 I wpa_supplicant: ssSupport state is = 1,
08-29 14:21:19.431  7851  7851 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-29 14:21:19.431  7851  7851 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-29 14:21:19.441  7851  7851 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-29 14:21:19.441   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7851
08-29 14:21:19.441   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-29 14:21:19.441  7851  7851 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-29 14:21:19.441  7851  7851 I wpa_supplicant: ssSupport state is = 1
08-29 14:21:19.441  7851  7851 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 14:21:19.441  7851  7851 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-29 14:21:19.441  7851  7851 E wpa_supplicant: SIM READ ERROR
08-29 14:21:19.441  7851  7851 I wpa_supplicant: wpa_default_ap_write_once
,08-29 14:21:19.441  7851  7851 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-29 14:21:19.441  7851  7851 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 14:21:19.451  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 14:21:19.451  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
08-29 14:21:19.451  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 14:21:19.451  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 14:21:19.451  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
08-29 14:21:19.451  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
,08-29 14:21:19.581  7851  7851 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-29 14:21:19.581  7851  7851 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-29 14:21:19.681  7851  7851 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-29 14:21:19.681  7851  7851 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-29 14:21:19.681  7851  7851 I wpa_supplicant: Skip scan - bUseNetwork false
,08-29 14:21:19.791  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 14:21:19.791  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 14:21:19.791  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-29 14:21:19.831  1014  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,08-29 14:21:19.841  1014  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21],
08-29 14:21:19.841  7851  7851 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-29 14:21:19.841  7851  7851 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-29 14:21:19.841  7851  7851 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 14:21:19.841  7851  7851 E wpa_supplicant: SIM READ ERROR
,08-29 14:21:19.841  7851  7851 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 14:21:19.851  7851  7851 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-29 14:21:19.861  7851  7851 I wpa_supplicant: Skip scan - bUseNetwork false
,08-29 14:21:19.861  1014  1124 D WifiConfigStore: Loading config and enabling all networks 
,08-29 14:21:19.871  4739  4739 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 14:21:19.871  1014  1486 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 14:21:19.881  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 14:21:19.881  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:19.881  1014  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 14:21:19.881  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 14:21:19.881  1014  1124 E WifiConfigStore: Not a HS20
08-29 14:21:19.881  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:19.881  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:19.881  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:19.881  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:19.881  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:19.881  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:19.881  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:19.881  7083  7083 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:21:19.881  7083  7083 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:21:19.891  1014  1124 D WifiNative-wlan0: callSECApiInt - ID [65]
08-29 14:21:19.891  1170  1170 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 14:21:19.891  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 14:21:19.891  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 14:21:19.891  1170  1170 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 14:21:19.891  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:19.891  1170  1768 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-29 14:21:19.891  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:19.891  1014  1124 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-29 14:21:19.891  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:19.891  7851  7851 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-29 14:21:19.891  7851  7851 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-29 14:21:19.891  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:19.891  1170  1170 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 14:21:19.891  7851  7851 I wpa_supplicant: reset timer : RESET_TIMER 0
08-29 14:21:19.891  1170  1170 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-29 14:21:19.891  7851  7851 I wpa_supplicant: P2P: Current p2p state = IDLE
08-29 14:21:19.891  7851  7851 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-29 14:21:19.891  7851  7851 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-29 14:21:19.891  7851  7851 I wpa_supplicant: First Scan Start
08-29 14:21:19.891  7851  7851 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-29 14:21:19.891  1170  1170 D HotspotTile: onReceive : 3, 0
08-29 14:21:19.891  1014  1124 D WifiNative-wlan0: Setting external_sim to 1
,08-29 14:21:19.891  1014  1124 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 14:21:19.891  1014  1124 I WifiNative-HAL: startHal
08-29 14:21:19.891  1014  1124 E wifi    : getStaticLongField sWifiHalHandle 0x9f2ae88c
08-29 14:21:19.891  1014  1124 I WifiNative-HAL: Could not start hal
,08-29 14:21:19.891  1603  1603 I Hs20UtilService: Starting #18
08-29 14:21:19.891  7390  7390 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 14:21:19.891  1603  1624 I Hs20UtilService: Message received 5011
,08-29 14:21:19.901  1014  1124 E WifiNative-wlan0: do suspend true
,08-29 14:21:19.901  1014  1123 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-29 14:21:19.901   277  1010 D CommandListener: Setting iface cfg,
08-29 14:21:19.901   277  1010 D CommandListener: Trying to bring up p2p0
08-29 14:21:19.901  1014  1123 D WifiP2pService: P2pEnablingState
08-29 14:21:19.901  7413  7413 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 14:21:19.901  7413  7413 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 14:21:19.901  1014  1123 D WifiP2pService: P2pEnablingState{ what=147457 }
08-29 14:21:19.901  7413  7413 D SecurityLogAgent: StateMachine : Current State = 1
08-29 14:21:19.901  7413  7413 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-29 14:21:19.901  1014  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-29 14:21:19.901  1014  1123 D WifiP2pService: P2p socket connection successful
08-29 14:21:19.901  1014  1123 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 14:21:19.901  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 14:21:19.901  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:19.901  1014  1123 D WifiP2pService: P2pEnabledState
08-29 14:21:19.901  1014  1148 I WifiNative-HAL: startHal
08-29 14:21:19.901  1014  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9e26e9bc
08-29 14:21:19.901  1014  1148 I WifiNative-HAL: Could not start hal
08-29 14:21:19.901  1014  1148 E WifiScanningService: could not start HAL
08-29 14:21:19.901  1014  1014 D RttService: SCAN_AVAILABLE : 3
08-29 14:21:19.901  1014  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 14:21:19.901  1014  1126 E ConnectivityService: updateNetworkInfo()
,08-29 14:21:19.901  1014  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-29 14:21:19.911  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-29 14:21:19.911  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-29 14:21:19.911  1014  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-29 14:21:19.911  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 14:21:19.911  1014  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215],
08-29 14:21:19.911  1014  1045 D WifiDisplayController: disconnect
08-29 14:21:19.911  1014  1124 E WifiNative-wlan0: invaild command id : 215
08-29 14:21:19.911  1014  1045 D WifiDisplayController: updateConnection
08-29 14:21:19.911  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-29 14:21:19.911  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-29 14:21:19.911  7851  7851 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-29 14:21:19.911  7851  7851 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-29 14:21:19.911  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 14:21:19.911  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
08-29 14:21:19.911  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 14:21:19.911  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-29 14:21:19.921  7851  7851 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-29 14:21:19.921  1170  1170 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-29 14:21:19.921  1014  1124 E WifiStateMachine: Failed to set frequency band 0
08-29 14:21:19.921  1014  3867 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 14:21:19.921  1014  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-29 14:21:19.921  1170  1170 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-29 14:21:19.921  1014  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-29 14:21:19.921  1014  1124 E WifiNative-wlan0: invaild command id : 215
08-29 14:21:19.921  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 14:21:19.921  1014  1124 D SecContentProvider2: mCursor = null
08-29 14:21:19.921  1014  1123 D WifiNative-p2p0: p2pGetDeviceAddress
08-29 14:21:19.921  1014  1123 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
08-29 14:21:19.921  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 14:21:19.921  1014  1124 D SecContentProvider2: mCursor = null
08-29 14:21:19.921  4739  4739 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-29 14:21:19.921  4739  4739 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 14:21:19.921  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 14:21:19.931  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 14:21:19.931  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 14:21:19.931  4739  4739 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 14:21:19.931  1014  1482 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-29 14:21:19.931  1014  1482 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4287, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 14:21:19.931  4739  4815 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-29 14:21:19.931  1014  1482 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 14:21:19.931  1014  1482 D BatteryService: stay LED for charging
08-29 14:21:19.931  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 14:21:19.931  1014  1123 D WifiP2pService: DeviceAddress: 0a:75:42
,08-29 14:21:19.931  1014  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-29 14:21:19.931  1014  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-29 14:21:19.931  1014  1045 D WifiDisplayController:  primary type: 10-0050F204-5
08-29 14:21:19.931  1014  1045 D WifiDisplayController:  secondary type: null
08-29 14:21:19.931  1014  1045 D WifiDisplayController:  wps: 0
08-29 14:21:19.931  1014  1045 D WifiDisplayController:  grpcapab: 0
08-29 14:21:19.931  1014  1045 D WifiDisplayController:  devcapab: 0
08-29 14:21:19.931  1014  1045 D WifiDisplayController:  status: 3
08-29 14:21:19.931  1014  1045 D WifiDisplayController:  wfdInfo: null
08-29 14:21:19.931  1014  1045 D WifiDisplayController:  groupownerAddress: null
08-29 14:21:19.931  1014  1045 D WifiDisplayController:  GOdeviceName: null
08-29 14:21:19.931  1014  1045 D WifiDisplayController:  interfaceAddress: 
08-29 14:21:19.931  1014  1045 D WifiDisplayController:  SConnectInfo : null
,08-29 14:21:19.941  1014  1014 I MotionRecognitionService: Plugged
08-29 14:21:19.941  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 14:21:19.941  1170  1170 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-29 14:21:19.941  1170  1170 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 14:21:19.941  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 14:21:19.941  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 14:21:19.951  3235  3235 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 14:21:19.951  3235  7826 D HeadsetStateMachine: Disconnected process message: 10
,08-29 14:21:19.951  7727  7727 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 14:21:19.951  7727  7727 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-29 14:21:19.951  7727  7727 D FileShare-Client: Outbound.stopDelayTimer - 
,08-29 14:21:19.961  1014  1123 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-29 14:21:19.961  1014  1123 D WifiP2pService: InactiveState
,08-29 14:21:19.961  1014  1123 D WifiP2pService: InactiveState{ what=143376 }
,08-29 14:21:19.961  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-29 14:21:19.961  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-29 14:21:19.961  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-29 14:21:19.961  7375  7375 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-29 14:21:19.961  1014  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-29 14:21:19.961  7851  7851 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-29 14:21:19.971  1014  1123 D WifiP2pService: InactiveState{ what=143376 }
08-29 14:21:19.971  1014  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-29 14:21:20.451  7083  7251 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:21:20.451  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:20.451  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:20.451  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:20.451  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:20.451  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:20.451  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:20.451  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:20.461  7083  7251 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,08-29 14:21:20.461  7083  7251 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 14:21:20.461  7083  7251 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 14:21:20.461  7083  7251 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3aa74a26 Bundle[{}]
,08-29 14:21:20.461  7083  7251 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 14:21:20.461  7083  7251 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-29 14:21:20.471  7083  7251 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 14:21:20.471  7083  7251 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-29 14:21:20.471  7083  7251 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-29 14:21:20.471  7083  7251 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 14:21:20.471  7083  7251 I System.out: Running OutgoingSocketThread
,08-29 14:21:20.471  7083  7860 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1440)
,08-29 14:21:20.481  7083  7860 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 60821
,08-29 14:21:20.481  7083  7860 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 14:21:20.881   287   287 E SMD     : DCD OFF,
,08-29 14:21:21.151  7851  7851 I wpa_supplicant: nl80211: Received scan results (21 BSSes),
,08-29 14:21:21.151  7851  7851 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-29 14:21:21.151  1014  7857 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-29 14:21:21.151  7851  7851 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-29 14:21:21.151  7851  7851 I wpa_supplicant: Trying to associate with  'G700'
08-29 14:21:21.151  7851  7851 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
,08-29 14:21:21.151  7851  7851 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,08-29 14:21:21.171  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 14:21:21.171  1014  1124 D SecContentProvider2: mCursor = null
,08-29 14:21:21.261  7851  7851 E wpa_supplicant: Cmd 35605 not handled
,08-29 14:21:21.261  7851  7851 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 14:21:21.261  7851  7851 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-29 14:21:21.261  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-29 14:21:21.261  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-29 14:21:21.261  7851  7851 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-29 14:21:21.271  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 14:21:21.271  7851  7851 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030,
08-29 14:21:21.271  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 14:21:21.271  7851  7851 I wpa_supplicant: Associated with F4.99.3E
08-29 14:21:21.271  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-29 14:21:21.271  7851  7851 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 14:21:21.271  7851  7851 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,08-29 14:21:21.271  7851  7851 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-29 14:21:21.271  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 14:21:21.271  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-29 14:21:21.271  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-29 14:21:21.271  1014  1042 D Tethering: interfaceStatusChanged wlan0, true
08-29 14:21:21.271  1014  1128 E Tethering: No numeric data
,08-29 14:21:21.271  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 14:21:21.271  1014  1128 D Tethering: clearTetheredNotification()
,08-29 14:21:21.281  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
,08-29 14:21:21.281  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 14:21:21.281  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 14:21:21.281  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 14:21:21.281  1170  1170 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 14:21:21.281  1170  1170 D HotspotTile: updateTetherState():false, false
08-29 14:21:21.281  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 14:21:21.281  1014  1124 D SecContentProvider2: mCursor = null
08-29 14:21:21.281  1014  1121 V NetworkStats: performPollLocked() took 6ms
08-29 14:21:21.281  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 14:21:21.291  7851  7851 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 14:21:21.291  7851  7851 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-29 14:21:21.291  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 14:21:21.291  1014  1124 D SecContentProvider2: mCursor = null
08-29 14:21:21.291  7851  7851 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-29 14:21:21.291  7851  7851 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-29 14:21:21.291  7851  7851 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP],
08-29 14:21:21.291  7851  7851 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,08-29 14:21:21.291  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-29 14:21:21.291  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 14:21:21.291  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 14:21:21.291  7851  7851 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-29 14:21:21.291  7851  7851 I wpa_supplicant: Blacklist: Clear (temp) 
,08-29 14:21:21.291  7851  7851 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-29 14:21:21.291  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, true
,08-29 14:21:21.291  1014  1042 D Tethering: interfaceStatusChanged wlan0, true
08-29 14:21:21.291  1014  1124 D WifiNative-wlan0: callSECApiVoid - ID [50]
08-29 14:21:21.291  1014  1124 E WifiConfigStore: setLastSelectedConfiguration -1
,08-29 14:21:21.301  1014  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-29 14:21:21.301  1014  1126 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false,
08-29 14:21:21.301  1014  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 14:21:21.301  1014  1126 E ConnectivityService: updateNetworkInfo()
08-29 14:21:21.301  1170  1170 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 14:21:21.301  1014  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 14:21:21.301  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 14:21:21.311  1014  1253 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 14:21:21.301  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 14:21:21.311  1014  1253 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 14:21:21.301  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 14:21:21.301  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:21.301  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:21.301  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:21.311  1014  1253 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:21.311  1014  1253 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:21.311  1014  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 14:21:21.311  1603  1603 I Hs20UtilService: Starting #19
,08-29 14:21:21.311  1603  1624 I Hs20UtilService: Message received 5007
,08-29 14:21:21.311  4739  4739 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 14:21:21.311  4739  4739 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 14:21:21.321  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 14:21:21.321  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-29 14:21:21.321  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 14:21:21.321  4739  4739 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 14:21:21.321  4739  4815 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 14:21:21.331  1014  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 14:21:21.351   277  1010 D CommandListener: Setting iface cfg,
,08-29 14:21:21.351  1014  1124 E WifiStateMachine: Start Dhcp Watchdog 2
,08-29 14:21:21.351  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 14:21:21.361  1014  1124 D SecContentProvider2: mCursor = null
,08-29 14:21:21.361  1170  1170 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 14:21:21.371  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 14:21:21.371  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-29 14:21:21.371  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 14:21:21.371  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 14:21:21.371  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-29 14:21:21.371  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 14:21:21.371  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 14:21:21.371  1014  1124 D SecContentProvider2: mCursor = null
,08-29 14:21:21.381  1014  1124 E WifiNative-wlan0: do suspend false,
,08-29 14:21:21.381  1014  1123 D WifiP2pService: InactiveState{ what=143375 },
,08-29 14:21:21.381  1014  1123 D WifiP2pService: P2pEnabledState{ what=143375 },
,08-29 14:21:21.471  7083  7251 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1441),
,08-29 14:21:21.471  7083  7251 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1441)
08-29 14:21:21.481  7083  7251 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1446)
,08-29 14:21:21.481  7083  7251 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...,
08-29 14:21:21.481  7083  7251 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1447)
,08-29 14:21:21.481  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 14:21:21.481  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@285ca755 added. We now have 2 listener(s)
,08-29 14:21:21.491  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
08-29 14:21:21.491  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
,08-29 14:21:21.491  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 14:21:21.491  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:21.491  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b2d556a added. We now have 9 listener(s)
,08-29 14:21:21.491  7083  7251 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:21.491  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 14:21:21.491  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:21:21.491  7083  7251 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:21:21.491  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:21.491  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:21.491  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:21.491  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:21.491  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:21.491  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:21.491  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:21.501  7083  7251 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-29 14:21:21.501  7083  7251 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 14:21:21.501  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:21.501  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:21:21.501  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fe9e2f8 added. We now have 3 listener(s)
,08-29 14:21:21.501  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:21.501  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-29 14:21:21.501  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 14:21:21.501  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 14:21:21.501  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 14:21:21.501  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d8d63d1 added. We now have 10 listener(s)
08-29 14:21:21.501  7083  7251 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-29 14:21:21.511  7083  7251 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-29 14:21:21.511  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:21.511  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:21.511  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 14:21:21.511  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:21.511  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:21:21.511  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 14:21:21.511  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@285ca755 removed from the list
,08-29 14:21:21.511  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:21.511  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b2d556a removed from the list
08-29 14:21:21.511  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:21.511  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:21.511  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:21:21.511  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:21.511  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 14:21:21.511  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 14:21:21.511  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:21:21.511  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b2d556a not in the list
,08-29 14:21:21.511  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:21:21.511  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:21.511  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 14:21:21.511  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 14:21:21.521  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-29 14:21:21.521  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d8d63d1 removed from the list
,08-29 14:21:21.521  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-29 14:21:21.521  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 14:21:21.521  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:21.521  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 14:21:21.521  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fe9e2f8 removed from the list
,08-29 14:21:21.521  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 14:21:21.521  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e435e36 added. We now have 2 listener(s)
,08-29 14:21:21.521  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
08-29 14:21:21.521  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 14:21:21.531  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 14:21:21.531  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 14:21:21.531  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d27c137 added. We now have 9 listener(s)
,08-29 14:21:21.531  7083  7251 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:21.531  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 14:21:21.531  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:21:21.541  7083  7251 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:21:21.541  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:21.541  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:21.541  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:21.541  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:21.541  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:21.541  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:21.541  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:21.541  7083  7251 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:21:21.541  7083  7251 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 14:21:21.541  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:21.541  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:21:21.541  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26336c0d added. We now have 3 listener(s)
,08-29 14:21:21.541  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-29 14:21:21.551  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-29 14:21:21.551  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:21:21.551  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 14:21:21.551  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:21.551  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ddf27c2 added. We now have 10 listener(s)
08-29 14:21:21.551  7083  7251 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:21.551  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 14:21:21.551  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 14:21:21.551  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 14:21:21.551  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:21.551  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 14:21:21.551  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 14:21:21.551  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 14:21:21.561  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 14:21:21.561  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 14:21:21.561  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 14:21:21.561  7083  7251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 14:21:21.561  3235  3248 D BtGatt.GattService: registerClient() - UUID=5eb0ee0e-daa7-4019-ab0f-ddba11452abe
,08-29 14:21:21.571  1014  1047 I PowerManagerService: [PWL] Off : 75s ago
,08-29 14:21:21.571  1014  1047 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-29 14:21:21.571  1014  1047 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-29 14:21:21.571  1014  1047 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1014, ws=null) (elapsedTime=22054)
,08-29 14:21:21.591  7866  7866 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-29 14:21:21.601  7866  7866 I dhcpcd  : version 5.5.6 starting
,08-29 14:21:21.601  7866  7866 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-29 14:21:21.611  3235  3317 D BtGatt.GattService: onClientRegistered() - UUID=5eb0ee0e-daa7-4019-ab0f-ddba11452abe, clientIf=6
08-29 14:21:21.611  7083  7093 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 14:21:21.611  3235  7773 D BtGatt.GattService: start scan with filters,
08-29 14:21:21.611  3235  3373 D BtGatt.ScanManager: handling starting scan
,08-29 14:21:21.611  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 14:21:21.611  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 14:21:21.611  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 14:21:21.611  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 14:21:21.611  3235  3317 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 14:21:21.611  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 14:21:21.621  3235  3373 D BtGatt.ScanManager: allow scan with filters
08-29 14:21:21.621  3235  3373 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-29 14:21:21.621  3235  3373 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
08-29 14:21:21.621  3235  3317 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-29 14:21:21.621  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 14:21:21.621  3235  3373 D BtGatt.ScanManager: Starting BLE batch scan,
08-29 14:21:21.621  3235  3373 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-29 14:21:21.621  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-29 14:21:21.621  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 14:21:21.621  7083  7083 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 14:21:21.621  3235  3317 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-29 14:21:21.621  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 14:21:21.621  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 14:21:21.621  3235  3317 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-29 14:21:21.621  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 14:21:21.631  7083  7251 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 14:21:21.631  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:21.631  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 14:21:21.631  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:21.631  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 14:21:21.631  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 14:21:21.631  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 14:21:21.631  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 14:21:21.631  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
08-29 14:21:21.631  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 14:21:21.631  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 14:21:21.631  3235  3318 D BtGatt.GattService: stopScan() - queue size =1
,08-29 14:21:21.631  3235  3244 D BtGatt.GattService: unregisterClient() - clientIf=6
08-29 14:21:21.631  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:21:21.631  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 14:21:21.631  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 14:21:21.631  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 14:21:21.631  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 14:21:21.631  3235  3373 D BtGatt.ScanManager: filter size is 1
,08-29 14:21:21.631  3235  3373 D BtGatt.ScanManager: delete FilterIndex - 6
08-29 14:21:21.631  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 14:21:21.631  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 14:21:21.631  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 14:21:21.631  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 14:21:21.641  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:21:21.641  7083  7083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:21:21.641  7083  7083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:21:21.641  7083  7083 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 14:21:21.641  3235  3317 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-29 14:21:21.641  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 14:21:21.641  3235  3373 D BtGatt.ScanManager: stopping BLe Batch
,08-29 14:21:21.641  3235  3317 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 14:21:21.641  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 14:21:21.641  3235  3373 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 14:21:21.641  7083  7251 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:21:21.641  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:21.641  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:21.641  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:21.641  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:21.641  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:21:21.641  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-29 14:21:21.641  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e435e36 removed from the list
08-29 14:21:21.641  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:21.641  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d27c137 removed from the list
08-29 14:21:21.641  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:21.641  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:21.641  3235  3317 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-29 14:21:21.641  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 14:21:21.641  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:21.641  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:21.651  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 14:21:21.651  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:21.651  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:21.651  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d27c137 not in the list
08-29 14:21:21.651  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:21.651  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:21.651  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:21.651  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:21.651  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:21.651  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ddf27c2 removed from the list
08-29 14:21:21.651  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:21.651  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:21.651  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:21.651  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 14:21:21.651  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26336c0d removed from the list
08-29 14:21:21.651  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 14:21:21.651  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17bfe0e added. We now have 2 listener(s)
,08-29 14:21:21.661  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-29 14:21:21.661  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:21:21.661  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 14:21:21.661  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:21.661  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3607a02f added. We now have 9 listener(s)
08-29 14:21:21.661  7083  7251 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:21:21.661  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 14:21:21.661  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:21:21.671  7083  7251 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-29 14:21:21.671  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:21.671  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:21.671  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:21.671  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:21.671  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:21.671  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:21.671  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:21.671  7083  7251 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-29 14:21:21.671  7083  7251 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 14:21:21.671  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:21:21.671  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f170fc5 added. We now have 3 listener(s)
08-29 14:21:21.671  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:21.681  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:21.681  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-29 14:21:21.681  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:21:21.681  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 14:21:21.681  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:21.681  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2afded1a added. We now have 10 listener(s)
08-29 14:21:21.681  7083  7251 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:21.681  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 14:21:21.681  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 14:21:21.681  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 14:21:21.681  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 14:21:21.681  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:21.681  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 14:21:21.681  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 14:21:21.691  7866  7866 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-29 14:21:21.691  7866  7866 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-29 14:21:21.691  7866  7866 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-29 14:21:21.691  7866  7866 I dhcpcd  : bssid match
,08-29 14:21:21.691  7866  7866 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-29 14:21:21.691  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 14:21:21.691  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 14:21:21.691  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 14:21:21.691  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 14:21:21.691  7083  7251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 14:21:21.701  3235  3248 D BtGatt.GattService: registerClient() - UUID=e6512fd2-84d9-43a6-9c68-8e28b96446b2
,08-29 14:21:21.741  3235  3317 D BtGatt.GattService: onClientRegistered() - UUID=e6512fd2-84d9-43a6-9c68-8e28b96446b2, clientIf=6
,08-29 14:21:21.741  7083  7242 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
08-29 14:21:21.741  3235  7773 D BtGatt.GattService: start scan with filters
08-29 14:21:21.741  3235  3373 D BtGatt.ScanManager: handling starting scan,
08-29 14:21:21.741  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 14:21:21.741  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
08-29 14:21:21.741  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 14:21:21.741  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 14:21:21.741  3235  3317 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-29 14:21:21.741  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 14:21:21.741  3235  3373 D BtGatt.ScanManager: allow scan with filters
,08-29 14:21:21.741  3235  3373 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-29 14:21:21.741  3235  3373 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,08-29 14:21:21.751  3235  3317 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-29 14:21:21.751  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 14:21:21.751  3235  3373 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 14:21:21.751  3235  3373 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-29 14:21:21.751  7866  7866 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-29 14:21:21.751  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 14:21:21.751  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 14:21:21.751  7083  7083 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 14:21:21.751  3235  3317 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-29 14:21:21.751  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 14:21:21.751  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 14:21:21.761  3235  3317 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-29 14:21:21.761  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 14:21:21.761  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 14:21:21.761  7083  7251 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 14:21:21.761  7083  7251 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 14:21:21.761  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:21:21.761  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 14:21:21.761  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 14:21:21.761  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:21:21.761  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 14:21:21.761  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 14:21:21.771  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17bfe0e removed from the list
,08-29 14:21:21.771  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:21:21.771  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3607a02f removed from the list
,08-29 14:21:21.771  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 14:21:21.771  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:21:21.771  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:21:21.771  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 14:21:21.771  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:21:21.771  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:21:21.771  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-29 14:21:21.771  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:21.771  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:21.771  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3607a02f not in the list
08-29 14:21:21.771  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 14:21:21.771  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 14:21:21.771  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 14:21:21.771  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 14:21:21.771  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 14:21:21.771  3235  3248 D BtGatt.GattService: stopScan() - queue size =1
,08-29 14:21:21.771  3235  3373 D BtGatt.ScanManager: filter size is 1
08-29 14:21:21.771  3235  3394 D BtGatt.GattService: unregisterClient() - clientIf=6
08-29 14:21:21.771  3235  3373 D BtGatt.ScanManager: delete FilterIndex - 7
,08-29 14:21:21.771  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:21:21.771  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 14:21:21.771  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 14:21:21.771  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 14:21:21.771  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 14:21:21.781  3235  3317 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-29 14:21:21.781  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 14:21:21.781  3235  3373 D BtGatt.ScanManager: stopping BLe Batch
,08-29 14:21:21.781  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
,08-29 14:21:21.781  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 14:21:21.781  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 14:21:21.781  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 14:21:21.781  3235  3317 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 14:21:21.781  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 14:21:21.781  3235  3373 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 14:21:21.781  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:21.781  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:21.781  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:21.781  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:21.781  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2afded1a removed from the list
08-29 14:21:21.781  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:21.781  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:21.781  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:21.781  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 14:21:21.781  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f170fc5 removed from the list
,08-29 14:21:21.781  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:21:21.781  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@247dc0e6 added. We now have 2 listener(s)
,08-29 14:21:21.781  3235  3317 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-29 14:21:21.781  7083  7083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:21:21.781  7083  7083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:21:21.781  7083  7083 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 14:21:21.781  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 14:21:21.791  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-29 14:21:21.791  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:21:21.791  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 14:21:21.791  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:21.791  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32356627 added. We now have 9 listener(s)
08-29 14:21:21.791  7083  7251 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:21.791  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 14:21:21.791  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:21:21.801  7083  7251 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:21:21.801  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:21.801  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:21.801  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:21.801  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:21.801  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:21.801  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:21.801  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:21.801  7083  7251 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:21:21.801  7083  7251 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 14:21:21.801  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:21:21.801  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3de4727d added. We now have 3 listener(s)
,08-29 14:21:21.801  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:21.801  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:21.801  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-29 14:21:21.801  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:21:21.801  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 14:21:21.801  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:21.801  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ed50572 added. We now have 10 listener(s)
08-29 14:21:21.801  7083  7251 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:21.801  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 14:21:21.801  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 14:21:21.801  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 14:21:21.801  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:21:21.801  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 14:21:21.811  7866  7866 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
,08-29 14:21:21.811  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,08-29 14:21:21.821  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 14:21:21.821  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 14:21:21.821  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 14:21:21.821  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 14:21:21.821  7083  7251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 14:21:21.831  3235  7773 D BtGatt.GattService: registerClient() - UUID=030dda6a-7152-47c4-9da8-76621fecc8ee
,08-29 14:21:21.841  1014  1320 E Watchdog: !@Sync 4
,08-29 14:21:21.871  3235  3317 D BtGatt.GattService: onClientRegistered() - UUID=030dda6a-7152-47c4-9da8-76621fecc8ee, clientIf=6,
08-29 14:21:21.871  7083  7094 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-29 14:21:21.871  3235  3244 D BtGatt.GattService: start scan with filters
,08-29 14:21:21.871  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
08-29 14:21:21.871  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 14:21:21.871  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
08-29 14:21:21.871  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 14:21:21.871  3235  3373 D BtGatt.ScanManager: handling starting scan,
,08-29 14:21:21.871  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 14:21:21.871  7083  7083 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 14:21:21.881  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 14:21:21.881  3235  3317 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-29 14:21:21.881  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 14:21:21.881  3235  3373 D BtGatt.ScanManager: allow scan with filters
,08-29 14:21:21.881  3235  3373 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-29 14:21:21.881  3235  3373 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
,08-29 14:21:21.881  3235  3317 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-29 14:21:21.881  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 14:21:21.881  3235  3373 D BtGatt.ScanManager: Starting BLE batch scan
08-29 14:21:21.881  3235  3373 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 14:21:21.881  3235  3317 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-29 14:21:21.881  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 14:21:21.881  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 14:21:21.891  3235  3317 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-29 14:21:21.891  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 14:21:21.901  7083  7251 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 14:21:21.901  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:21:21.901  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:21.901  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:21.901  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:21.901  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 14:21:21.901  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 14:21:21.901  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@247dc0e6 removed from the list
08-29 14:21:21.901  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:21.901  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32356627 removed from the list
08-29 14:21:21.901  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:21.901  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:21:21.901  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:21.901  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 14:21:21.901  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:21.901  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:21:21.911  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:21.911  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:21.911  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:21.911  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32356627 not in the list
08-29 14:21:21.911  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 14:21:21.911  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 14:21:21.911  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 14:21:21.911  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 14:21:21.911  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 14:21:21.911  3235  3318 D BtGatt.GattService: stopScan() - queue size =1
08-29 14:21:21.911  3235  3248 D BtGatt.GattService: unregisterClient() - clientIf=6
08-29 14:21:21.911  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:21:21.911  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 14:21:21.911  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 14:21:21.911  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 14:21:21.911  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 14:21:21.911  3235  3373 D BtGatt.ScanManager: filter size is 1
08-29 14:21:21.911  3235  3373 D BtGatt.ScanManager: delete FilterIndex - 8
08-29 14:21:21.911  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 14:21:21.911  3235  3317 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-29 14:21:21.911  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 14:21:21.911  3235  3373 D BtGatt.ScanManager: stopping BLe Batch
08-29 14:21:21.911  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 14:21:21.911  7083  7251 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 14:21:21.911  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 14:21:21.911  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:21.911  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:21.911  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:21.911  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:21.911  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ed50572 removed from the list
08-29 14:21:21.911  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:21.911  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:21.911  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:21.911  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 14:21:21.911  7083  7083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:21:21.911  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3de4727d removed from the list
08-29 14:21:21.911  7083  7083 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:21:21.911  7083  7083 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 14:21:21.911  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:21:21.911  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cea06be added. We now have 2 listener(s)
08-29 14:21:21.911  3235  3317 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 14:21:21.911  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 14:21:21.911  3235  3373 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-29 14:21:21.921  3235  3317 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-29 14:21:21.921  3235  3317 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 14:21:21.921  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-29 14:21:21.921  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:21:21.921  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 14:21:21.921  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:21.921  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f31f added. We now have 9 listener(s)
08-29 14:21:21.921  7083  7251 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:21.921  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 14:21:21.931  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:21:21.931  7083  7251 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-29 14:21:21.931  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:21:21.931  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:21:21.931  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:21:21.931  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:21:21.931  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:21:21.931  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:21:21.931  7083  7251 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:21:21.941  7083  7251 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-29 14:21:21.941  7083  7251 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 14:21:21.941  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:21:21.941  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:21:21.941  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30347435 added. We now have 3 listener(s)
,08-29 14:21:21.951  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:21:21.951  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-29 14:21:21.951  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:21:21.951  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 14:21:21.951  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:21:21.951  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bbd0ca added. We now have 10 listener(s)
08-29 14:21:21.951  7083  7251 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:21:21.951  7083  7251 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-29 14:21:21.951  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:21:21.951  7083  7251 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:21:21.951  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:21.951  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:21.951  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:21:21.951  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 14:21:21.951  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cea06be removed from the list,
08-29 14:21:21.951  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:21:21.951  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f31f removed from the list
08-29 14:21:21.951  7083  7251 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:21:21.951  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:21.951  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 14:21:21.951  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 14:21:21.951  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:21.951  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:21.951  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:21:21.951  7083  7251 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a6f31f not in the list
08-29 14:21:21.951  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:21.951  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:21.961  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:21:21.961  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:21:21.961  7083  7251 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:21:21.961  7083  7251 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bbd0ca removed from the list
08-29 14:21:21.961  7083  7251 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:21:21.961  7083  7251 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:21:21.961  7083  7251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 14:21:21.961  7083  7251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 14:21:21.961  7083  7251 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30347435 removed from the list
08-29 14:21:21.961  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 14:21:21.961  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-29 14:21:21.961  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 14:21:21.961  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 14:21:21.961  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 14:21:21.961  7083  7251 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:21:21.961  7083  7891 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1454, name: My test thread name)
,08-29 14:21:21.961  7083  7891 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1454, thread name: My test thread name)
08-29 14:21:21.961  7083  7891 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1454, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 14:21:21.971  7083  7893 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1456, name: My test thread name)
,08-29 14:21:21.971  7083  7893 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1456, thread name: My test thread name)
,08-29 14:21:21.971  7083  7893 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1456, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 14:21:21.971  7083  7251 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80,
08-29 14:21:21.971  7083  7251 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 14:21:21.971  7083  7251 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 14:21:21.971  7083  7251 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-29 14:21:21.971  7083  7251 D com.test.thalitest.ThaliTestRunner: Total duration: 23286 ms
,08-29 14:21:21.971  7083  7251 I jxcore-log: *Native tests were executed*
08-29 14:21:21.971  7083  7251 I jxcore-log: 
08-29 14:21:21.971  7083  7251 I jxcore-log: Total number of executed tests:  80
08-29 14:21:21.971  7083  7251 I jxcore-log: 
,08-29 14:21:21.971  7083  7251 I jxcore-log: Number of passed tests:  80
08-29 14:21:21.971  7083  7251 I jxcore-log: 
08-29 14:21:21.971  7083  7251 I jxcore-log: Number of failed tests:  0
08-29 14:21:21.971  7083  7251 I jxcore-log: 
,08-29 14:21:21.971  7083  7251 I jxcore-log: Number of ignored tests:  0
08-29 14:21:21.971  7083  7251 I jxcore-log: 
08-29 14:21:21.971  7083  7251 I jxcore-log: Total duration:  23286
,08-29 14:21:21.971  7083  7251 I jxcore-log: 
08-29 14:21:21.971  7083  7251 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 14:21:21.971  7083  7251 I jxcore-log: 
,08-29 14:21:21.981  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:21.981  7083  7251 I jxcore-log: 
08-29 14:21:21.981  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:21.981  7083  7251 I jxcore-log: 
08-29 14:21:21.981  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:21.981  7083  7251 I jxcore-log: 
08-29 14:21:21.981  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:21.981  7083  7251 I jxcore-log: 
08-29 14:21:21.981  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:21.981  7083  7251 I jxcore-log: 
08-29 14:21:21.981  7083  7083 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-29 14:21:21.981  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 14:21:21.981  7083  7251 I jxcore-log: 
,08-29 14:21:21.991  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
08-29 14:21:21.991  7083  7251 I jxcore-log: 
,08-29 14:21:21.991  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-29 14:21:21.991  7083  7251 I jxcore-log: 
,08-29 14:21:21.991  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 14:21:21.991  7083  7251 I jxcore-log: 
,08-29 14:21:21.991  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 14:21:21.991  7083  7251 I jxcore-log: 
,08-29 14:21:21.991  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"},
08-29 14:21:21.991  7083  7251 I jxcore-log: 
,08-29 14:21:21.991  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 14:21:21.991  7083  7251 I jxcore-log: 
,08-29 14:21:21.991  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-29 14:21:21.991  7083  7251 I jxcore-log: 
,08-29 14:21:22.001  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-29 14:21:22.001  7083  7251 I jxcore-log: 
,08-29 14:21:22.001  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 14:21:22.001  7083  7251 I jxcore-log: 
08-29 14:21:22.001  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"},
08-29 14:21:22.001  7083  7251 I jxcore-log: 
08-29 14:21:22.001  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-29 14:21:22.001  7083  7251 I jxcore-log: 
08-29 14:21:22.001  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-29 14:21:22.001  7083  7251 I jxcore-log: 
08-29 14:21:22.001  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"},
08-29 14:21:22.001  7083  7251 I jxcore-log: 
,08-29 14:21:22.001  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 14:21:22.001  7083  7251 I jxcore-log: 
08-29 14:21:22.001  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 14:21:22.001  7083  7251 I jxcore-log: 
08-29 14:21:22.001  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-29 14:21:22.001  7083  7251 I jxcore-log: 
,08-29 14:21:22.011  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 14:21:22.011  7083  7251 I jxcore-log: 
,08-29 14:21:22.011  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 14:21:22.011  7083  7251 I jxcore-log: 
,08-29 14:21:22.011  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 14:21:22.011  7083  7251 I jxcore-log: 
,08-29 14:21:22.011  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 14:21:22.011  7083  7251 I jxcore-log: 
,08-29 14:21:22.011  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 14:21:22.011  7083  7251 I jxcore-log: 
,08-29 14:21:22.141  7083  7083 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 14:21:22.141  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 14:21:22.141  7083  7251 I jxcore-log: 
,08-29 14:21:22.191  1014  1124 E WifiNative-wlan0: do suspend true,
,08-29 14:21:22.211  1014  1123 D WifiP2pService: InactiveState{ what=143375 },
08-29 14:21:22.211  1014  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-29 14:21:22.221  1014  1124 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-29 14:21:22.221  1014  1124 E WifiStateMachine: VerifyingLinkState enter
,08-29 14:21:22.221  1170  1170 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-29 14:21:22.221  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 14:21:22.221  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 14:21:22.221  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:22.221  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-29 14:21:22.221  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:22.221  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 14:21:22.221  1014  1126 E ConnectivityService: updateNetworkInfo()
,08-29 14:21:22.221  1014  1126 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null,
08-29 14:21:22.221  1014  1126 D ConnectivityService: Adding iface wlan0 to network 503
,08-29 14:21:22.231  1014  1142 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter,
08-29 14:21:22.231  1014  1142 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-29 14:21:22.231  1014  1142 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-29 14:21:22.231  1014  1142 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
08-29 14:21:22.231  1014  1142 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-29 14:21:22.241  1170  1170 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-29 14:21:22.241  1014  1487 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 14:21:22.241  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-29 14:21:22.241  1014  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 14:21:22.241  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
08-29 14:21:22.241  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:22.241  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:22.241  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 14:21:22.241  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:22.241  1014  1487 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:22.241  1014  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:22.241  1014  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 14:21:22.251  1603  1603 I Hs20UtilService: Starting #20
,08-29 14:21:22.251  1603  1624 I Hs20UtilService: Message received 5007
08-29 14:21:22.251  4739  4739 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 14:21:22.251  4739  4739 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-29 14:21:22.251  1014  1124 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-29 14:21:22.261  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling,
08-29 14:21:22.261  1014  1126 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
08-29 14:21:22.261  1014  1126 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
08-29 14:21:22.261  1014  1126 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503,
08-29 14:21:22.261  7898  7898 D AndroidRuntime: 
08-29 14:21:22.261  7898  7898 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-29 14:21:22.261  1014  1126 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 14:21:22.261  1014  1126 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
,08-29 14:21:22.271  1014  1126 D ConnectivityService: LTETest block dns file not exists
08-29 14:21:22.271  7898  7898 D AndroidRuntime: CheckJNI is OFF
08-29 14:21:22.271  7898  7898 D AndroidRuntime: readGMSProperty: start
08-29 14:21:22.271  7898  7898 D AndroidRuntime: readGMSProperty: already setted!!
08-29 14:21:22.271  7898  7898 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-29 14:21:22.271  7898  7898 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-29 14:21:22.271  7898  7898 D AndroidRuntime: readGMSProperty: end
08-29 14:21:22.271  7898  7898 D AndroidRuntime: addProductProperty: start
08-29 14:21:22.271  1170  1170 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 14:21:22.271  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 14:21:22.271  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 14:21:22.271  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:22.271  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:22.271  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 14:21:22.271  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 14:21:22.271  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-29 14:21:22.271  1014  1014 I WifiTrafficPoller: mBoosterFLAG : 0
,08-29 14:21:22.271  1014  1014 I WifiTrafficPoller: current booster mode : FullMode
08-29 14:21:22.271  1014  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 14:21:22.281  1014  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 14:21:22.281  1170  1170 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 14:21:22.281  1014  1484 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 14:21:22.281  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-29 14:21:22.281  1014  1484 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 14:21:22.281  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:22.281  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:22.281  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:22.281  1014  1126 V NetworkStats: updateIfacesLocked()
08-29 14:21:22.281  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:22.281  1014  1126 V NetworkStats: performPollLocked(flags=0x1)
08-29 14:21:22.281  1014  1484 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:22.281  1014  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:22.281  1014  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 14:21:22.281  7083  7083 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-29 14:21:22.281  1014  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 14:21:22.291  1014  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 14:21:22.291  1014  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 14:21:22.291  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 14:21:22.291  7083  7251 I jxcore-log: 
08-29 14:21:22.291  1014  1126 V NetworkStats: performPollLocked() took 4ms
08-29 14:21:22.291  1014  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 14:21:22.301  1014  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
08-29 14:21:22.301  1014  1126 E ConnectivityService: updateNetworkInfo()
08-29 14:21:22.301  1014  1126 E ConnectivityService: updateNetworkInfo()
08-29 14:21:22.301  1014  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-29 14:21:22.301  1014  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:21:22.301  1014  1126 V NetworkStats: updateIfacesLocked()
08-29 14:21:22.301  1014  1126 V NetworkStats: performPollLocked(flags=0x1)
08-29 14:21:22.301  1014  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 14:21:22.301  1014  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 14:21:22.301  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:21:22.301  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:21:22.301  1603  1603 I Hs20UtilService: Starting #21
,08-29 14:21:22.301  1014  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:21:22.301  1014  1126 V NetworkStats: performPollLocked() took 3ms
08-29 14:21:22.301  1603  1624 I Hs20UtilService: Message received 5007
08-29 14:21:22.301  4739  4739 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-29 14:21:22.311  4739  4739 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 14:21:22.311  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:21:22.311  1014  1126 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
08-29 14:21:22.311  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:21:22.311  1014  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
08-29 14:21:22.311  1014  7863 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:22.311  1014  7863 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-29 14:21:22.311  1014  7863 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 14:21:22.311  1014  7863 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-29 14:21:22.311  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-29 14:21:22.311  1014  7863 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-29 14:21:22.311  1014  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-29 14:21:22.311  1014  1126 D ConnectivityService:    accepting network in place of null
08-29 14:21:22.311  1014  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-29 14:21:22.311  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 14:21:22.311  4739  4739 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 14:21:22.311  4739  4739 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 14:21:22.311  4739  4815 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-29 14:21:22.311  1456  1456 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-29 14:21:22.311  1456  1456 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-29 14:21:22.311   277  1006 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 14:21:22.311   277  1006 D Netd    : getNetworkForDns: using netid 503 for uid 1000
08-29 14:21:22.311  1014  1126 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-29 14:21:22.311  1014  1126 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
08-29 14:21:22.311  1014  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-29 14:21:22.321  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE,
,08-29 14:21:22.321  1014  1126 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-29 14:21:22.321  1014  1128 D Tethering: MasterInitialState.processMessage what=3
08-29 14:21:22.321  1014  1121 V NetworkStats: updateIfacesLocked()
08-29 14:21:22.321  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:21:22.321  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
08-29 14:21:22.321  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 14:21:22.321  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 14:21:22.321  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
08-29 14:21:22.321  1014  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,08-29 14:21:22.321  1170  1170 D StatusBar.NetworkController: EthernetConnected: false
08-29 14:21:22.321  1014  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-29 14:21:22.321  1170  1170 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-29 14:21:22.321  1014  1121 V NetworkStats: performPollLocked() took 7ms
08-29 14:21:22.321  1170  1170 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-29 14:21:22.331  1014  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 14:21:22.321  1170  1170 D StatusBar.NetworkController: updateDataNetType()
08-29 14:21:22.331  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 14:21:22.321  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:21:22.321  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:21:22.321  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:21:22.321  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:21:22.331  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:22.331  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:22.331  1014  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-29 14:21:22.331  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 14:21:22.331  1603  1603 I Hs20UtilService: Starting #22
,08-29 14:21:22.331  1170  1759 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 14:21:22.331  1603  1624 I Hs20UtilService: Message received 5007
,08-29 14:21:22.331  1170  1170 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 14:21:22.331  1170  1170 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-29 14:21:22.331  4739  4739 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-29 14:21:22.331  4739  4739 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-29 14:21:22.341  1170  1170 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-29 14:21:22.341  1170  1170 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 19 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-29 14:21:22.341  1170  1170 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-29 14:21:22.341  1170  1170 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-29 14:21:22.341  1170  1170 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 14:21:22.341  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-29 14:21:22.341  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:22.341  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:22.341  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:22.341  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 14:21:22.341  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:21:22.341  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 14:21:22.341  1014  1485 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-29 14:21:22.351  1014  1253 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState,
08-29 14:21:22.351  1014  1253 D SecContentProvider2: mCursor = null
,08-29 14:21:22.351  1014  1027 D SecContentProvider2: uri = 15 selection = getToastGravity
08-29 14:21:22.351  1014  1027 D SecContentProvider2: mCursor = null
08-29 14:21:22.351  1014  1026 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset,
08-29 14:21:22.351  1014  1026 D SecContentProvider2: mCursor = null
,08-29 14:21:22.351  1014  1487 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset,
08-29 14:21:22.351  1014  1487 D SecContentProvider2: mCursor = null
,08-29 14:21:22.361  1014  1208 D SecContentProvider2: uri = 15 selection = getToastEnabledState,
08-29 14:21:22.361  1014  1208 D SecContentProvider2: mCursor = null
,08-29 14:21:22.361  1014  1510 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-29 14:21:22.361  1014  1510 D SecContentProvider2: mCursor = null
,08-29 14:21:22.381   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-29 14:21:22.401  1014  1026 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014
,08-29 14:21:22.401  1170  1170 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-29 14:21:22.411  7898  7898 E AffinityControl: AffinityControl: registerfunction enter
,08-29 14:21:22.411  7083  7083 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 14:21:22.421  7083  7251 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 14:21:22.421  7083  7251 I jxcore-log: 
,08-29 14:21:22.421  1014  7863 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-29 14:21:22.441  7898  7898 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 14:21:22.451  1014  1484 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-29 14:21:22.451  1014  1484 D PackageManager: START PACKAGE DELETE: observer{796851672}
08-29 14:21:22.451  1014  1484 D PackageManager: pkg{<packageName>}
08-29 14:21:22.451  1014  1484 D PackageManager: user{0}
08-29 14:21:22.451  1014  1484 D PackageManager: caller{2000}
08-29 14:21:22.451  1014  1484 D PackageManager: flags{2}
08-29 14:21:22.451  1014  1484 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-29 14:21:22.451  1014  1484 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-29 14:21:22.451  1014  1484 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-29 14:21:22.451  1014  1484 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-29 14:21:22.461  1014  1054 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,08-29 14:21:22.461  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-29 14:21:22.461  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-29 14:21:22.461  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled
,08-29 14:21:22.461  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-29 14:21:22.471  1014  1054 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,08-29 14:21:22.491  1014  1040 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,08-29 14:21:22.491  1014  1040 I ActivityManager: Killing 7083:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-29 14:21:22.491  1014  7863 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 12:21:22 GMT], X-Android-Received-Millis=[1472473282506], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472473282468]}
,08-29 14:21:22.491  1014  7863 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-29 14:21:22.491  1014  7863 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-29 14:21:22.491  1014  1126 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 503]
,08-29 14:21:22.491  1014  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
08-29 14:21:22.491  1014  1126 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,08-29 14:21:22.491  1014  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,08-29 14:21:22.491  1170  1759 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290,
08-29 14:21:22.491  1014  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 14:21:22.571   257  1036 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-29 14:21:22.571  1014  1487 I WindowState: WIN DEATH: Window{2e1e475d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 14:21:22.571   257  1159 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
08-29 14:21:22.571  1014  1487 D InputDispatcher: Focus left window: 7083
,08-29 14:21:22.581  1014  1040 I ActivityManager:   Force finishing activity ActivityRecord{1eef85e3 u0 com.test.thalitest/.MainActivity t163}
,08-29 14:21:22.591  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-29 14:21:22.591  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 14:21:22.611  1014  1040 D InputDispatcher: Focused application released
,08-29 14:21:22.611  1170  1170 D StatusBar.NetworkController: EthernetConnected: false
,08-29 14:21:22.611  1170  1170 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-29 14:21:22.611  1170  1170 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
,08-29 14:21:22.611  1170  1170 D StatusBar.NetworkController: updateDataNetType()
,08-29 14:21:22.621  1014  1054 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-29 14:21:22.621  1170  1170 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 14:21:22.621  1170  1170 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-29 14:21:22.621  1170  1170 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-29 14:21:22.621  1170  1170 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 19 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,08-29 14:21:22.621  1170  1170 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
,08-29 14:21:22.621  1170  1170 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-29 14:21:22.621  1170  1170 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 14:21:22.621  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-29 14:21:22.621  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 14:21:22.621  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 14:21:22.621  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 14:21:22.621  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 14:21:22.631  1014  1054 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-29 14:21:22.661  1014  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 14:21:22.671  1868  1868 E SamsungIME: mOCRHelper is null
,08-29 14:21:22.671  1729  1997 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 14:21:22.671  2847  2847 I art     : Explicit concurrent mark sweep GC freed 17386(1024KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 812us total 35.998ms
,08-29 14:21:22.681  1014  1014 D RCPManagerService: PackageReceiver onReceive()
,08-29 14:21:22.681  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-29 14:21:22.681  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-29 14:21:22.681  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-29 14:21:22.681  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-29 14:21:22.691  1014  1026 W ActivityManager: Spurious death for ProcessRecord{10caa2ab 7083:com.test.thalitest/u0a170}, curProc for 7083: null
,08-29 14:21:22.701  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
,08-29 14:21:22.701  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-29 14:21:22.721  2831  2831 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Aug 29 14:21:22 GMT+02:00 2016
,08-29 14:21:22.731  1014  1121 V NetworkStats: removeUidsLocked() for UIDs [10170]
08-29 14:21:22.731  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 14:21:22.731  1014  1121 V NetworkStats: performPollLocked(flags=0x3)
,08-29 14:21:22.731  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 14:21:22.741  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 14:21:22.741  1014  1121 V NetworkStats: performPollLocked() took 8ms
,08-29 14:21:22.741  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 14:21:22.741  1440  1440 D PersonaManager: isKioskContainerExistOnDevice,
,08-29 14:21:22.751  1014  3867 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-29 14:21:22.751  1014  3867 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-29 14:21:22.751  1014  3867 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:22.751  1014  3867 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:22.751  1014  3867 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-29 14:21:22.751  1440  1440 D RegisteredServicesCache: empty dynamic service
,08-29 14:21:22.761  2831  2831 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-29 14:21:22.761  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 14:21:22.761  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 14:21:22.761  1014  1486 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
08-29 14:21:22.761  1014  1486 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-29 14:21:22.761  1014  1486 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-29 14:21:22.771  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:22.771  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:22.771  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:22.771  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:22.781  7916  7916 E Zygote  : MountEmulatedStorage(),
08-29 14:21:22.781  7916  7916 I libpersona: KNOX_SDCARD checking this for 10090
08-29 14:21:22.781  7916  7916 E Zygote  : v2
,08-29 14:21:22.781  7916  7916 I libpersona: KNOX_SDCARD not a persona
08-29 14:21:22.791  7916  7916 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 14:21:22.791  7916  7916 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-29 14:21:22.791  1014  1486 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7916 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
08-29 14:21:22.791  7916  7916 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-29 14:21:22.801  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,08-29 14:21:22.811  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:22.811  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:22.811  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:22.811  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:22.821  1014  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:21:22.831  7931  7931 E Zygote  : MountEmulatedStorage(),
08-29 14:21:22.831  2831  2831 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
08-29 14:21:22.831  7931  7931 E Zygote  : v2
08-29 14:21:22.831  7931  7931 I libpersona: KNOX_SDCARD checking this for 10052
08-29 14:21:22.831  7931  7931 I libpersona: KNOX_SDCARD not a persona
08-29 14:21:22.831  7931  7931 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 14:21:22.831  1014  1040 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7931 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
08-29 14:21:22.831  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-29 14:21:22.831  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-29 14:21:22.831  7931  7931 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 14:21:22.831  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-29 14:21:22.831  1014  1014 V EnterpriseBillingPolicy: uID is 10170
08-29 14:21:22.831  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
08-29 14:21:22.831  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-29 14:21:22.831  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-29 14:21:22.831  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-29 14:21:22.831  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-29 14:21:22.831  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-29 14:21:22.831  7931  7931 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-29 14:21:22.831  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-29 14:21:22.831  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,08-29 14:21:22.841  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:22.841  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:22.841  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:22.841  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:22.841  2831  2831 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-29 14:21:22.841  7916  7916 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 14:21:22.841  1014  1485 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-29 14:21:22.841  1014  1485 D SecContentProvider2: mCursor = null
08-29 14:21:22.841  7916  7916 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:22.851  7941  7941 E Zygote  : MountEmulatedStorage(),
08-29 14:21:22.851  7941  7941 E Zygote  : v2
08-29 14:21:22.851  7941  7941 I libpersona: KNOX_SDCARD checking this for 10098,
08-29 14:21:22.851  2831  2831 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-29 14:21:22.851  7941  7941 I libpersona: KNOX_SDCARD not a persona
,08-29 14:21:22.861  7941  7941 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 14:21:22.861  7941  7941 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 14:21:22.861  7941  7941 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 14:21:22.861  1014  1040 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7941 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-29 14:21:22.861  7931  7931 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-29 14:21:22.861  7931  7931 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:22.871  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-29 14:21:22.871  2831  7915 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-29 14:21:22.871  2831  7915 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
08-29 14:21:22.871  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:22.871  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:22.871  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:22.871  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:22.871  2831  7915 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-29 14:21:22.881  2831  7915 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-29 14:21:22.881   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 14:21:22.891  7941  7941 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 14:21:22.891  7941  7941 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:22.901  1014  1026 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7961 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-29 14:21:22.901  7961  7961 E Zygote  : MountEmulatedStorage()
08-29 14:21:22.901  7961  7961 I libpersona: KNOX_SDCARD checking this for 10032
08-29 14:21:22.901  7961  7961 E Zygote  : v2
08-29 14:21:22.901  7961  7961 I libpersona: KNOX_SDCARD not a persona
,08-29 14:21:22.901  7961  7961 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 14:21:22.911  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-29 14:21:22.911  7961  7961 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-29 14:21:22.911  1014  1014 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
08-29 14:21:22.911  1014  3374 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-29 14:21:22.911  1014  1160 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,08-29 14:21:22.911  7961  7961 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-29 14:21:22.941  7961  7961 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 14:21:22.951  7961  7961 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:22.961  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-29 14:21:22.961  1014  1014 V EnterpriseBillingPolicy: uID is 10170
08-29 14:21:22.961  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
08-29 14:21:22.961  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-29 14:21:22.961  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-29 14:21:22.961  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-29 14:21:22.961  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-29 14:21:22.961  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-29 14:21:22.961  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-29 14:21:22.961  1440  1440 D RegisteredComponentCache: Collect Tech packages for Knox
,08-29 14:21:22.971  1014  1054 I art     : Explicit concurrent mark sweep GC freed 66439(4MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 23MB/35MB, paused 21.774ms total 281.825ms
,08-29 14:21:22.981  1014  1024 I art     : WaitForGcToComplete blocked for 239.741ms for cause HeapTrim
,08-29 14:21:23.011  1014  1054 D PackageManager: delete codoeFile: 
,08-29 14:21:23.011  1440  1440 D PersonaManager: isKioskContainerExistOnDevice
,08-29 14:21:23.041  2831  7915 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-29 14:21:23.041  1014  3867 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
08-29 14:21:23.041  7916  7916 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-29 14:21:23.041  7916  7916 D elm:15121: ELMEngine.ELMEngine( context ).
08-29 14:21:23.041  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:23.041  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:23.041  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:23.041  1014  1054 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,08-29 14:21:23.041  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:23.041  1014  1054 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
,08-29 14:21:23.041  7916  7916 D elm:15121: MDMBridge.setEnterpriseBridge()
08-29 14:21:23.041  1014  1054 D PackageManager: result of delete: 1{796851672}
,08-29 14:21:23.051  2831  7915 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-29 14:21:23.051  2831  7915 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-29 14:21:23.061  7977  7977 E Zygote  : MountEmulatedStorage()
08-29 14:21:23.061  7977  7977 E Zygote  : v2
08-29 14:21:23.061  7977  7977 I libpersona: KNOX_SDCARD checking this for 1000
08-29 14:21:23.061  7977  7977 I libpersona: KNOX_SDCARD not a persona
08-29 14:21:23.061  7977  7977 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 14:21:23.061  1014  3867 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7977 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-29 14:21:23.061  7977  7977 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 14:21:23.061  7977  7977 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 14:21:23.071  7898  7898 D AndroidRuntime: Shutting down VM
,08-29 14:21:23.071  1014  3867 I ActivityManager: Killing 7433:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-29 14:21:23.071  1014  1253 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-29 14:21:23.071  1014  1253 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-29 14:21:23.071  1014  1253 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:23.071  1014  1253 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:23.071  1014  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-29 14:21:23.081  7916  7916 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-29 14:21:23.091  2831  2831 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-29 14:21:23.101  7916  7916 D elm:15121: ElmAgentService : onCreate()
,08-29 14:21:23.101  7916  7988 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
08-29 14:21:23.101  7916  7988 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-29 14:21:23.101  7916  7988 D elm:15121: MDMBridge.getInstance()
08-29 14:21:23.101  7916  7988 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-29 14:21:23.101  7977  7977 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 14:21:23.101  7977  7977 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:23.101  7916  7988 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-29 14:21:23.111  1014  1054 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-29 14:21:23.111  1014  1054 D PackageManager: userId{-1}
08-29 14:21:23.111  1014  1054 D PackageManager: andCode{true}
,08-29 14:21:23.111  7961  7994 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-29 14:21:23.111  1014  1054 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-29 14:21:23.111  7961  7994 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-29 14:21:23.121  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:23.121  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:23.121  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:23.121  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:23.131  7997  7997 E Zygote  : MountEmulatedStorage(),
08-29 14:21:23.131  7997  7997 I libpersona: KNOX_SDCARD checking this for 10003
,08-29 14:21:23.131  7997  7997 E Zygote  : v2
08-29 14:21:23.131  7997  7997 I libpersona: KNOX_SDCARD not a persona,
08-29 14:21:23.131  7997  7997 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 14:21:23.131  7997  7997 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 14:21:23.141  7997  7997 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 14:21:23.141  7961  7994 D SPPClientService: PushLog.txt file is not deleted.
08-29 14:21:23.141  7961  7994 D SPPClientService: PushLog.txt file is not deleted.
08-29 14:21:23.141  7961  7994 D SPPClientService: ============PushLog. stop!
,08-29 14:21:23.141  1014  1054 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7997 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-29 14:21:23.141  1014  1484 I ActivityManager: Killing 7450:com.sec.android.diagmonagent/1000 (adj 15): empty #21
08-29 14:21:23.151  7916  7916 D elm:15121: ElmAgentService : onDestroy().
,08-29 14:21:23.171  2635  2635 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
08-29 14:21:23.171  2635  2635 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-29 14:21:23.171  1014  1484 I ActivityManager: Killing 7467:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-29 14:21:23.171  7997  7997 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 14:21:23.171  1014  1336 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-29 14:21:23.171  1014  1336 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-29 14:21:23.171   305   305 I art     : Explicit concurrent mark sweep GC freed 8689(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 963us total 35.934ms
,08-29 14:21:23.171  7997  7997 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:23.171  1014  1336 W ActivityManager: userId = 0, bbcId = -10000
,08-29 14:21:23.181  1014  1336 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:21:23.181  1014  1336 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-29 14:21:23.181  1014  1253 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
,08-29 14:21:23.181  1014  1253 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,08-29 14:21:23.181  1014  1253 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:23.181  1014  1253 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:23.181  1014  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,08-29 14:21:23.191   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 614us total 16.779ms
,08-29 14:21:23.191  1014  1510 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-29 14:21:23.191  1014  1510 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-29 14:21:23.191  1014  1510 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:23.191  1014  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:21:23.191  1014  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-29 14:21:23.211   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.634ms total 17.713ms
,08-29 14:21:23.211  1014  1253 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,08-29 14:21:23.211  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:23.211  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:23.211  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:23.211  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:23.221  1014  1039 D EnterpriseDeviceManagerService: Package has changed for user 0
08-29 14:21:23.221  1014  1039 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-29 14:21:23.221  1014  1039 W TextServicesManagerService: no available spell checker services found
,08-29 14:21:23.231  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 14:21:23.231  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 14:21:23.241  8016  8016 E Zygote  : MountEmulatedStorage()
08-29 14:21:23.241  8016  8016 E Zygote  : v2
08-29 14:21:23.241  8016  8016 I libpersona: KNOX_SDCARD checking this for 10039
,08-29 14:21:23.241  8016  8016 I libpersona: KNOX_SDCARD not a persona
08-29 14:21:23.241  8016  8016 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 14:21:23.241  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 14:21:23.241  8016  8016 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 14:21:23.241  1014  1253 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=8016 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-29 14:21:23.241  8016  8016 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 14:21:23.251  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 14:21:23.251  1014  1054 W PackageManager: Package named 'com.test.thalitest' doesn't exist.
08-29 14:21:23.251  1014  1054 I PackageManager: Observer no longer exists.
08-29 14:21:23.251  1014  1054 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,08-29 14:21:23.251  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 14:21:23.251  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
08-29 14:21:23.251  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:23.251  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:21:23.251  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:21:23.261  1932  8025 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-29 14:21:23.261  1932  8025 D AccountUtils: Clearing selected account for com.test.thalitest
,08-29 14:21:23.271  7748  7748 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,08-29 14:21:23.271  1014  1253 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,08-29 14:21:23.271  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:23.271  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:23.271  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:23.271  1014  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:23.281  7898  7898 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-29 14:21:23.291  8033  8033 E Zygote  : MountEmulatedStorage()
08-29 14:21:23.291  8033  8033 I libpersona: KNOX_SDCARD checking this for 1000
08-29 14:21:23.291  8033  8033 E Zygote  : v2
08-29 14:21:23.291  8033  8033 I libpersona: KNOX_SDCARD not a persona
,08-29 14:21:23.291  8033  8033 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 14:21:23.291  1014  1253 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8033 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-29 14:21:23.301  8016  8016 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 14:21:23.301  8016  8016 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:23.301  8033  8033 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 14:21:23.301  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 14:21:23.311  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:23.311  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:21:23.311  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:21:23.321  8033  8033 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 14:21:23.321  1014  1126 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-29 14:21:23.331  1014  7976 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,08-29 14:21:23.331  1014  7976 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:23.331  1014  7976 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:23.331  1014  7976 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:23.331  1014  7976 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:23.351  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,08-29 14:21:23.351  8050  8050 E Zygote  : MountEmulatedStorage(),
08-29 14:21:23.351  8050  8050 I libpersona: KNOX_SDCARD checking this for 1000
08-29 14:21:23.351  8050  8050 E Zygote  : v2
08-29 14:21:23.351  8050  8050 I libpersona: KNOX_SDCARD not a persona
08-29 14:21:23.351  8050  8050 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 14:21:23.351  8050  8050 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 14:21:23.351  8050  8050 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 14:21:23.361  8033  8033 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 14:21:23.361  1014  7976 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=8050 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-29 14:21:23.361  8033  8033 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:23.361  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,08-29 14:21:23.361  8016  8016 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-29 14:21:23.361  8016  8016 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 14:21:23.361  8016  8016 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 14:21:23.371  8016  8016 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,08-29 14:21:23.371  8016  8016 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-29 14:21:23.371  8016  8016 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-29 14:21:23.371  8016  8016 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-29 14:21:23.371  1014  1510 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 14:21:23.371  1014  1510 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
,08-29 14:21:23.371  1014  1510 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:23.371  1014  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:21:23.371  1014  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,08-29 14:21:23.381  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
08-29 14:21:23.381  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,08-29 14:21:23.381  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-29 14:21:23.381  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,08-29 14:21:23.381  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,08-29 14:21:23.381  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
08-29 14:21:23.381  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
08-29 14:21:23.381  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
08-29 14:21:23.381  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-29 14:21:23.381  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-29 14:21:23.381  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-29 14:21:23.381  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-29 14:21:23.381  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
08-29 14:21:23.381  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
08-29 14:21:23.381  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
08-29 14:21:23.381  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-29 14:21:23.381  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,08-29 14:21:23.381  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-29 14:21:23.381  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-29 14:21:23.381  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
08-29 14:21:23.381  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
08-29 14:21:23.381  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,08-29 14:21:23.381  1932  8025 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-29 14:21:23.391  1014  1485 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-29 14:21:23.391  1014  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,08-29 14:21:23.391  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:23.391  1014  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:21:23.391  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:21:23.411  7748  7748 D BluetoothAdapter: cancelDiscovery
08-29 14:21:23.411  8050  8050 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 14:21:23.411  1014  1039 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
08-29 14:21:23.411  3235  7773 D BluetoothAdapterProperties: mDiscovering is false
08-29 14:21:23.411  3235  7773 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
08-29 14:21:23.411  8050  8050 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:23.411  7748  7748 D BluetoothAdapter: cancelDiscovery = true
08-29 14:21:23.411  7748  7748 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
08-29 14:21:23.411  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 14:21:23.421  1014  1208 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-29 14:21:23.421  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-29 14:21:23.421  7748  7748 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-29 14:21:23.421  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 14:21:23.421  1014  1253 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 14:21:23.421  1014  1253 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:23.421  1014  1253 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:21:23.421  1014  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:21:23.431  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 14:21:23.431  1014  1485 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 14:21:23.431  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:23.431  1014  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
08-29 14:21:23.431  1014  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:21:23.431  8033  8033 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
08-29 14:21:23.431  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-29 14:21:23.431  1014  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:23.431  1014  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:23.431  1014  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:23.431  1014  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:23.441  8050  8050 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 14:21:23.441  8066  8066 E Zygote  : MountEmulatedStorage()
,08-29 14:21:23.441  8066  8066 E Zygote  : v2
08-29 14:21:23.441  8066  8066 I libpersona: KNOX_SDCARD checking this for 10011
08-29 14:21:23.441  8066  8066 I libpersona: KNOX_SDCARD not a persona
,08-29 14:21:23.441  8066  8066 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 14:21:23.441  1014  1485 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=8066 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-29 14:21:23.451  1014  3867 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
08-29 14:21:23.451  1014  3867 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,08-29 14:21:23.451  1014  3867 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:23.451  1014  3867 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 14:21:23.451  1014  3867 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,08-29 14:21:23.451  8066  8066 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 14:21:23.451  8066  8066 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 14:21:23.461  1014  3867 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,08-29 14:21:23.471  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:23.471  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:23.471  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 14:21:23.471  1014  3867 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 14:21:23.491  8083  8083 E Zygote  : MountEmulatedStorage()
,08-29 14:21:23.491  8083  8083 E Zygote  : v2
08-29 14:21:23.491  8083  8083 I libpersona: KNOX_SDCARD checking this for 1000
08-29 14:21:23.491  8083  8083 I libpersona: KNOX_SDCARD not a persona,
,08-29 14:21:23.491  8083  8083 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 14:21:23.501  1014  3867 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=8083 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
08-29 14:21:23.501  8083  8083 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 14:21:23.501  8083  8083 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 14:21:23.501  1014  1039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-29 14:21:23.501  1014  1039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 14:21:23.501  1014  1039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 14:21:23.501  8066  8066 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 14:21:23.511  8066  8066 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:23.511  1932  8074 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
08-29 14:21:23.511  1932  8074 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,08-29 14:21:23.511  1932  8074 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
08-29 14:21:23.511  1014  1510 I ActivityManager: Killing 7484:com.sec.android.soagent/u0a31 (adj 15): empty #21
08-29 14:21:23.511  1932  8074 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,08-29 14:21:23.541  8083  8083 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 14:21:23.541  1932  8074 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/databases/help_responses.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,08-29 14:21:23.541  1932  8074 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
08-29 14:21:23.541  1932  8074 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,08-29 14:21:23.541  1932  8074 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-29 14:21:23.541  1932  8074 E SQLiteLog: (3850) statement aborts at 21: [DELETE FROM help_responses WHERE app_package_name="com.test.thalitest"] disk I/O error
08-29 14:21:23.541  1932  8074 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,08-29 14:21:23.541  8083  8083 D ActivityThread: Added TimaKeyStore provider
,08-29 14:21:23.551  8066  8066 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-29 14:21:23.551  8066  8066 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-29 14:21:23.561  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 14:21:23.571  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-29 14:21:23.571  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 14:21:23.571  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 14:21:23.571  8016  8016 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)
,08-29 14:21:23.571  1932  8074 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
08-29 14:21:23.571  1932  8074 E AndroidRuntime: Process: com.google.android.gms, PID: 1932
08-29 14:21:23.571  1932  8074 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 14:21:23.571  1932  8074 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 14:21:23.571  1932  8074 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
08-29 14:21:23.571  1932  8074 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 14:21:23.571  1932  8074 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 14:21:23.571  1932  8074 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
08-29 14:21:23.571  1932  8074 E AndroidRuntime: 	at com.google.android.gms.googlehelp.c.b.d(SourceFile:535)
08-29 14:21:23.571  1932  8074 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:52)
08-29 14:21:23.571  1932  8074 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-29 14:21:23.571  1932  8074 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:21:23.571  1932  8074 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-29 14:21:23.571  1932  8074 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 14:21:23.571  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.gallery3d/databases/picasa.db'.
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider$SyncContext.<init>(PicasaContentProvider.java:911)
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider.attachInfo(PicasaContentProvider.java:103)
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 14:21:23.571  8016  8016 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-29 14:21:23.571  3235  3313 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-29 14:21:23.581  1014  1026 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,08-29 14:21:23.601  8050  8050 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/history.db" with flag (131138) and mode_t (0) due to error (30)
,08-29 14:21:23.601  8066  8066 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-29 14:21:23.601  8066  8066 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-29 14:21:23.611  1014  8105 E DropBoxManagerService: Can't write: system_app_crash
08-29 14:21:23.611  1014  8105 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop191.tmp: open failed: EROFS (Read-only file system)
08-29 14:21:23.611  1014  8105 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-29 14:21:23.611  1014  8105 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 14:21:23.611  1014  8105 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 14:21:23.611  1014  8105 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 14:21:23.611  1014  8105 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-29 14:21:23.611  1014  8105 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
08-29 14:21:23.611  1014  8105 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 14:21:23.611  1014  8105 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 14:21:23.611  1014  8105 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 14:21:23.611  1014  8105 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-29 14:21:23.611  1014  8105 E DropBoxManagerService: 	... 5 more
,08-29 14:21:23.611  8066  8066 I MultiDex: VM with version 2.1.0 has multidex support
08-29 14:21:23.611  8066  8066 I MultiDex: install
08-29 14:21:23.611  8066  8066 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-29 14:21:23.611  1014  3867 D LocationManagerService: getProviders()=[passive, gps]
,08-29 14:21:23.611  8050  8050 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/history.db'.
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:159)
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:66)
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 14:21:23.611  8050  8050 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-29 14:21:23.611  8050  8050 D AndroidRuntime: Shutting down VM
,08-29 14:21:23.621  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 14:21:23.621  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 14:21:23.621  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 14:21:23.621  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-29 14:21:23.631  8050  8050 E AndroidRuntime: FATAL EXCEPTION: main
08-29 14:21:23.631  8050  8050 E AndroidRuntime: Process: com.samsung.android.sm, PID: 8050
08-29 14:21:23.631  8050  8050 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.samsung.android.sm.ui.security.MonitorReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3132)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:159)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:66)
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125),
08-29 14:21:23.631  8050  8050 E AndroidRuntime: 	... 9 more
08-29 14:21:23.631  1932  8074 I Process : Sending signal. PID: 1932 SIG: 9
,08-29 14:21:23.631  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 14:21:23.631  1014  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sm
,08-29 14:21:23.631  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 14:21:23.631  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}

```
