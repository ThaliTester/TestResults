#### Test 830701775d60530_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
09-12 14:41:39.244  6958  6958 E Zygote  : MountEmulatedStorage()
09-12 14:41:39.244  6958  6958 E Zygote  : v2
--------- beginning of system
09-12 14:41:39.244  1019  4367 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=6958 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
09-12 14:41:39.244  6958  6958 I libpersona: KNOX_SDCARD checking this for 10041
09-12 14:41:39.244  6958  6958 I libpersona: KNOX_SDCARD not a persona
09-12 14:41:39.254  6958  6958 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 14:41:39.254  6958  6958 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 14:41:39.254  6916  6916 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-12 14:41:39.254  6958  6958 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-12 14:41:39.254  1019  4367 I ActivityManager: Killing 6514:com.wsomacp/u0a23 (adj 15): empty #21
09-12 14:41:39.274  1639  1670 I art     : Explicit concurrent mark sweep GC freed 14325(680KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 8MB/13MB, paused 1.020ms total 65.936ms
09-12 14:41:39.274  6916  6916 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-12 14:41:39.274  6958  6958 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 14:41:39.274  6958  6958 D ActivityThread: Added TimaKeyStore provider
09-12 14:41:39.304  6938  6938 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
09-12 14:41:39.314  1019  3798 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
09-12 14:41:39.324  1019  3798 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:39.324  1019  3798 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:39.324  1019  3798 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:39.324  1019  3798 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:39.334  6958  6958 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
09-12 14:41:39.334  6958  6958 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 14:41:39.334  6958  6958 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 14:41:39.334  6958  6958 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-12 14:41:39.334  6958  6958 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
09-12 14:41:39.334  6978  6978 E Zygote  : MountEmulatedStorage()
09-12 14:41:39.334  6978  6978 I libpersona: KNOX_SDCARD checking this for 1000
09-12 14:41:39.334  6978  6978 E Zygote  : v2
09-12 14:41:39.334  6978  6978 I libpersona: KNOX_SDCARD not a persona
09-12 14:41:39.334  6978  6978 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 14:41:39.344  1019  3798 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=6978 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-12 14:41:39.344  1019  3798 I ActivityManager: Killing 6531:com.sec.esdk.elm/u0a90 (adj 15): empty #21
09-12 14:41:39.344  6978  6978 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 14:41:39.354  6978  6978 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 14:41:39.354  1019  4368 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-12 14:41:39.354  1019  4368 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:39.354  1019  4368 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:39.354  1019  4368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
09-12 14:41:39.364  3862  6825 W BaseAppContext: Using Auth Proxy for data requests.
09-12 14:41:39.364  1019  1499 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 14:41:39.364  1019  1499 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-12 14:41:39.364  1019  1499 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:39.364  1019  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:39.364  1019  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-12 14:41:39.374  6978  6978 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 14:41:39.374  6978  6978 D ActivityThread: Added TimaKeyStore provider
09-12 14:41:39.394  3862  6825 W BaseAppContext: Using Auth Proxy for data requests.
09-12 14:41:39.394  6978  6978 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
09-12 14:41:39.414  6916  6916 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
09-12 14:41:39.414  6958  6958 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
09-12 14:41:39.424  1019  1266 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-12 14:41:39.424  1019  1266 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:39.424  1019  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:39.424  1019  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-12 14:41:39.424  6916  6916 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-12 14:41:39.454  1019  4368 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 14:41:39.454  1019  4368 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-12 14:41:39.454  1019  4368 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:39.454  1019  4368 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:39.454  1019  4368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-12 14:41:39.464  3862  6825 W BaseAppContext: Using Auth Proxy for data requests.
09-12 14:41:39.614  1019  1341 I art     : Explicit concurrent mark sweep GC freed 20989(1186KB) AllocSpace objects, 1(22KB) LOS objects, 33% free, 23MB/34MB, paused 3.008ms total 145.581ms
09-12 14:41:39.614  1019  1341 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-12 14:41:39.614  6994  6994 D AndroidRuntime: 
09-12 14:41:39.614  6994  6994 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-12 14:41:39.624  6994  6994 D AndroidRuntime: CheckJNI is OFF
09-12 14:41:39.624  6994  6994 D AndroidRuntime: readGMSProperty: start
09-12 14:41:39.624  6994  6994 D AndroidRuntime: readGMSProperty: already setted!!
09-12 14:41:39.624  6994  6994 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-12 14:41:39.624  6994  6994 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-12 14:41:39.624  6994  6994 D AndroidRuntime: readGMSProperty: end
09-12 14:41:39.624  6994  6994 D AndroidRuntime: addProductProperty: start
09-12 14:41:39.624  1019  1341 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:39.624  1019  1341 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:39.624  1019  1341 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-12 14:41:39.634  1019  3798 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
09-12 14:41:39.634  3862  6796 I qtaguid : Untagging socket 89
09-12 14:41:39.634  1019  3798 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:39.634  1019  3798 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:39.634  1019  3798 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:39.634  1019  3798 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:39.634  3862  3862 I ConfigFetchService: fetch service done; releasing wakelock
09-12 14:41:39.654  1019  3798 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7001 uid=10152 gids={50152, 9997} abi=armeabi-v7a
09-12 14:41:39.654  7001  7001 E Zygote  : MountEmulatedStorage()
09-12 14:41:39.654  7001  7001 E Zygote  : v2
09-12 14:41:39.654  7001  7001 I libpersona: KNOX_SDCARD checking this for 10152
09-12 14:41:39.654  3862  3862 I ConfigFetchService: stopping self
09-12 14:41:39.654  7001  7001 I libpersona: KNOX_SDCARD not a persona
09-12 14:41:39.654  7001  7001 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 14:41:39.654  1019  3798 I ActivityManager: Killing 6550:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
09-12 14:41:39.654  7001  7001 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 14:41:39.664  7001  7001 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 14:41:39.704  7001  7001 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 14:41:39.704  7001  7001 D ActivityThread: Added TimaKeyStore provider
09-12 14:41:39.704  6958  6958 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 224.859ms
09-12 14:41:39.714  1019  1489 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-12 14:41:39.714  1019  1489 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:39.714  1019  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:39.714  1019  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
09-12 14:41:39.754  6916  6916 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-12 14:41:39.754  6916  6916 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-12 14:41:39.754  6916  6916 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-12 14:41:39.764  6916  6916 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-12 14:41:39.784  6916  6916 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-12 14:41:39.784  6916  6916 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-12 14:41:39.784  6916  6916 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-12 14:41:39.784  6724  6795 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 807 ms] updated apps [took 807 ms] 
09-12 14:41:39.784  6916  6916 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-12 14:41:39.784  1019  1341 I ActivityManager: Killing 6581:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
09-12 14:41:39.784  6916  6916 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-12 14:41:39.794  6994  6994 E AffinityControl: AffinityControl: registerfunction enter
09-12 14:41:39.794  6916  6916 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-12 14:41:39.794  6916  6916 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-12 14:41:39.804  7001  7001 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
09-12 14:41:39.804  7001  7001 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
09-12 14:41:39.814  6916  6916 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-12 14:41:39.814  6916  6916 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-12 14:41:39.814  6916  6916 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-12 14:41:39.824  6916  6916 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-12 14:41:39.824  6994  6994 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-12 14:41:39.824  7001  7001 I TapandpayWidget:Utils: Clear T&P info.
09-12 14:41:39.824  6916  6916 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-12 14:41:39.824  6916  6916 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
09-12 14:41:39.834  7001  7001 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
09-12 14:41:39.834  1019  1499 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
09-12 14:41:39.844  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:39.844  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:39.844  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:39.844  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:39.844  1019  1341 E PersonaManagerService: inState():  stateMachine is null !!
09-12 14:41:39.844  1019  1341 I PersonaManagerService: PersonaId don't exist
09-12 14:41:39.844  1019  1341 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-12 14:41:39.864  6916  6916 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-12 14:41:39.864  6916  6916 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-12 14:41:39.874  1019  1499 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7038 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
09-12 14:41:39.874  6958  6958 W art     : Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 172.265ms
09-12 14:41:39.874  1019  1499 I ActivityManager: Killing 6597:com.qualcomm.timeservice/1000 (adj 15): empty #21
09-12 14:41:39.874  7038  7038 E Zygote  : MountEmulatedStorage()
09-12 14:41:39.884  7038  7038 E Zygote  : v2
09-12 14:41:39.884  7038  7038 I libpersona: KNOX_SDCARD checking this for 10009
09-12 14:41:39.884  7038  7038 I libpersona: KNOX_SDCARD not a persona
09-12 14:41:39.884  7038  7038 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 14:41:39.884  6958  7044 D Mms/ArtClassLoader: init before art
09-12 14:41:39.884  7038  7038 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 14:41:39.884  7038  7038 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-12 14:41:39.894  6958  6958 D Mms/TelephonyPermission: start operation mode monitor
09-12 14:41:39.924  1019  1341 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-12 14:41:39.924  6916  6916 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-12 14:41:39.924  6916  6916 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-12 14:41:39.924  6916  6916 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-12 14:41:39.924  7038  7038 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 14:41:39.924  7038  7038 D ActivityThread: Added TimaKeyStore provider
09-12 14:41:39.934  6958  6958 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-12 14:41:39.944  1019  1341 W ActivityManager: mDVFSHelper.acquire()
09-12 14:41:39.944  1019  1341 D FocusedStackFrame: Set to : 0
09-12 14:41:39.964  1019  1341 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:39.964  1019  1341 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:39.964  1019  1341 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:39.964  1019  1341 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:39.964  1019  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-12 14:41:39.964  1019  1049 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-12 14:41:39.984  7055  7055 E Zygote  : MountEmulatedStorage()
09-12 14:41:39.984  7055  7055 E Zygote  : v2
09-12 14:41:39.984  7055  7055 I libpersona: KNOX_SDCARD checking this for 10170
09-12 14:41:39.984  7055  7055 I libpersona: KNOX_SDCARD not a persona
09-12 14:41:39.984  7055  7055 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 14:41:39.984  1019  1341 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-12 14:41:39.984  1019  1341 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7055 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-12 14:41:39.984  1019  1341 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-12 14:41:39.984  1019  1341 D InputDispatcher: Focused application set to: xxxx
09-12 14:41:39.984  1019  1341 D InputDispatcher: Focus left window: 1488
09-12 14:41:39.984  7055  7055 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 14:41:39.984  6994  6994 D AndroidRuntime: Shutting down VM
09-12 14:41:39.994  7055  7055 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-12 14:41:39.994  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-12 14:41:39.994  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-12 14:41:39.994   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
09-12 14:41:39.994  1019  1347 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
09-12 14:41:40.014  7055  7055 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 14:41:40.014  7055  7055 D ActivityThread: Added TimaKeyStore provider
09-12 14:41:40.024  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-12 14:41:40.024  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
09-12 14:41:40.024  1019  1032 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-12 14:41:40.034  1019  1019 V ActivityManager: Display changed displayId=0
09-12 14:41:40.034  6958  6958 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
09-12 14:41:40.034  6958  6958 D Mms/TelephonyPermission: isDefault true
09-12 14:41:40.054  6958  6958 D Mms/MmsApp: onCreate() com.android.mms
09-12 14:41:40.064  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-12 14:41:40.094  1019  1032 D PersonaManager: isKioskContainerExistOnDevice
09-12 14:41:40.104  1019  1504 I ActivityManager: Killing 6560:com.android.providers.calendar/u0a37 (adj 15): empty #21
09-12 14:41:40.124  6958  6958 D Mms/MmsApp: [start]    initCountryIso consume time = 701.810521
09-12 14:41:40.124   259  1100 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
09-12 14:41:40.124  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-12 14:41:40.124   259   444 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
09-12 14:41:40.134  6916  6916 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
09-12 14:41:40.134  1019  1341 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
09-12 14:41:40.134  1488  1488 V ActivityThread: updateVisibility : ActivityRecord{326e60d token=android.os.BinderProxy@1588b54a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-12 14:41:40.134  1488  1488 D Launcher: onTrimMemory. Level: 20
09-12 14:41:40.134  1019  1341 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
09-12 14:41:40.134  1019  1341 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:40.134  1019  1341 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:40.134  1019  1341 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
09-12 14:41:40.154  1019  1031 D CountryDetector: The first listener is added
09-12 14:41:40.164  6916  6916 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
09-12 14:41:40.174  6958  6958 D Mms/MmsApp: [end]    initCountryIso consume time = 49.20875
09-12 14:41:40.174  6958  6958 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.123021
09-12 14:41:40.184  6958  6958 D Mms/MmsConfig: before partial update
09-12 14:41:40.194  6994  6994 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-12 14:41:40.194  6916  7076 D Ads     : Skipping gmscore version check
,09-12 14:41:40.204  6958  6958 D Mms/MmsConfig: Load Resize quality : 80
09-12 14:41:40.214  1019  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-12 14:41:40.224  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:40.224  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:40.224  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
09-12 14:41:40.224  6958  6958 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
09-12 14:41:40.234  6958  6958 D EasySignUpManager_1.0.1: isAuth is false
09-12 14:41:40.234  6958  6958 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
09-12 14:41:40.264  1452  1481 D TP/MmsSmsProvider: query,matched:2117, calling pid = 6958
09-12 14:41:40.264  1452  1481 D TP/MmsSmsProvider: match 2117:Elapsed time : 3.275 ms
09-12 14:41:40.274  3862  6825 W art     : Verification of void com.google.android.gms.games.broker.GameAgent.addGameBadgeOps(com.google.android.gms.common.internal.ClientContext, com.google.android.gms.games.server.api.MarketInstance, java.lang.String, java.util.ArrayList, int) took 119.704ms
09-12 14:41:40.274  1019  3798 I ActivityManager: Killing 6239:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
09-12 14:41:40.284  6958  6958 D EasySignUpManager_1.0.1: isAuth is false
09-12 14:41:40.284  6958  6958 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
09-12 14:41:40.284  6958  6958 E CscParser: mps_code.dat does not exist
09-12 14:41:40.284  6958  6958 E CscParser: customer_path =/system/csc/customer.xml
09-12 14:41:40.284  6958  6958 E CscParser: fileName + /system/csc/customer.xml
09-12 14:41:40.294  7055  7055 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
09-12 14:41:40.304  6916  6916 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-12 14:41:40.314  7055  7055 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 9975-9978)
09-12 14:41:40.314  7055  7055 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-12 14:41:40.324  6833  6913 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-12 14:41:40.324  6833  6913 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-12 14:41:40.324  6833  6913 I GAv4    :   adb logcat -s GAv4
09-12 14:41:40.324  6958  6958 E CscParser: mps_code.dat does not exist
09-12 14:41:40.324  6958  6958 E CscParser: customer_path =/system/csc/customer.xml
09-12 14:41:40.324  6958  6958 E CscParser: fileName + /system/csc/customer.xml
09-12 14:41:40.334  6958  6958 D CscParser: getInstance fileName =/system/csc/customer.xml
09-12 14:41:40.344  6958  6958 D Mms/MmsConfig:  enable multiwindow = false
09-12 14:41:40.354  6958  6958 E Mms/MessageUtils: setCountryDetector : update country detector info 
09-12 14:41:40.354  6958  6958 E Mms/MessageUtils: updateCountryIso : update country iso info 
09-12 14:41:40.354  6958  6958 D Mms/MmsConfig: [end]    init() consume time = 188.868698
09-12 14:41:40.364  6958  6958 D Mms/Contact: [start]    init() consume time = 1.129531
09-12 14:41:40.374  6833  6913 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
09-12 14:41:40.374  1019  1504 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
09-12 14:41:40.384  1452  6619 D TP/MmsSmsProvider: query,matched:13, calling pid = 6958
09-12 14:41:40.384  1452  6619 D TP/MmsSmsProvider: match 13:Elapsed time : 1.211 ms
09-12 14:41:40.394  7055  7055 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {22ba5468}
09-12 14:41:40.394  7055  7055 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-12 14:41:40.394  7055  7055 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
09-12 14:41:40.394  6958  6958 D Mms/Contact: [end]    init consume time = 37.501146
09-12 14:41:40.424  6833  6913 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
09-12 14:41:40.434  6958  7085 D Mms/DraftCache: [start]    rebuildCache consume time = 36.480573
09-12 14:41:40.444  1452  1702 D TP/MmsSmsProvider: query,matched:12, calling pid = 6958
09-12 14:41:40.444  1452  1702 D TP/MmsSmsProvider: match 12:Elapsed time : 0.944 ms
09-12 14:41:40.454  6958  7085 D Mms/DraftCache: [end]    rebuildCache consume time = 16.901093
09-12 14:41:40.454  6833  7087 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
09-12 14:41:40.454  7055  7055 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
09-12 14:41:40.464  7055  7055 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-12 14:41:40.464  6833  6913 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
09-12 14:41:40.464  6958  6958 D Mms/MethodReflector: getSubId is called
09-12 14:41:40.464  6958  6958 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
09-12 14:41:40.464  6958  6958 D Mms/MethodReflector: getTelephonyProperty is called
09-12 14:41:40.464  6958  6958 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-12 14:41:40.464  6958  6958 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-12 14:41:40.464  6958  6958 D Mms/DownloadManager: auto download without roaming -> true
09-12 14:41:40.464  6958  6958 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
09-12 14:41:40.464  6958  6958 D Mms/MethodReflector: getSubId is called
09-12 14:41:40.464  6958  6958 D Mms/MethodReflector: getDefaultSmsSubId is called
09-12 14:41:40.464  6958  6958 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
09-12 14:41:40.464  6958  6958 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
09-12 14:41:40.464  6958  6958 D Mms/MethodReflector: getTelephonyProperty is called
09-12 14:41:40.464  6958  6958 D Mms/DownloadManager: roaming -> false (slotId = 1)
09-12 14:41:40.464  6958  6958 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
09-12 14:41:40.464  6958  6958 D Mms/DownloadManager: auto download without roaming -> true
09-12 14:41:40.464  6958  6958 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
09-12 14:41:40.464  6958  6958 D Mms/DownloadManager: auto download during roaming secondary -> false
09-12 14:41:40.464  6958  6958 D Mms/DownloadManager: mAutoDownload ------> true
09-12 14:41:40.474  7055  7055 E SysUtils: ApplicationContext is null in ApplicationStatus
09-12 14:41:40.534  6958  6958 D ComposerPerformance: 1473684100548 ms / [DONE] Composer constructor
09-12 14:41:40.534  6958  6958 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
09-12 14:41:40.534  6958  6958 I Mms/ReservationManager: ReservationManager()
09-12 14:41:40.554  6958  6958 I Mms/ReservationManager: resetAfterConnected()
09-12 14:41:40.554  1452  4774 D TP/MmsSmsProvider: query,matched:7, calling pid = 6958
09-12 14:41:40.554  6958  7089 D Mms/Conversation: [start]    init() consume time = 102.873021
09-12 14:41:40.554  1452  4774 D TP/MmsSmsProvider: match 7:Elapsed time : 2.496 ms
09-12 14:41:40.554  1452  1702 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
09-12 14:41:40.554  1452  1702 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
09-12 14:41:40.554  1452  1702 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
09-12 14:41:40.554  1452  1702 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
09-12 14:41:40.564  7055  7055 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-12 14:41:40.564  7055  7055 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-12 14:41:40.564  7055  7055 I Adreno-EGL: Build Date: 04/06/15 Mon
09-12 14:41:40.564  7055  7055 I Adreno-EGL: Local Branch: 
09-12 14:41:40.564  7055  7055 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-12 14:41:40.564  7055  7055 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-12 14:41:40.564  7055  7055 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
09-12 14:41:40.564  1452  1702 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
09-12 14:41:40.564  1452  1702 D TP/MmsSmsProvider: need read changed broadcast:false
09-12 14:41:40.564  6958  7089 D Mms/Conversation: [end]    init consume time = 12.913959
09-12 14:41:40.564  6958  7089 D Mms/MessagingNotification: [start]    init() consume time = 2.629218
09-12 14:41:40.574  6958  7044 D Mms/ArtClassLoader: init [DONE] art
09-12 14:41:40.584  6958  7089 D Mms/MessagingNotification: [end]    init consume time = 10.359844
09-12 14:41:40.584  6958  6958 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
09-12 14:41:40.584  1452  2463 D TP/MmsSmsProvider: query,matched:0, calling pid = 6958
09-12 14:41:40.584  1452  2463 V TP/MmsSmsProvider: getSimpleConversations entered.
09-12 14:41:40.584  1452  2463 D TP/MmsSmsProvider: match 0:Elapsed time : 0.949 ms
09-12 14:41:40.584  6958  6958 D Mms/MmsApp: [end]    onCreate() consume time = 9.250521
09-12 14:41:40.594  1019  1044 W ActivityManager: Activity pause timeout for ActivityRecord{2fe5e55a u0 com.test.thalitest/.MainActivity t163}
09-12 14:41:40.604  6958  7096 D Mms/Synchronizer: [start]    doSync consume time = 11.31776
09-12 14:41:40.604  6958  7095 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 0.994479
09-12 14:41:40.614  1452  6619 D TP/MmsSmsProvider: update, matched:300, calling pid = 6958
09-12 14:41:40.614  1452  6619 V TP/MmsSmsProvider: syncDBData start
09-12 14:41:40.614  1452  6619 V TP/MmsSmsProvider: syncDBData sms end
09-12 14:41:40.614  1452  6619 V TP/MmsSmsProvider: syncDBData mms end
09-12 14:41:40.614  1452  6619 V TP/MmsSmsProvider: syncDBData end
09-12 14:41:40.624  6958  6958 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
09-12 14:41:40.624  6958  6958 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
09-12 14:41:40.624  6958  6958 D Mms/MethodReflector: getSubId is called
09-12 14:41:40.624  6958  6958 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
09-12 14:41:40.624  6958  6958 D Mms/MethodReflector: getTelephonyProperty is called
09-12 14:41:40.624  6958  6958 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-12 14:41:40.624  6958  6958 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-12 14:41:40.624  6958  6958 D Mms/DownloadManager: auto download without roaming -> true
09-12 14:41:40.624  6958  6958 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
09-12 14:41:40.624  6958  6958 D Mms/DownloadManager: mAutoDownload ------> true
09-12 14:41:40.624  1019  1266 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
09-12 14:41:40.634  1452  1702 D TP/MmsSmsProvider: query,matched:400, calling pid = 6958
09-12 14:41:40.634  1019  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:40.634  1019  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:40.634  1019  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:40.634  1019  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:40.644  7101  7101 E Zygote  : MountEmulatedStorage()
09-12 14:41:40.644  7101  7101 I libpersona: KNOX_SDCARD checking this for 10068
09-12 14:41:40.644  7101  7101 E Zygote  : v2
09-12 14:41:40.644  7101  7101 I libpersona: KNOX_SDCARD not a persona
09-12 14:41:40.654  7101  7101 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 14:41:40.654  6958  6958 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
09-12 14:41:40.654  1019  1266 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7101 uid=10068 gids={50068, 9997} abi=armeabi-v7a
09-12 14:41:40.654  6958  7096 D Mms/Synchronizer: [end]    doSync consume time = 54.723282
09-12 14:41:40.654  1019  4366 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
09-12 14:41:40.654  1019  4366 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
09-12 14:41:40.654  1019  4366 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:40.654  1019  4366 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:40.654  1019  4366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
09-12 14:41:40.654  7101  7101 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 14:41:40.654  7101  7101 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-12 14:41:40.664  1019  3798 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
09-12 14:41:40.664  1019  3798 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:40.664  1019  3798 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:40.664  1019  3798 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:40.664  1019  3798 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:40.684  7115  7115 E Zygote  : MountEmulatedStorage()
09-12 14:41:40.684  7115  7115 I libpersona: KNOX_SDCARD checking this for 10042
09-12 14:41:40.684  7115  7115 E Zygote  : v2
09-12 14:41:40.684  7115  7115 I libpersona: KNOX_SDCARD not a persona
09-12 14:41:40.684  7115  7115 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 14:41:40.684  1019  3798 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7115 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
09-12 14:41:40.684  7101  7101 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 14:41:40.684  7101  7101 D ActivityThread: Added TimaKeyStore provider
09-12 14:41:40.684  7115  7115 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 14:41:40.694  7115  7115 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
09-12 14:41:40.694  6958  7095 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 34.376875
09-12 14:41:40.694  6958  7127 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
09-12 14:41:40.694  6958  7127 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
09-12 14:41:40.714  1019  1507 I ActivityManager: Killing 6367:com.android.defcontainer/u0a3 (adj 15): empty #21
09-12 14:41:40.714  7055  7055 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 14:41:40.724  1019  1507 I ActivityManager: Killing 6254:com.android.calendar/u0a131 (adj 15): empty #22
09-12 14:41:40.734  7115  7115 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 14:41:40.734  7115  7115 D ActivityThread: Added TimaKeyStore provider
09-12 14:41:40.744  7055  7055 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
09-12 14:41:40.744  7055  7055 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
09-12 14:41:40.754  7115  7115 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 14:41:40.754  7115  7115 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-12 14:41:40.754  7115  7115 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-12 14:41:40.754  7055  7055 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
09-12 14:41:40.754  7101  7101 D BadgeProvider: onCreate
09-12 14:41:40.754  7101  7101 D BadgeProvider: DatabaseHelper
09-12 14:41:40.754  7055  7055 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
09-12 14:41:40.784  6958  7089 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
09-12 14:41:40.784  1452  1481 D TP/SmsProvider: query,matched:26, calling pid = 6958
09-12 14:41:40.794  1452  1481 D TP/SmsProvider: match 26:Elapsed time : 1.424 ms
09-12 14:41:40.794  1452  4774 D TP/MmsSmsProvider: query,matched:6, calling pid = 6958
09-12 14:41:40.804  1452  4774 D TP/MmsSmsProvider: match 6:Elapsed time : 1.786 ms
09-12 14:41:40.824  1019  1139 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
09-12 14:41:40.824  1019  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:40.824  1019  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:40.824  1019  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:40.824  1019  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:40.834  7140  7140 E Zygote  : MountEmulatedStorage()
09-12 14:41:40.834  7140  7140 E Zygote  : v2
09-12 14:41:40.834  7140  7140 I libpersona: KNOX_SDCARD checking this for 10023
09-12 14:41:40.834  7140  7140 I libpersona: KNOX_SDCARD not a persona
09-12 14:41:40.834  7115  7115 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
09-12 14:41:40.844  1019  1139 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7140 uid=10023 gids={50023, 9997} abi=armeabi-v7a
09-12 14:41:40.844  7140  7140 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 14:41:40.844  1019  1057 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
09-12 14:41:40.844  1019  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
09-12 14:41:40.844  7140  7140 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 14:41:40.844  7140  7140 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 14:41:40.854  1019  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:40.854  1019  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:40.854  1019  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:40.854  1019  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:40.854  3862  4383 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
,09-12 14:41:40.864  7155  7155 E Zygote  : MountEmulatedStorage(),
09-12 14:41:40.864  7155  7155 E Zygote  : v2
09-12 14:41:40.864  7155  7155 I libpersona: KNOX_SDCARD checking this for 10003
09-12 14:41:40.864  7155  7155 I libpersona: KNOX_SDCARD not a persona
09-12 14:41:40.864  7155  7155 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-12 14:41:40.864  1019  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7155 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-12 14:41:40.874  7155  7155 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 14:41:40.874  7155  7155 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 14:41:40.874  1019  1347 I ActivityManager: Killing 6630:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
,09-12 14:41:40.884  7140  7140 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 14:41:40.884  7140  7140 D ActivityThread: Added TimaKeyStore provider
,09-12 14:41:40.884  1019  3798 I ActivityManager: Killing 6641:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
,09-12 14:41:40.894   304   304 I art     : Explicit concurrent mark sweep GC freed 8692(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 639us total 25.955ms
,09-12 14:41:40.894  1019  4366 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
,09-12 14:41:40.894  1019  4366 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:40.894  1019  4366 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:40.894  1019  4366 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:40.894  1019  4366 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:40.914   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 17.536ms
,09-12 14:41:40.914  7155  7155 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:41:40.924  7155  7155 D ActivityThread: Added TimaKeyStore provider
,09-12 14:41:40.934   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 564us total 17.467ms
,09-12 14:41:40.944  7175  7175 E Zygote  : MountEmulatedStorage(),
09-12 14:41:40.944  7175  7175 E Zygote  : v2
09-12 14:41:40.944  7175  7175 I libpersona: KNOX_SDCARD checking this for 1000
09-12 14:41:40.944  7175  7175 I libpersona: KNOX_SDCARD not a persona
,09-12 14:41:40.944  7175  7175 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 14:41:40.954  7175  7175 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-12 14:41:40.954  7175  7175 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 14:41:40.964  1019  4366 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7175 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
09-12 14:41:40.964  1019  4366 I ActivityManager: Killing 6676:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
,09-12 14:41:40.984  7140  7140 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,09-12 14:41:40.994  7175  7175 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:41:40.994  7175  7175 D ActivityThread: Added TimaKeyStore provider
,09-12 14:41:41.014   285   285 E installd: system dir 0 : /system/app/
09-12 14:41:41.014   285   285 E installd: system dir 1 : /system/priv-app/
09-12 14:41:41.014   285   285 E installd: system dir 2 : /vendor/app/
09-12 14:41:41.014   285   285 E installd: system dir 3 : /oem/app/
,09-12 14:41:41.024  6958  7089 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,09-12 14:41:41.034  7140  7140 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,09-12 14:41:41.044  7140  7140 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,09-12 14:41:41.044  7140  7140 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,09-12 14:41:41.044  7140  7140 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,09-12 14:41:41.044  7140  7140 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,09-12 14:41:41.044  7140  7140 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,09-12 14:41:41.044  7140  7140 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,09-12 14:41:41.054  7140  7140 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,09-12 14:41:41.054  1019  1057 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,09-12 14:41:41.054  7140  7140 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,09-12 14:41:41.054  7140  7140 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,09-12 14:41:41.054  7140  7140 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,09-12 14:41:41.054  7055  7055 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-12 14:41:41.054  7140  7140 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,09-12 14:41:41.054  7140  7140 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
09-12 14:41:41.064  3862  4383 D Icing   : Loaded CLD2 Version V2.0 - 20141016
09-12 14:41:41.064  7175  7175 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
09-12 14:41:41.064  7175  7175 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
09-12 14:41:41.064  1019  1032 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
09-12 14:41:41.064  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
,09-12 14:41:41.064  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:41.064  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:41.064  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,09-12 14:41:41.074  1019  1489 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-12 14:41:41.074  1019  1044 D ActivityManager: startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,09-12 14:41:41.074  7175  7175 I FilterInstaller: FilterPackageService : ACTION_CHANGED
,09-12 14:41:41.074  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:41.074  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:41.074  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:41.074  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:41.094  7195  7195 E Zygote  : MountEmulatedStorage(),
09-12 14:41:41.094  7195  7195 E Zygote  : v2
,09-12 14:41:41.094  7195  7195 I libpersona: KNOX_SDCARD checking this for 10037
09-12 14:41:41.094  7195  7195 I libpersona: KNOX_SDCARD not a persona
09-12 14:41:41.094  1019  1044 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=7195 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 14:41:41.094  7195  7195 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 14:41:41.094  7175  7194 E FilterInstaller: installFilters
09-12 14:41:41.094  7195  7195 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 14:41:41.094  7195  7195 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-12 14:41:41.104  7175  7194 E FilterInstaller: There is no requred permission
,09-12 14:41:41.114  6833  7166 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-12 14:41:41.114  6833  7166 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-12 14:41:41.114  7055  7055 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-12 14:41:41.124  7195  7195 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:41:41.124  7195  7195 D ActivityThread: Added TimaKeyStore provider
,09-12 14:41:41.134  7055  7055 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-12 14:41:41.134  7055  7055 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-12 14:41:41.134  1019  1031 I ActivityManager: Killing 6693:com.samsung.helphub/1000 (adj 15): empty #21
,09-12 14:41:41.144  7055  7055 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-12 14:41:41.144  7195  7195 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,09-12 14:41:41.144  7055  7055 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-12 14:41:41.144  7055  7055 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-12 14:41:41.164  6833  7166 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,09-12 14:41:41.184  3862  4383 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
,09-12 14:41:41.194  1019  1139 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-12 14:41:41.194  1019  1139 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:41.194  1019  1139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:41.194  1019  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.194  6833  6847 W art     : Suspending all threads took: 7.307ms
,09-12 14:41:41.204  7195  7195 I CalendarProvider2: CalendarProvider2.onCreate() called
,09-12 14:41:41.234  6833  7166 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-12 14:41:41.244  6833  7166 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1768e31e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-12 14:41:41.244  6833  7166 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-12 14:41:41.244  1019  1032 I ActivityManager: Killing 6660:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,09-12 14:41:41.274  1019  1507 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,09-12 14:41:41.274  1019  1507 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.CalendarProviderIntentService; callingUser = 0; userId(target) = 0
,09-12 14:41:41.274  1019  1507 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:41.274  1019  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:41.274  1019  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,09-12 14:41:41.284  1019  4366 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,09-12 14:41:41.284  1019  4366 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-12 14:41:41.284  1019  4366 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:41.284  1019  4366 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:41.284  1019  4366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.284  1019  1499 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
09-12 14:41:41.284  1019  1499 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
09-12 14:41:41.284  1019  1499 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
09-12 14:41:41.284  1019  1499 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,09-12 14:41:41.294  1639  5067 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-12 14:41:41.294  7055  7217 D OpenGLRenderer: Render dirty regions requested: true
,09-12 14:41:41.294  1639  1639 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-12 14:41:41.304  7195  7216 E SQLiteLog: (284) automatic index on view_events(_id)
,09-12 14:41:41.304  1019  1507 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-12 14:41:41.304  1019  1507 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-12 14:41:41.304  1019  1507 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-12 14:41:41.304  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-12 14:41:41.304  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,09-12 14:41:41.314  7055  7055 V ActivityThread: updateVisibility : ActivityRecord{a608b6b token=android.os.BinderProxy@e510de5 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-12 14:41:41.314  7055  7105 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,09-12 14:41:41.314  7055  7055 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-12 14:41:41.314  7055  7055 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-12 14:41:41.324  1019  1499 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
09-12 14:41:41.324  1019  1499 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,09-12 14:41:41.324  1019  1499 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:41.324  1019  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:41.324  1019  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.334  1639  1639 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 14:41:41.334  1639  1639 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 14:41:41.344  7195  7216 D CalendarAlarmManager: sys current time:1473684101298
,09-12 14:41:41.344  7195  7216 D CalendarAlarmManager: reminder amount:0
,09-12 14:41:41.344   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,09-12 14:41:41.344  3862  3862 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,09-12 14:41:41.344  1019  4367 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 14:41:41.354  1019  4367 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,09-12 14:41:41.354  1019  4368 D InputDispatcher: Focus entered window: 7055
,09-12 14:41:41.354  1019  4367 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:41.354  1019  4367 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:41.354  1019  4367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.354   289   289 E SMD     : DCD OFF
09-12 14:41:41.354  1019  1504 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
09-12 14:41:41.354  1019  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,09-12 14:41:41.354  1019  1504 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:41.354  1019  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:41.354  1019  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,09-12 14:41:41.364  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-12 14:41:41.364  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
09-12 14:41:41.364  7055  7055 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-12 14:41:41.364  7055  7217 I OpenGLRenderer: Initialized EGL, version 1.4
,09-12 14:41:41.364  7055  7217 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
09-12 14:41:41.364  7055  7217 D OpenGLRenderer: Enabling debug mode 0
,09-12 14:41:41.394  1019  1489 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 14:41:41.394  1019  1489 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:41.394  1019  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:41.394  1019  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.394  1019  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:41.394  1019  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:41.394  1019  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:41.394  1019  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:41.404  1019  4366 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-12 14:41:41.414  7224  7224 E Zygote  : MountEmulatedStorage()
,09-12 14:41:41.414  7224  7224 E Zygote  : v2
09-12 14:41:41.414  7224  7224 I libpersona: KNOX_SDCARD checking this for 10011
,09-12 14:41:41.414  7224  7224 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-12 14:41:41.414  7224  7224 I libpersona: KNOX_SDCARD not a persona
09-12 14:41:41.414  1019  1489 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7224 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,09-12 14:41:41.414  7224  7224 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 14:41:41.424  1183  1183 D PanelView: There is/are notification(s) 
09-12 14:41:41.424  1019  7230 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-12 14:41:41.424  7224  7224 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-12 14:41:41.434  1019  1049 I ActivityManager: Displayed Component not be shown by security: +1s344ms (total +1s476ms)
,09-12 14:41:41.434  1019  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2fe5e55a u0 com.test.thalitest/.MainActivity t163} time:101098
09-12 14:41:41.434  1019  1049 W ActivityManager: mDVFSHelper.release()
,09-12 14:41:41.444   259  1099 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,09-12 14:41:41.444   259   444 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,09-12 14:41:41.464  7224  7224 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-12 14:41:41.464  7055  7055 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection,
09-12 14:41:41.464  7055  7055 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@e510de5 time:101127
,09-12 14:41:41.474  7224  7224 D ActivityThread: Added TimaKeyStore provider
,09-12 14:41:41.474  1971  1971 I SamsungIME: getCurrentCandidateView
,09-12 14:41:41.484  7055  7055 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7055
,09-12 14:41:41.494  1019  1504 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 14:41:41.504  7224  7224 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-12 14:41:41.504  1019  1504 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:41.504  1019  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:41.504  1019  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.504  7224  7224 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-12 14:41:41.524  1019  1347 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:41.524  1019  1347 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 14:41:41.524  1019  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:41.524  1019  1347 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
09-12 14:41:41.524  1019  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.534  3862  7244 D LocationInitializer: Restart initialization of location
,09-12 14:41:41.534  1019  4368 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 14:41:41.534  1019  4368 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,09-12 14:41:41.534  1019  4368 W ActivityManager: userId = 0, bbcId = -10000,
09-12 14:41:41.534  1019  4368 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:41.534  1019  4368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.554  7224  7224 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>,
,09-12 14:41:41.564  7224  7224 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,09-12 14:41:41.564  1019  4366 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 14:41:41.564  1019  4366 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:41.564  1019  4366 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:41.564  1019  4366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.574  7224  7224 I MultiDex: VM with version 2.1.0 has multidex support
09-12 14:41:41.574  7224  7224 I MultiDex: install
09-12 14:41:41.574  7224  7224 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-12 14:41:41.594  7224  7224 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,09-12 14:41:41.634  1971  1971 D SamsungIME: Dismiss ExpandCandiate
,09-12 14:41:41.664  7224  7224 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-12 14:41:41.664  7224  7224 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3f9315a4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-12 14:41:41.664  7224  7224 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-12 14:41:41.664  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:41.664  1019  1044 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:41.664  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.664  1019  4367 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,09-12 14:41:41.664  1019  4367 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-12 14:41:41.674  1019  4367 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:41.674  1019  4367 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:41.674  1019  4367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.674  1019  1504 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
09-12 14:41:41.674  1019  1504 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
09-12 14:41:41.674  1019  1504 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
09-12 14:41:41.674  1019  1504 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
09-12 14:41:41.674  1639  2521 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-12 14:41:41.674  1019  1504 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:41.674  1019  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:41.674  1019  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.684  1019  1499 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:41.684  1019  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 14:41:41.684  1019  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.684  1639  1639 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-12 14:41:41.684  7224  7224 D WearableService: callingUid 10011, callindPid: 7224
,09-12 14:41:41.694  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:41.694  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:41.694  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.694  1019  1507 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,09-12 14:41:41.694  1019  1507 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,09-12 14:41:41.694  1019  1507 W ActivityManager: userId = 0, bbcId = -10000,
09-12 14:41:41.694  1019  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:41.694  1019  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.704  1019  3798 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:41.704  1019  3798 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:41.704  1019  3798 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.704  1639  1639 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 14:41:41.704  1019  1347 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:41.714  1019  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 14:41:41.714  1019  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.714  3862  3862 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,09-12 14:41:41.714  1019  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 14:41:41.714  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,09-12 14:41:41.724  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:41.724  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:41.724  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.734  1019  1347 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:41.734  1019  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 14:41:41.734  1019  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.734  1019  1347 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:41.734  1019  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:41.734  1019  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.744  7224  7251 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0
,09-12 14:41:41.744  1019  1347 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:41.744  1019  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:41.744  1019  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.744  1019  1139 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:41.744  1019  1139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:41.744  1019  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.754  1019  4368 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:41.754  1019  4368 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:41.754  1019  4368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.764  1019  1504 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:41.764  1019  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 14:41:41.774  1019  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.774  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:41.774  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:41.774  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.784  1019  1499 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 14:41:41.784  1019  1499 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:41.784  1019  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 14:41:41.784  1019  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.784  1019  4366 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:41.784  1019  4366 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:41.784  1019  4366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.794  7055  7055 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-12 14:41:41.794  1019  1341 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 14:41:41.794  1019  1341 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,09-12 14:41:41.794  1019  1341 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:41.794  1019  1341 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:41.794  1019  1341 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.804  3862  7253 D LocationInitializer: Restart initialization of location
,09-12 14:41:41.804  1019  1266 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 14:41:41.804  1019  1266 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,09-12 14:41:41.804  1019  1266 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:41.804  1019  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:41.804  1019  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:41:41.814  1647  2701 E MDM     : [161] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,09-12 14:41:41.814  1647  2701 E MDM     : [161] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,09-12 14:41:41.874  1971  1971 I SamsungIME: getDebugLevel  : 0x4f4c
,09-12 14:41:41.894  7055  7222 D jxcore_app_log: JniHelper::setJavaVM(0xb86de2b0), pthread_self() = -1194915536
,09-12 14:41:41.904  7055  7222 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-12 14:41:41.904  7055  7222 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-12 14:41:41.904  7055  7222 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-12 14:41:41.904  7055  7222 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-12 14:41:41.904  7055  7222 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-12 14:41:41.904  7055  7222 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2124a85e added. We now have 1 listener(s)
,09-12 14:41:41.904  7055  7222 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,09-12 14:41:41.904  7055  7222 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-12 14:41:41.914  7055  7222 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 14:41:41.914  7055  7222 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 14:41:41.914  7055  7222 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-12 14:41:41.914  7055  7222 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-12 14:41:41.914  7055  7222 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-12 14:41:41.914  7055  7222 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
09-12 14:41:41.914  7055  7222 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-12 14:41:41.914  7055  7222 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-12 14:41:41.914  7055  7222 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-12 14:41:41.914  7055  7222 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-12 14:41:41.914  7055  7222 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-12 14:41:41.914  7055  7222 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-12 14:41:41.914  7055  7222 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-12 14:41:41.914  7055  7222 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-12 14:41:41.914  7055  7222 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-12 14:41:41.914  7055  7222 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-12 14:41:41.914  7055  7222 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@377a3a55 added. We now have 1 listener(s)
,09-12 14:41:41.914  7055  7222 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 14:41:41.924  7055  7222 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 14:41:41.924  7055  7222 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-12 14:41:41.924  7055  7222 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-12 14:41:41.924  7055  7222 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-12 14:41:41.924  7055  7222 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-12 14:41:41.924  7055  7222 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 14:41:41.924  1971  1971 I SamsungIME: getDebugLevel  : 0x4f4c
,09-12 14:41:41.934  7055  7222 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,09-12 14:41:41.934  7055  7222 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-12 14:41:41.934  7055  7222 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:41:41.934  7055  7222 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:41:41.934  7055  7222 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:41:41.934  7055  7222 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:41:41.934  7055  7222 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:41:41.934  7055  7222 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:41:41.934  7055  7222 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:41:41.934  7055  7222 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 14:41:41.934  7055  7222 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-12 14:41:41.934  7055  7222 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 14:41:41.944  7055  7222 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 14:41:41.944  1971  1971 I SamsungIME: KeybaordView init() : load resources
,09-12 14:41:41.944  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:41.944  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:41.964  1971  1971 I SamsungIME: getCurrentKeyboard
09-12 14:41:41.964  1971  1971 I SamsungIME: getTextKeyboard
,09-12 14:41:41.974  7055  7055 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-12 14:41:41.994  1971  1971 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-12 14:41:42.374  7195  7195 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,09-12 14:41:42.374  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:42.374  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:42.374  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
09-12 14:41:42.374  1019  1044 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,09-12 14:41:42.374  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:42.374  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:42.374  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:42.374  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:42.394  7257  7257 E Zygote  : MountEmulatedStorage()
09-12 14:41:42.394  7257  7257 E Zygote  : v2
09-12 14:41:42.394  7257  7257 I libpersona: KNOX_SDCARD checking this for 10130
09-12 14:41:42.394  7257  7257 I libpersona: KNOX_SDCARD not a persona
09-12 14:41:42.394  7257  7257 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 14:41:42.394  7257  7257 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 14:41:42.394  7257  7257 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,09-12 14:41:42.394  1019  1044 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7257 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,09-12 14:41:42.404  1019  1504 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:42.404  1019  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:42.404  1019  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
09-12 14:41:42.404  1019  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,09-12 14:41:42.434  7257  7257 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:41:42.434  7257  7257 D ActivityThread: Added TimaKeyStore provider
,09-12 14:41:42.464  7257  7257 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 14:41:42.464  7257  7257 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,09-12 14:41:42.474  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:42.474  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:42.474  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
09-12 14:41:42.474  1019  1031 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,09-12 14:41:42.474  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:42.474  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:42.474  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:42.474  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:42.484  7272  7272 E Zygote  : MountEmulatedStorage()
09-12 14:41:42.484  7272  7272 E Zygote  : v2
09-12 14:41:42.484  7272  7272 I libpersona: KNOX_SDCARD checking this for 10131
09-12 14:41:42.484  7272  7272 I libpersona: KNOX_SDCARD not a persona
09-12 14:41:42.484  1019  1031 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7272 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,09-12 14:41:42.494  7272  7272 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 14:41:42.494  1019  1031 I ActivityManager: Killing 6708:com.sec.spp.push/u0a32 (adj 15): empty #21
,09-12 14:41:42.494  7272  7272 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 14:41:42.494  7272  7272 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 14:41:42.514  1019  3350 D SSRM:n  : SIOP:: AP = 410
,09-12 14:41:42.514  7272  7272 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:41:42.514  7272  7272 D ActivityThread: Added TimaKeyStore provider
,09-12 14:41:42.534  7272  7272 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-12 14:41:42.534  7272  7272 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 14:41:42.534  7272  7272 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-12 14:41:42.574  1019  4367 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
09-12 14:41:42.574  1019  4367 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,09-12 14:41:42.574  1019  4367 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:42.574  1019  4367 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:42.574  1019  4367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-12 14:41:42.584  1019  1266 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:42.584  1019  1266 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 14:41:42.584  1019  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,09-12 14:41:42.594  6958  6958 I Mms/MmsApp:  start initViewCache mms
,09-12 14:41:42.594  6958  6958 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1899.673228
09-12 14:41:42.594  6958  6958 D Mms/ComposeMessageFragment: fillCache, easy = false
,09-12 14:41:42.594  2672  2682 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,09-12 14:41:42.604  7055  7256 W jxcore-log: Initializing JXcore engine
09-12 14:41:42.604  7055  7256 W jxcore-log: JXcore engine is ready
,09-12 14:41:42.674  1963  1963 E audit   : type=1400 msg=audit(1473684102.674:205): avc:  denied  { ioctl } for  pid=7256 comm="Thread-1330" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-12 14:41:42.674  1963  1963 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
09-12 14:41:42.674  1963  1963 E audit   : type=1300 msg=audit(1473684102.674:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e3ef8f8 items=0 ppid=304 ppcomm=main pid=7256 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1330" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-12 14:41:42.674  1963  1963 E audit   : type=1320 msg=audit(1473684102.674:205): 
,09-12 14:41:42.684  7055  7256 W jxcore-log: Starting JXcore engine
,09-12 14:41:42.744  1019  1507 I art     : Explicit concurrent mark sweep GC freed 24601(1359KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/34MB, paused 2.640ms total 145.581ms
,09-12 14:41:42.754  1019  1499 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,09-12 14:41:42.754  1019  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,09-12 14:41:42.754  1019  1499 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:42.754  1019  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:42.754  1019  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-12 14:41:42.774  1019  4366 I ActivityManager: Killing 6763:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,09-12 14:41:42.814  7055  7256 W jxcore-log: Platform android
09-12 14:41:42.814  7055  7256 W jxcore-log: 
,09-12 14:41:42.814  7055  7256 W jxcore-log: Process ARCH arm
09-12 14:41:42.814  7055  7256 W jxcore-log: 
,09-12 14:41:42.854  6958  6958 D AbsListView: Get MotionRecognitionManager
,09-12 14:41:42.854  1019  1341 D MotionRecognitionService:  ssp status : false
,09-12 14:41:42.864  6958  6958 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 277.562344
,09-12 14:41:42.954  6958  6958 D Mms/BubbleViewCache: fillCache bubble = 1
,09-12 14:41:43.024  7055  7256 I jxcore-log: JXcore Cordova bridge is ready!
09-12 14:41:43.024  7055  7256 I jxcore-log: 
,09-12 14:41:43.024  7055  7256 W jxcore-log: JXcore engine is started
,09-12 14:41:43.034  7055  7222 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-12 14:41:43.034  7055  7055 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-12 14:41:43.174  1019  3374 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-12 14:41:44.354   289   289 E SMD     : DCD OFF
,09-12 14:41:44.694  1639  1639 I ConfigService: onDestroy
,09-12 14:41:45.384  6742  6794 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,09-12 14:41:45.404  6742  6794 I AcmsKeyStoreHelper: Key Store exist
,09-12 14:41:45.404  6742  6794 I AcmsKeyStoreHelper: Hence loading the keystore file
,09-12 14:41:45.464  6742  6794 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
,09-12 14:41:45.464  6742  6794 I AcmsCertificateMngr: getKeyStoreForApplication success 
09-12 14:41:45.464  6742  6794 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
,09-12 14:41:45.464  6742  6794 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-12 14:41:45.464  6742  6794 D AcmsServiceMonitor: Decrementing - Counter value: 1
,09-12 14:41:45.464  6742  6794 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,09-12 14:41:45.464  6742  6794 D AcmsCore: This is NOT a valid MirrorLink app
09-12 14:41:45.464  6742  6794 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
09-12 14:41:45.464  6742  6794 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-12 14:41:45.464  6742  6794 D AcmsServiceMonitor: Decrementing - Counter value: 0
09-12 14:41:45.464  6742  6794 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,09-12 14:41:45.464  6742  6742 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,09-12 14:41:45.464  6742  6742 D AcmsService: Enter onDestroy
09-12 14:41:45.464  6742  6742 I AcmsService: cleanUp(): inside service clean up
,09-12 14:41:45.464  6742  6742 D AcmsCore: AcmsCore: inside DeInit
09-12 14:41:45.464  6742  6742 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
,09-12 14:41:45.464  6742  6742 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
,09-12 14:41:45.464  6742  6742 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
09-12 14:41:45.464  6742  6742 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
09-12 14:41:45.464  6742  6742 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,09-12 14:41:45.464  6742  6742 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,09-12 14:41:45.474  6742  6742 D AcmsService: killing acms process
09-12 14:41:45.474  6742  6742 I Process : Sending signal. PID: 6742 SIG: 9
,09-12 14:41:45.534  1019  1139 I ActivityManager: Process ACMS.Process (pid 6742)(adj 0) has died(30,747)
,09-12 14:41:46.264  1019  1341 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-12 14:41:46.274  1019  1341 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4237, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-12 14:41:46.274  1019  1341 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-12 14:41:46.274  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-12 14:41:46.274  1019  1341 D BatteryService: stay LED for charging
,09-12 14:41:46.274  1019  1019 I MotionRecognitionService: Plugged
,09-12 14:41:46.274  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,09-12 14:41:46.274  1183  1183 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-12 14:41:46.274  1183  1183 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-12 14:41:46.274  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-12 14:41:46.274  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,09-12 14:41:46.294  3211  3211 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-12 14:41:46.294  3211  3349 D HeadsetStateMachine: Disconnected process message: 10
,09-12 14:41:46.304  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,09-12 14:41:46.304  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,09-12 14:41:46.304  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,09-12 14:41:46.824  1019  1489 I ActivityManager: Killing 6724:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,09-12 14:41:46.844  1019  1031 I ActivityManager: Killing 6318:com.samsung.android.sm/1000 (adj 15): empty #21
,09-12 14:41:47.354   289   289 E SMD     : DCD OFF
,09-12 14:41:48.234  1019  1309 E Watchdog: !@Sync 3
,09-12 14:41:49.364   317   317 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-12 14:41:49.364   317   317 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-12 14:41:50.014  1019  1057 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-12 14:41:50.354   289   289 E SMD     : DCD OFF
,09-12 14:41:51.054  1019  1057 D PackageManager: [MSG] MCS_UNBIND
,09-12 14:41:51.064  1019  1347 I ActivityManager: Killing 6803:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,09-12 14:41:52.494  1019  1051 I PowerManagerService: [PWL] Off : 50s ago
,09-12 14:41:52.544  1019  3350 D SSRM:n  : SIOP:: AP = 400
,09-12 14:41:53.354   289   289 E SMD     : DCD OFF
,09-12 14:41:54.364   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 14:41:54.944  1019  1097 V AlarmManager: waitForAlarm result :4
,09-12 14:41:54.944  1019  1097 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,09-12 14:41:55.174  6916  7035 D Finsky  : [1294] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,09-12 14:41:55.174  6916  6916 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,09-12 14:41:55.364   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 14:41:55.474  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-12 14:41:55.474  7055  7256 I jxcore-log: 
,09-12 14:41:55.484  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-12 14:41:55.484  7055  7256 I jxcore-log: 
,09-12 14:41:55.484  7055  7256 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:41:55.484  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:41:55.484  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:41:55.484  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:41:55.484  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:41:55.484  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:41:55.484  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:41:55.484  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 14:41:55.484  7055  7256 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 14:41:55.494  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-12 14:41:55.494  7055  7256 I jxcore-log: 
,09-12 14:41:55.494  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-12 14:41:55.494  7055  7256 I jxcore-log: 
,09-12 14:41:56.144  7055  7256 D executeNativeTests: Running unit tests
,09-12 14:41:56.234  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 14:41:56.234  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efabae added. We now have 2 listener(s)
,09-12 14:41:56.234  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-12 14:41:56.234  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:41:56.234  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 14:41:56.234  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:41:56.234  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f added. We now have 2 listener(s)
09-12 14:41:56.234  7055  7256 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 14:41:56.234  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 14:41:56.244  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 14:41:56.244  7055  7256 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:41:56.244  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:41:56.244  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:41:56.244  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:41:56.244  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:41:56.244  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:41:56.244  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:41:56.244  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 14:41:56.244  7055  7256 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 14:41:56.244  7055  7256 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 14:41:56.244  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:56.254  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:56.254  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 14:41:56.254  7055  7256 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 14:41:56.254  7055  7256 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 14:41:56.254  7055  7256 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-12 14:41:56.254  7055  7256 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 14:41:56.254  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 14:41:56.254  7055  7256 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 14:41:56.254  7055  7256 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 14:41:56.254  7055  7256 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 14:41:56.254  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:56.254  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 14:41:56.254  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:56.254  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.254  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:41:56.254  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:41:56.254  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efabae removed from the list
09-12 14:41:56.254  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.254  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f removed from the list
09-12 14:41:56.254  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:56.254  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:56.254  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.254  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:56.264  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 14:41:56.264  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:56.264  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 14:41:56.264  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
,09-12 14:41:56.264  7055  7256 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-12 14:41:56.264  7055  7256 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:56.264  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:56.264  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:41:56.264  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:56.264  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.264  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.264  7055  7256 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efabae not in the list
09-12 14:41:56.264  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.264  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.264  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:56.264  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.264  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.264  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.264  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:56.284  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:56.284  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:56.284  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.284  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
,09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 14:41:56.284  7055  7256 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:56.284  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:56.284  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:41:56.284  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:56.284  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.284  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.284  7055  7256 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efabae not in the list
09-12 14:41:56.284  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.284  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.284  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:56.284  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.284  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.284  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.284  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.284  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:56.284  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:56.284  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.284  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.284  7055  7256 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 14:41:56.284  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:41:56.294  7055  7256 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:41:56.294  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:41:56.294  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:41:56.294  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:41:56.294  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:41:56.294  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:41:56.294  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:41:56.294  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 14:41:56.294  7055  7256 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 14:41:56.294  7055  7256 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 14:41:56.294  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 14:41:56.294  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 14:41:56.294  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 14:41:56.294  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:41:56.294  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 14:41:56.294  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:41:56.294  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 14:41:56.304  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:41:56.314  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 14:41:56.314  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 14:41:56.314  7055  7256 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-12 14:41:56.314  7055  7256 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-12 14:41:56.314  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 14:41:56.314  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 14:41:56.314  7055  7256 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 14:41:56.324  1019  1504 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-12 14:41:56.324  1019  1504 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4242, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-12 14:41:56.324  1019  1504 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-12 14:41:56.324  1019  1504 D BatteryService: stay LED for charging
09-12 14:41:56.324  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-12 14:41:56.324  1019  1019 I MotionRecognitionService: Plugged
09-12 14:41:56.334  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
09-12 14:41:56.334  3211  3224 D BtGatt.GattService: registerClient() - UUID=7bc4edb6-ddf1-4bca-8d24-b4f86ca3e86e
09-12 14:41:56.334  1183  1183 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-12 14:41:56.334  1183  1183 D KeyguardUpdateMonitor: handleBatteryUpdate
09-12 14:41:56.334  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-12 14:41:56.334  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
09-12 14:41:56.344  3211  3211 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-12 14:41:56.344  3211  3349 D HeadsetStateMachine: Disconnected process message: 10
09-12 14:41:56.354  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
09-12 14:41:56.354  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
09-12 14:41:56.354  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
09-12 14:41:56.354   289   289 E SMD     : DCD OFF
,09-12 14:41:56.364   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 14:41:56.374  3211  3286 D BtGatt.GattService: onClientRegistered() - UUID=7bc4edb6-ddf1-4bca-8d24-b4f86ca3e86e, clientIf=6
,09-12 14:41:56.384  7055  7069 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-12 14:41:56.384  3211  3228 D BtGatt.GattService: start scan with filters
,09-12 14:41:56.384  3211  3348 D BtGatt.ScanManager: handling starting scan
,09-12 14:41:56.384  3211  3348 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
,09-12 14:41:56.384  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 14:41:56.394  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-12 14:41:56.394  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 14:41:56.394  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 14:41:56.394  3211  3286 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-12 14:41:56.394  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 14:41:56.394  3211  3348 D BtGatt.ScanManager: allow scan with filters
,09-12 14:41:56.394  3211  3348 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-12 14:41:56.394  3211  3348 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-12 14:41:56.394  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 14:41:56.404  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 14:41:56.404  7055  7055 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 14:41:56.404  3211  3286 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-12 14:41:56.404  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 14:41:56.404  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 14:41:56.404  3211  3348 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 14:41:56.404  3211  3348 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-12 14:41:56.404  7055  7256 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 14:41:56.414  3211  3286 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-12 14:41:56.414  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 14:41:56.414  7055  7256 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 14:41:56.414  7055  7256 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 14:41:56.414  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:56.414  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 14:41:56.414  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.414  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 14:41:56.414  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 14:41:56.414  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 14:41:56.414  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 14:41:56.414  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 14:41:56.414  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 14:41:56.414  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 14:41:56.414  3211  3228 D BtGatt.GattService: stopScan() - queue size =1
,09-12 14:41:56.414  3211  3364 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 14:41:56.414  3211  3286 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-12 14:41:56.414  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 14:41:56.424  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 14:41:56.424  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 14:41:56.424  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 14:41:56.424  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 14:41:56.424  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 14:41:56.424  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 14:41:56.424  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 14:41:56.424  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 14:41:56.424  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 14:41:56.424  3211  3348 D BtGatt.ScanManager: filter size is 1
09-12 14:41:56.424  3211  3348 D BtGatt.ScanManager: delete FilterIndex - 3
,09-12 14:41:56.424  3211  3286 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-12 14:41:56.424  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 14:41:56.424  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:41:56.434  3211  3348 D BtGatt.ScanManager: stopping BLe Batch
,09-12 14:41:56.434  7055  7055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 14:41:56.434  7055  7055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 14:41:56.434  7055  7055 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 14:41:56.434  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:56.434  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.434  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:41:56.434  7055  7256 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efabae not in the list
09-12 14:41:56.434  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.434  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.434  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:56.434  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.434  7055  7256 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 14:41:56.434  3211  3286 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-12 14:41:56.434  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 14:41:56.434  3211  3348 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-12 14:41:56.434  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 14:41:56.434  3211  3286 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-12 14:41:56.444  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 14:41:56.444  7055  7256 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:41:56.444  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:41:56.444  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:41:56.444  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:41:56.444  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:41:56.444  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:41:56.444  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:41:56.444  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 14:41:56.444  7055  7256 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 14:41:56.444  7055  7256 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 14:41:56.444  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:56.444  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:56.454  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 14:41:56.454  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 14:41:56.454  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 14:41:56.454  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 14:41:56.454  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 14:41:56.454  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 14:41:56.464  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 14:41:56.464  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 14:41:56.464  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 14:41:56.464  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 14:41:56.464  7055  7256 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 14:41:56.464  3211  3224 D BtGatt.GattService: registerClient() - UUID=3b6827aa-52e6-4e0a-aae9-9f8b1060cdab
,09-12 14:41:56.514  3211  3286 D BtGatt.GattService: onClientRegistered() - UUID=3b6827aa-52e6-4e0a-aae9-9f8b1060cdab, clientIf=6
,09-12 14:41:56.514  7055  7069 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-12 14:41:56.514  3211  3228 D BtGatt.GattService: start scan with filters
,09-12 14:41:56.514  3211  3348 D BtGatt.ScanManager: handling starting scan
,09-12 14:41:56.514  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 14:41:56.514  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-12 14:41:56.514  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 14:41:56.514  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 14:41:56.514  3211  3286 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-12 14:41:56.514  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 14:41:56.514  3211  3348 D BtGatt.ScanManager: allow scan with filters
09-12 14:41:56.514  3211  3348 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-12 14:41:56.524  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 14:41:56.524  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 14:41:56.524  7055  7055 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
,09-12 14:41:56.524  3211  3348 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
09-12 14:41:56.524  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 14:41:56.524  7055  7256 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 14:41:56.524  3211  3286 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-12 14:41:56.524  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 14:41:56.524  3211  3348 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 14:41:56.524  3211  3348 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-12 14:41:56.534  7055  7256 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 14:41:56.534  7055  7256 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 14:41:56.534  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 14:41:56.534  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 14:41:56.534  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:41:56.534  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 14:41:56.534  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 14:41:56.534  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 14:41:56.534  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 14:41:56.534  3211  3286 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-12 14:41:56.534  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 14:41:56.534  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 14:41:56.534  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 14:41:56.534  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 14:41:56.544  3211  3228 D BtGatt.GattService: stopScan() - queue size =1
,09-12 14:41:56.544  3211  3364 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 14:41:56.544  3211  3286 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
09-12 14:41:56.544  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 14:41:56.544  3211  3348 D BtGatt.ScanManager: filter size is 1
09-12 14:41:56.544  3211  3348 D BtGatt.ScanManager: delete FilterIndex - 4
09-12 14:41:56.544  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 14:41:56.544  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 14:41:56.544  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 14:41:56.544  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 14:41:56.544  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
,09-12 14:41:56.554  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 14:41:56.554  3211  3286 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-12 14:41:56.554  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 14:41:56.554  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 14:41:56.554  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 14:41:56.554  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 14:41:56.554  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-12 14:41:56.554  3211  3348 D BtGatt.ScanManager: stopping BLe Batch,
09-12 14:41:56.564  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:56.564  7055  7055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 14:41:56.564  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.564  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:41:56.564  7055  7055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 14:41:56.564  7055  7256 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efabae not in the list
09-12 14:41:56.564  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.564  7055  7055 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 14:41:56.564  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.564  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:56.564  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.564  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.564  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:56.564  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:56.564  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:56.564  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.564  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
,09-12 14:41:56.564  7055  7256 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 14:41:56.564  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 14:41:56.564  3211  3286 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-12 14:41:56.564  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 14:41:56.564  3211  3348 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-12 14:41:56.574  7055  7256 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:41:56.574  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:41:56.574  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:41:56.574  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:41:56.574  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:41:56.574  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:41:56.574  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:41:56.574  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 14:41:56.574  3211  3286 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-12 14:41:56.574  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 14:41:56.574  7055  7256 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 14:41:56.574  7055  7256 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 14:41:56.574  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 14:41:56.574  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 14:41:56.574  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 14:41:56.574  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:41:56.574  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 14:41:56.574  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:56.584  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:56.584  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 14:41:56.584  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 14:41:56.584  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 14:41:56.594  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 14:41:56.594  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 14:41:56.594  7055  7256 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 14:41:56.594  3211  3228 D BtGatt.GattService: registerClient() - UUID=3b848793-0c03-4ff6-a593-fdbd2b7ef87d
,09-12 14:41:56.644  3211  3286 D BtGatt.GattService: onClientRegistered() - UUID=3b848793-0c03-4ff6-a593-fdbd2b7ef87d, clientIf=6
,09-12 14:41:56.644  7055  7063 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-12 14:41:56.644  3211  3364 D BtGatt.GattService: start scan with filters
,09-12 14:41:56.644  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 14:41:56.644  3211  3348 D BtGatt.ScanManager: handling starting scan
09-12 14:41:56.644  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 14:41:56.644  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 14:41:56.644  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 14:41:56.644  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 14:41:56.644  7055  7055 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 14:41:56.644  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 14:41:56.644  3211  3286 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-12 14:41:56.644  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 14:41:56.644  3211  3348 D BtGatt.ScanManager: allow scan with filters
09-12 14:41:56.644  3211  3348 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-12 14:41:56.644  3211  3348 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-12 14:41:56.644  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 14:41:56.654  3211  3286 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-12 14:41:56.654  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 14:41:56.654  3211  3348 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 14:41:56.654  3211  3348 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-12 14:41:56.654  7055  7256 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 14:41:56.654  7055  7256 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 14:41:56.654  7055  7256 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 14:41:56.654  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:56.654  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 14:41:56.654  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.654  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 14:41:56.664  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 14:41:56.664  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 14:41:56.664  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 14:41:56.664  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 14:41:56.664  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 14:41:56.664  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 14:41:56.664  3211  3224 D BtGatt.GattService: stopScan() - queue size =1
,09-12 14:41:56.664  3211  3228 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 14:41:56.664  3211  3286 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-12 14:41:56.664  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 14:41:56.664  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 14:41:56.664  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 14:41:56.664  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 14:41:56.664  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 14:41:56.674  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 14:41:56.674  3211  3286 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-12 14:41:56.674  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 14:41:56.674  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 14:41:56.674  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
09-12 14:41:56.674  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 14:41:56.674  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 14:41:56.674  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 14:41:56.674  7055  7256 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:56.674  7055  7256 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 14:41:56.674  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:56.674  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 14:41:56.674  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:56.674  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.674  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:41:56.674  7055  7256 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efabae not in the list
09-12 14:41:56.674  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.674  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
,09-12 14:41:56.674  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:56.674  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.674  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.674  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:56.684  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-12 14:41:56.684  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:56.684  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.684  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.684  7055  7055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 14:41:56.684  7055  7055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 14:41:56.684  7055  7055 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 14:41:56.684  3211  3348 D BtGatt.ScanManager: filter size is 1
09-12 14:41:56.684  3211  3348 D BtGatt.ScanManager: delete FilterIndex - 5
,09-12 14:41:56.684  7055  7256 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported,
09-12 14:41:56.684  7055  7256 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:56.684  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 14:41:56.684  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:41:56.684  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-12 14:41:56.684  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.684  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.684  7055  7256 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efabae not in the list
,09-12 14:41:56.684  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.684  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.684  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:56.684  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:41:56.684  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:56.684  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.684  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.684  3211  3286 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-12 14:41:56.684  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 14:41:56.684  3211  3348 D BtGatt.ScanManager: stopping BLe Batch
09-12 14:41:56.684  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 14:41:56.684  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:56.684  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.684  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.684  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 14:41:56.684  7055  7256 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 14:41:56.684  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:56.684  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:41:56.684  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-12 14:41:56.684  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.684  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.684  7055  7256 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efabae not in the list
,09-12 14:41:56.684  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.684  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.684  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 14:41:56.684  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.684  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.684  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:41:56.684  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.684  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:56.684  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:56.684  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.684  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list,
09-12 14:41:56.684  7055  7256 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-12 14:41:56.684  7055  7256 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:56.684  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 14:41:56.684  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:41:56.684  3211  3286 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-12 14:41:56.684  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:56.684  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 14:41:56.684  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.684  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.684  3211  3348 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-12 14:41:56.684  7055  7256 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efabae not in the list
09-12 14:41:56.684  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-12 14:41:56.684  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.684  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 14:41:56.684  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.684  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.684  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.684  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:56.694  3211  3286 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-12 14:41:56.694  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 14:41:56.694  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:56.694  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:56.694  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.694  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.694  7055  7256 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-12 14:41:56.694  7055  7256 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:56.694  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 14:41:56.694  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:41:56.694  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:56.694  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.694  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:56.694  7055  7256 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efabae not in the list
09-12 14:41:56.694  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 14:41:56.694  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.694  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:56.694  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.694  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.694  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.694  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:56.694  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:56.694  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:56.694  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.694  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
,09-12 14:41:56.694  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 14:41:56.694  7055  7256 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 14:41:56.694  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 14:41:56.694  7055  7256 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 14:41:56.694  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 14:41:56.694  7055  7256 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 14:41:56.694  7055  7256 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:56.694  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:56.694  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 14:41:56.694  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:56.694  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.694  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.694  7055  7256 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efabae not in the list
09-12 14:41:56.694  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.694  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.694  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:56.694  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:41:56.694  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.694  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.694  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.694  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:56.694  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 14:41:56.694  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.694  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.704  7055  7256 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 14:41:56.704  7055  7256 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-12 14:41:56.704  7055  7256 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 14:41:56.704  7055  7256 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-12 14:41:56.704  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 14:41:56.704  7055  7256 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-12 14:41:56.704  7055  7256 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 14:41:56.704  7055  7256 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-12 14:41:56.704  7055  7256 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 14:41:56.704  7055  7256 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 14:41:56.704  7055  7256 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,09-12 14:41:56.704  7055  7256 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 14:41:56.704  7055  7256 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 14:41:56.704  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-12 14:41:56.704  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-12 14:41:56.714  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-12 14:41:56.714  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-12 14:41:56.714  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-12 14:41:56.714  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-12 14:41:56.714  7055  7256 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,09-12 14:41:56.714  7055  7256 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 14:41:56.714  7055  7256 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-12 14:41:56.714  7055  7256 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:56.714  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:56.714  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 14:41:56.714  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:56.714  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.714  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.714  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-12 14:41:56.714  7055  7303 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1394)
09-12 14:41:56.714  7055  7256 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efabae not in the list
09-12 14:41:56.714  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.714  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.714  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:56.714  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.714  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.714  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.714  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:56.714  7055  7304 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1394
09-12 14:41:56.714  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:56.714  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:56.714  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.714  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
,09-12 14:41:56.714  7055  7256 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-12 14:41:56.714  7055  7256 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:56.714  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:56.714  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 14:41:56.714  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:56.714  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.714  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.714  7055  7256 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efabae not in the list
09-12 14:41:56.714  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.714  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.714  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:56.714  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.714  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.714  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.714  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:56.714  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:56.714  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:56.714  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.714  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
,09-12 14:41:56.724  7055  7256 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,09-12 14:41:56.724  7055  7256 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:56.724  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:56.724  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:41:56.724  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:56.724  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.724  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.724  7055  7256 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efabae not in the list
09-12 14:41:56.724  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.724  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.724  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:56.724  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.724  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.724  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.724  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:56.724  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:56.724  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:56.724  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.724  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
,09-12 14:41:56.724  7055  7256 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-12 14:41:56.724  7055  7256 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-12 14:41:56.724  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 14:41:56.724  7055  7256 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-12 14:41:56.724  7055  7256 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 14:41:56.724  7055  7256 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,09-12 14:41:56.724  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 14:41:56.724  7055  7256 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-12 14:41:56.724  7055  7256 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 14:41:56.724  7055  7256 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 14:41:56.724  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-12 14:41:56.724  7055  7256 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-12 14:41:56.724  7055  7256 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:56.724  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:56.724  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:41:56.724  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:56.724  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:41:56.724  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.724  7055  7256 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efabae not in the list
09-12 14:41:56.724  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.724  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.724  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:56.724  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:41:56.724  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.724  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.724  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.724  7055  7303 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-12 14:41:56.724  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:56.724  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 14:41:56.724  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.724  7055  7303 D BluetoothSocket: connect(): myUserId = 0
09-12 14:41:56.724  7055  7303 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 14:41:56.724  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.724  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:56.724  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.724  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.724  7055  7256 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efabae not in the list
09-12 14:41:56.724  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.724  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.724  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:56.724  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.724  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.724  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 14:41:56.724  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.724  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:56.724  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.724  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.724  7055  7256 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efabae not in the list
09-12 14:41:56.724  7055  7256 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:56.724  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:56.724  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:41:56.724  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:56.724  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.724  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.724  7055  7256 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efabae not in the list
09-12 14:41:56.724  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.724  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.724  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:56.724  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.724  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.724  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.724  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.734  3211  3228 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:41:56.734  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:56.734  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:56.734  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.734  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.734  7055  7256 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections,
09-12 14:41:56.734  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:41:56.734  7055  7303 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
09-12 14:41:56.734  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-12 14:41:56.734  7055  7256 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 14:41:56.734  7055  7256 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-12 14:41:56.734  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 14:41:56.734  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-12 14:41:56.734  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:56.734  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 14:41:56.734  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 14:41:56.734  7055  7055 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 14:41:56.734  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 14:41:56.734  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.734  7055  7256 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-12 14:41:56.734  7055  7256 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efabae not in the list
09-12 14:41:56.734  7055  7055 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 14:41:56.734  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.734  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 14:41:56.734  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 14:41:56.734  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 14:41:56.734  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:41:56.734  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.734  7055  7305 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 14:41:56.734  7055  7305 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-12 14:41:56.734  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 14:41:56.734  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.734  7055  7055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 14:41:56.734  7055  7256 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:56.734  7055  7055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 14:41:56.734  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 14:41:56.734  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:41:56.734  7055  7055 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 14:41:56.734  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:56.734  7055  7055 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 14:41:56.734  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.734  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.734  7055  7256 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efabae not in the list
09-12 14:41:56.734  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.734  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.734  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:56.734  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.734  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.734  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:41:56.734  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.734  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:56.734  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:56.734  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.734  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.734  7055  7256 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-12 14:41:56.734  7055  7256 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 14:41:56.734  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 14:41:56.734  7055  7256 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 14:41:56.734  7055  7256 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:56.744  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:56.744  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:41:56.744  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:56.744  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.744  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.744  7055  7256 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efabae not in the list
09-12 14:41:56.744  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.744  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.744  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:56.744  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.744  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.744  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.744  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.744  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:56.744  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 14:41:56.744  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.744  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
,09-12 14:41:56.744  7055  7256 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 14:41:56.744  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:56.744  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:41:56.744  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:56.744  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.744  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.744  7055  7256 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efabae not in the list
09-12 14:41:56.744  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.744  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.744  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:56.744  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.744  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.744  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.744  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.744  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:56.744  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:56.744  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.744  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.744  7055  7256 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:56.744  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:56.744  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 14:41:56.744  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:56.744  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.744  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.744  7055  7256 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efabae not in the list
09-12 14:41:56.744  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.744  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.744  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:56.744  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.744  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:56.744  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:56.744  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:56.744  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:56.744  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:56.744  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:56.744  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22ef4d4f not in the list
09-12 14:41:56.754  7055  7256 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-12 14:41:56.754  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 14:41:56.754  7055  7256 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-12 14:41:56.754  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 14:41:56.754  7055  7256 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-12 14:41:56.754  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-12 14:41:56.754  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 14:41:56.754  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-12 14:41:56.754  7055  7256 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-12 14:41:56.754  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 14:41:56.754  7055  7256 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-12 14:41:56.754  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 14:41:56.754  7055  7256 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-12 14:41:56.754  7055  7256 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-12 14:41:56.754  7055  7256 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-12 14:41:56.754  7055  7256 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-12 14:41:56.754  7055  7256 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-12 14:41:56.754  7055  7256 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-12 14:41:56.754  7055  7256 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-12 14:41:56.754  7055  7256 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-12 14:41:56.754  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:41:56.754  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@30986199 added. We now have 2 listener(s)
09-12 14:41:56.754  7055  7256 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 14:41:56.754  7055  7256 D BluetoothAdapter: enable()
,09-12 14:41:56.754  7055  7256 D BluetoothAdapter: enable(): BT is already enabled..!
,09-12 14:41:56.764  1019  1266 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-12 14:41:56.764  1019  1266 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 14:41:56.764  1019  1266 D SecContentProvider2: mCursor = null
09-12 14:41:56.764  1019  1266 D WifiService: setWifiEnabled: true pid=7055, uid=10170
,09-12 14:41:56.774  1019  1266 W ActivityManager: Permission Denial: getCurrentUser() from pid=7055, uid=10170 requires android.permission.INTERACT_ACROSS_USERS,
,09-12 14:41:56.774  1019  1266 W WifiService: Failed getting userId using ActivityManagerNative,
09-12 14:41:56.774  1019  1266 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7055, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 14:41:56.774  1019  1266 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-12 14:41:56.774  1019  1266 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 14:41:56.774  1019  1266 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 14:41:56.774  1019  1266 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
,09-12 14:41:56.774  1019  1266 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-12 14:41:56.774  1019  1266 D SettingsProvider: name = wifi_on
,09-12 14:41:56.774  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:41:56.774  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@33f45c5e added. We now have 3 listener(s)
09-12 14:41:56.774  7055  7256 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 14:41:56.784  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 14:41:56.784  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@21e4283f added. We now have 4 listener(s)
09-12 14:41:56.784  7055  7256 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 14:41:56.784  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 14:41:56.784  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1222850c added. We now have 5 listener(s)
09-12 14:41:56.784  7055  7256 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 14:41:56.784  1019  1032 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-12 14:41:56.784  1019  1032 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-12 14:41:56.784  1019  1032 D SecContentProvider2: mCursor = null
09-12 14:41:56.794  1019  1032 D WifiService: setWifiEnabled: false pid=7055, uid=10170
09-12 14:41:56.794  1019  1032 D SettingsProvider: name = wifi_on
,09-12 14:41:56.794  1019  1129 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-12 14:41:56.794  1382  1382 I wpa_supplicant: reset timer : RESET_TIMER 0
09-12 14:41:56.794  1382  1382 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-12 14:41:56.804  1382  1382 I wpa_supplicant: P2P: Current p2p state = IDLE
09-12 14:41:56.804  1382  1382 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-12 14:41:56.804  7055  7256 D BluetoothAdapter: disable()
,09-12 14:41:56.804  1019  4367 D SettingsProvider: name = bluetooth_on
,09-12 14:41:56.804  1019  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 14:41:56.814  3211  3283 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-12 14:41:56.814  3211  3283 D BluetoothAdapterProperties: Setting state to 13
,09-12 14:41:56.814  3211  3283 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 14:41:56.814  3211  3283 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 14:41:56.814  3211  3283 D BluetoothAdapterService: updateAdapterState state is 13
09-12 14:41:56.814  1019  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 14:41:56.814  1019  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-12 14:41:56.814  1019  1504 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:56.814  1019  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:56.814  1019  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 14:41:56.824  3211  3211 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-12 14:41:56.824  3211  3211 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@ff01b4b, channel: 19, state: LISTENING
09-12 14:41:56.824  3211  3211 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@ff01b4b, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2efae4d3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@188ea928mSocket: android.net.LocalSocket@29386641 impl:android.net.LocalSocketImpl@137187e6 fd:FileDescriptor[80]
09-12 14:41:56.824  3211  3211 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@29386641 impl:android.net.LocalSocketImpl@137187e6 fd:FileDescriptor[80]
09-12 14:41:56.824  3211  3283 D BluetoothAdapterService: Autoconnection is available 
09-12 14:41:56.824  3211  3283 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-12 14:41:56.824  3211  3283 D BluetoothAdapterService: terminating service from this receiver
09-12 14:41:56.824  1019  1266 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-12 14:41:56.824  1019  1266 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:56.824  1019  1266 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:56.824  1019  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:41:56.824  3211  3283 D BluetoothAdapterProperties: onBluetoothDisable()
09-12 14:41:56.824  3211  3283 D BluetoothAdapterProperties: mDiscovering is false
,09-12 14:41:56.824  1019  1499 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-12 14:41:56.824  3211  3283 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-12 14:41:56.834  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 14:41:56.834  1382  1382 I wpa_supplicant: nl80211: Received scan results (9 BSSes)
,09-12 14:41:56.834  4827  4827 D BluetoothPbap: Proxy object disconnected,
09-12 14:41:56.834  4827  4827 D PbapServerProfile: Bluetooth service disconnected
,09-12 14:41:56.834  1019  1128 D WifiP2pService: InactiveState{ what=147461 }
09-12 14:41:56.834  1019  1129 E WifiNative-wlan0: do suspend true
09-12 14:41:56.834  1019  1128 D WifiP2pService: P2pEnabledState{ what=147461 }
09-12 14:41:56.834  1019  1128 D WifiP2pService: DefaultState{ what=147461 }
,09-12 14:41:56.834  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
09-12 14:41:56.834  1019  1019 I InputMethodManagerService: [BT Setting State] State =13
,09-12 14:41:56.844  3211  3286 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-12 14:41:56.844  3211  3286 D BluetoothAdapterProperties: Scan Mode:20
,09-12 14:41:56.844  1183  1183 D BluetoothTile:  onBluetoothStateChange:
,09-12 14:41:56.844  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 14:41:56.844  1183  1183 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-12 14:41:56.844  1183  1183 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:41:56.844  7055  7256 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:41:56.844  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:41:56.844  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:41:56.844  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:41:56.844  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:41:56.844  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:41:56.844  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:41:56.844  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 14:41:56.844  1183  1183 D BluetoothTile:  getBluetoothState : 13
,09-12 14:41:56.844  1183  1710 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 14:41:56.854  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:41:56.854  7055  7256 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 14:41:56.854  1183  1710 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 14:41:56.854  7055  7256 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 14:41:56.854  1971  1971 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 14:41:56.854  1183  1710 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-12 14:41:56.854  4827  4827 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 14:41:56.854  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:56.854  1019  1266 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-12 14:41:56.854  1019  3798 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-12 14:41:56.854  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-12 14:41:56.854  1183  1183 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-12 14:41:56.864  3211  3283 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-12 14:41:56.864  3211  3283 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-12 14:41:56.864  3211  3283 E bt-btif : cmd socket is not created
,09-12 14:41:56.864  3211  5278 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 14:41:56.864  3211  3287 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,09-12 14:41:56.864  7055  7303 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@11a5e06a, channel: -1, state: INIT
09-12 14:41:56.864  7055  7303 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@11a5e06a, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@9fd095b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@30f8e5f8mSocket: android.net.LocalSocket@5dbaad1 impl:android.net.LocalSocketImpl@1b399936 fd:FileDescriptor[106]
09-12 14:41:56.864  7055  7303 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@5dbaad1 impl:android.net.LocalSocketImpl@1b399936 fd:FileDescriptor[106]
09-12 14:41:56.864  7055  7303 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1394)
09-12 14:41:56.864  3211  3283 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-12 14:41:56.864  3211  3211 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@24b92fd4, channel: 5, state: LISTENING
,09-12 14:41:56.864  3211  3211 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@24b92fd4, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@bde810, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2164257dmSocket: android.net.LocalSocket@36be3c72 impl:android.net.LocalSocketImpl@3796a8c3 fd:FileDescriptor[82]
09-12 14:41:56.864  3211  3211 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@36be3c72 impl:android.net.LocalSocketImpl@3796a8c3 fd:FileDescriptor[82]
,09-12 14:41:56.874  7055  7055 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:41:56.874  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:41:56.874  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:41:56.874  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:41:56.874  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:41:56.874  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:41:56.874  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:41:56.874  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:41:56.874  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 14:41:56.874  3211  3211 I BtOppRfcommListener: stopping Accept Thread
09-12 14:41:56.874  3211  3211 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1c637540, channel: 12, state: LISTENING
09-12 14:41:56.874  3211  3211 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1c637540, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2273441a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@13929c79mSocket: android.net.LocalSocket@3fafadbe impl:android.net.LocalSocketImpl@3b10e1f fd:FileDescriptor[85]
09-12 14:41:56.874  3211  3211 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3fafadbe impl:android.net.LocalSocketImpl@3b10e1f fd:FileDescriptor[85]
09-12 14:41:56.874  3211  5278 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-12 14:41:56.874  7055  7055 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:41:56.874  7055  7055 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 14:41:56.874  3211  3287 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
09-12 14:41:56.874  3211  3287 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
09-12 14:41:56.874  3211  3287 W bt-btif : invalid rfc slot id: 4
,09-12 14:41:56.874  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:56.874  4827  4827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 14:41:56.874  1019  3798 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-12 14:41:56.874  1019  3798 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 14:41:56.874  3211  3211 V BluetoothOppManager: cleanUp...
,09-12 14:41:56.874  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:56.884  3211  3287 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-12 14:41:56.884  3211  3287 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 14:41:56.884  3211  3287 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 14:41:56.884  3211  3287 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-12 14:41:56.884  3211  3287 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 14:41:56.884  3211  3287 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 14:41:56.884  1019  3798 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:56.884  1019  3798 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:56.884  1019  3798 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 14:41:56.884  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:56.884  1639  1639 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 14:41:56.894  1019  1128 D WifiP2pService: InactiveState{ what=143375 }
,09-12 14:41:56.894  1019  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
09-12 14:41:56.894  4827  4827 D DockEventReceiver: finishStartingService: stopping service
,09-12 14:41:56.894   279   986 D CommandListener: Clearing all IP addresses on wlan0
,09-12 14:41:56.904  1639  2532 V NativeCrypto: Read error: ssl=0xb8c49d98: I/O error during system call, Connection timed out
,09-12 14:41:56.904  1639  2532 V NativeCrypto: SSL shutdown failed: ssl=0xb8c49d98: I/O error during system call, Broken pipe
,09-12 14:41:56.904  1183  1183 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 14:41:56.904  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-12 14:41:56.904  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:41:56.904  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:41:56.904  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:41:56.904  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:41:56.904  4827  4827 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 14:41:56.904  1019  1131 E ConnectivityService: updateNetworkInfo()
09-12 14:41:56.904  1019  1131 E ConnectivityService: updateNetworkInfo()
09-12 14:41:56.904  1019  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-12 14:41:56.904  1019  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2,
,09-12 14:41:56.914  1019  1139 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,09-12 14:41:56.914  1183  1183 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:41:56.914  1183  1183 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-12 14:41:56.924  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-12 14:41:56.924  1019  1720 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-9ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:41:56.924  1019  1720 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-9ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 14:41:56.924  1019  1720 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-12 14:41:56.924  1019  1720 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 14:41:56.924  1019  1720 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,09-12 14:41:56.934  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 1
,09-12 14:41:56.934  1019  1154 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler },
09-12 14:41:56.934  1019  1128 D WifiP2pService: InactiveState{ what=131204 }
09-12 14:41:56.934  1019  1720 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-12 14:41:56.934  1019  1128 D WifiP2pService: P2pEnabledState{ what=131204 }
09-12 14:41:56.934  1019  1720 I qtaguid : Tagging socket 360 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1019, getuid(): 1000,
,09-12 14:41:56.934  1019  1019 D RttService: SCAN_AVAILABLE : 1
,09-12 14:41:56.934  1019  1504 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
09-12 14:41:56.934  1019  1155 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:41:56.934  1019  1128 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-12 14:41:56.934  1019  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:56.934  1019  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:56.934  1019  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:56.934  1019  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:56.934  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 14:41:56.934  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 14:41:56.934  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
09-12 14:41:56.944  1019  1720 I qtaguid : Untagging socket 360
09-12 14:41:56.944  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:41:56.944  1019  1720 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-12 14:41:56.944  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:41:56.944  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:41:56.944  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:41:56.954  7312  7312 E Zygote  : MountEmulatedStorage()
09-12 14:41:56.954  7312  7312 E Zygote  : v2
,09-12 14:41:56.954  7312  7312 I libpersona: KNOX_SDCARD checking this for 10055
09-12 14:41:56.954  7312  7312 I libpersona: KNOX_SDCARD not a persona
,09-12 14:41:56.954  7312  7312 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-12 14:41:56.954  1019  1504 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7312 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
09-12 14:41:56.954  7312  7312 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 14:41:56.954  7312  7312 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 14:41:56.964  1019  1129 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-12 14:41:56.974  1019  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:41:56.974  1019  1049 D WifiDisplayAdapter: onP2pDisconnected
,09-12 14:41:56.974  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED,
09-12 14:41:56.974  1019  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-12 14:41:56.974  1019  1128 D WifiP2pService: P2pDisablingState
,09-12 14:41:56.984  1019  1128 D WifiP2pService: P2pDisablingState{ what=147458 }
,09-12 14:41:56.984  1019  1128 D WifiP2pService: p2p socket connection lost
09-12 14:41:56.984  1019  1129 E WifiNative-wlan0: do suspend true
09-12 14:41:56.984  1019  1128 D WifiP2pService: P2pDisabledState
,09-12 14:41:56.984  7312  7312 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:41:56.984  7312  7312 D ActivityThread: Added TimaKeyStore provider
,09-12 14:41:56.994  1019  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 14:41:56.994  1019  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-12 14:41:56.994  1019  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,09-12 14:41:56.994  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 14:41:56.994  1019  1049 D WifiDisplayController: disconnect
09-12 14:41:56.994  1019  1049 D WifiDisplayController: updateConnection
09-12 14:41:56.994  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 14:41:56.994  1019  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-12 14:41:56.994  1019  1049 D WifiDisplayAdapter: onP2pDisconnected
09-12 14:41:56.994  1019  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 14:41:56.994  1019  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
09-12 14:41:56.994  1019  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 14:41:56.994  1183  1183 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-12 14:41:56.994  1019  4366 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 14:41:56.994  1183  1183 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-12 14:41:57.014  7312  7312 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-12 14:41:57.014  1019  1128 D WifiP2pService: P2pDisabledState{ what=143375 }
09-12 14:41:57.014  1019  1128 D WifiP2pService: DefaultState{ what=143375 }
,09-12 14:41:57.024  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 14:41:57.024  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 14:41:57.024  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-12 14:41:57.024  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:41:57.024  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:41:57.024  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:41:57.024  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:41:57.044   279   982 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
09-12 14:41:57.044   279   982 D Netd    : getNetworkForDns: using netid 0 for uid 1000
09-12 14:41:57.044  1019  1131 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-12 14:41:57.044  1019  1131 V NetworkStats: updateIfacesLocked()
09-12 14:41:57.044  1019  1131 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:41:57.044  1019  1131 V NetworkStats: performPollLocked(flags=0x1)
09-12 14:41:57.044  1019  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 14:41:57.044  1019  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 14:41:57.044   279   986 D CommandListener: Clearing all IP addresses on wlan0
,09-12 14:41:57.044  7312  7312 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
09-12 14:41:57.044  1019  1131 V NetworkStats: performPollLocked() took 6ms
09-12 14:41:57.044  1019  1131 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 14:41:57.044  7312  7312 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-12 14:41:57.044  7312  7312 D UserAnalysis: Create SecureDbHelper
09-12 14:41:57.044  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-12 14:41:57.054  1382  1382 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-12 14:41:57.054  1019  1720 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-12 14:41:57.054  1019  1720 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-12 14:41:57.054  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit,
09-12 14:41:57.054  1019  1131 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
09-12 14:41:57.054  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:41:57.054  1019  1720 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 14:41:57.054  1183  1704 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-12 14:41:57.054  1019  1131 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:41:57.054  1019  1048 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-12 14:41:57.054  1019  1131 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-12 14:41:57.054  1019  1128 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-12 14:41:57.054  1019  1131 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-12 14:41:57.054  1452  1452 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-12 14:41:57.064  1019  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-12 14:41:57.054  1452  1452 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-12 14:41:57.064  1019  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-12 14:41:57.064  1019  1129 D SecContentProvider2: mCursor = null
09-12 14:41:57.064  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-12 14:41:57.064  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 14:41:57.064  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 14:41:57.064  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:41:57.064  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:41:57.064  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:41:57.064  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:41:57.064  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-12 14:41:57.064  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 14:41:57.064  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 14:41:57.064  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:41:57.074  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:41:57.074  4827  4827 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 14:41:57.074  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:41:57.074  1183  1183 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 14:41:57.074  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:41:57.074  1183  1710 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-12 14:41:57.074  1183  1183 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 14:41:57.074  1183  1183 D HotspotTile: onReceive : 0, 0
09-12 14:41:57.074  1183  1183 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-12 14:41:57.074  1019  1129 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-12 14:41:57.074  1019  1019 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-12 14:41:57.074  1019  1134 D Tethering: MasterInitialState.processMessage what=3
09-12 14:41:57.074  7312  7312 D IntelligenceServiceApplication: onCreate()
,09-12 14:41:57.074  7055  7055 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:41:57.084  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:41:57.084  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:41:57.084  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:41:57.084  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:41:57.084  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:41:57.084  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:41:57.084  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:41:57.084  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 14:41:57.084  7055  7055 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:41:57.084  1019  1126 V NetworkStats: updateIfacesLocked()
09-12 14:41:57.084  7055  7055 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:41:57.084  1019  1126 V NetworkStats: performPollLocked(flags=0x1)
09-12 14:41:57.084  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:41:57.084  1019  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 14:41:57.084  1019  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-12 14:41:57.084  1019  1131 D ConnectivityService: nai.networkMonitor.doQuit()
09-12 14:41:57.084  1019  1131 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-12 14:41:57.084  1019  1131 E ConnectivityService: updateNetworkInfo()
09-12 14:41:57.084  1019  1131 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 14:41:57.084  1019  1131 E ConnectivityService: updateNetworkInfo()
,09-12 14:41:57.084  3211  3283 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-12 14:41:57.084  1019  1126 V NetworkStats: performPollLocked() took 4ms
09-12 14:41:57.084  3211  3283 D BtConfig.SecureMode: isSecureModeOn:false
09-12 14:41:57.084  3211  3283 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-12 14:41:57.084  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
09-12 14:41:57.084  3211  3283 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
09-12 14:41:57.084  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-12 14:41:57.084  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-12 14:41:57.084  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:41:57.084  3211  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-12 14:41:57.084  1019  1048 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false,
09-12 14:41:57.084  1183  1183 D StatusBar.NetworkController: EthernetConnected: false
09-12 14:41:57.084  1183  1183 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-12 14:41:57.084  1183  1183 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-12 14:41:57.084  1183  1183 D StatusBar.NetworkController: updateDataNetType()
,09-12 14:41:57.084  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:41:57.084  1019  1127 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-12 14:41:57.084  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:41:57.084  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:41:57.084  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:41:57.084  7055  7055 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:41:57.084  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:41:57.084  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:41:57.084  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:41:57.084  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:41:57.084  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:41:57.084  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:41:57.084  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:41:57.084  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 14:41:57.084  7312  7312 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-12 14:41:57.094  7055  7055 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:41:57.094  7055  7055 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 14:41:57.094  1019  4368 I ActivityManager: Killing 6833:com.google.android.apps.docs/u0a87 (adj 15): empty #21
09-12 14:41:57.094  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-12 14:41:57.094  1183  1183 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-12 14:41:57.094  1183  1183 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-12 14:41:57.094  1183  1183 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 22 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-12 14:41:57.094  1183  1183 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
,09-12 14:41:57.094  1183  1183 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,09-12 14:41:57.094  1019  1139 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:57.094  1019  1139 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 14:41:57.094  1019  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:57.094  1019  1139 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-12 14:41:57.094  1019  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 14:41:57.104  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-12 14:41:57.104  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-12 14:41:57.104  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 14:41:57.104  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 14:41:57.104  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 14:41:57.104  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:41:57.104  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:41:57.104  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:41:57.104  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:41:57.104  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:41:57.104  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 14:41:57.104  3211  3211 D HeadsetService: Received stop request...Stopping profile...
,09-12 14:41:57.104  1019  1347 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
09-12 14:41:57.104  3211  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-12 14:41:57.104  1019  1347 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:57.104  1019  1347 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:57.104  1019  1347 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:57.104  1019  1347 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:57.114  7331  7331 E Zygote  : MountEmulatedStorage()
09-12 14:41:57.114  7331  7331 E Zygote  : v2
09-12 14:41:57.114  7331  7331 I libpersona: KNOX_SDCARD checking this for 10105
09-12 14:41:57.114  7331  7331 I libpersona: KNOX_SDCARD not a persona
,09-12 14:41:57.114  7331  7331 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 14:41:57.124  7331  7331 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 14:41:57.124  7331  7331 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-12 14:41:57.124  1019  1347 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7331 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-12 14:41:57.124  1019  1507 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-12 14:41:57.124  1019  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 14:41:57.124  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-12 14:41:57.124  7312  7312 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
09-12 14:41:57.124  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
09-12 14:41:57.134  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:57.134  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:57.134  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:41:57.134  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,09-12 14:41:57.134  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 14:41:57.134  3211  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-12 14:41:57.134  1019  4368 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 14:41:57.134  1019  4368 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 14:41:57.134  1019  4368 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:57.134  1019  4368 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:57.134  1019  4368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:41:57.134  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-12 14:41:57.134  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-12 14:41:57.134  3211  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-12 14:41:57.134  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-12 14:41:57.134  1019  1266 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 14:41:57.134  1019  1266 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-12 14:41:57.134  4827  4827 D HeadsetProfile: Bluetooth service disconnected
,09-12 14:41:57.134  1019  1266 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:57.134  1019  1266 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:57.134  1019  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:41:57.144  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,09-12 14:41:57.144  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-12 14:41:57.144  1382  1382 I wpa_supplicant: Blacklist: Clear (all) 
09-12 14:41:57.144  3211  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-12 14:41:57.144  7312  7312 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-12 14:41:57.144  1019  1507 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:57.144  1019  1507 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 14:41:57.144  1019  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:57.144  1019  1507 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-12 14:41:57.144  1019  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 14:41:57.144  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-12 14:41:57.144  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 14:41:57.144  3211  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-12 14:41:57.144  1019  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
09-12 14:41:57.144  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-12 14:41:57.144  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:57.144  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:57.144  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:41:57.144  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-12 14:41:57.144  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService,
,09-12 14:41:57.154  3211  3283 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-12 14:41:57.154  1019  1341 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 14:41:57.154  1019  1341 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:57.154  1019  1341 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-12 14:41:57.154  1019  1341 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:57.154  1019  1341 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 14:41:57.154  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-12 14:41:57.154  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 14:41:57.154  3211  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-12 14:41:57.154  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-12 14:41:57.154  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-12 14:41:57.154  3211  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-12 14:41:57.154  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-12 14:41:57.154  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-12 14:41:57.154  7331  7331 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 14:41:57.154  3211  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-12 14:41:57.154  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-12 14:41:57.154  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-12 14:41:57.154  7331  7331 D ActivityThread: Added TimaKeyStore provider
,09-12 14:41:57.154  3211  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-12 14:41:57.154  3211  3283 D BluetoothAdapterState: Stopping profile services that were post enabled
09-12 14:41:57.154  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-12 14:41:57.154  3211  3211 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 14:41:57.154  3211  3211 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-12 14:41:57.154  3211  3211 D A2dpService: Received stop request...Stopping profile...
09-12 14:41:57.154  3211  3353 D A2dpStateMachine: Exit Disconnected: -1
,09-12 14:41:57.164  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
,09-12 14:41:57.164  1019  1019 D BluetoothA2dp: Proxy object disconnected
,09-12 14:41:57.174  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-12 14:41:57.174  3211  3211 D HidService: Received stop request...Stopping profile...
09-12 14:41:57.174  3211  3211 D HidService: Stopping Bluetooth HidService
09-12 14:41:57.174  3211  3211 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 14:41:57.174  3211  3211 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-12 14:41:57.174  3211  3211 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 14:41:57.174  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
09-12 14:41:57.174  4827  4827 D BluetoothA2dp: Proxy object disconnected
09-12 14:41:57.174  4827  4827 D A2dpProfile: Bluetooth service disconnected
,09-12 14:41:57.174  4827  4827 D BluetoothInputDevice: Proxy object disconnected
,09-12 14:41:57.174  4827  4827 D HidProfile: Bluetooth service disconnected
,09-12 14:41:57.184  1382  1382 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-12 14:41:57.184  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 14:41:57.184  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
,09-12 14:41:57.184  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
,09-12 14:41:57.184  3211  3211 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 14:41:57.184  3211  3211 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-12 14:41:57.184  3211  3211 D HealthService: Received stop request...Stopping profile...
09-12 14:41:57.184  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
,09-12 14:41:57.184  3211  3211 D PanService: Received stop request...Stopping profile...
09-12 14:41:57.184  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
,09-12 14:41:57.194  4827  4827 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 14:41:57.194  4827  4827 D PanProfile: Bluetooth service disconnected
,09-12 14:41:57.194  1019  1019 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 14:41:57.194  3211  3211 D BluetoothMapService: Received stop request...Stopping profile...
,09-12 14:41:57.194  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
,09-12 14:41:57.194  3211  3211 D SapService: Received stop request...Stopping profile...
,09-12 14:41:57.194  3211  3211 D SapService: Stopping Bluetooth SapService
09-12 14:41:57.194  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
,09-12 14:41:57.204  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-12 14:41:57.204  3211  3211 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 14:41:57.204  3211  3211 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-12 14:41:57.204  3211  3211 D BluetoothA2dp: Proxy object disconnected
09-12 14:41:57.204  3211  3211 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-12 14:41:57.204  3211  3354 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-12 14:41:57.204  3211  3211 I GKI_LINUX: GKI_exit_task 2 done
09-12 14:41:57.204  3211  3211 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-12 14:41:57.204  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-12 14:41:57.204  3211  3211 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-12 14:41:57.204  3211  3211 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 14:41:57.204  3211  3211 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-12 14:41:57.204  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-12 14:41:57.204  3211  3211 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-12 14:41:57.204  3211  3211 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 14:41:57.204  3211  3211 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-12 14:41:57.204  3211  3211 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 14:41:57.204  3211  3211 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 14:41:57.204  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-12 14:41:57.204  3211  3211 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-12 14:41:57.204  3211  3211 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 14:41:57.204  3211  3211 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-12 14:41:57.204  3211  3211 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 14:41:57.204  3211  3211 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 14:41:57.204  4827  4827 D BluetoothMap: Proxy object disconnected
09-12 14:41:57.204  4827  4827 D MapProfile: Bluetooth service disconnected
09-12 14:41:57.204  4827  4827 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-12 14:41:57.204  4827  4827 D SapProfile: Bluetooth service disconnected
,09-12 14:41:57.204  1382  1382 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-12 14:41:57.204  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-12 14:41:57.204  3211  3211 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-12 14:41:57.204  3211  3211 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-12 14:41:57.204  3211  3211 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-12 14:41:57.204  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-12 14:41:57.204  3211  3211 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-12 14:41:57.204  1382  1382 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-12 14:41:57.204  1382  1382 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-12 14:41:57.204  1382  1382 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-12 14:41:57.204  1382  1382 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-12 14:41:57.204  3211  3211 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-12 14:41:57.204  3211  3211 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-12 14:41:57.214  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 14:41:57.214  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 14:41:57.214  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-12 14:41:57.214  1019  1134 D Tethering: InitialState.processMessage what=4
,09-12 14:41:57.214  3211  3283 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-12 14:41:57.214  3211  3283 D BluetoothAdapterProperties: Setting state to 10
09-12 14:41:57.214  3211  3283 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-12 14:41:57.214  3211  3283 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 14:41:57.214  3211  3283 D BluetoothAdapterService: updateAdapterState state is 10
,09-12 14:41:57.214  3211  3283 D BluetoothAdapterService: Autoconnection is available 
09-12 14:41:57.214  3211  3283 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-12 14:41:57.214  3211  3283 I BluetoothAdapterState: Entering OffState
09-12 14:41:57.214  1639  1657 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 14:41:57.214  1639  1657 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 14:41:57.214  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 14:41:57.214  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 14:41:57.214  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-12 14:41:57.214  1019  1134 E Tethering: No numeric data
,09-12 14:41:57.214  1019  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 14:41:57.214  1019  1134 D Tethering: clearTetheredNotification()
09-12 14:41:57.214  4827  4840 D BluetoothMap: onBluetoothStateChange: up=false
,09-12 14:41:57.224  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 14:41:57.224  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 14:41:57.224  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
09-12 14:41:57.224  1019  1126 V NetworkStats: performPollLocked(flags=0x1)
09-12 14:41:57.224  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 14:41:57.224  1019  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 14:41:57.224  1019  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 14:41:57.224  1019  1126 V NetworkStats: performPollLocked() took 4ms
,09-12 14:41:57.224  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:41:57.224  1183  1183 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 14:41:57.224  1183  1183 D HotspotTile: updateTetherState():false, false
,09-12 14:41:57.234  4827  4838 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 14:41:57.234  4827  4838 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 14:41:57.234  4827  4840 D Bluetoothsap: onBluetoothStateChange: up=false
09-12 14:41:57.234  4827  4840 D Bluetoothsap: Unbinding service...
,09-12 14:41:57.234  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:41:57.234  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 14:41:57.234  1452  4774 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 14:41:57.234  1452  4774 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 14:41:57.234  1183  1192 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 14:41:57.234  1183  1192 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 14:41:57.234  7055  7055 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 14:41:57.234  4827  4838 D BluetoothPbap: onBluetoothStateChange: up=false
,09-12 14:41:57.244  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 14:41:57.244  4827  4840 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-12 14:41:57.244  4827  4838 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 14:41:57.244  1019  1048 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 14:41:57.244  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 14:41:57.244  3211  3363 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 14:41:57.244  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 14:41:57.244  3211  3363 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 14:41:57.254  1442  1471 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 14:41:57.254  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 14:41:57.254  1442  1471 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 14:41:57.254  3211  3346 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 14:41:57.254  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 14:41:57.254  1647  1659 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 14:41:57.254  1647  1659 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 14:41:57.254  1433  1451 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 14:41:57.254  1433  1451 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 14:41:57.254  1019  1048 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 14:41:57.254  1019  1048 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 14:41:57.254  7055  7069 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 14:41:57.254  7055  7069 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 14:41:57.254  7055  7069 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-12 14:41:57.254  7055  7069 D BluetoothLeAdvertiser: Exit stop advertising
09-12 14:41:57.254  7055  7069 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-12 14:41:57.254  7055  7069 D BluetoothLeScanner: Exiting stopAllScan
09-12 14:41:57.254  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 14:41:57.254  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 14:41:57.264  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-12 14:41:57.264  1019  1019 I InputMethodManagerService: [BT Setting State] State =10
09-12 14:41:57.264  1019  1019 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-12 14:41:57.264  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 14:41:57.264  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 14:41:57.264  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 14:41:57.264  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 14:41:57.264  1183  1183 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-12 14:41:57.264  1183  1183 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:41:57.264  1183  1183 D BluetoothTile:  getBluetoothState : 10
,09-12 14:41:57.264  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 14:41:57.264  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 14:41:57.274  4827  4827 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:41:57.274  1971  1971 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 14:41:57.274  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 14:41:57.274  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 14:41:57.274  1019  1499 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 14:41:57.274  1019  1489 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-12 14:41:57.274  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 14:41:57.274  1183  1183 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 14:41:57.274  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 14:41:57.274  7055  7055 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 14:41:57.274  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:41:57.274  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:41:57.274  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:41:57.274  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:41:57.274  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:41:57.274  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:41:57.274  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:41:57.274  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 14:41:57.274  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-12 14:41:57.274  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 14:41:57.284  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 14:41:57.284  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 14:41:57.284  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:57.284  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 14:41:57.284  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 14:41:57.284  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 14:41:57.284  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 14:41:57.284  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 14:41:57.284  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 14:41:57.284  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-12 14:41:57.284  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 14:41:57.284  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 14:41:57.304   258   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-12 14:41:57.304   258   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 14:41:57.304  7331  7366 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-12 14:41:57.314   258   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-12 14:41:57.314   258   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 14:41:57.314  7331  7366 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-12 14:41:57.364   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 14:41:57.404  1382  1382 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 14:41:57.454  7331  7331 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.io.File.exists(File.java:363)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 14:41:57.454  7331  7331 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 14:41:57.454  7331  7331 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 14:41:57.454  7331  7331 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.q.e.b(PG:170)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 14:41:57.454  7331  7331 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.q.k.d(PG:583)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.q.e.b(PG:170)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 14:41:57.454  7331  7331 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.io.File.exists(File.java:363)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 14:41:57.454  7331  7331 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.io.File.exists(File.java:363)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread.handl,eBindApplication(ActivityThread.java:5256)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 14:41:57.454  7331  7331 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 14:41:57.454  7331  7331 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 14:41:57.464  1019  4368 I ActivityManager: Killing 6865:com.google.android.partnersetup/u0a14 (adj 15): empty #21
09-12 14:41:57.464  1019  1347 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 14:41:57.464  1019  1347 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-12 14:41:57.474  1019  1347 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:57.474  1019  1347 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:57.474  1019  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 14:41:57.474  2187  2187 I Hs20UtilService: Starting #8
09-12 14:41:57.474  2187  2202 I Hs20UtilService: Message received 5007
09-12 14:41:57.474  4827  4827 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 14:41:57.474  4827  4827 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-12 14:41:57.474  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-12 14:41:57.484  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 14:41:57.484  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 14:41:57.484  4827  4827 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-12 14:41:57.484  4827  4902 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-12 14:41:57.484  1019  1266 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:57.484  1019  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:57.484  1019  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
09-12 14:41:57.484  1019  1266 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
09-12 14:41:57.484  1019  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:57.484  1019  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:57.484  1019  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:57.484  1019  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:57.494  1382  1382 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-12 14:41:57.504  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 14:41:57.504  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 14:41:57.504  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
09-12 14:41:57.504  7331  7367 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
09-12 14:41:57.514  7377  7377 E Zygote  : MountEmulatedStorage()
09-12 14:41:57.514  7377  7377 E Zygote  : v2
09-12 14:41:57.514  7377  7377 I libpersona: KNOX_SDCARD checking this for 10102
09-12 14:41:57.514  7377  7377 I libpersona: KNOX_SDCARD not a persona
09-12 14:41:57.514  7377  7377 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 14:41:57.514  1019  1266 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7377 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-12 14:41:57.514  7377  7377 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 14:41:57.524  7377  7377 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-12 14:41:57.544  7377  7377 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:41:57.544  7377  7377 D ActivityThread: Added TimaKeyStore provider
,09-12 14:41:57.554  1019  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 14:41:57.554  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:57.554  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:57.554  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-12 14:41:57.564  7377  7377 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-12 14:41:57.574  1019  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 14:41:57.584  1019  1019 I ApplicationPolicy: updateDataUsageMap
,09-12 14:41:57.594  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:57.594  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:57.594  1019  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-12 14:41:57.604  1019  1043 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-12 14:41:57.604  1019  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-12 14:41:57.614  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 14:41:57.614  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 14:41:57.614  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 14:41:57.614  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:41:57.614  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:41:57.614  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:41:57.614  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:41:57.614  1183  1183 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 14:41:57.614  1183  1183 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-12 14:41:57.614  1183  1183 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-12 14:41:57.614  1183  1710 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 14:41:57.614  4827  4827 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 14:41:57.614  1183  1183 D HotspotTile: onReceive : 1, 0
,09-12 14:41:57.614  1647  2118 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 14:41:57.614  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:57.614  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:57.774  7377  7399 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-12 14:41:57.774  7377  7399 I Babel_SMS: MmsConfig.loadMmsSettings
,09-12 14:41:57.774  7377  7399 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-12 14:41:57.774  7377  7399 I Babel_SMS: MmsConfig.loadFromDatabase
,09-12 14:41:57.804  7377  7399 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-12 14:41:57.804  7377  7399 I Babel_SMS: MmsConfig.loadFromResources
,09-12 14:41:57.804  7377  7399 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-12 14:41:57.804  7377  7399 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-12 14:41:57.814  1019  1341 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,09-12 14:41:57.814  1019  1341 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-12 14:41:57.824  1019  1341 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:57.824  1019  1341 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:57.824  1019  1341 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-12 14:41:57.834  7377  7377 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 14:41:57.844  7377  7377 I Babel_Crash: startup - clean
,09-12 14:41:57.874  4827  4827 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-12 14:41:57.874  4827  4827 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 14:41:57.874  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 14:41:57.874  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-12 14:41:57.884  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 14:41:57.884  4827  4827 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 14:41:57.884  4827  4902 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 14:41:57.884  7377  7377 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 14:41:57.884  7377  7377 W AudioCapabilities: Unsupported mime audio/evrc
,09-12 14:41:57.894  1019  1504 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-12 14:41:57.894  1019  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:57.894  1019  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:57.894  1019  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:57.894  1019  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:57.904  7377  7377 W AudioCapabilities: Unsupported mime audio/qcelp,
,09-12 14:41:57.914  7402  7402 E Zygote  : MountEmulatedStorage()
,09-12 14:41:57.914  7402  7402 E Zygote  : v2
09-12 14:41:57.914  7402  7402 I libpersona: KNOX_SDCARD checking this for 10064
09-12 14:41:57.914  7402  7402 I libpersona: KNOX_SDCARD not a persona
,09-12 14:41:57.914  7402  7402 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 14:41:57.914  7402  7402 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 14:41:57.914  7402  7402 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 14:41:57.914  1019  1504 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7402 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 14:41:57.924  7377  7377 W AudioCapabilities: Unsupported mime audio/mpeg-L1
09-12 14:41:57.924  7377  7377 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-12 14:41:57.924  7377  7377 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-12 14:41:57.924  7377  7377 W AudioCapabilities: Unsupported mime audio/x-ima
,09-12 14:41:57.924  7377  7377 W AudioCapabilities: Unsupported mime audio/qcelp
,09-12 14:41:57.934  7377  7377 W AudioCapabilities: Unsupported mime audio/evrc
,09-12 14:41:57.934  7402  7402 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:41:57.944  7377  7377 W VideoCapabilities: Unsupported mime video/wvc1
,09-12 14:41:57.944  7402  7402 D ActivityThread: Added TimaKeyStore provider
,09-12 14:41:57.944  7377  7377 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-12 14:41:57.954  7377  7377 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
09-12 14:41:57.954  7402  7402 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-12 14:41:57.954  7377  7377 W VideoCapabilities: Unsupported mime video/wvc1
,09-12 14:41:57.954  7377  7377 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-12 14:41:57.964  7377  7377 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-12 14:41:57.964  7377  7377 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-12 14:41:57.964  7377  7377 W VideoCapabilities: Unsupported mime video/mp43
,09-12 14:41:57.964  7402  7402 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 14:41:57.974  7377  7377 W VideoCapabilities: Unsupported mime video/sorenson
,09-12 14:41:57.974  7402  7402 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-12 14:41:57.974  7377  7377 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-12 14:41:57.984  7377  7377 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-12 14:41:58.004  7402  7402 D FileShare-Client: Outbound.stopDelayTimer - 
,09-12 14:41:58.004  1019  1031 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-12 14:41:58.014  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:58.014  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:58.014  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:58.014  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:58.014  7377  7377 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-12 14:41:58.014  7377  7377 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 14:41:58.024  7377  7377 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 14:41:58.024  1019  1031 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7417 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 14:41:58.024  1019  1031 I ActivityManager: Killing 6892:com.sec.pcw.device/1000 (adj 15): empty #21
,09-12 14:41:58.024  7417  7417 E Zygote  : MountEmulatedStorage()
09-12 14:41:58.024  7417  7417 E Zygote  : v2
,09-12 14:41:58.024  7417  7417 I libpersona: KNOX_SDCARD checking this for 10065
09-12 14:41:58.034  7417  7417 I libpersona: KNOX_SDCARD not a persona
,09-12 14:41:58.034  7377  7377 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 14:41:58.034  7417  7417 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 14:41:58.034  1019  1489 I ActivityManager: Killing 6776:com.google.android.apps.plus/u0a117 (adj 15): empty #21
09-12 14:41:58.034  7377  7377 I vclib   : onServiceConnected
09-12 14:41:58.034  7417  7417 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 14:41:58.034  7417  7417 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 14:41:58.054  7417  7417 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-12 14:41:58.054  7417  7417 D ActivityThread: Added TimaKeyStore provider
,09-12 14:41:58.074  7417  7417 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 14:41:58.074  1019  4368 I ActivityManager: Killing 6938:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,09-12 14:41:58.084  1019  4366 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 14:41:58.084  1019  4366 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 14:41:58.084  1019  4366 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:58.084  1019  4366 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:58.084  1019  4366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 14:41:58.094  2187  2187 I Hs20UtilService: Starting #9
,09-12 14:41:58.094  4827  4827 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-12 14:41:58.094  4827  4827 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-12 14:41:58.094  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 14:41:58.094  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 14:41:58.094  2187  2202 I Hs20UtilService: Message received 5007
09-12 14:41:58.094  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 14:41:58.094  4827  4827 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 14:41:58.094  4827  4902 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 14:41:58.104  1019  1489 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 14:41:58.104  1019  1489 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 14:41:58.104  1019  1489 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:58.104  1019  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 14:41:58.104  1019  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 14:41:58.104  1019  4366 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,09-12 14:41:58.104  1019  4366 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:58.114  2187  2187 I Hs20UtilService: Starting #10
09-12 14:41:58.114  1019  4366 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:58.114  1019  4366 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:58.114  1019  4366 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:58.114  2187  2202 I Hs20UtilService: Message received 5011
,09-12 14:41:58.124  7432  7432 E Zygote  : MountEmulatedStorage(),
09-12 14:41:58.124  7432  7432 E Zygote  : v2
,09-12 14:41:58.124  7432  7432 I libpersona: KNOX_SDCARD checking this for 1000
09-12 14:41:58.124  7432  7432 I libpersona: KNOX_SDCARD not a persona,
,09-12 14:41:58.124  7432  7432 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 14:41:58.124  1019  4366 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7432 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-12 14:41:58.124  7432  7432 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 14:41:58.134  7432  7432 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-12 14:41:58.154   304   304 I art     : Explicit concurrent mark sweep GC freed 8710(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 654us total 25.065ms
,09-12 14:41:58.164  1019  1046 D Tethering: interfaceRemoved wlan0
,09-12 14:41:58.164  1019  1046 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-12 14:41:58.164  7432  7432 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:41:58.164  7432  7432 D ActivityThread: Added TimaKeyStore provider
,09-12 14:41:58.174   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 17.841ms
,09-12 14:41:58.174  5932  5932 D FactoryTest: Not factory mode
,09-12 14:41:58.184  5932  5932 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-12 14:41:58.184  5932  5932 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-12 14:41:58.184  5932  5932 D MTPRx   : still no open session command from host, so toast
,09-12 14:41:58.184  5932  5932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,09-12 14:41:58.184  5932  5932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,09-12 14:41:58.184  5932  5932 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:117846,
09-12 14:41:58.184  1019  4366 E PersonaManagerService: inState():  stateMachine is null !!
09-12 14:41:58.184  1019  4366 I PersonaManagerService: PersonaId don't exist,
09-12 14:41:58.184  1019  4366 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-12 14:41:58.194  1019  4366 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
09-12 14:41:58.194   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 657us total 18.236ms
,09-12 14:41:58.194  1019  4366 W ActivityManager: userId = 0, bbcId = -10000,
09-12 14:41:58.194  1019  4366 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:58.194  1019  4366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-12 14:41:58.194  1019  4366 W ActivityManager: mDVFSHelper.acquire()
,09-12 14:41:58.204  7432  7432 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 14:41:58.204  7432  7432 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-12 14:41:58.204  7432  7432 D SecurityLogAgent: StateMachine : Current State = 1
,09-12 14:41:58.214  1019  4366 D PersonaManager: isKioskContainerExistOnDevice
,09-12 14:41:58.224  1019  4366 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-12 14:41:58.224  1019  4366 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-12 14:41:58.224  1019  4366 D InputDispatcher: Focused application set to: xxxx
09-12 14:41:58.224  1019  4366 D InputDispatcher: Focus left window: 7055
,09-12 14:41:58.224  5932  5932 E MTPRx   : started activity for popup
,09-12 14:41:58.224  7432  7432 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 14:41:58.234  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-12 14:41:58.234  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-12 14:41:58.234  1019  4367 I ActivityManager: Killing 6978:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,09-12 14:41:58.244  1019  1507 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:58.244  1019  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 14:41:58.244  1019  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 14:41:58.244  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:58.244  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 14:41:58.244  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 14:41:58.244  5932  5932 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,09-12 14:41:58.244  5932  5932 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-12 14:41:58.244  5932  5932 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-12 14:41:58.244  5932  5932 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 14:41:58.244  5932  5932 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 14:41:58.244  5932  5932 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-12 14:41:58.254  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:58.254  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 14:41:58.254  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 14:41:58.254  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:58.254  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 14:41:58.264  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 14:41:58.264  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:58.264  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 14:41:58.264  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 14:41:58.264  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:58.274  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:58.274  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 14:41:58.274  5932  5932 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-12 14:41:58.274  1019  1341 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-12 14:41:58.274  1019  1341 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-12 14:41:58.274  1019  1341 D InputDispatcher: Focused application set to: xxxx
,09-12 14:41:58.274  1019  1341 D InputDispatcher: Focus entered window: 7055
,09-12 14:41:58.284  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-12 14:41:58.284  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-12 14:41:58.284  1019  4367 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-12 14:41:58.284  1019  4367 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@18a53873 attribute=null, token = android.os.BinderProxy@1701fe41
,09-12 14:41:58.284  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:58.284  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:58.284  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 14:41:58.284  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:58.284  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 14:41:58.284  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 14:41:58.284  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:58.284  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 14:41:58.294  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 14:41:58.294  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:58.294  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:58.294  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 14:41:58.294  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:58.294  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:58.294  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 14:41:58.294  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:58.294  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:58.294  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 14:41:58.304  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:58.304  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:58.304  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 14:41:58.304  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:58.304  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:58.304  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 14:41:58.304  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:58.304  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:58.304  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 14:41:58.314  4827  4827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 14:41:58.314  1019  1031 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-12 14:41:58.314  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 14:41:58.314  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:58.314  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 14:41:58.314  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 14:41:58.324  1639  1639 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 14:41:58.324  4827  4827 D DockEventReceiver: finishStartingService: stopping service
,09-12 14:41:58.324  4827  4827 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 14:41:58.324  1183  1183 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 14:41:58.334  1183  1183 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-12 14:41:58.334  5932  5932 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-12 14:41:58.344  5932  5932 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-12 14:41:58.344  5932  5932 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-12 14:41:58.344  1019  1504 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-12 14:41:58.344  1019  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:58.344  1019  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:58.344  1019  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:58.344  1019  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:58.354  7452  7452 E Zygote  : MountEmulatedStorage()
09-12 14:41:58.354  7452  7452 E Zygote  : v2
09-12 14:41:58.354  7452  7452 I libpersona: KNOX_SDCARD checking this for 1000
09-12 14:41:58.354  7452  7452 I libpersona: KNOX_SDCARD not a persona
09-12 14:41:58.354  7452  7452 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 14:41:58.364  7452  7452 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 14:41:58.364  1019  1504 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7452 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-12 14:41:58.364  7452  7452 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 14:41:58.364   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 14:41:58.384  7055  7055 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-12 14:41:58.384  7055  7055 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
09-12 14:41:58.384  7055  7055 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-12 14:41:58.384  7055  7055 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-12 14:41:58.384  1019  1031 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-12 14:41:58.384  1019  1031 D KnoxTimeoutHandler: postActiveUserChange for user 0
,09-12 14:41:58.384  1019  1031 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false,
09-12 14:41:58.384  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
09-12 14:41:58.384  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-12 14:41:58.394  7452  7452 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:41:58.394  7452  7452 D ActivityThread: Added TimaKeyStore provider
,09-12 14:41:58.394  7055  7055 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 14:41:58.404  7055  7055 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-12 14:41:58.404  7055  7055 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@15adbf1 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@19f8e037, 16908290=android.view.AbsSavedState$1@19f8e037}, android:focusedViewId=100}]}]
09-12 14:41:58.404  7055  7055 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-12 14:41:58.404  7055  7055 V ActivityThread: updateVisibility : ActivityRecord{a608b6b token=android.os.BinderProxy@e510de5 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-12 14:41:58.404  7055  7055 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-12 14:41:58.404  7055  7055 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-12 14:41:58.404  7055  7055 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@e510de5 time:118066
,09-12 14:41:58.414  1019  1139 D PersonaManager: isKioskContainerExistOnDevice
,09-12 14:41:58.424  1019  1046 D Tethering: interfaceRemoved p2p0
,09-12 14:41:58.424  1019  1046 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-12 14:41:58.434  7452  7452 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-12 14:41:58.434  7452  7452 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-12 14:41:58.434  7452  7452 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-12 14:41:58.444  7452  7452 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-12 14:41:58.444  7452  7452 I PCWCLIENTTRACE_PushUtil: sales region : global
09-12 14:41:58.444  7452  7452 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-12 14:41:58.444  7452  7452 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-12 14:41:58.444  1019  4368 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,09-12 14:41:58.444  1019  4368 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
09-12 14:41:58.444  7452  7467 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-12 14:41:58.444  1019  4368 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
,09-12 14:41:58.444  1019  4368 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,09-12 14:41:58.454  1019  4368 I ActivityManager: Killing 7001:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,09-12 14:41:58.454  1019  1019 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-12 14:41:58.454  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:58.454  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:58.454  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:58.464  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:58.474  7469  7469 E Zygote  : MountEmulatedStorage(),
,09-12 14:41:58.474  1019  1019 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7469 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 14:41:58.474  7469  7469 E Zygote  : v2
09-12 14:41:58.474  7469  7469 I libpersona: KNOX_SDCARD checking this for 10001
09-12 14:41:58.474  7469  7469 I libpersona: KNOX_SDCARD not a persona
,09-12 14:41:58.474  7469  7469 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 14:41:58.484  7469  7469 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-12 14:41:58.484  7469  7469 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-12 14:41:58.494  7469  7469 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:41:58.494  7469  7469 D ActivityThread: Added TimaKeyStore provider
,09-12 14:41:58.574  1019  1341 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-12 14:41:58.574  1019  1341 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:58.574  1019  1341 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:58.574  1019  1341 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:58.574  1019  1341 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:58.584  7486  7486 E Zygote  : MountEmulatedStorage()
,09-12 14:41:58.584  7486  7486 E Zygote  : v2
09-12 14:41:58.594  7486  7486 I libpersona: KNOX_SDCARD checking this for 1000
09-12 14:41:58.594  7486  7486 I libpersona: KNOX_SDCARD not a persona
,09-12 14:41:58.594  7486  7486 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 14:41:58.594  1019  1341 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7486 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
09-12 14:41:58.594  1019  1341 I ActivityManager: Killing 7038:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,09-12 14:41:58.594  7486  7486 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 14:41:58.594  7486  7486 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 14:41:58.604  7486  7486 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:41:58.614  7486  7486 D ActivityThread: Added TimaKeyStore provider
,09-12 14:41:58.644  7486  7486 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-12 14:41:58.764  7486  7486 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-12 14:41:58.774  7486  7486 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-12 14:41:58.774  7486  7486 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-12 14:41:58.774  7486  7486 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-12 14:41:58.774  7486  7486 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-12 14:41:58.774  7486  7486 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-12 14:41:58.774  1019  4368 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-12 14:41:58.774  1019  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:58.774  1019  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:58.774  1019  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:58.774  1019  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:58.794  7501  7501 E Zygote  : MountEmulatedStorage(),
09-12 14:41:58.794  7501  7501 E Zygote  : v2
09-12 14:41:58.794  7501  7501 I libpersona: KNOX_SDCARD checking this for 10008,
09-12 14:41:58.794  7501  7501 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 14:41:58.794  7501  7501 I libpersona: KNOX_SDCARD not a persona,
,09-12 14:41:58.794  1019  4368 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7501 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
09-12 14:41:58.794  7501  7501 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 14:41:58.794  1019  4368 I ActivityManager: Killing 6958:com.android.mms/u0a41 (adj 15): empty #21
,09-12 14:41:58.794  7501  7501 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-12 14:41:58.814  7501  7501 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:41:58.814  7501  7501 D ActivityThread: Added TimaKeyStore provider
,09-12 14:41:58.884  1019  1032 I ActivityManager: Killing 7101:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,09-12 14:41:58.884  1019  4366 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
09-12 14:41:58.884  1019  4366 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-12 14:41:58.884  1019  4366 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:58.884  1019  4366 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:58.884  1019  4366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-12 14:41:58.904  3862  7517 I iu.SyncManager: SYNC; picasa accounts
,09-12 14:41:58.914  3862  3862 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,09-12 14:41:58.924  1019  4367 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 14:41:58.924  1019  4367 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,09-12 14:41:58.924  1019  4367 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:58.924  1019  4367 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:58.924  1019  4367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:41:58.934  3862  3862 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 14:41:58.934  3862  3862 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,09-12 14:41:58.944  2815  2815 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Sep 12 14:41:58 GMT+02:00 2016
,09-12 14:41:58.944  1019  1139 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-12 14:41:58.944  1019  1139 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-12 14:41:58.944  1019  1139 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:58.944  1019  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:41:58.944  1019  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-12 14:41:58.944  2815  2815 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-12 14:41:58.954  1019  1032 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-12 14:41:58.954  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:58.954  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:58.954  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:58.954  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:58.964  7520  7520 E Zygote  : MountEmulatedStorage()
,09-12 14:41:58.964  7520  7520 E Zygote  : v2
09-12 14:41:58.964  7520  7520 I libpersona: KNOX_SDCARD checking this for 10031
09-12 14:41:58.964  7520  7520 I libpersona: KNOX_SDCARD not a persona
,09-12 14:41:58.964  2815  2815 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-12 14:41:58.964  7520  7520 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-12 14:41:58.964  1019  1032 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7520 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,09-12 14:41:58.974  7520  7520 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 14:41:58.974  2815  2815 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-12 14:41:58.974  2815  2815 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
09-12 14:41:58.974  1019  1139 D CountryDetector: No listener is left
09-12 14:41:58.974  7520  7520 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 14:41:58.974  2815  7519 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-12 14:41:58.984  2815  7519 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-12 14:41:58.984  2815  7519 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-12 14:41:58.984  2815  7519 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-12 14:41:58.994  2815  2815 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-12 14:41:58.994  7520  7520 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:41:58.994  7520  7520 D ActivityThread: Added TimaKeyStore provider
,09-12 14:41:59.024  7520  7520 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-12 14:41:59.024  1019  1341 I ActivityManager: Killing 7115:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,09-12 14:41:59.034  1019  1032 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-12 14:41:59.034  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:59.034  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:59.034  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:59.034  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:59.044  2753  7535 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-12 14:41:59.044  2753  7535 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-12 14:41:59.044  7536  7536 I libpersona: KNOX_SDCARD checking this for 10032
09-12 14:41:59.044  2753  7535 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
09-12 14:41:59.044  7536  7536 I libpersona: KNOX_SDCARD not a persona
,09-12 14:41:59.044  2753  7535 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
09-12 14:41:59.044  2753  7535 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... ,
09-12 14:41:59.044  7536  7536 E Zygote  : MountEmulatedStorage()
09-12 14:41:59.044  7536  7536 E Zygote  : v2
09-12 14:41:59.054  7536  7536 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-12 14:41:59.054  7536  7536 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 14:41:59.054  7536  7536 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
09-12 14:41:59.054  1019  1032 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7536 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 14:41:59.074  7536  7536 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:41:59.084  7536  7536 D ActivityThread: Added TimaKeyStore provider
,09-12 14:41:59.124  7536  7551 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-12 14:41:59.124  7536  7551 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-12 14:41:59.124  7536  7536 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-12 14:41:59.134  7536  7551 D SPPClientService: PushLog.txt file is not deleted.
,09-12 14:41:59.134  1019  1266 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,09-12 14:41:59.134  7536  7551 D SPPClientService: PushLog.txt file is not deleted.
09-12 14:41:59.134  7536  7551 D SPPClientService: ============PushLog. stop!
,09-12 14:41:59.134  1019  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:59.134  1019  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:59.134  1019  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:59.134  1019  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:59.144  7553  7553 E Zygote  : MountEmulatedStorage(),
09-12 14:41:59.144  7553  7553 I libpersona: KNOX_SDCARD checking this for 10036
09-12 14:41:59.144  7553  7553 E Zygote  : v2,
09-12 14:41:59.144  1019  1266 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7553 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 14:41:59.144  7553  7553 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-12 14:41:59.144  7553  7553 I libpersona: KNOX_SDCARD not a persona
09-12 14:41:59.144  1019  1504 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push,
09-12 14:41:59.144  1019  1504 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
09-12 14:41:59.154  1019  1504 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:59.154  1019  1504 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-12 14:41:59.154  1019  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-12 14:41:59.154  7553  7553 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 14:41:59.154  7553  7553 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,09-12 14:41:59.164  7553  7553 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:41:59.174  7553  7553 D ActivityThread: Added TimaKeyStore provider
,09-12 14:41:59.174  7536  7559 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-12 14:41:59.194  1019  4368 I ActivityManager: Killing 7140:com.wsomacp/u0a23 (adj 15): empty #21
,09-12 14:41:59.214  7553  7553 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@37846b50
,09-12 14:41:59.224  7553  7553 I SA      : [SSP] onCreated
,09-12 14:41:59.234  7553  7553 I SA      : [TPM] There is no property file
,09-12 14:41:59.234  7553  7553 I SA      : [SCU] isHaveSA() - false
,09-12 14:41:59.234  7553  7553 I SA      : [TPM] getModelProperty : null
09-12 14:41:59.234  7553  7553 I SA      : [TPM] getCSCProperty : null
,09-12 14:41:59.234  7553  7553 I SA      : [DM] FLOATING AMOLED FEATURE: true
09-12 14:41:59.234  7553  7553 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-12 14:41:59.234  7553  7553 I SA      : [DM] TFT FEATURE: false
,09-12 14:41:59.244  7553  7553 I SA      : [DM] init START
,09-12 14:41:59.244  7553  7553 I SA      : [DM] This device is not a Vodafone
,09-12 14:41:59.244  7553  7553 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,09-12 14:41:59.244  7553  7553 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,09-12 14:41:59.244  7553  7553 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,09-12 14:41:59.244  7553  7553 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-12 14:41:59.244  7553  7553 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
09-12 14:41:59.244  7553  7553 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,09-12 14:41:59.244  7553  7553 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-12 14:41:59.254  7553  7553 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-12 14:41:59.254  7553  7553 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,09-12 14:41:59.254  7553  7553 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,09-12 14:41:59.254  7553  7553 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,09-12 14:41:59.254  7553  7553 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,09-12 14:41:59.254  7553  7553 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-12 14:41:59.254  7553  7553 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
09-12 14:41:59.254  7553  7553 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,09-12 14:41:59.254  7553  7553 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,09-12 14:41:59.254  7553  7553 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,09-12 14:41:59.254  7553  7553 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
09-12 14:41:59.254  7553  7553 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,09-12 14:41:59.254  7553  7553 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-12 14:41:59.254  7553  7553 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
09-12 14:41:59.254  7553  7553 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-12 14:41:59.254  7553  7553 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,09-12 14:41:59.254  7553  7553 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
09-12 14:41:59.254  7553  7553 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
09-12 14:41:59.254  7553  7553 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75),
09-12 14:41:59.254  7553  7553 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
09-12 14:41:59.254  7553  7553 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-12 14:41:59.264  7553  7553 I SA      : [SCU] isHaveSA() - false
,09-12 14:41:59.264  7553  7553 I SA      : support phone number id : false
,09-12 14:41:59.264  7553  7553 I SA      : [DM] Supports Ref Jpn : true
09-12 14:41:59.264  7553  7553 I SA      : [DM] init END
,09-12 14:41:59.264  7553  7553 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-12 14:41:59.264  7553  7553 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ],
,09-12 14:41:59.264  7553  7553 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-12 14:41:59.274  7553  7553 I SA      : [SLFUCHKMGR] constructor called,
,09-12 14:41:59.274  1019  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-12 14:41:59.274  7553  7553 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-12 14:41:59.274  7553  7553 I SA      : [OR] == isSIMCardReady false ==
,09-12 14:41:59.274  7553  7553 I SA      : [SCU] == networkStateCheck == false
09-12 14:41:59.274  7553  7553 I SA      : [OR] onReceive END
,09-12 14:41:59.284  1019  1489 I ActivityManager: Killing 7175:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,09-12 14:41:59.284  1238  1238 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-12 14:41:59.284  1767  1767 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-12 14:41:59.294  2672  2689 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,09-12 14:41:59.294  1767  1767 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-12 14:41:59.294  1767  1767 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,09-12 14:41:59.294  1767  1767 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,09-12 14:41:59.294  1767  1767 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-12 14:41:59.304  1767  1767 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-12 14:41:59.304  1767  1767 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-12 14:41:59.304  1019  1139 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-12 14:41:59.304  1019  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:59.304  1019  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:59.304  1019  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:59.314  1019  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:59.324  7575  7575 E Zygote  : MountEmulatedStorage(),
09-12 14:41:59.324  7575  7575 E Zygote  : v2
09-12 14:41:59.324  7575  7575 I libpersona: KNOX_SDCARD checking this for 10077
09-12 14:41:59.324  7575  7575 I libpersona: KNOX_SDCARD not a persona
,09-12 14:41:59.324  1019  1139 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7575 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-12 14:41:59.324  7575  7575 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-12 14:41:59.334  7575  7575 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-12 14:41:59.334  7575  7575 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL,
,09-12 14:41:59.344  7575  7575 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:41:59.344  7575  7575 D ActivityThread: Added TimaKeyStore provider
,09-12 14:41:59.364   289   289 E SMD     : DCD OFF
,09-12 14:41:59.364   317   317 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-12 14:41:59.534  1019  1266 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-12 14:41:59.534  1019  1266 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-12 14:41:59.534  1019  1266 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:41:59.534  1019  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 14:41:59.534  1019  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk,
,09-12 14:41:59.534  1019  1341 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-12 14:41:59.534  1019  1341 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:59.534  1019  1341 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:59.534  1019  1341 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:41:59.544  1019  1341 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:41:59.554  7593  7593 E Zygote  : MountEmulatedStorage(),
09-12 14:41:59.554  7593  7593 I libpersona: KNOX_SDCARD checking this for 10110
09-12 14:41:59.554  7593  7593 E Zygote  : v2,
09-12 14:41:59.554  7593  7593 I libpersona: KNOX_SDCARD not a persona
09-12 14:41:59.554  7593  7593 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-12 14:41:59.554  1019  1341 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7593 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
09-12 14:41:59.554  1019  4368 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-12 14:41:59.554  1019  4368 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:41:59.554  1019  4368 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
09-12 14:41:59.554  1019  4368 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:41:59.554  1019  4368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-12 14:41:59.554  7593  7593 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 14:41:59.554  7377  7592 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-12 14:41:59.554  7593  7593 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-12 14:41:59.574  1019  1507 I ActivityManager: Killing 7195:com.android.providers.calendar/u0a37 (adj 15): empty #21
,09-12 14:41:59.574  7593  7593 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:41:59.574  7593  7593 D ActivityThread: Added TimaKeyStore provider
,09-12 14:41:59.714  1019  3798 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-12 14:41:59.824   258   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/,
09-12 14:41:59.824   258   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 14:41:59.824  7593  7611 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-12 14:41:59.824   258   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-12 14:41:59.824   258   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 14:41:59.824  7593  7611 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-12 14:41:59.834   258   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-12 14:41:59.834   258   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 14:41:59.844  7593  7612 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache,
,09-12 14:41:59.844  7593  7612 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files,
09-12 14:41:59.844   258   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-12 14:41:59.844   258   531 W Vold    : Returning OperationFailed - no handler for errno 0,
,09-12 14:41:59.854  1019  1499 D SecContentProvider: uri = 18 selection = isWifiEnabled,
09-12 14:41:59.854  1019  1499 D WifiService: setWifiEnabled: true pid=7055, uid=10170
09-12 14:41:59.854  1019  1499 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed,
09-12 14:41:59.854  1019  1499 W ActivityManager: Permission Denial: getCurrentUser() from pid=7055, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 14:41:59.854  1019  1499 D SecContentProvider2: mCursor = null
09-12 14:41:59.854  1019  1499 W WifiService: Failed getting userId using ActivityManagerNative,
09-12 14:41:59.854  1019  1499 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7055, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 14:41:59.854  1019  1499 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-12 14:41:59.854  1019  1499 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 14:41:59.854  1019  1499 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
,09-12 14:41:59.854  1019  1499 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-12 14:41:59.854  1019  1499 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-12 14:41:59.854  1019  1499 D SettingsProvider: name = wifi_on
,09-12 14:41:59.864  1019  1129 E WifiHW  : ##################### set firmware type 0 #####################,
,09-12 14:41:59.904  7593  7593 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-12 14:41:59.904  7593  7593 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-12 14:41:59.904  7593  7593 I GAv4    :   adb logcat -s GAv4
,09-12 14:41:59.924  7593  7593 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
09-12 14:41:59.924  1019  1031 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-12 14:41:59.944  7593  7593 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-12 14:41:59.954  7593  7615 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-12 14:41:59.984  1019  1097 V AlarmManager: waitForAlarm result :8
,09-12 14:42:00.164  1019  3798 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 14:42:00.174  1019  3798 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:42:00.174  1019  3798 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:42:00.174  1019  3798 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-12 14:42:00.204  7593  7593 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-12 14:42:00.214  1019  1046 D Tethering: interfaceAdded wlan0
,09-12 14:42:00.224  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 14:42:00.224  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 14:42:00.224  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-12 14:42:00.234  1019  1134 E Tethering: No numeric data
,09-12 14:42:00.234  1019  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-12 14:42:00.234  1019  1134 D Tethering: clearTetheredNotification()
,09-12 14:42:00.234   279   986 I WifiHW  : wifi_change_fw_path(): fwpath = sta,
09-12 14:42:00.234  1019  1126 V NetworkStats: performPollLocked(flags=0x1)
09-12 14:42:00.234  1019  1134 D Tethering: InitialState.processMessage what=4
09-12 14:42:00.234  1183  1183 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 14:42:00.234  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:00.234  1183  1183 D HotspotTile: updateTetherState():false, false
09-12 14:42:00.234  1019  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 14:42:00.244  1019  1126 V NetworkStats: performPollLocked() took 4ms
09-12 14:42:00.234  1019  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-12 14:42:00.234   279   986 D SoftapController: Softap fwReload - Ok
09-12 14:42:00.234  1019  1046 D Tethering: interfaceAdded p2p0
09-12 14:42:00.244  1019  1134 E Tethering: No numeric data
09-12 14:42:00.244  1019  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 14:42:00.244  1019  1134 D Tethering: clearTetheredNotification()
09-12 14:42:00.244  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:00.244   279   986 D CommandListener: Setting iface cfg,
09-12 14:42:00.244   279   986 D CommandListener: Trying to bring down wlan0
09-12 14:42:00.244  1019  1046 D Tethering: p2p0 is not a tetherable iface, ignoring
09-12 14:42:00.244   279   986 D CommandListener: Clearing all IP addresses on wlan0
,09-12 14:42:00.244  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 14:42:00.244  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 14:42:00.244  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
,09-12 14:42:00.244  1019  1126 V NetworkStats: performPollLocked(flags=0x1)
09-12 14:42:00.244  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 14:42:00.244  1019  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 14:42:00.244  1019  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 14:42:00.244  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:00.244  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 14:42:00.244  1183  1183 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 14:42:00.244  1183  1183 D HotspotTile: updateTetherState():false, false
,09-12 14:42:00.244  1019  1129 E WifiHW  : supplicant_name : p2p_supplicant
,09-12 14:42:00.254  1019  1126 V NetworkStats: performPollLocked() took 4ms
09-12 14:42:00.254  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:00.254  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 14:42:00.254  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 14:42:00.254  1019  1129 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-12 14:42:00.254  7593  7593 I cr.library_loader: Time to load native libraries: 26 ms (timestamps 9890-9916)
09-12 14:42:00.254  7593  7593 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-12 14:42:00.264  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 14:42:00.264  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 14:42:00.264  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 14:42:00.264  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:00.264  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:00.264  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:00.264  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:42:00.264  1183  1183 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 14:42:00.264  1183  1183 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-12 14:42:00.264  1183  1183 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 14:42:00.264  1183  1710 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 14:42:00.264  4827  4827 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 14:42:00.264  1183  1183 D HotspotTile: onReceive : 2, 0
,09-12 14:42:00.274  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:00.274  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:00.274  7593  7593 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ff01b4b},
09-12 14:42:00.274  7593  7593 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-12 14:42:00.274  7593  7593 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-12 14:42:00.294  7593  7593 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
09-12 14:42:00.294  7593  7593 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-12 14:42:00.304  7593  7593 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-12 14:42:00.304  7638  7638 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-12 14:42:00.304  7638  7638 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-12 14:42:00.304  7638  7638 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-12 14:42:00.314  7593  7593 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-12 14:42:00.314  7593  7593 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-12 14:42:00.314  7593  7593 I Adreno-EGL: Build Date: 04/06/15 Mon
09-12 14:42:00.314  7593  7593 I Adreno-EGL: Local Branch: 
09-12 14:42:00.314  7593  7593 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-12 14:42:00.314  7593  7593 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-12 14:42:00.314  7593  7593 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-12 14:42:00.344  7638  7638 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
09-12 14:42:00.344   370   370 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7638
09-12 14:42:00.344   370   370 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,09-12 14:42:00.344  7638  7638 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-12 14:42:00.344  7638  7638 I wpa_supplicant: ssSupport state is = 1
09-12 14:42:00.344  7638  7638 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-12 14:42:00.344  7638  7638 I SecureStorage: [INFO]: SPID(0x00000000)Processing data,
09-12 14:42:00.344   370   370 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7638
09-12 14:42:00.344   370   370 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,09-12 14:42:00.384  7593  7593 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY),
,09-12 14:42:00.394  7593  7593 I NSApplication: Starting up...
,09-12 14:42:00.394  1019  3798 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-12 14:42:00.404  1019  1489 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-12 14:42:00.404  7593  7652 W cr.media: Requires BLUETOOTH permission
,09-12 14:42:00.414  1019  1139 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-12 14:42:00.414  1019  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:00.414  1019  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:00.414  1019  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:00.414  1019  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:42:00.434  1019  1139 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7657 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-12 14:42:00.434  7657  7657 E Zygote  : MountEmulatedStorage()
09-12 14:42:00.434  7657  7657 I libpersona: KNOX_SDCARD checking this for 10117
09-12 14:42:00.434  7657  7657 E Zygote  : v2
09-12 14:42:00.434  7657  7657 I libpersona: KNOX_SDCARD not a persona
09-12 14:42:00.434  7657  7657 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 14:42:00.434  1019  1139 I ActivityManager: Killing 7257:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,09-12 14:42:00.434  7657  7657 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 14:42:00.444  7657  7657 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-12 14:42:00.464  7657  7657 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:42:00.464  7657  7657 D ActivityThread: Added TimaKeyStore provider
,09-12 14:42:00.484  7657  7657 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 14:42:00.534   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,09-12 14:42:00.544  7638  7638 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,09-12 14:42:00.584  7638  7638 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-12 14:42:00.584  7638  7638 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-12 14:42:00.594  7638  7638 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-12 14:42:00.604   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7638
09-12 14:42:00.604   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
,09-12 14:42:00.604  7638  7638 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-12 14:42:00.604  7638  7638 I wpa_supplicant: ssSupport state is = 1
,09-12 14:42:00.604  7638  7638 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-12 14:42:00.604  7638  7638 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 14:42:00.604  7638  7638 E wpa_supplicant: SIM READ ERROR
09-12 14:42:00.604  7638  7638 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-12 14:42:00.604  7638  7638 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 14:42:00.604  7638  7638 E wpa_supplicant: SIM READ ERROR
,09-12 14:42:00.604  7638  7638 I wpa_supplicant: Blacklist: Clear (all) 
09-12 14:42:00.604  7638  7638 I wpa_supplicant: wpa_default_ap_write_once
09-12 14:42:00.604  7638  7638 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
09-12 14:42:00.604  7638  7638 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 14:42:00.604  7638  7638 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
09-12 14:42:00.604  7638  7638 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 14:42:00.614  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 14:42:00.604  7638  7638 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-12 14:42:00.604  7638  7638 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-12 14:42:00.614  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,09-12 14:42:00.614  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-12 14:42:00.724  7638  7638 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-12 14:42:00.844  1019  1266 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-12 14:42:00.844  1019  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:00.844  1019  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:00.844  1019  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:00.844  1019  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:42:00.864  1019  1266 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7679 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,09-12 14:42:00.864  7679  7679 E Zygote  : MountEmulatedStorage()
09-12 14:42:00.864  7679  7679 I libpersona: KNOX_SDCARD checking this for 10121
09-12 14:42:00.864  7679  7679 E Zygote  : v2
09-12 14:42:00.864  7679  7679 I libpersona: KNOX_SDCARD not a persona
,09-12 14:42:00.864  1019  1266 I ActivityManager: Killing 7272:com.android.calendar/u0a131 (adj 15): empty #21
,09-12 14:42:00.864  7679  7679 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 14:42:00.864  7679  7679 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-12 14:42:00.874  7679  7679 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 14:42:00.884   304   304 I art     : Explicit concurrent mark sweep GC freed 8699(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 22.357ms
,09-12 14:42:00.894  7679  7679 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:42:00.894  7679  7679 D ActivityThread: Added TimaKeyStore provider
,09-12 14:42:00.904   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 608us total 16.457ms
,09-12 14:42:00.904  7679  7679 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 14:42:00.904  7679  7679 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-12 14:42:00.904  7679  7679 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-12 14:42:00.914  7638  7638 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-12 14:42:00.914  7638  7638 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-12 14:42:00.914   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 620us total 18.196ms
,09-12 14:42:00.924  7638  7638 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-12 14:42:00.924   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7638
09-12 14:42:00.924   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-12 14:42:00.924  7638  7638 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-12 14:42:00.924  7638  7638 I wpa_supplicant: ssSupport state is = 1
09-12 14:42:00.924  7679  7679 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-12 14:42:00.924  7679  7679 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-12 14:42:00.934  7638  7638 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-12 14:42:00.934  7638  7638 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-12 14:42:00.934  7679  7679 I QuickConnect: PeriphStartReceiver.onReceive - no need to start,
09-12 14:42:00.934  1019  4366 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
09-12 14:42:00.934  1019  4366 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:00.934  1019  4366 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:00.934  1019  4366 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:42:00.934  1019  4366 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:42:00.944  7638  7638 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-12 14:42:00.944   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7638
09-12 14:42:00.944   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-12 14:42:00.944  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 14:42:00.944  7638  7638 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-12 14:42:00.944  7638  7638 I wpa_supplicant: ssSupport state is = 1
,09-12 14:42:00.944  7638  7638 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 14:42:00.944  7638  7638 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 14:42:00.944  7638  7638 E wpa_supplicant: SIM READ ERROR
09-12 14:42:00.944  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 14:42:00.944  7638  7638 I wpa_supplicant: wpa_default_ap_write_once
09-12 14:42:00.944  7638  7638 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-12 14:42:00.944  7638  7638 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-12 14:42:00.944  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 14:42:00.944  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
09-12 14:42:00.944  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 14:42:00.944  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
,09-12 14:42:00.954  7698  7698 E Zygote  : MountEmulatedStorage(),
,09-12 14:42:00.954  7698  7698 E Zygote  : v2
09-12 14:42:00.954  7698  7698 I libpersona: KNOX_SDCARD checking this for 10141
,09-12 14:42:00.954  7698  7698 I libpersona: KNOX_SDCARD not a persona
,09-12 14:42:00.954  7698  7698 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-12 14:42:00.954  1019  4366 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7698 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,09-12 14:42:00.954  1019  4366 I ActivityManager: Killing 7224:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
,09-12 14:42:00.954  7698  7698 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 14:42:00.964  7698  7698 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 14:42:00.974  7698  7698 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:42:00.974  7698  7698 D ActivityThread: Added TimaKeyStore provider
,09-12 14:42:00.994  7698  7698 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-12 14:42:00.994  7698  7698 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 14:42:00.994  7698  7698 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 14:42:00.994  7698  7698 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-12 14:42:01.014  7638  7638 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-12 14:42:01.014  7638  7638 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-12 14:42:01.044  1019  1499 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 14:42:01.054  1019  1032 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 14:42:01.074  7638  7638 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
09-12 14:42:01.074  7638  7638 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-12 14:42:01.074  7638  7638 I wpa_supplicant: Skip scan - bUseNetwork false
,09-12 14:42:01.074  1019  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-12 14:42:01.084  1019  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-12 14:42:01.084  7638  7638 I wpa_supplicant: HOTSPOT20_ENABLE called
09-12 14:42:01.084  7638  7638 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 14:42:01.084  7638  7638 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 14:42:01.084  7638  7638 E wpa_supplicant: SIM READ ERROR
09-12 14:42:01.084  7638  7638 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 14:42:01.094  1019  1341 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 14:42:01.104  1019  1347 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 14:42:01.114  7638  7638 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-12 14:42:01.124  7638  7638 I wpa_supplicant: Skip scan - bUseNetwork false
,09-12 14:42:01.124  1019  1129 D WifiConfigStore: Loading config and enabling all networks 
,09-12 14:42:01.134  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 14:42:01.134  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 14:42:01.134  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 14:42:01.134  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:42:01.134  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:01.134  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:01.134  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:42:01.134  1183  1183 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 14:42:01.134  1183  1183 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-12 14:42:01.134  1183  1183 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-12 14:42:01.134  1183  1710 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 14:42:01.144  1183  1183 D HotspotTile: onReceive : 3, 0
,09-12 14:42:01.144  4827  4827 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 14:42:01.144  1019  1129 E WifiConfigStore: Not a HS20
,09-12 14:42:01.144  7055  7055 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 14:42:01.144  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:01.144  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:01.144  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:01.144  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:42:01.144  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:42:01.144  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:01.144  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:01.144  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 14:42:01.144  7055  7055 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 14:42:01.144  7055  7055 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 14:42:01.144  1019  1129 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-12 14:42:01.154  1019  1129 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-12 14:42:01.154  7638  7638 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-12 14:42:01.154  7638  7638 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-12 14:42:01.154  7638  7638 I wpa_supplicant: reset timer : RESET_TIMER 0
09-12 14:42:01.154  7638  7638 I wpa_supplicant: P2P: Current p2p state = IDLE
09-12 14:42:01.154  7638  7638 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-12 14:42:01.154  7638  7638 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-12 14:42:01.154  7638  7638 I wpa_supplicant: First Scan Start
09-12 14:42:01.154  7638  7638 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-12 14:42:01.154  7055  7055 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:42:01.154  1019  1129 D WifiNative-wlan0: Setting external_sim to 1
,09-12 14:42:01.154  1019  1129 D WifiStateMachine: Setting OUI to DA-A1-19
09-12 14:42:01.154  1019  1129 I WifiNative-HAL: startHal
09-12 14:42:01.154  1019  1129 E wifi    : getStaticLongField sWifiHalHandle 0x9f37088c
09-12 14:42:01.154  1019  1129 I WifiNative-HAL: Could not start hal
,09-12 14:42:01.154  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:01.154  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:01.154  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:01.154  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:42:01.154  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:42:01.154  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:01.154  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:01.154  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 14:42:01.154  7377  7377 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,09-12 14:42:01.154  7055  7055 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 14:42:01.154  7055  7055 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:42:01.154  1019  1129 E WifiNative-wlan0: do suspend true
,09-12 14:42:01.164  1019  1128 D WifiP2pService: P2pDisabledState{ what=131203 }
09-12 14:42:01.164  1019  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-12 14:42:01.164   279   986 D CommandListener: Setting iface cfg
09-12 14:42:01.164   279   986 D CommandListener: Trying to bring up p2p0
09-12 14:42:01.164  1019  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-12 14:42:01.164  1019  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-12 14:42:01.164  1019  1129 E WifiNative-wlan0: invaild command id : 215
,09-12 14:42:01.164  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 3
,09-12 14:42:01.164  7638  7638 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-12 14:42:01.164  7638  7638 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-12 14:42:01.164  7638  7638 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,09-12 14:42:01.164  1019  1499 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
09-12 14:42:01.164  1019  1129 E WifiStateMachine: Failed to set frequency band 0
09-12 14:42:01.164  1019  1128 D WifiP2pService: P2pEnablingState
09-12 14:42:01.164  1019  1128 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-12 14:42:01.164  1019  1128 D WifiP2pService: P2pEnablingState{ what=143376 }
09-12 14:42:01.164  1019  1019 D RttService: SCAN_AVAILABLE : 3
,09-12 14:42:01.164  1019  1128 D WifiP2pService: DefaultState{ what=143376 }
09-12 14:42:01.164  1019  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 14:42:01.174  1019  1128 D WifiP2pService: P2pEnablingState{ what=147457 }
09-12 14:42:01.164  1019  1129 D SecContentProvider2: mCursor = null
09-12 14:42:01.174  1019  1128 D WifiP2pService: P2p socket connection successful
09-12 14:42:01.164  1019  1154 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 14:42:01.174  1019  1128 D WifiP2pService: P2pEnabledState
09-12 14:42:01.164  1019  1154 I WifiNative-HAL: startHal
09-12 14:42:01.174  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:01.164  1019  1154 E wifi    : getStaticLongField sWifiHalHandle 0x9e2329bc
09-12 14:42:01.174  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-12 14:42:01.164  1019  1154 I WifiNative-HAL: Could not start hal
09-12 14:42:01.174  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:42:01.164  1019  1154 E WifiScanningService: could not start HAL
09-12 14:42:01.174  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:01.164  1019  1155 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 14:42:01.174  1019  1489 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 14:42:01.184  1019  1504 D RCPManagerService: exchangeData() failure , invalid userId,
,09-12 14:42:01.184  7724  7724 E Zygote  : MountEmulatedStorage()
,09-12 14:42:01.184  7724  7724 E Zygote  : v2
09-12 14:42:01.184  7724  7724 I libpersona: KNOX_SDCARD checking this for 10068
09-12 14:42:01.184  7724  7724 I libpersona: KNOX_SDCARD not a persona
,09-12 14:42:01.194  7724  7724 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 14:42:01.194  1019  1499 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7724 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,09-12 14:42:01.194  1019  1131 E ConnectivityService: updateNetworkInfo()
09-12 14:42:01.194  1019  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-12 14:42:01.194  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-12 14:42:01.194  1019  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 14:42:01.194  1019  1044 W ActivityManager: mDVFSHelper.release()
09-12 14:42:01.194  1019  1129 D SecContentProvider2: mCursor = null
09-12 14:42:01.194  1019  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-12 14:42:01.194  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 14:42:01.194  1019  1049 D WifiDisplayController: disconnect
09-12 14:42:01.194  1019  1049 D WifiDisplayController: updateConnection
09-12 14:42:01.194  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 14:42:01.194  1019  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 14:42:01.204  7724  7724 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 14:42:01.204  7724  7724 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-12 14:42:01.204  1183  1183 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-12 14:42:01.204  1019  1031 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 14:42:01.204  1183  1183 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-12 14:42:01.204  1019  1128 D WifiNative-p2p0: p2pGetDeviceAddress
09-12 14:42:01.204  1019  1128 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
09-12 14:42:01.204  1019  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:42:01.204  1019  1049 D WifiDisplayAdapter: onP2pDisconnected
09-12 14:42:01.204  1019  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 14:42:01.204  1019  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-12 14:42:01.214  1019  1128 D WifiP2pService: DeviceAddress: 0a:75:42
09-12 14:42:01.214  1019  1049 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-12 14:42:01.214  1019  1049 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-12 14:42:01.214  1019  1049 D WifiDisplayController:  primary type: 10-0050F204-5
09-12 14:42:01.214  1019  1049 D WifiDisplayController:  secondary type: null
09-12 14:42:01.214  1019  1049 D WifiDisplayController:  wps: 0
09-12 14:42:01.214  1019  1049 D WifiDisplayController:  grpcapab: 0
09-12 14:42:01.214  1019  1049 D WifiDisplayController:  devcapab: 0
09-12 14:42:01.214  1019  1049 D WifiDisplayController:  status: 3
09-12 14:42:01.214  1019  1049 D WifiDisplayController:  wfdInfo: null
09-12 14:42:01.214  1019  1049 D WifiDisplayController:  groupownerAddress: null
09-12 14:42:01.214  1019  1049 D WifiDisplayController:  GOdeviceName: null
09-12 14:42:01.214  1019  1049 D WifiDisplayController:  interfaceAddress: ,
09-12 14:42:01.214  1019  1049 D WifiDisplayController:  SConnectInfo : null
,09-12 14:42:01.224  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 14:42:01.224  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 14:42:01.224  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
,09-12 14:42:01.224  7724  7724 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 14:42:01.224  7724  7724 D ActivityThread: Added TimaKeyStore provider
,09-12 14:42:01.234  1019  1266 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 14:42:01.234  1019  3798 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-12 14:42:01.234  1019  3798 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:01.234  1019  3798 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:01.234  1019  3798 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:01.234  1019  3798 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:42:01.244  7739  7739 E Zygote  : MountEmulatedStorage()
09-12 14:42:01.244  7739  7739 I libpersona: KNOX_SDCARD checking this for 10009
09-12 14:42:01.244  7739  7739 E Zygote  : v2
09-12 14:42:01.244  7739  7739 I libpersona: KNOX_SDCARD not a persona
,09-12 14:42:01.244  7739  7739 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 14:42:01.254  7739  7739 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 14:42:01.254  7739  7739 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-12 14:42:01.254  1019  1128 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-12 14:42:01.254  1019  3798 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7739 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
09-12 14:42:01.254  1019  3798 I ActivityManager: Killing 6916:com.android.vending/u0a26 (adj 15): empty #21
09-12 14:42:01.254  1019  3798 I ActivityManager: Killing 7155:com.android.defcontainer/u0a3 (adj 15): empty #22
,09-12 14:42:01.254  1019  1128 D WifiP2pService: InactiveState
09-12 14:42:01.264  1019  1128 D WifiP2pService: InactiveState{ what=143376 }
09-12 14:42:01.264  1019  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
09-12 14:42:01.264  7638  7638 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-12 14:42:01.264  7724  7724 D BadgeProvider: onCreate
,09-12 14:42:01.264  7724  7724 D BadgeProvider: DatabaseHelper
,09-12 14:42:01.304  7739  7739 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:42:01.304  7739  7739 D ActivityThread: Added TimaKeyStore provider
,09-12 14:42:01.414  1019  1032 I art     : Explicit concurrent mark sweep GC freed 69829(3MB) AllocSpace objects, 10(208KB) LOS objects, 33% free, 23MB/34MB, paused 2.358ms total 154.159ms
,09-12 14:42:01.434  7724  7732 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-12 14:42:01.454  7724  7732 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-12 14:42:01.454  7724  7732 D BadgeProvider: sendNotify, [notify] : null
09-12 14:42:01.454  7724  7732 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-12 14:42:01.454  7724  7732 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-12 14:42:01.454  7724  7732 D BadgeProvider: update, [UpdateCount] : 1
,09-12 14:42:01.454  1488  1488 D Launcher.Model: reloadBadges entered.
,09-12 14:42:01.484  1019  4368 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,09-12 14:42:01.484  1019  4368 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-12 14:42:01.484  1019  1347 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-12 14:42:01.484  1019  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-12 14:42:01.514  1019  1499 I ActivityManager: Killing 7402:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,09-12 14:42:01.524  1019  1266 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 14:42:01.524  1019  1266 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 14:42:01.524  1019  1266 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:01.524  1019  1266 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:01.524  1019  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 14:42:01.524  2187  2187 I Hs20UtilService: Starting #11
,09-12 14:42:01.524  2187  2202 I Hs20UtilService: Message received 5011
,09-12 14:42:01.524  7432  7432 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 14:42:01.524  7432  7432 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-12 14:42:01.524  7432  7432 D SecurityLogAgent: StateMachine : Current State = 1
09-12 14:42:01.524  7432  7432 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 14:42:01.534  1019  1139 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 14:42:01.534  1019  1139 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 14:42:01.544  1019  1139 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:42:01.544  1019  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:01.544  1019  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 14:42:01.544  2187  2187 I Hs20UtilService: Starting #12
,09-12 14:42:01.544  2187  2202 I Hs20UtilService: Message received 5011
,09-12 14:42:01.544  7432  7432 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 14:42:01.544  7432  7432 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 14:42:01.544  7432  7432 D SecurityLogAgent: StateMachine : Current State = 1
09-12 14:42:01.544  7432  7432 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 14:42:01.554  1019  1266 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 14:42:01.554  1019  1266 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 14:42:01.554  1019  1266 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:01.554  1019  1266 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:01.554  1019  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 14:42:01.554  2187  2187 I Hs20UtilService: Starting #13
,09-12 14:42:01.554  2187  2202 I Hs20UtilService: Message received 5011
,09-12 14:42:01.554  1019  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-12 14:42:01.554  1019  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-12 14:42:01.554  1019  1129 E WifiNative-wlan0: invaild command id : 215
,09-12 14:42:01.564  7432  7432 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 14:42:01.564  7432  7432 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 14:42:01.564  7432  7432 D SecurityLogAgent: StateMachine : Current State = 1
09-12 14:42:01.564  7432  7432 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 14:42:01.574  4827  4827 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-12 14:42:01.574  4827  4827 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 14:42:01.574  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 14:42:01.574  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-12 14:42:01.574  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 14:42:01.574  4827  4827 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 14:42:01.574  4827  4902 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 14:42:01.574  1019  1499 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-12 14:42:01.584  1019  1499 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.samsung.android.app.FileShareClient/com.samsung.android.app.FileShareClient.ClientBroadcastReceiver}
09-12 14:42:01.584  1019  1499 W BroadcastQueue: android.os.TransactionTooLargeException
09-12 14:42:01.584  1019  1499 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-12 14:42:01.584  1019  1499 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-12 14:42:01.584  1019  1499 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-12 14:42:01.584  1019  1499 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-12 14:42:01.584  1019  1499 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-12 14:42:01.584  1019  1499 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
09-12 14:42:01.584  1019  1499 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-12 14:42:01.584  1019  1499 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
09-12 14:42:01.584  1019  1499 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,09-12 14:42:01.584  1019  1499 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-12 14:42:01.584  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:42:01.584  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:01.584  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:42:01.584  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:42:01.594  1019  1499 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7757 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 14:42:01.604  7757  7757 E Zygote  : MountEmulatedStorage()
,09-12 14:42:01.604  7757  7757 E Zygote  : v2
09-12 14:42:01.604  7757  7757 I libpersona: KNOX_SDCARD checking this for 10064
09-12 14:42:01.604  7757  7757 I libpersona: KNOX_SDCARD not a persona
,09-12 14:42:01.604  7757  7757 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 14:42:01.604  7757  7757 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-12 14:42:01.604  7757  7757 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 14:42:01.624  7757  7757 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:42:01.624  7757  7757 D ActivityThread: Added TimaKeyStore provider,
,09-12 14:42:01.634  7757  7757 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-12 14:42:01.644  7757  7757 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 14:42:01.654  7757  7757 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-12 14:42:01.674  7757  7757 D FileShare-Client: Outbound.stopDelayTimer - 
,09-12 14:42:01.684  7417  7417 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
,09-12 14:42:01.684  1019  4368 I ActivityManager: Killing 7312:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,09-12 14:42:01.724  1019  1043 W libprocessgroup: failed to open /acct/uid_10064/pid_7402/cgroup.procs: No such file or directory
,09-12 14:42:02.324  7638  7638 I wpa_supplicant: nl80211: Received scan results (28 BSSes),
09-12 14:42:02.324  7638  7638 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,09-12 14:42:02.334  1019  7716 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
09-12 14:42:02.334  7638  7638 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-12 14:42:02.334  7638  7638 I wpa_supplicant: Trying to associate with  'G700',
09-12 14:42:02.334  7638  7638 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,09-12 14:42:02.334  7638  7638 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,09-12 14:42:02.344  1019  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 14:42:02.344  1019  1129 D SecContentProvider2: mCursor = null
,09-12 14:42:02.364   289   289 E SMD     : DCD OFF,
,09-12 14:42:02.454  7638  7638 E wpa_supplicant: Cmd 35605 not handled,
09-12 14:42:02.464  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 14:42:02.464  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 14:42:02.464  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
09-12 14:42:02.464  7638  7638 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-12 14:42:02.464  7638  7638 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-12 14:42:02.464  7638  7638 I wpa_supplicant: Associated with F4.99.3E
,09-12 14:42:02.464  7638  7638 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-12 14:42:02.464  7638  7638 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-12 14:42:02.464  7638  7638 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-12 14:42:02.464  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 14:42:02.464  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,09-12 14:42:02.464  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-12 14:42:02.464  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false,
,09-12 14:42:02.464  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 14:42:02.464  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
09-12 14:42:02.464  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-12 14:42:02.464  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, true
09-12 14:42:02.464  1019  1046 D Tethering: interfaceStatusChanged wlan0, true
09-12 14:42:02.474  1019  1134 E Tethering: No numeric data
09-12 14:42:02.474  1019  1126 V NetworkStats: performPollLocked(flags=0x1)
09-12 14:42:02.474  1019  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-12 14:42:02.474  1019  1134 D Tethering: clearTetheredNotification()
09-12 14:42:02.474  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:02.474  7638  7638 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-12 14:42:02.474  7638  7638 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-12 14:42:02.474  1019  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 14:42:02.474  1019  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-12 14:42:02.474  7638  7638 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-12 14:42:02.474  7638  7638 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-12 14:42:02.474  7638  7638 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 14:42:02.474  7638  7638 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-12 14:42:02.484  7638  7638 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-12 14:42:02.484  7638  7638 I wpa_supplicant: Blacklist: Clear (temp) 
09-12 14:42:02.484  1183  1183 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 14:42:02.484  7638  7638 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-12 14:42:02.484  1183  1183 D HotspotTile: updateTetherState():false, false
,09-12 14:42:02.484  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:02.484  1019  1126 V NetworkStats: performPollLocked() took 9ms
09-12 14:42:02.484  1019  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 14:42:02.484  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-12 14:42:02.484  1019  1129 D SecContentProvider2: mCursor = null
09-12 14:42:02.484  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, true
09-12 14:42:02.484  1019  1046 D Tethering: interfaceStatusChanged wlan0, true
,09-12 14:42:02.484  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:02.484  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 14:42:02.494  1019  1129 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-12 14:42:02.504  1019  1129 E WifiConfigStore: setLastSelectedConfiguration -1
,09-12 14:42:02.504  1019  1129 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-12 14:42:02.504  1019  1131 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-12 14:42:02.504  1019  1131 E ConnectivityService: updateNetworkInfo()
09-12 14:42:02.504  1019  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-12 14:42:02.504  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 14:42:02.514  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 14:42:02.514  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 14:42:02.514  1019  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 14:42:02.514  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:02.514  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:42:02.514  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:02.514  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:42:02.514  1019  3798 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 14:42:02.514  1019  3798 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 14:42:02.524  1019  3798 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:02.524  1019  3798 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:02.524  1019  3798 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 14:42:02.524  2187  2187 I Hs20UtilService: Starting #14,
09-12 14:42:02.524  2187  2202 I Hs20UtilService: Message received 5007
,09-12 14:42:02.524  4827  4827 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-12 14:42:02.524  4827  4827 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 14:42:02.524  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 14:42:02.524  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 14:42:02.524  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 14:42:02.524  4827  4827 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 14:42:02.524  4827  4902 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 14:42:02.534  1019  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 14:42:02.544   279   986 D CommandListener: Setting iface cfg
,09-12 14:42:02.544  1019  1129 E WifiStateMachine: Start Dhcp Watchdog 2
,09-12 14:42:02.544  1019  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 14:42:02.544  1019  1129 D SecContentProvider2: mCursor = null
,09-12 14:42:02.554  1019  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 14:42:02.554  1019  1129 D SecContentProvider2: mCursor = null
,09-12 14:42:02.564  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 14:42:02.564  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 14:42:02.564  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-12 14:42:02.564  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:02.564  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:02.564  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:02.564  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:42:02.564  1019  3350 D SSRM:n  : SIOP:: AP = 390
09-12 14:42:02.564  1019  1129 E WifiNative-wlan0: do suspend false
,09-12 14:42:02.564  1019  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 14:42:02.564  1019  1129 D SecContentProvider2: mCursor = null
09-12 14:42:02.564  1019  1128 D WifiP2pService: InactiveState{ what=143375 }
,09-12 14:42:02.564  1019  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-12 14:42:02.784  7776  7776 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-12 14:42:02.784  7776  7776 I dhcpcd  : version 5.5.6 starting
,09-12 14:42:02.794  7776  7776 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-12 14:42:02.844  7776  7776 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-12 14:42:02.844  7776  7776 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-12 14:42:02.844  7776  7776 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
09-12 14:42:02.844  7776  7776 I dhcpcd  : bssid match,
,09-12 14:42:02.854  7776  7776 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116,
,09-12 14:42:02.864  1019  1031 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-12 14:42:02.864  1019  1031 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 14:42:02.864  1019  1031 D SecContentProvider2: mCursor = null
,09-12 14:42:02.864  1019  1031 D WifiService: setWifiEnabled: false pid=7055, uid=10170
,09-12 14:42:02.864  1019  1031 D SettingsProvider: name = wifi_on
,09-12 14:42:02.874  1019  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 14:42:02.894  1019  1129 E WifiNative-wlan0: do suspend true,
,09-12 14:42:02.904  7776  7776 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
09-12 14:42:02.904  7776  7776 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,09-12 14:42:02.914  1019  1128 D WifiP2pService: InactiveState{ what=143375 },
09-12 14:42:02.914  1019  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-12 14:42:02.924   279   986 D CommandListener: Clearing all IP addresses on wlan0
,09-12 14:42:02.934  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-12 14:42:02.934  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 14:42:02.934  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 14:42:02.934  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:02.934  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-12 14:42:02.934  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:02.934  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:42:02.944  1019  1131 E ConnectivityService: updateNetworkInfo()
09-12 14:42:02.944  1019  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 14:42:02.944  1019  1131 E ConnectivityService: updateNetworkInfo()
09-12 14:42:02.944  1019  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
09-12 14:42:02.944   279   986 E Netd    : no such netId 503
,09-12 14:42:02.944  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-12 14:42:02.954  1019  1131 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)',
09-12 14:42:02.954  1019  1131 D NtpTrustedTime: currentTimeMillis() cache hit,
09-12 14:42:02.954  1019  1131 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,09-12 14:42:02.954  1019  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-12 14:42:02.954  1019  1131 V NetworkStats: updateIfacesLocked()
09-12 14:42:02.954  1019  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-12 14:42:02.954  1019  1131 V NetworkStats: performPollLocked(flags=0x1)
,09-12 14:42:02.964  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-12 14:42:02.964  1019  1131 V NetworkStats: performPollLocked() took 10ms
09-12 14:42:02.964  1019  1131 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:02.974  1019  1499 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 14:42:02.964  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 14:42:02.974  1019  1499 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-12 14:42:02.964  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 14:42:02.974  1019  1128 D WifiP2pService: InactiveState{ what=131204 }
09-12 14:42:02.974  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:02.974  1019  1128 D WifiP2pService: P2pEnabledState{ what=131204 }
09-12 14:42:02.974  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:02.974  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:02.974  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:02.974  1019  1128 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-12 14:42:02.974  1019  1499 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:02.974  1019  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:02.974  1019  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 14:42:02.974  2187  2187 I Hs20UtilService: Starting #15
09-12 14:42:02.974  1019  1131 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
09-12 14:42:02.974  1019  7774 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:42:02.974  1019  1131 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-12 14:42:02.974  1019  7774 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-12 14:42:02.974  1019  1131 D ConnectivityService: nai.networkMonitor.doQuit()
09-12 14:42:02.974  1019  1131 D NetworkMo,nitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-12 14:42:02.974  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 1
09-12 14:42:02.974  1019  1154 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:42:02.974  1019  1129 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-12 14:42:02.974  1019  1131 E ConnectivityService: updateNetworkInfo()
09-12 14:42:02.974  1019  1019 D RttService: SCAN_AVAILABLE : 1
09-12 14:42:02.974  1019  1155 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:42:02.974  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:02.974  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:02.974  2187  2202 I Hs20UtilService: Message received 5007
,09-12 14:42:02.984  4827  4827 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 14:42:02.984  4827  4827 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 14:42:02.984  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
09-12 14:42:02.984  1019  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:42:02.984  1019  1049 D WifiDisplayAdapter: onP2pDisconnected
09-12 14:42:02.984  1019  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 14:42:02.984  1019  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-12 14:42:02.994  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - P2P: FAILED
09-12 14:42:02.994  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 14:42:02.994  4827  4827 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 14:42:02.994  4827  4902 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 14:42:02.994  1019  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-12 14:42:02.994  1019  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-12 14:42:02.994  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-12 14:42:02.994  1019  1049 D WifiDisplayController: disconnect
09-12 14:42:02.994  1019  1049 D WifiDisplayController: updateConnection
09-12 14:42:02.994  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-12 14:42:02.994  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 14:42:02.994  1019  1131 E ConnectivityService: updateNetworkInfo()
09-12 14:42:02.994  1019  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 14:42:03.004  1019  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-12 14:42:03.004  1019  1049 D WifiDisplayAdapter: onP2pDisconnected
09-12 14:42:03.004  1019  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 14:42:03.004  1019  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
09-12 14:42:03.004  1019  1128 D WifiP2pService: P2pDisablingState
09-12 14:42:03.004  1019  1128 D WifiP2pService: P2pDisablingState{ what=147458 }
09-12 14:42:03.004  1019  1128 D WifiP2pService: p2p socket connection lost
09-12 14:42:03.004  1019  1128 D WifiP2pService: P2pDisabledState
,09-12 14:42:03.004  1019  1129 E WifiNative-wlan0: do suspend true,
,09-12 14:42:03.014  1183  1183 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-12 14:42:03.014  1019  1341 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 14:42:03.014  1183  1183 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-12 14:42:03.014  4827  4827 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-12 14:42:03.014  4827  4827 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 14:42:03.014  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 14:42:03.014  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
09-12 14:42:03.014  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 14:42:03.014  4827  4827 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-12 14:42:03.014  4827  4902 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 14:42:03.024  7757  7757 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 14:42:03.024  7757  7757 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-12 14:42:03.024  7757  7757 D FileShare-Client: Outbound.stopDelayTimer - 
,09-12 14:42:03.034  7417  7417 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 14:42:03.044   279   986 D CommandListener: Clearing all IP addresses on wlan0,
09-12 14:42:03.044  1019  1128 D WifiP2pService: P2pDisabledState{ what=143375 },
09-12 14:42:03.044  1019  1128 D WifiP2pService: DefaultState{ what=143375 }
,09-12 14:42:03.044  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-12 14:42:03.054  7638  7638 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-12 14:42:03.054  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-12 14:42:03.054  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 14:42:03.054  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 14:42:03.054  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:03.054  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:42:03.054  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:03.054  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:42:03.064  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 14:42:03.064  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 14:42:03.064  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-12 14:42:03.064  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:03.064  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:03.064  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:03.064  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:42:03.074  1019  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-12 14:42:03.074  1019  1129 D SecContentProvider2: mCursor = null
,09-12 14:42:03.084  4827  4827 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 14:42:03.084  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-12 14:42:03.084  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 14:42:03.084  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null,
09-12 14:42:03.084  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-12 14:42:03.084  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:03.084  1183  1183 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-12 14:42:03.084  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:03.084  1183  1710 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-12 14:42:03.084  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:03.084  1183  1183 D HotspotTile: onReceive : 0, 0
09-12 14:42:03.084  1183  1183 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 14:42:03.084  1019  1139 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
09-12 14:42:03.084  1183  1183 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-12 14:42:03.084  1019  1139 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-12 14:42:03.084  1019  1139 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:42:03.084  1019  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:03.084  1019  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 14:42:03.084  2187  2187 I Hs20UtilService: Starting #16
09-12 14:42:03.094  2187  2202 I Hs20UtilService: Message received 5007
,09-12 14:42:03.094  7055  7055 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:42:03.094  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:03.094  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:03.094  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:03.094  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:42:03.094  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:42:03.094  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:03.094  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:03.094  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 14:42:03.094  4827  4827 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 14:42:03.094  4827  4827 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 14:42:03.094  7055  7055 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:42:03.094  7055  7055 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 14:42:03.094  7055  7055 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 14:42:03.094  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:03.094  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:03.094  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:03.094  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:42:03.094  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:42:03.094  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:03.094  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:03.094  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 14:42:03.094  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-12 14:42:03.094  7055  7055 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:42:03.094  7055  7055 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 14:42:03.104  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 14:42:03.104  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 14:42:03.104  4827  4827 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-12 14:42:03.104  4827  4902 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 14:42:03.114  1019  1266 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 14:42:03.114  1019  1266 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 14:42:03.114  1019  1266 W ActivityManager: userId = 0, bbcId = -10000,
09-12 14:42:03.114  1019  1266 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:03.114  1019  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
,09-12 14:42:03.114  2187  2187 I Hs20UtilService: Starting #17
09-12 14:42:03.114  2187  2202 I Hs20UtilService: Message received 5011
,09-12 14:42:03.114  7432  7432 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-12 14:42:03.114  7432  7432 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 14:42:03.114  7432  7432 D SecurityLogAgent: StateMachine : Current State = 1,
09-12 14:42:03.114  7432  7432 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 14:42:03.174  1019  3374 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-12 14:42:03.254  7638  7638 I wpa_supplicant: Blacklist: Clear (all) ,
,09-12 14:42:03.334  7638  7638 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-12 14:42:03.334  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-12 14:42:03.334  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 14:42:03.334  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
,09-12 14:42:03.364  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 14:42:03.364  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 14:42:03.364  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
09-12 14:42:03.364  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 14:42:03.364  1019  1134 D Tethering: InitialState.processMessage what=4
09-12 14:42:03.364  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 14:42:03.364  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-12 14:42:03.364  7638  7638 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-12 14:42:03.364  7638  7638 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-12 14:42:03.364  7638  7638 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,09-12 14:42:03.364  7638  7638 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-12 14:42:03.364  7638  7638 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-12 14:42:03.364  1019  1134 E Tethering: No numeric data
09-12 14:42:03.364  1019  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 14:42:03.364  1019  1134 D Tethering: clearTetheredNotification()
,09-12 14:42:03.364  1019  1126 V NetworkStats: performPollLocked(flags=0x1)
09-12 14:42:03.364  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 14:42:03.364  1019  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 14:42:03.364  1019  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 14:42:03.374  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 14:42:03.374  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 14:42:03.374  1183  1183 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 14:42:03.374  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
09-12 14:42:03.374  1183  1183 D HotspotTile: updateTetherState():false, false
,09-12 14:42:03.374  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:03.374  1019  1126 V NetworkStats: performPollLocked() took 6ms
09-12 14:42:03.374  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:03.374  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 14:42:03.454  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 14:42:03.454  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,09-12 14:42:03.454  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-12 14:42:03.524  7638  7638 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 14:42:03.594  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false,
09-12 14:42:03.594  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
09-12 14:42:03.594  1019  1046 D Tethering: interfaceStatusChanged wlan0, false,
,09-12 14:42:03.604  7638  7638 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,09-12 14:42:03.714  1019  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-12 14:42:03.714  1019  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-12 14:42:03.714  7377  7377 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 14:42:03.714  1647  2118 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 14:42:03.724  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-12 14:42:03.724  4827  4827 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-12 14:42:03.724  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 14:42:03.724  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 14:42:03.724  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:03.724  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:03.724  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:03.724  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:03.724  1183  1183 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 14:42:03.724  1183  1183 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 14:42:03.724  1183  1183 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-12 14:42:03.724  1183  1710 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 14:42:03.724  1183  1183 D HotspotTile: onReceive : 1, 0
,09-12 14:42:03.724  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:03.724  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:03.724  1019  1347 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 14:42:03.734  1019  1347 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 14:42:03.734  1019  1347 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:42:03.734  1019  1347 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 14:42:03.734  1019  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 14:42:03.734  7432  7432 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 14:42:03.744  7432  7432 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 14:42:03.744  7432  7432 D SecurityLogAgent: StateMachine : Current State = 1
09-12 14:42:03.744  7432  7432 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 14:42:03.744  2187  2187 I Hs20UtilService: Starting #18
,09-12 14:42:03.744  2187  2202 I Hs20UtilService: Message received 5011
,09-12 14:42:04.374   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 14:42:04.574  1019  1046 D Tethering: interfaceRemoved wlan0
,09-12 14:42:04.574  1019  1046 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-12 14:42:04.694  1019  1046 D Tethering: interfaceRemoved p2p0
,09-12 14:42:04.694  1019  1046 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-12 14:42:05.374   289   289 E SMD     : DCD OFF,
,09-12 14:42:05.374   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 14:42:05.394  1019  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-12 14:42:05.764  1019  1097 V AlarmManager: waitForAlarm result :4
,09-12 14:42:05.774  1019  1019 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,09-12 14:42:05.774   279   982 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-12 14:42:05.774   279   982 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-12 14:42:05.774  1019  1019 V AlarmManagerEXT: <AppSync3 Whitelist>
,09-12 14:42:05.774  1019  1019 V AlarmManagerEXT: (AppSync) ### 0 added ###
09-12 14:42:05.774  1183  1183 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK,
09-12 14:42:05.774  1183  1183 D KeyguardUpdateMonitor: handleTimeUpdate
,09-12 14:42:05.784  1183  1183 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-12 14:42:05.794  1183  1183 D SecKeyguardClockView: HomeTimezone(): 1
,09-12 14:42:05.794  1183  1183 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-12 14:42:05.794  1183  1183 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK,
09-12 14:42:05.794  1183  1183 I KeyguardEffectViewController: *** don't update sliding image ***
,09-12 14:42:05.804  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:42:05.804  1019  1044 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:42:05.804  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,09-12 14:42:05.844  1183  1183 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-12 14:42:05.844  1183  1183 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-12 14:42:05.854  1183  1183 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-12 14:42:05.864  1183  1183 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-12 14:42:05.874  7055  7256 D BluetoothAdapter: enable()
,09-12 14:42:05.874  1019  1032 W ActivityManager: Permission Denial: getCurrentUser() from pid=7055, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-12 14:42:05.884  1019  1032 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-12 14:42:05.884  1019  1032 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7055, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 14:42:05.884  1019  1032 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-12 14:42:05.884  1019  1032 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-12 14:42:05.884  1019  1032 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-12 14:42:05.884  1019  1032 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-12 14:42:05.884  1019  1032 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-12 14:42:05.884  1019  1032 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-12 14:42:05.884  1019  1032 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 14:42:05.884  1019  1032 D SettingsProvider: name = bluetooth_on
,09-12 14:42:05.894  1019  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 14:42:05.894  1019  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 14:42:05.894  1019  1048 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-12 14:42:05.894  3211  3283 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-12 14:42:05.894  3211  3283 D BluetoothAdapterProperties: Setting state to 11
,09-12 14:42:05.894  3211  3283 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-12 14:42:05.894  3211  3283 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-12 14:42:05.894  3211  3283 D BluetoothAdapterService: updateAdapterState state is 11
,09-12 14:42:05.894  3211  3283 D BluetoothAdapterService: Autoconnection is available 
,09-12 14:42:05.894  3211  3283 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-12 14:42:05.894  3211  3283 D BtConfig.SecureMode: isSecureModeOn:false
,09-12 14:42:05.904  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-12 14:42:05.904  3211  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
09-12 14:42:05.904  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-12 14:42:05.904  3211  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
09-12 14:42:05.904  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-12 14:42:05.904  3211  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-12 14:42:05.904  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 14:42:05.904  3211  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-12 14:42:05.904  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-12 14:42:05.904  3211  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-12 14:42:05.904  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-12 14:42:05.904  3211  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-12 14:42:05.904  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 14:42:05.904  3211  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-12 14:42:05.904  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-12 14:42:05.904  3211  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-12 14:42:05.904  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 14:42:05.904  3211  3283 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 14:42:05.904  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-12 14:42:05.904  3211  3283 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-12 14:42:05.904  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-12 14:42:05.904  3211  3283 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-12 14:42:05.904  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 14:42:05.904  3211  3283 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-12 14:42:05.904  3211  3283 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-12 14:42:05.904  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-12 14:42:05.904  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-12 14:42:05.904  3211  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-12 14:42:05.904  1019  4368 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 14:42:05.904  1019  4368 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-12 14:42:05.904  1019  4368 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:05.904  1019  4368 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:05.904  1019  4368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:05.904  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,09-12 14:42:05.904  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-12 14:42:05.904  3211  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-12 14:42:05.914  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-12 14:42:05.914  1019  1019 I InputMethodManagerService: [BT Setting State] State =11
,09-12 14:42:05.914  3211  3211 D HeadsetService: Received start request. Starting profile...
,09-12 14:42:05.914  3211  3211 D HeadsetService: start()
09-12 14:42:05.914  3211  3211 D HeadsetStateMachine: make
,09-12 14:42:05.914  3211  3211 E HeadsetStateMachine: # of Max HF connection is 2
,09-12 14:42:05.924  1183  1183 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-12 14:42:05.924  1183  1183 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:42:05.924  1183  1183 D BluetoothTile:  getBluetoothState : 11
,09-12 14:42:05.934  1019  3798 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 14:42:05.934  1019  1031 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-12 14:42:05.934  1183  1183 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 14:42:05.934  1971  1971 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 14:42:05.934  1183  1710 D BluetoothTile:  handleUpdatestate:false name:null
09-12 14:42:05.934  1183  1710 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-12 14:42:05.934  4827  4827 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 14:42:05.944  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:05.944  1019  4366 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 14:42:05.944  1019  4366 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 14:42:05.944  1019  4366 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:42:05.944  1019  4366 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 14:42:05.944  1019  4366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:05.944  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,09-12 14:42:05.944  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 14:42:05.944  3211  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-12 14:42:05.944  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:05.954  1639  1639 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 14:42:05.954  1019  1507 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-12 14:42:05.954  1019  1507 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-12 14:42:05.954  1019  1507 W ActivityManager: userId = 0, bbcId = -10000,
09-12 14:42:05.954  1019  4368 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 14:42:05.954  1019  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 14:42:05.954  1019  4368 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-12 14:42:05.954  1019  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-12 14:42:05.954  1019  4368 W ActivityManager: userId = 0, bbcId = -10000,
,09-12 14:42:05.954  1019  4368 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-12 14:42:05.954  1019  4368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:05.964  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-12 14:42:05.964  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-12 14:42:05.964  3211  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-12 14:42:05.964  1019  4367 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 14:42:05.964  1019  4367 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-12 14:42:05.964  1019  4367 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:42:05.964  1019  4367 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:05.964  1019  4367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:05.964  1019  1031 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-12 14:42:05.964  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-12 14:42:05.964  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-12 14:42:05.964  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-12 14:42:05.964  3211  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-12 14:42:05.964  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:05.964  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-12 14:42:05.964  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-12 14:42:05.964  3211  3211 I bluedroid: get_profile_interface handsfree
09-12 14:42:05.964  1019  1347 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 14:42:05.964  1019  1347 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 14:42:05.974  1019  1347 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:05.974  1019  1347 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:05.974  1019  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:05.974  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-12 14:42:05.974  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-12 14:42:05.974  3211  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-12 14:42:05.974  1019  1139 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 14:42:05.974  1019  1139 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:42:05.974  1019  1139 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-12 14:42:05.974  1019  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:05.974  1019  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 14:42:05.974  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,09-12 14:42:05.974  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-12 14:42:05.974  3211  3283 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-12 14:42:05.974  4827  4827 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 14:42:05.974  1019  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 14:42:05.984  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 14:42:05.984  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:05.984  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:05.984  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 14:42:05.984  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-12 14:42:05.984  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 14:42:05.984  3211  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-12 14:42:05.984  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-12 14:42:05.984  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-12 14:42:05.984  3211  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-12 14:42:05.984  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
,09-12 14:42:05.984  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-12 14:42:05.984  3211  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-12 14:42:05.984  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-12 14:42:05.984  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 14:42:05.984  3211  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-12 14:42:05.984  3211  3283 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-12 14:42:05.984  1183  1183 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 14:42:05.984  1183  1183 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-12 14:42:05.984  3211  3211 E DualScoManager: Dual Sco Manager already instantiated
09-12 14:42:05.984  3211  3211 I DualScoManager: Set HeadsetServiceHelper
09-12 14:42:05.984  3211  3211 D BluetoothAtMessage: createCMTIContentObservers
,09-12 14:42:05.994  1019  1499 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-12 14:42:05.994  1019  1499 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 14:42:05.994  1019  1499 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 14:42:05.994  1019  1499 D SettingsProvider: selectionArgs: false
09-12 14:42:05.994  1019  1499 D SettingsProvider: selectionArgs: 1002
09-12 14:42:05.994  1019  4366 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
09-12 14:42:05.994  1019  1499 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 14:42:05.994  1019  1499 D SettingsProvider: ret = -1
09-12 14:42:05.994  3211  7809 D HeadsetStateMachine: Enter Disconnected: -2
,09-12 14:42:05.994  1019  4366 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:05.994  1019  4366 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:05.994  1019  4366 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:05.994  1019  4366 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:42:06.004  7810  7810 E Zygote  : MountEmulatedStorage()
09-12 14:42:06.004  7810  7810 E Zygote  : v2
09-12 14:42:06.004  7810  7810 I libpersona: KNOX_SDCARD checking this for 10055
09-12 14:42:06.004  7810  7810 I libpersona: KNOX_SDCARD not a persona
,09-12 14:42:06.004  7810  7810 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 14:42:06.004  1019  4366 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7810 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-12 14:42:06.004  7810  7810 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 14:42:06.004  3211  3211 D HeadsetService: mStartError = false
09-12 14:42:06.004  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
,09-12 14:42:06.014  3211  7809 D HeadsetStateMachine: Clear mHeadsetBrsf
09-12 14:42:06.014  3211  7809 D HeadsetStateMachine: map size, before remove : 0
09-12 14:42:06.014  3211  7809 D HeadsetStateMachine: map size, after remove: 0
09-12 14:42:06.014  3211  3211 D A2dpService: Received start request. Starting profile...
09-12 14:42:06.014  3211  3211 D A2dpService: start()
09-12 14:42:06.014  3211  3211 I bluedroid: get_profile_interface avrcp
,09-12 14:42:06.014  3211  3211 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-12 14:42:06.014  3211  3211 D Avrcp   : Initialize Media Controller
09-12 14:42:06.014  3211  3211 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-12 14:42:06.014  3211  3211 E Avrcp   : getActiveSessions
,09-12 14:42:06.014  3211  3211 D Avrcp   : pick active media Controller
09-12 14:42:06.014  3211  3211 D Avrcp   : Get the active Media Controller 
,09-12 14:42:06.024  7810  7810 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 14:42:06.024  3211  3211 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-12 14:42:06.024  3211  3211 D A2dpStateMachine: make
,09-12 14:42:06.024  3211  7816 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-12 14:42:06.024  3211  3211 I bluedroid: get_profile_interface a2dp
,09-12 14:42:06.034  3211  7819 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-12 14:42:06.034  3211  3211 E bt-btif : warning : media task started media_task_refcnt 1 
,09-12 14:42:06.034  3211  3211 D A2dpService: mStartError = false
09-12 14:42:06.034  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
09-12 14:42:06.034  3211  3211 D HeadsetStateMachine: Try to query the phonestate on bind
,09-12 14:42:06.034  1433  1466 I Telecom : BluetoothPhoneService: queryPhoneState
,09-12 14:42:06.034  1433  1433 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-12 14:42:06.034  3211  7818 D A2dpStateMachine: Enter Disconnected: -2
09-12 14:42:06.034  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-12 14:42:06.034  1433  1466 I Telecom : BluetoothPhoneService: Result of Message : true
,09-12 14:42:06.034  3211  7816 D BluetoothMediaBrowser: no now playing list
09-12 14:42:06.034  3211  7816 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-12 14:42:06.034  3211  3211 D HidService: Received start request. Starting profile...
09-12 14:42:06.034  3211  3211 D HidService: start()
09-12 14:42:06.034  3211  3211 I bluedroid: get_profile_interface hidhost
09-12 14:42:06.034  3211  3211 D HidService: setHidService(): set to: null
09-12 14:42:06.034  3211  3211 D HidService: mStartError = false
09-12 14:42:06.034  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
09-12 14:42:06.044  3211  3211 D HealthService: Received start request. Starting profile...
09-12 14:42:06.044  3211  3211 D HealthService: start()
,09-12 14:42:06.044  3211  3211 I bluedroid: get_profile_interface health
,09-12 14:42:06.044  3211  3211 D HealthService: mStartError = false
09-12 14:42:06.044  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
09-12 14:42:06.044  3211  3211 D HeadsetStateMachine: Proxy object connected
09-12 14:42:06.044  3211  3211 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-12 14:42:06.044  3211  7809 D HeadsetStateMachine: Disconnected process message: 11
,09-12 14:42:06.044  3211  3211 D PanService: Received start request. Starting profile...
09-12 14:42:06.044  3211  3211 D PanService: start()
09-12 14:42:06.044  3211  3211 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 14:42:06.044  3211  3211 I bluedroid: get_profile_interface pan
09-12 14:42:06.044  3211  3211 D PanService: mStartError = false
09-12 14:42:06.044  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
,09-12 14:42:06.044  3211  3211 D BluetoothMapService: Received start request. Starting profile...
09-12 14:42:06.044  3211  3211 D BluetoothMapService: start()
,09-12 14:42:06.044  3211  3211 D BluetoothMapService: mStartError = false
,09-12 14:42:06.044  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
,09-12 14:42:06.044  3211  3211 D SapService: Received start request. Starting profile...
09-12 14:42:06.044  3211  3211 D SapService: start()
09-12 14:42:06.044  3211  3211 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-12 14:42:06.044  3211  3211 I bluedroid: get_profile_interface sap
09-12 14:42:06.044  3211  3211 D SapService: mStartError = false
09-12 14:42:06.044  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
09-12 14:42:06.044  3211  3211 D HeadsetPhoneState: sendDeviceDataStateChanged
09-12 14:42:06.054  3211  3211 D HeadsetPhoneState: Signal level : previous=0 curr=4
09-12 14:42:06.054  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-12 14:42:06.054  3211  7809 D HeadsetStateMachine: Disconnected process message: 18
09-12 14:42:06.054  3211  3211 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-12 14:42:06.054  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-12 14:42:06.054  3211  7809 D HeadsetStateMachine: Disconnected process message: 10
09-12 14:42:06.054  3211  7809 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 14:42:06.054  3211  7809 D HeadsetStateMachine: Disconnected process message: 11
,09-12 14:42:06.054  7810  7810 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 14:42:06.054  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-12 14:42:06.054  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-12 14:42:06.054  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-12 14:42:06.054  7810  7810 D ActivityThread: Added TimaKeyStore provider
,09-12 14:42:06.064  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
09-12 14:42:06.064  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-12 14:42:06.064  3211  3283 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
09-12 14:42:06.064  3211  3283 I bluedroid: enable
,09-12 14:42:06.074  3211  3286 E bt-btif : Calling BTA_HhEnable
09-12 14:42:06.074  3211  3286 E bt-btif : BTA got event 0x1716
09-12 14:42:06.074  3211  3286 E bt-btif :                : sec: 0xb6ert failed: section && *section && key && *key && name && *name && bytes && type
09-12 14:42:06.074  3211  3286 E bt-btif :                : sec: 0xb6roperty sename [mask:0x2120048
09-12 14:42:06.074  3211  3286 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
09-12 14:42:06.074  3211  3286 E BluetoothServiceJni: populateRssiValuesNative
09-12 14:42:06.074  3211  3286 I bluedroid: getModelRssiValues
09-12 14:42:06.074  3211  3286 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-12 14:42:06.074  3211  3286 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-12 14:42:06.074  3211  3286 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-12 14:42:06.074  1019  1019 D SettingsProvider: name = bluetooth_name
,09-12 14:42:06.084  3211  3286 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-12 14:42:06.084  3211  3286 D BluetoothAdapterProperties: Scan Mode:20
09-12 14:42:06.084  3211  3286 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 14:42:06.084  3211  3286 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
09-12 14:42:06.084  3211  3286 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
09-12 14:42:06.084  3211  3286 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
09-12 14:42:06.084  3211  3286 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-12 14:42:06.084  3211  3286 E bt-btif : JVenable fails
,09-12 14:42:06.084  3211  3286 D bte_conf: Device ID record 1 : primary
09-12 14:42:06.084  3211  3286 D bte_conf:   vendorId            = 0075
09-12 14:42:06.084  3211  3286 D bte_conf:   vendorIdSource      = 0001
09-12 14:42:06.084  3211  3286 D bte_conf:   product             = 0100
09-12 14:42:06.084  3211  3286 D bte_conf:   version             = 0200
09-12 14:42:06.084  3211  3286 D bte_conf:   clientExecutableURL = 
09-12 14:42:06.084  3211  3286 D bte_conf:   serviceDescription  = 
09-12 14:42:06.084  3211  3286 D bte_conf:   documentationURL    = 
09-12 14:42:06.084  3211  3286 D bte_conf: bte_load_did_conf no section named DID2.
,09-12 14:42:06.084  3211  3286 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-12 14:42:06.084  3211  3286 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-12 14:42:06.084  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:06.084  3211  3283 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-12 14:42:06.084  3211  3283 D BluetoothAdapterProperties: ScanMode =  20
,09-12 14:42:06.084  3211  3283 D BluetoothAdapterProperties: State =  11
09-12 14:42:06.084  1019  1507 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-12 14:42:06.084  3211  3283 D BluetoothAdapterProperties: Setting state to 12
09-12 14:42:06.084  3211  3283 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-12 14:42:06.094  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:06.094  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:06.094  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:06.094  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:42:06.094  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:42:06.094  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:06.094  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:06.094  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 14:42:06.094  3211  3286 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-12 14:42:06.094  3211  3286 D BluetoothAdapterProperties: Scan Mode:21
,09-12 14:42:06.094  3211  3286 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 14:42:06.094  1019  1507 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-12 14:42:06.094  1019  1507 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 14:42:06.094  1019  1507 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 14:42:06.094  1019  1507 D SettingsProvider: selectionArgs: false
09-12 14:42:06.094  1019  1507 D SettingsProvider: selectionArgs: 1002
09-12 14:42:06.094  1019  1507 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 14:42:06.094  1019  1507 D SettingsProvider: ret = -1
09-12 14:42:06.094  3211  3283 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 14:42:06.094  3211  3283 D BluetoothAdapterService: updateAdapterState state is 12
,09-12 14:42:06.094  1019  4368 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 14:42:06.094  1019  4368 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-12 14:42:06.094  7810  7810 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-12 14:42:06.094  1019  4368 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:42:06.094  1019  4368 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:06.094  1019  4368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:06.104  3211  3283 D BluetoothAdapterService: Autoconnection is available 
09-12 14:42:06.104  3211  3283 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-12 14:42:06.104  3211  3283 D BluetoothAdapterService: starting service from this receiver
,09-12 14:42:06.104  1019  1347 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 14:42:06.104  1019  1347 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-12 14:42:06.104  3211  3211 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-12 14:42:06.104  3211  3211 I BluetoothPbapService: Handler(): got msg=1
,09-12 14:42:06.104  1639  1670 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 14:42:06.104  1639  1670 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 14:42:06.104  1019  1347 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:06.104  7055  7055 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 14:42:06.104  1019  1266 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-12 14:42:06.104  1019  1347 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:06.104  1019  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:06.114  1452  6619 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 14:42:06.114  3211  3283 I BluetoothAdapterState: Entering On State from state = 11
,09-12 14:42:06.114  1019  1048 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-12 14:42:06.114  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 14:42:06.114  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:06.114  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:06.114  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:06.114  1452  6619 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 14:42:06.114  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:06.114  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:06.114  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:06.114  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:42:06.114  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:42:06.114  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:06.114  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:06.114  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 14:42:06.124  4827  4840 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 14:42:06.124  3211  7832 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-12 14:42:06.124  7055  7055 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 14:42:06.124  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-12 14:42:06.124  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 14:42:06.124  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:06.124  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:06.124  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:06.124  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:06.124  7810  7810 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-12 14:42:06.134  3211  7832 D BluetoothSocket: bindListen(): myUserId = 0
09-12 14:42:06.134  3211  7832 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 14:42:06.134  7810  7810 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-12 14:42:06.134  7810  7810 D UserAnalysis: Create SecureDbHelper
,09-12 14:42:06.134  1433  1451 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 14:42:06.134  1019  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-12 14:42:06.134  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-12 14:42:06.134  4827  4827 D BluetoothMap: Proxy object connected
,09-12 14:42:06.134  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:06.134  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:06.134  4827  4827 D MapProfile: Bluetooth service connected
09-12 14:42:06.134  4827  4827 D BluetoothMap: getConnectedDevices()
09-12 14:42:06.134  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:06.134  1433  1451 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 14:42:06.134  3211  7832 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,09-12 14:42:06.144  3211  7832 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 14:42:06.144  3211  7832 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 14:42:06.144  3211  7832 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@4a90664
09-12 14:42:06.144  3211  7832 D BluetoothSocket: channel: 19
09-12 14:42:06.144  3211  7832 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
09-12 14:42:06.144  7810  7810 D IntelligenceServiceApplication: onCreate()
,09-12 14:42:06.144  4827  7755 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 14:42:06.144  4827  7755 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 14:42:06.144  4827  4838 D Bluetoothsap: onBluetoothStateChange: up=true
,09-12 14:42:06.144  4827  4838 D Bluetoothsap: Binding service...
09-12 14:42:06.144  1019  1266 I ActivityManager: Killing 7331:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,09-12 14:42:06.144  4827  4838 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-12 14:42:06.144  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-12 14:42:06.144  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 14:42:06.144  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:06.144  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:06.144  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:06.144  4827  4838 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-12 14:42:06.144  1452  1702 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 14:42:06.144  1452  1702 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 14:42:06.144  1183  3282 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 14:42:06.144  1183  3282 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 14:42:06.154  4827  7755 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 14:42:06.154  7810  7810 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-12 14:42:06.154  4827  4827 D Bluetoothsap: BluetoothSAP Proxy object connected
09-12 14:42:06.154  4827  4827 D SapProfile: Bluetooth service connected
09-12 14:42:06.154  4827  4827 D Bluetoothsap: getConnectedDevices()
,09-12 14:42:06.154  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-12 14:42:06.154  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-12 14:42:06.154  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:06.154  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:06.154  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:06.154  1019  1507 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-12 14:42:06.154  4827  4840 D BluetoothPan: Binding service...
,09-12 14:42:06.154  4827  4827 D BluetoothPbap: Proxy object connected
09-12 14:42:06.154  4827  4827 D PbapServerProfile: Bluetooth service connected
09-12 14:42:06.154  7810  7810 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-12 14:42:06.154  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-12 14:42:06.154  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 14:42:06.154  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:06.154  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:06.154  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:06.164  4827  4827 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 14:42:06.164  4827  7755 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-12 14:42:06.164  4827  4827 D PanProfile: Bluetooth service connected
,09-12 14:42:06.164  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 14:42:06.164  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-12 14:42:06.164  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:06.164  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:06.164  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:06.164  4827  7755 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 14:42:06.164  1019  1048 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-12 14:42:06.164  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 14:42:06.164  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 14:42:06.164  1019  1048 E BluetoothHeadset: BluetoothHeadset service is binded
09-12 14:42:06.164  4827  4838 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 14:42:06.164  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-12 14:42:06.164  4827  4827 D HeadsetProfile: Bluetooth service connected
09-12 14:42:06.164  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 14:42:06.164  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:06.164  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:06.164  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:06.164  4827  4840 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 14:42:06.174  4827  4840 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 14:42:06.174  4827  4827 D BluetoothInputDevice: Proxy object connected
09-12 14:42:06.174  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 14:42:06.174  4827  4827 D HidProfile: Bluetooth service connected
09-12 14:42:06.174  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 14:42:06.174  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:06.174  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:06.174  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:06.174  7810  7810 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-12 14:42:06.174  1019  1048 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 14:42:06.174  1019  1048 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-12 14:42:06.174  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 14:42:06.174  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 14:42:06.174  1433  1451 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 14:42:06.174  1019  1019 D BluetoothA2dp: Proxy object connected
,09-12 14:42:06.174  1019  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-12 14:42:06.174  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-12 14:42:06.174  4827  4827 D BluetoothA2dp: Proxy object connected
09-12 14:42:06.174  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:06.174  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:06.174  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-12 14:42:06.174  4827  4827 D A2dpProfile: Bluetooth service connected
09-12 14:42:06.174  1433  1451 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 14:42:06.174  3211  3228 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 14:42:06.174  3211  3228 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 14:42:06.184  1442  1842 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 14:42:06.184  1442  1842 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 14:42:06.184  3211  3224 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 14:42:06.184  3211  3224 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 14:42:06.184  1019  1048 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 14:42:06.184  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 14:42:06.184  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:06.184  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:06.184  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:06.184  1647  1861 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 14:42:06.184  1647  1861 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 14:42:06.184  3211  3211 D BluetoothA2dp: Proxy object connected
09-12 14:42:06.184  1433  1451 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 14:42:06.184  1433  1451 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 14:42:06.184  1019  1048 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 14:42:06.184  1019  1048 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 14:42:06.184  3211  3211 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-12 14:42:06.254  1019  1048 E BluetoothManagerService: Unable to call onBluetoothStateChange() on callback #22
09-12 14:42:06.254  1019  1048 E BluetoothManagerService: android.os.DeadObjectException
09-12 14:42:06.254  1019  1048 E BluetoothManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
09-12 14:42:06.254  1019  1048 E BluetoothManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
09-12 14:42:06.254  1019  1048 E BluetoothManagerService: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub$Proxy.onBluetoothStateChange(IBluetoothStateChangeCallback.java:84)
09-12 14:42:06.254  1019  1048 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:1053)
09-12 14:42:06.254  1019  1048 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2007)
09-12 14:42:06.254  1019  1048 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
09-12 14:42:06.254  1019  1048 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1576)
09-12 14:42:06.254  1019  1048 E BluetoothManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:42:06.254  1019  1048 E BluetoothManagerService: 	at android.os.Looper.loop(Looper.java:145)
09-12 14:42:06.254  1019  1048 E BluetoothManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 14:42:06.254  1019  1048 E BluetoothManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-12 14:42:06.254  7055  7063 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 14:42:06.254  7055  7063 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 14:42:06.254  1019  1048 D BluetoothPan: Binding service...
,09-12 14:42:06.264  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-12 14:42:06.264  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 14:42:06.264  1019  1019 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 14:42:06.264  1433  7833 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 14:42:06.264  1019  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 14:42:06.264  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 14:42:06.264  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:06.264  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:06.264  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-12 14:42:06.264  1433  7833 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 14:42:06.264  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-12 14:42:06.264  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-12 14:42:06.264  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-12 14:42:06.264  1019  1019 I InputMethodManagerService: [BT Setting State] State =12
09-12 14:42:06.264  1019  1019 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-12 14:42:06.274  1433  1433 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2124a85e, true
,09-12 14:42:06.274  1433  1433 D BluetoothHeadset: registerMessageListener
,09-12 14:42:06.284  1183  1183 D BluetoothTile:  onBluetoothStateChange:
,09-12 14:42:06.284  1183  1183 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-12 14:42:06.284  1183  1710 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 14:42:06.284  1183  1710 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 14:42:06.284  1183  1183 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-12 14:42:06.294  1183  1183 D BluetoothTile:  getBluetoothState : 12
,09-12 14:42:06.294  1971  1971 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 14:42:06.294  1183  1710 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 14:42:06.294  4827  4827 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 14:42:06.304  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-12 14:42:06.304  1019  1507 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 14:42:06.304  1019  4367 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-12 14:42:06.304  1183  1183 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-12 14:42:06.304  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:42:06.304  3211  3228 D HeadsetService: registerMessageListener
,09-12 14:42:06.314  3211  3228 D HeadsetService: registerMessageListener,
09-12 14:42:06.314  1433  1433 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-12 14:42:06.314  3211  7809 D HeadsetStateMachine: Disconnected process message: 70
,09-12 14:42:06.314  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-12 14:42:06.314  3211  7809 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@114260cd
09-12 14:42:06.314  4827  4827 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-12 14:42:06.314  4827  4827 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-12 14:42:06.314  4827  4827 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-12 14:42:06.314  4827  4827 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
09-12 14:42:06.314  3211  7836 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-12 14:42:06.314  1433  1433 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-12 14:42:06.314  1433  1433 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-12 14:42:06.314  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-12 14:42:06.324  3211  7809 D HeadsetStateMachine: Disconnected process message: 9
09-12 14:42:06.324  3211  7809 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-12 14:42:06.324  3211  7836 D BluetoothSocket: bindListen(): myUserId = 0,
09-12 14:42:06.324  3211  7836 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 14:42:06.324  3211  7836 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
09-12 14:42:06.324  3211  7836 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 14:42:06.324  3211  7836 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 14:42:06.324  3211  7836 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3e4fdd82,
09-12 14:42:06.324  3211  7836 D BluetoothSocket: channel: 5
,09-12 14:42:06.334  4827  4827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 14:42:06.334  1019  1031 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-12 14:42:06.334  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-12 14:42:06.334   284   678 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-12 14:42:06.334  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:06.334  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:06.334  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
09-12 14:42:06.334   284   678 V voice   : voice_set_parameters: enter: A2dpSuspended=false
,09-12 14:42:06.334   284   678 V voice   : voice_set_parameters: exit with code(-2)
09-12 14:42:06.334   284   678 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-12 14:42:06.334   284   678 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-12 14:42:06.334   284   678 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-12 14:42:06.334   284   678 V audio_hw_primary: adev_set_parameters: exit
,09-12 14:42:06.334  3211  7809 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-12 14:42:06.344  4827  4827 D DockEventReceiver: finishStartingService: stopping service
,09-12 14:42:06.344  1639  1639 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 14:42:06.354  4827  4827 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 14:42:06.354  1183  1183 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:42:06.354  1183  1183 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-12 14:42:06.364  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
,09-12 14:42:06.364  3211  3211 D BtConfig.SecureMode: isSecureModeOn:false
,09-12 14:42:06.374  1019  3798 W ActivityManager: userId = 0, bbcId = -10000,
09-12 14:42:06.374  1019  3798 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 14:42:06.374  1019  3798 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:06.374  1019  3798 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
09-12 14:42:06.374  1019  3798 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:06.384  1019  1139 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-12 14:42:06.384   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 14:42:06.384  1019  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:06.384  1019  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:06.384  1019  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:06.384  1019  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:42:06.384  1019  4367 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-12 14:42:06.384  1019  4367 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4271, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-12 14:42:06.384  1019  4367 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-12 14:42:06.384  1019  4367 D BatteryService: stay LED for charging
09-12 14:42:06.384  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-12 14:42:06.394  7839  7839 E Zygote  : MountEmulatedStorage()
,09-12 14:42:06.394  7839  7839 E Zygote  : v2
09-12 14:42:06.394  7839  7839 I libpersona: KNOX_SDCARD checking this for 10105
09-12 14:42:06.394  7839  7839 I libpersona: KNOX_SDCARD not a persona
,09-12 14:42:06.404  7839  7839 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 14:42:06.404  1019  1139 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7839 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-12 14:42:06.404  7839  7839 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 14:42:06.404  7839  7839 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-12 14:42:06.404  1019  1019 I MotionRecognitionService: Plugged
,09-12 14:42:06.404  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,09-12 14:42:06.414  1183  1183 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-12 14:42:06.414  1183  1183 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-12 14:42:06.414  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-12 14:42:06.414  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,09-12 14:42:06.424  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,09-12 14:42:06.434  3211  3211 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-12 14:42:06.434  1019  1032 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-12 14:42:06.434  3211  7809 D HeadsetStateMachine: Disconnected process message: 10
,09-12 14:42:06.444  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
09-12 14:42:06.444  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,09-12 14:42:06.444  7839  7839 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:42:06.444  7839  7839 D ActivityThread: Added TimaKeyStore provider
,09-12 14:42:06.454  3211  7856 D BluetoothSocket: bindListen(): myUserId = 0
09-12 14:42:06.454  3211  7856 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 14:42:06.454  3211  7856 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[85]}
09-12 14:42:06.454  3211  7856 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 14:42:06.454  3211  7856 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 14:42:06.454  3211  7856 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25a24fce
,09-12 14:42:06.454  3211  7856 D BluetoothSocket: channel: 12
09-12 14:42:06.454  3211  7856 I BtOppRfcommListener: Accept thread started.
,09-12 14:42:06.564   258   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-12 14:42:06.564   258   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 14:42:06.574  7839  7860 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-12 14:42:06.574   258   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-12 14:42:06.574   258   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 14:42:06.574  7839  7860 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-12 14:42:06.724  7839  7839 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.io.File.exists(File.java:363)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 14:42:06.724  7839  7839 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 14:42:06.724  7839  7839 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 14:42:06.724  7839  7839 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.q.e.b(PG:170)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 14:42:06.724  7839  7839 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.q.k.d(PG:583)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.q.e.b(PG:170)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 14:42:06.724  7839  7839 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.io.File.exists(File.java:363)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 14:42:06.724  7839  7839 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.io.File.exists(File.java:363)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 14:42:06.724  7839  7839 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 14:42:06.724  7839  7839 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 14:42:06.734  1019  1341 I ActivityManager: Killing 7452:com.sec.pcw.device/1000 (adj 15): empty #21
,09-12 14:42:06.784  7839  7870 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-12 14:42:06.804  1019  4368 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 14:42:06.804  1019  4368 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:06.804  1019  4368 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:42:06.804  1019  4368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-12 14:42:07.384   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 14:42:08.364   289   289 E SMD     : DCD OFF,
,09-12 14:42:08.394   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 14:42:08.894  7055  7256 D BluetoothAdapter: disable()
,09-12 14:42:08.894  1019  1266 D SettingsProvider: name = bluetooth_on
,09-12 14:42:08.904  3211  3283 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-12 14:42:08.904  3211  3283 D BluetoothAdapterProperties: Setting state to 13
,09-12 14:42:08.904  3211  3283 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 14:42:08.904  3211  3283 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-12 14:42:08.904  3211  3283 D BluetoothAdapterService: updateAdapterState state is 13
,09-12 14:42:08.904  1019  1499 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 14:42:08.914  1019  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0,
,09-12 14:42:08.914  1019  1499 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:42:08.914  1019  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:08.914  1019  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:08.914  3211  3283 D BluetoothAdapterService: Autoconnection is available 
09-12 14:42:08.914  3211  3283 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-12 14:42:08.914  3211  3283 D BluetoothAdapterService: terminating service from this receiver
,09-12 14:42:08.914  1019  1341 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-12 14:42:08.914  3211  3211 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-12 14:42:08.914  3211  3211 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1c0eeef, channel: 19, state: LISTENING,
09-12 14:42:08.914  3211  3211 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1c0eeef, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@4a90664, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3ccbdfcmSocket: android.net.LocalSocket@2cf7dc85 impl:android.net.LocalSocketImpl@3e979ada fd:FileDescriptor[80]
,09-12 14:42:08.914  3211  3211 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2cf7dc85 impl:android.net.LocalSocketImpl@3e979ada fd:FileDescriptor[80]
09-12 14:42:08.914  1019  1341 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:08.914  1019  1341 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-12 14:42:08.914  1019  1341 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:08.924  3211  3283 D BluetoothAdapterProperties: onBluetoothDisable()
09-12 14:42:08.924  3211  3283 D BluetoothAdapterProperties: mDiscovering is false
,09-12 14:42:08.924  1019  1507 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-12 14:42:08.924  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-12 14:42:08.924  3211  3283 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-12 14:42:08.924  1019  1019 I InputMethodManagerService: [BT Setting State] State =13
,09-12 14:42:08.934  1183  1183 D BluetoothTile:  onBluetoothStateChange:
,09-12 14:42:08.934  4827  4827 D BluetoothPbap: Proxy object disconnected
09-12 14:42:08.934  4827  4827 D PbapServerProfile: Bluetooth service disconnected
,09-12 14:42:08.934  1183  1183 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-12 14:42:08.944  1183  1183 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-12 14:42:08.944  1183  1710 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 14:42:08.944  1183  1183 D BluetoothTile:  getBluetoothState : 13
,09-12 14:42:08.944  1183  1710 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 14:42:08.944  1971  1971 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 14:42:08.944  4827  4827 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 14:42:08.944  1019  1032 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 14:42:08.954  1019  1504 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-12 14:42:08.954  1183  1183 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-12 14:42:08.954  1183  1710 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-12 14:42:08.954  7055  7055 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:42:08.954  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:08.954  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:08.954  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:08.954  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:42:08.954  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:42:08.954  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:08.954  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:08.954  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 14:42:08.964  3211  3286 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-12 14:42:08.964  3211  3286 D BluetoothAdapterProperties: Scan Mode:20
09-12 14:42:08.964  7055  7055 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 14:42:08.964  7055  7055 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 14:42:08.964  3211  3211 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2525bde8, channel: 5, state: LISTENING
,09-12 14:42:08.964  3211  3283 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true,
09-12 14:42:08.964  3211  3211 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2525bde8, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3e4fdd82, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1a5ebc01mSocket: android.net.LocalSocket@1648aa6 impl:android.net.LocalSocketImpl@1c71cce7 fd:FileDescriptor[82],
09-12 14:42:08.964  3211  3283 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
09-12 14:42:08.964  3211  3211 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1648aa6 impl:android.net.LocalSocketImpl@1c71cce7 fd:FileDescriptor[82]
09-12 14:42:08.964  3211  3283 E bt-btif : BTM_SEC_CLR[170x1a1c
09-12 14:42:08.964  3211  3287 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
09-12 14:42:08.964  3211  3283 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
09-12 14:42:08.964  3211  7856 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 14:42:08.964  3211  3211 I BtOppRfcommListener: stopping Accept Thread
09-12 14:42:08.964  3211  3211 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2a8cd094, channel: 12, state: LISTENING
09-12 14:42:08.964  3211  3211 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2a8cd094, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25a24fce, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2bfa173dmSocket: android.net.LocalSocket@22beab32 impl:android.net.LocalSocketImpl@3e045083 fd:FileDescriptor[85]
09-12 14:42:08.964  3211  3211 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@22beab32 impl:android.net.LocalSocketImpl@3e045083 fd:FileDescriptor[85]
,09-12 14:42:08.964  3211  7856 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-12 14:42:08.974  3211  3211 V BluetoothOppManager: cleanUp...
,09-12 14:42:08.974  3211  3287 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 14:42:08.974  3211  3287 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 14:42:08.974  3211  3287 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 14:42:08.974  3211  3287 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 14:42:08.974  3211  3287 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 14:42:08.974  3211  3287 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-12 14:42:08.974  4827  4827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 14:42:08.974  1019  1347 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-12 14:42:08.974  7055  7055 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:42:08.974  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:08.974  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:08.974  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:08.974  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:42:08.974  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:42:08.974  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:08.974  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:08.974  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 14:42:08.974  7055  7055 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:42:08.974  7055  7055 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 14:42:08.974  1019  1347 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 14:42:08.974  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:42:08.984  1019  1347 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:08.984  1019  1347 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:08.984  1019  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 14:42:08.984  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:08.984  1639  1639 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 14:42:08.994  4827  4827 D DockEventReceiver: finishStartingService: stopping service
,09-12 14:42:08.994  4827  4827 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 14:42:08.994  1183  1183 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 14:42:08.994  1183  1183 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-12 14:42:09.174  3211  3283 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-12 14:42:09.174  3211  3283 D BtConfig.SecureMode: isSecureModeOn:false
09-12 14:42:09.174  3211  3283 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-12 14:42:09.174  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
09-12 14:42:09.174  3211  3283 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
09-12 14:42:09.174  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-12 14:42:09.174  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-12 14:42:09.174  1019  4367 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 14:42:09.174  3211  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-12 14:42:09.174  1019  4367 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-12 14:42:09.174  1019  4367 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:09.174  1019  4367 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:09.174  1019  4367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:09.174  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-12 14:42:09.174  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-12 14:42:09.174  3211  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-12 14:42:09.174  1019  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 14:42:09.174  1019  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 14:42:09.174  3211  3211 D HeadsetService: Received stop request...Stopping profile...
,09-12 14:42:09.174  1019  1489 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:42:09.174  1019  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:09.174  1019  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:09.174  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,09-12 14:42:09.174  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
,09-12 14:42:09.174  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 14:42:09.174  3211  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-12 14:42:09.174  1019  4368 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 14:42:09.174  1019  4368 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 14:42:09.174  1019  4368 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:09.174  1019  4368 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 14:42:09.174  1019  4368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:09.184  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-12 14:42:09.184  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,09-12 14:42:09.184  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-12 14:42:09.184  3211  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-12 14:42:09.184  4827  4827 D HeadsetProfile: Bluetooth service disconnected
09-12 14:42:09.184  3211  3211 D A2dpService: Received stop request...Stopping profile...
,09-12 14:42:09.184  1019  1507 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 14:42:09.184  1019  1507 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-12 14:42:09.184  3211  7818 D A2dpStateMachine: Exit Disconnected: -1
,09-12 14:42:09.184  1019  1507 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:42:09.184  1019  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:09.184  1019  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:09.194  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-12 14:42:09.194  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-12 14:42:09.194  3211  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-12 14:42:09.194  1019  1139 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 14:42:09.194  1019  1139 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 14:42:09.194  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
,09-12 14:42:09.194  1019  1139 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:09.194  1019  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 14:42:09.194  1019  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:09.194  1019  1019 D BluetoothA2dp: Proxy object disconnected
09-12 14:42:09.194  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-12 14:42:09.194  4827  4827 D BluetoothA2dp: Proxy object disconnected
09-12 14:42:09.194  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-12 14:42:09.194  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 14:42:09.194  3211  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-12 14:42:09.194  4827  4827 D A2dpProfile: Bluetooth service disconnected
,09-12 14:42:09.194  1019  4368 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 14:42:09.194  1019  4368 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 14:42:09.204  1019  4368 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:42:09.204  1019  4368 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:09.204  1019  4368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:09.204  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,09-12 14:42:09.204  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-12 14:42:09.204  3211  3283 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-12 14:42:09.204  1019  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 14:42:09.204  1019  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 14:42:09.204  1019  1504 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:42:09.204  1019  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:09.204  1019  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:09.204  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-12 14:42:09.204  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 14:42:09.204  3211  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-12 14:42:09.204  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-12 14:42:09.204  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-12 14:42:09.204  3211  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-12 14:42:09.204  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-12 14:42:09.204  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-12 14:42:09.204  3211  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-12 14:42:09.204  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-12 14:42:09.204  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 14:42:09.204  3211  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-12 14:42:09.204  3211  3283 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-12 14:42:09.204  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-12 14:42:09.204  3211  3211 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 14:42:09.204  3211  3211 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-12 14:42:09.214  3211  3211 D HidService: Received stop request...Stopping profile...
,09-12 14:42:09.214  3211  3211 D HidService: Stopping Bluetooth HidService
09-12 14:42:09.214  3211  3211 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-12 14:42:09.214  3211  3211 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-12 14:42:09.214  3211  3211 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-12 14:42:09.214  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
,09-12 14:42:09.214  3211  3211 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-12 14:42:09.214  3211  3211 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-12 14:42:09.214  3211  3211 D HealthService: Received stop request...Stopping profile...
,09-12 14:42:09.214  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
,09-12 14:42:09.214  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,09-12 14:42:09.224  3211  3211 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 14:42:09.224  3211  3211 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-12 14:42:09.224  4827  4827 D BluetoothInputDevice: Proxy object disconnected
09-12 14:42:09.224  4827  4827 D HidProfile: Bluetooth service disconnected
,09-12 14:42:09.224  3211  3211 D PanService: Received stop request...Stopping profile...
,09-12 14:42:09.224  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
,09-12 14:42:09.224  1019  1019 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-12 14:42:09.224  3211  3211 D BluetoothA2dp: Proxy object disconnected
,09-12 14:42:09.224  3211  3211 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,09-12 14:42:09.224  3211  7819 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-12 14:42:09.224  3211  3211 I GKI_LINUX: GKI_exit_task 2 done
09-12 14:42:09.224  3211  3211 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-12 14:42:09.224  4827  4827 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 14:42:09.224  4827  4827 D PanProfile: Bluetooth service disconnected
,09-12 14:42:09.224  3211  3211 D BluetoothMapService: Received stop request...Stopping profile...
,09-12 14:42:09.224  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
,09-12 14:42:09.234  3211  3211 D SapService: Received stop request...Stopping profile...
09-12 14:42:09.234  3211  3211 D SapService: Stopping Bluetooth SapService
09-12 14:42:09.234  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
,09-12 14:42:09.234  4827  4827 D BluetoothMap: Proxy object disconnected
09-12 14:42:09.234  4827  4827 D MapProfile: Bluetooth service disconnected
09-12 14:42:09.234  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,09-12 14:42:09.234  3211  3211 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-12 14:42:09.234  3211  3211 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 14:42:09.234  3211  3211 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-12 14:42:09.234  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-12 14:42:09.234  3211  3211 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. ,
09-12 14:42:09.234  3211  3211 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 14:42:09.234  3211  3211 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-12 14:42:09.234  3211  3211 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 14:42:09.234  3211  3211 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object,
09-12 14:42:09.234  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-12 14:42:09.234  3211  3211 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-12 14:42:09.234  3211  3211 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 14:42:09.234  3211  3211 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-12 14:42:09.234  3211  3211 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-12 14:42:09.234  3211  3211 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 14:42:09.234  4827  4827 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-12 14:42:09.234  4827  4827 D SapProfile: Bluetooth service disconnected
09-12 14:42:09.234  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,09-12 14:42:09.234  3211  3211 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-12 14:42:09.234  3211  3211 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-12 14:42:09.234  3211  3211 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-12 14:42:09.234  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,09-12 14:42:09.234  3211  3211 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-12 14:42:09.234  3211  3211 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-12 14:42:09.234  3211  3211 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-12 14:42:09.234  3211  3283 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-12 14:42:09.234  3211  3283 D BluetoothAdapterProperties: Setting state to 10
,09-12 14:42:09.234  3211  3283 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-12 14:42:09.234  3211  3283 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-12 14:42:09.234  3211  3283 D BluetoothAdapterService: updateAdapterState state is 10
,09-12 14:42:09.244  3211  3283 D BluetoothAdapterService: Autoconnection is available 
09-12 14:42:09.244  3211  3283 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-12 14:42:09.244  3211  3283 I BluetoothAdapterState: Entering OffState
09-12 14:42:09.244  1639  1670 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 14:42:09.244  1639  1670 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 14:42:09.244  4827  7755 D BluetoothMap: onBluetoothStateChange: up=false
,09-12 14:42:09.244  4827  4840 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 14:42:09.244  4827  4840 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 14:42:09.244  4827  4838 D Bluetoothsap: onBluetoothStateChange: up=false
,09-12 14:42:09.244  4827  4838 D Bluetoothsap: Unbinding service...
,09-12 14:42:09.244  1452  1473 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 14:42:09.244  1452  1473 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 14:42:09.244  1183  1956 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 14:42:09.244  1183  1956 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 14:42:09.244  4827  7755 D BluetoothPbap: onBluetoothStateChange: up=false
,09-12 14:42:09.244  4827  7755 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-12 14:42:09.254  4827  4840 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 14:42:09.254  7839  7853 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 14:42:09.254  7839  7853 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 14:42:09.254  1019  1048 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 14:42:09.254  3211  3364 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 14:42:09.254  3211  3364 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 14:42:09.254  1442  1471 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 14:42:09.254  1442  1471 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 14:42:09.254  3211  3224 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 14:42:09.254  1647  2494 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 14:42:09.254  1647  2494 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 14:42:09.254  1433  7878 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 14:42:09.254  1433  7878 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 14:42:09.254  1019  1048 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 14:42:09.254  1019  1048 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 14:42:09.254  7055  7069 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 14:42:09.254  7055  7069 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 14:42:09.254  7055  7069 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-12 14:42:09.254  7055  7069 D BluetoothLeAdvertiser: Exit stop advertising
,09-12 14:42:09.254  7055  7069 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,09-12 14:42:09.254  7055  7069 D BluetoothLeScanner: Exiting stopAllScan
,09-12 14:42:09.264  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-12 14:42:09.264  1019  1019 I InputMethodManagerService: [BT Setting State] State =10
,09-12 14:42:09.264  1019  1019 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-12 14:42:09.264  1183  1183 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED,
09-12 14:42:09.264  1183  1183 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-12 14:42:09.264  1183  1183 D BluetoothTile:  getBluetoothState : 10
,09-12 14:42:09.274  1971  1971 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 14:42:09.274  1019  1031 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 14:42:09.274  4827  4827 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 14:42:09.274  1019  1341 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-12 14:42:09.274  1183  1183 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 14:42:09.274  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:09.274  1183  1183 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 14:42:09.274  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:09.284  4827  4827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 14:42:09.284  1019  4368 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-12 14:42:09.284  1019  4368 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 14:42:09.284  1019  4368 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:42:09.284  1019  4368 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 14:42:09.284  1019  4368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 14:42:09.294  1639  1639 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 14:42:09.294  4827  4827 D DockEventReceiver: finishStartingService: stopping service
,09-12 14:42:09.304  4827  4827 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 14:42:09.304  1183  1183 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:42:09.304  1183  1183 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-12 14:42:09.384   317   317 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-12 14:42:11.374   289   289 E SMD     : DCD OFF
,09-12 14:42:11.924  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 14:42:11.924  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:42:12.594  1019  3350 D SSRM:n  : SIOP:: AP = 340
,09-12 14:42:14.364   289   289 E SMD     : DCD OFF,
,09-12 14:42:14.924  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 14:42:14.924  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4d269a4 added. We now have 6 listener(s)
09-12 14:42:14.924  7055  7256 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 14:42:14.924  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 14:42:14.924  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29f230d added. We now have 7 listener(s)
,09-12 14:42:14.924  7055  7256 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 14:42:14.924  7055  7256 I System.out: IsBluetoothEnabled
,09-12 14:42:14.924  7055  7256 D BluetoothAdapter: disable()
,09-12 14:42:14.934  1019  3798 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-12 14:42:14.934  7055  7256 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:14.934  7055  7256 D BluetoothAdapter: enable()
,09-12 14:42:14.934  1019  1507 W ActivityManager: Permission Denial: getCurrentUser() from pid=7055, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-12 14:42:14.944  1019  1507 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-12 14:42:14.944  1019  1507 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7055, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 14:42:14.944  1019  1507 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-12 14:42:14.944  1019  1507 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-12 14:42:14.944  1019  1507 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-12 14:42:14.944  1019  1507 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-12 14:42:14.944  1019  1507 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-12 14:42:14.944  1019  1507 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-12 14:42:14.944  1019  1507 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 14:42:14.944  1019  1507 D SettingsProvider: name = bluetooth_on
,09-12 14:42:14.944  1019  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-12 14:42:14.944  1019  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 14:42:14.954  1019  1048 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-12 14:42:14.954  3211  3283 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-12 14:42:14.954  3211  3283 D BluetoothAdapterProperties: Setting state to 11
,09-12 14:42:14.954  3211  3283 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-12 14:42:14.954  3211  3283 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-12 14:42:14.954  3211  3283 D BluetoothAdapterService: updateAdapterState state is 11
,09-12 14:42:14.954  3211  3283 D BluetoothAdapterService: Autoconnection is available 
,09-12 14:42:14.954  3211  3283 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-12 14:42:14.954  3211  3283 D BtConfig.SecureMode: isSecureModeOn:false
,09-12 14:42:14.954  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-12 14:42:14.954  3211  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,09-12 14:42:14.964  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-12 14:42:14.964  3211  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
,09-12 14:42:14.964  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-12 14:42:14.964  3211  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-12 14:42:14.964  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService,
,09-12 14:42:14.964  3211  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-12 14:42:14.964  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-12 14:42:14.964  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-12 14:42:14.964  1019  1019 I InputMethodManagerService: [BT Setting State] State =11
09-12 14:42:14.964  3211  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
,09-12 14:42:14.964  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-12 14:42:14.964  3211  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-12 14:42:14.964  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-12 14:42:14.964  3211  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-12 14:42:14.964  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-12 14:42:14.964  3211  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10,
,09-12 14:42:14.964  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 14:42:14.964  3211  3283 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,09-12 14:42:14.964  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-12 14:42:14.964  3211  3283 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-12 14:42:14.964  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-12 14:42:14.964  3211  3283 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-12 14:42:14.964  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 14:42:14.964  3211  3283 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-12 14:42:14.964  3211  3283 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-12 14:42:14.964  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,09-12 14:42:14.964  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-12 14:42:14.964  3211  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-12 14:42:14.974  4827  4827 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 14:42:14.974  1971  1971 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 14:42:14.974  1019  1499 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 14:42:14.974  1019  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-12 14:42:14.974  1183  1183 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-12 14:42:14.974  1183  1183 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:42:14.974  1183  1183 D BluetoothTile:  getBluetoothState : 11
,09-12 14:42:14.974  1019  1499 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:14.974  1019  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:14.974  1019  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:14.984  3211  3211 D HeadsetService: Received start request. Starting profile...
,09-12 14:42:14.984  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:42:14.984  3211  3211 D HeadsetService: start()
09-12 14:42:14.984  3211  3211 D HeadsetStateMachine: make
,09-12 14:42:14.984  1183  1710 D BluetoothTile:  handleUpdatestate:false name:null
09-12 14:42:14.984  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-12 14:42:14.984  1183  1710 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
09-12 14:42:14.984  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-12 14:42:14.984  3211  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-12 14:42:14.984  3211  3211 E HeadsetStateMachine: # of Max HF connection is 2
,09-12 14:42:14.984  1019  3798 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 14:42:14.984  1019  4368 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 14:42:14.984  1019  4368 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 14:42:14.994  1639  1639 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 14:42:14.994  1019  1266 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-12 14:42:14.994  1183  1183 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-12 14:42:14.994  1019  4368 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:14.994  1019  4368 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:14.994  1019  4368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:14.994  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-12 14:42:14.994  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 14:42:14.994  3211  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-12 14:42:14.994  1019  3798 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-12 14:42:14.994  1019  3798 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-12 14:42:14.994  1019  3798 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:42:14.994  1019  3798 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:14.994  1019  3798 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-12 14:42:14.994  1019  1347 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 14:42:14.994  1019  1347 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 14:42:14.994  1019  1347 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:14.994  1019  1347 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:14.994  1019  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:15.004  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,09-12 14:42:15.004  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-12 14:42:15.004  3211  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-12 14:42:15.004  1019  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 14:42:15.004  1019  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-12 14:42:15.004  1019  1489 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:42:15.004  1019  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:15.004  1019  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:15.004  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-12 14:42:15.004  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-12 14:42:15.004  3211  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-12 14:42:15.004  1019  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 14:42:15.004  1019  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 14:42:15.014  1019  1489 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:15.014  1019  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:15.014  1019  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:15.014  1183  1183 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 14:42:15.014  1019  1341 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-12 14:42:15.014  1019  1341 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-12 14:42:15.014  1019  1341 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:42:15.014  1019  1341 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:15.014  1019  1341 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-12 14:42:15.014  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-12 14:42:15.014  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 14:42:15.014  3211  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-12 14:42:15.014  3211  3211 I bluedroid: get_profile_interface handsfree
,09-12 14:42:15.024  1019  1499 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 14:42:15.024  1019  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 14:42:15.024  1019  1499 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:15.024  1019  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:15.024  1019  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:15.024  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,09-12 14:42:15.024  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-12 14:42:15.024  4827  4827 D BluetoothNotiBroadcastReceiver: onReceive
09-12 14:42:15.024  3211  3283 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-12 14:42:15.024  1019  1507 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 14:42:15.024  1019  1507 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 14:42:15.034  1183  1183 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:42:15.034  1183  1183 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-12 14:42:15.034  1019  1507 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:42:15.034  1019  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:15.034  1019  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:15.034  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService,
09-12 14:42:15.034  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 14:42:15.034  3211  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,09-12 14:42:15.034  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-12 14:42:15.034  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-12 14:42:15.034  3211  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-12 14:42:15.034  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
,09-12 14:42:15.034  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-12 14:42:15.034  3211  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-12 14:42:15.034  3211  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-12 14:42:15.034  3211  3211 E DualScoManager: Dual Sco Manager already instantiated
09-12 14:42:15.034  3211  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-12 14:42:15.034  3211  3211 I DualScoManager: Set HeadsetServiceHelper
09-12 14:42:15.034  3211  3211 D BluetoothAtMessage: createCMTIContentObservers
09-12 14:42:15.034  3211  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-12 14:42:15.034  3211  3283 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-12 14:42:15.034  1019  1031 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-12 14:42:15.034  1019  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 14:42:15.034  1019  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 14:42:15.034  1019  1031 D SettingsProvider: selectionArgs: false
09-12 14:42:15.034  1019  1031 D SettingsProvider: selectionArgs: 1002
09-12 14:42:15.034  1019  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 14:42:15.034  1019  1031 D SettingsProvider: ret = -1
09-12 14:42:15.034  3211  7886 D HeadsetStateMachine: Enter Disconnected: -2
,09-12 14:42:15.044  3211  3211 D HeadsetService: mStartError = false,
09-12 14:42:15.044  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
,09-12 14:42:15.044  3211  3211 D A2dpService: Received start request. Starting profile...
09-12 14:42:15.044  3211  3211 D A2dpService: start()
09-12 14:42:15.044  3211  3211 I bluedroid: get_profile_interface avrcp
09-12 14:42:15.044  3211  7886 D HeadsetStateMachine: Clear mHeadsetBrsf
09-12 14:42:15.044  3211  7886 D HeadsetStateMachine: map size, before remove : 0
09-12 14:42:15.044  3211  7886 D HeadsetStateMachine: map size, after remove: 0
,09-12 14:42:15.044  3211  3211 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 14:42:15.044  3211  3211 D Avrcp   : Initialize Media Controller
09-12 14:42:15.044  3211  3211 D Avrcp   : Get the Context Package Name: com.android.bluetooth
09-12 14:42:15.044  3211  3211 E Avrcp   : getActiveSessions
09-12 14:42:15.044  3211  3211 D Avrcp   : pick active media Controller
,09-12 14:42:15.054  3211  3211 D Avrcp   : Get the active Media Controller 
,09-12 14:42:15.054  3211  3211 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-12 14:42:15.054  3211  3211 D A2dpStateMachine: make
,09-12 14:42:15.054  3211  7887 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-12 14:42:15.054  3211  3211 I bluedroid: get_profile_interface a2dp
09-12 14:42:15.054  3211  7889 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-12 14:42:15.054  3211  3211 E bt-btif : warning : media task started media_task_refcnt 1 
,09-12 14:42:15.064  3211  3211 D A2dpService: mStartError = false
09-12 14:42:15.064  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
,09-12 14:42:15.064  3211  3211 D HeadsetStateMachine: Try to query the phonestate on bind
09-12 14:42:15.064  3211  7888 D A2dpStateMachine: Enter Disconnected: -2
,09-12 14:42:15.064  1433  1451 I Telecom : BluetoothPhoneService: queryPhoneState
,09-12 14:42:15.064  1433  1433 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-12 14:42:15.064  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-12 14:42:15.064  1433  1451 I Telecom : BluetoothPhoneService: Result of Message : true
,09-12 14:42:15.064  3211  3211 D HidService: Received start request. Starting profile...
09-12 14:42:15.064  3211  3211 D HidService: start()
09-12 14:42:15.064  3211  3211 I bluedroid: get_profile_interface hidhost
09-12 14:42:15.064  3211  3211 D HidService: setHidService(): set to: null
09-12 14:42:15.064  3211  3211 D HidService: mStartError = false
09-12 14:42:15.064  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
,09-12 14:42:15.064  3211  3211 D HealthService: Received start request. Starting profile...
,09-12 14:42:15.064  3211  3211 D HealthService: start()
,09-12 14:42:15.074  3211  3211 I bluedroid: get_profile_interface health
,09-12 14:42:15.074  3211  3211 D HealthService: mStartError = false
09-12 14:42:15.074  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
,09-12 14:42:15.074  3211  3211 D HeadsetStateMachine: Proxy object connected
09-12 14:42:15.074  3211  3211 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0,
09-12 14:42:15.074  3211  3211 D PanService: Received start request. Starting profile...
09-12 14:42:15.074  3211  3211 D PanService: start()
09-12 14:42:15.074  3211  3211 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 14:42:15.074  3211  3211 I bluedroid: get_profile_interface pan
09-12 14:42:15.074  3211  7886 D HeadsetStateMachine: Disconnected process message: 11
09-12 14:42:15.074  3211  3211 D PanService: mStartError = false
09-12 14:42:15.074  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
09-12 14:42:15.074  3211  3211 D BluetoothMapService: Received start request. Starting profile...
09-12 14:42:15.074  3211  3211 D BluetoothMapService: start()
,09-12 14:42:15.074  3211  7887 D BluetoothMediaBrowser: no now playing list,
09-12 14:42:15.074  3211  7887 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
09-12 14:42:15.074  3211  3211 D BluetoothMapService: mStartError = false
09-12 14:42:15.074  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
,09-12 14:42:15.074  3211  3211 D SapService: Received start request. Starting profile...
09-12 14:42:15.074  3211  3211 D SapService: start()
09-12 14:42:15.074  3211  3211 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-12 14:42:15.074  3211  3211 I bluedroid: get_profile_interface sap
09-12 14:42:15.074  3211  3211 D SapService: mStartError = false
09-12 14:42:15.074  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
,09-12 14:42:15.074  3211  3211 D HeadsetPhoneState: sendDeviceDataStateChanged
09-12 14:42:15.074  3211  3211 D HeadsetPhoneState: Signal level : previous=0 curr=4
09-12 14:42:15.074  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-12 14:42:15.074  3211  3211 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-12 14:42:15.074  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-12 14:42:15.074  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-12 14:42:15.074  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,09-12 14:42:15.074  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
09-12 14:42:15.074  3211  7886 D HeadsetStateMachine: Disconnected process message: 18
09-12 14:42:15.074  3211  7886 D HeadsetStateMachine: Disconnected process message: 10
09-12 14:42:15.074  3211  7886 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 14:42:15.074  3211  7886 D HeadsetStateMachine: Disconnected process message: 11
,09-12 14:42:15.094  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-12 14:42:15.094  3211  3211 E BluetoothAdapterService(715025291): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true,
,09-12 14:42:15.094  3211  3283 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-12 14:42:15.104  3211  3283 I bluedroid: enable
,09-12 14:42:15.104  3211  3286 E bt-btif : Calling BTA_HhEnable
,09-12 14:42:15.104  3211  3286 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-12 14:42:15.104  3211  3286 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-12 14:42:15.104  3211  3286 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-12 14:42:15.104  3211  3286 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
09-12 14:42:15.104  3211  3286 E BluetoothServiceJni: populateRssiValuesNative
09-12 14:42:15.104  3211  3286 I bluedroid: getModelRssiValues
,09-12 14:42:15.104  3211  3286 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-12 14:42:15.104  3211  3286 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-12 14:42:15.114  1019  1019 D SettingsProvider: name = bluetooth_name
,09-12 14:42:15.114  3211  3286 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-12 14:42:15.114  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:15.114  3211  3286 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-12 14:42:15.114  3211  3286 D BluetoothAdapterProperties: Scan Mode:20
,09-12 14:42:15.114  3211  3286 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 14:42:15.114  3211  3286 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
09-12 14:42:15.114  3211  3286 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
09-12 14:42:15.114  3211  3286 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,09-12 14:42:15.124  3211  3286 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-12 14:42:15.124  3211  3286 E bt-btif : JVenable fails
,09-12 14:42:15.124  3211  3286 D bte_conf: Device ID record 1 : primary,
,09-12 14:42:15.124  3211  3286 D bte_conf:   vendorId            = 0075
09-12 14:42:15.124  3211  3286 D bte_conf:   vendorIdSource      = 0001
09-12 14:42:15.124  3211  3286 D bte_conf:   product             = 0100
09-12 14:42:15.124  3211  3286 D bte_conf:   version             = 0200,
09-12 14:42:15.124  3211  3286 D bte_conf:   clientExecutableURL = 
09-12 14:42:15.124  3211  3286 D bte_conf:   serviceDescription  = 
09-12 14:42:15.124  3211  3286 D bte_conf:   documentationURL    = 
,09-12 14:42:15.124  3211  3286 D bte_conf: bte_load_did_conf no section named DID2.
09-12 14:42:15.124  3211  3286 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-12 14:42:15.124  3211  3286 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-12 14:42:15.124  3211  3283 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-12 14:42:15.124  3211  3283 D BluetoothAdapterProperties: ScanMode =  20
09-12 14:42:15.124  3211  3283 D BluetoothAdapterProperties: State =  11
09-12 14:42:15.124  1019  1499 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-12 14:42:15.124  3211  3283 D BluetoothAdapterProperties: Setting state to 12
09-12 14:42:15.124  3211  3283 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-12 14:42:15.124  3211  3286 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-12 14:42:15.124  3211  3286 D BluetoothAdapterProperties: Scan Mode:21
,09-12 14:42:15.124  3211  3286 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 14:42:15.124  1019  3798 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-12 14:42:15.124  1019  3798 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 14:42:15.124  1019  3798 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 14:42:15.124  1019  3798 D SettingsProvider: selectionArgs: false
09-12 14:42:15.124  1019  3798 D SettingsProvider: selectionArgs: 1002
09-12 14:42:15.124  1019  3798 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 14:42:15.124  1019  3798 D SettingsProvider: ret = -1
,09-12 14:42:15.124  3211  3283 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 14:42:15.124  3211  3283 D BluetoothAdapterService: updateAdapterState state is 12
09-12 14:42:15.134  1019  4366 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 14:42:15.134  1019  4366 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-12 14:42:15.134  1019  4366 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:15.134  1019  4366 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:15.134  1019  4366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:15.134  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:15.134  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:15.134  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:15.134  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:42:15.134  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:42:15.134  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:15.134  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:15.134  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 14:42:15.134  1639  1670 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 14:42:15.134  3211  3283 D BluetoothAdapterService: Autoconnection is available 
09-12 14:42:15.134  3211  3283 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-12 14:42:15.134  3211  3283 D BluetoothAdapterService: starting service from this receiver
09-12 14:42:15.134  1019  1499 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 14:42:15.134  1019  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-12 14:42:15.134  1639  1670 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 14:42:15.134  1019  1499 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:15.134  1019  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:15.134  1019  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:15.144  1452  1473 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-12 14:42:15.144  1019  1048 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 14:42:15.144  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 14:42:15.144  3211  3211 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-12 14:42:15.144  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:42:15.144  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:15.144  3211  3283 I BluetoothAdapterState: Entering On State from state = 11
09-12 14:42:15.144  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:15.144  7055  7055 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 14:42:15.154  1452  1473 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 14:42:15.154  4827  7755 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 14:42:15.154  3211  3211 I BluetoothPbapService: Handler(): got msg=1
,09-12 14:42:15.294  1019  1048 I art     : Explicit concurrent mark sweep GC freed 54267(3MB) AllocSpace objects, 8(129KB) LOS objects, 33% free, 23MB/34MB, paused 2.319ms total 140.929ms
09-12 14:42:15.294  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-12 14:42:15.294  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 14:42:15.294  1019  3798 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-12 14:42:15.294  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:15.294  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:15.294  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:15.294  1433  7833 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 14:42:15.294  1019  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 14:42:15.294  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 14:42:15.294  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:15.294  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:15.294  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:15.294  1433  7833 E BluetoothHeadset: BluetoothHeadset service is binded
09-12 14:42:15.294  4827  4838 D BluetoothAdapter: onBluetoothStateChange: up=true,
09-12 14:42:15.294  4827  4838 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 14:42:15.294  4827  4840 D Bluetoothsap: onBluetoothStateChange: up=true
09-12 14:42:15.294  4827  4840 D Bluetoothsap: Binding service...
,09-12 14:42:15.304  4827  4840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-12 14:42:15.304  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-12 14:42:15.304  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 14:42:15.304  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:15.304  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:15.304  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-12 14:42:15.304  3211  7894 V BluetoothPbapService: PBAP Service initSocket try: 0
09-12 14:42:15.304  4827  4840 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-12 14:42:15.304  4827  4827 D BluetoothMap: Proxy object connected
09-12 14:42:15.304  4827  4827 D MapProfile: Bluetooth service connected
09-12 14:42:15.304  4827  4827 D BluetoothMap: getConnectedDevices()
09-12 14:42:15.304  1452  6619 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 14:42:15.304  1452  6619 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 14:42:15.304  1183  1947 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 14:42:15.304  1183  1947 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 14:42:15.304  4827  4838 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 14:42:15.304  4827  4827 D Bluetoothsap: BluetoothSAP Proxy object connected
09-12 14:42:15.304  4827  4827 D SapProfile: Bluetooth service connected
09-12 14:42:15.304  4827  4827 D Bluetoothsap: getConnectedDevices()
,09-12 14:42:15.314  3211  7894 D BluetoothSocket: bindListen(): myUserId = 0
09-12 14:42:15.314  3211  7894 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 14:42:15.314  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-12 14:42:15.314  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-12 14:42:15.314  3211  7894 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-12 14:42:15.314  3211  7894 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 14:42:15.314  3211  7894 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 14:42:15.314  3211  7894 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ad4e4db
,09-12 14:42:15.314  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:15.314  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:15.314  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-12 14:42:15.314  3211  7894 D BluetoothSocket: channel: 19
09-12 14:42:15.314  3211  7894 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-12 14:42:15.314  4827  4840 D BluetoothPan: Binding service...
09-12 14:42:15.314  4827  4827 D BluetoothPbap: Proxy object connected
09-12 14:42:15.314  4827  4827 D PbapServerProfile: Bluetooth service connected
,09-12 14:42:15.314  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-12 14:42:15.314  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-12 14:42:15.314  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:15.314  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 14:42:15.314  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:15.314  4827  4827 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 14:42:15.314  4827  4827 D PanProfile: Bluetooth service connected
,09-12 14:42:15.314  4827  7755 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 14:42:15.314  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 14:42:15.314  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-12 14:42:15.314  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:15.314  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 14:42:15.324  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:15.324  4827  4827 D HeadsetProfile: Bluetooth service connected
,09-12 14:42:15.324  4827  7755 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 14:42:15.324  1019  1048 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-12 14:42:15.324  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 14:42:15.324  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 14:42:15.324  1019  1048 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 14:42:15.324  4827  4838 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 14:42:15.324  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-12 14:42:15.324  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 14:42:15.324  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:15.324  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:15.324  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:15.324  4827  4840 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 14:42:15.324  4827  4840 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 14:42:15.324  4827  4827 D BluetoothInputDevice: Proxy object connected
09-12 14:42:15.324  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 14:42:15.324  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 14:42:15.324  4827  4827 D HidProfile: Bluetooth service connected
09-12 14:42:15.324  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:15.324  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:15.324  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:15.334  7839  7847 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 14:42:15.334  7839  7847 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 14:42:15.334  1019  1048 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 14:42:15.334  1019  1048 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-12 14:42:15.334  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 14:42:15.334  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 14:42:15.334  1019  1019 D BluetoothA2dp: Proxy object connected
,09-12 14:42:15.334  1433  1466 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 14:42:15.334  1019  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 14:42:15.334  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 14:42:15.334  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:15.334  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:15.334  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:15.334  1433  1466 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 14:42:15.334  3211  3363 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 14:42:15.334  3211  3363 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 14:42:15.334  4827  4827 D BluetoothA2dp: Proxy object connected
09-12 14:42:15.334  4827  4827 D A2dpProfile: Bluetooth service connected
09-12 14:42:15.334  1442  1842 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 14:42:15.334  1442  1842 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 14:42:15.334  3211  3364 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 14:42:15.334  3211  3364 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 14:42:15.344  1019  1048 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-12 14:42:15.344  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-12 14:42:15.344  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:15.344  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:15.344  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:15.344  1647  2494 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 14:42:15.344  1647  2494 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 14:42:15.344  1433  7878 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 14:42:15.344  1433  7878 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 14:42:15.344  1019  1048 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 14:42:15.344  1019  1048 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 14:42:15.344  3211  3211 D BluetoothA2dp: Proxy object connected
09-12 14:42:15.344  3211  3211 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-12 14:42:15.344  7055  7063 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 14:42:15.344  7055  7063 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 14:42:15.344  1019  1048 D BluetoothPan: Binding service...
09-12 14:42:15.344  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-12 14:42:15.344  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 14:42:15.344  1019  1019 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 14:42:15.344  1433  7833 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-12 14:42:15.344  1019  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 14:42:15.344  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-12 14:42:15.344  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:15.344  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:15.344  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:15.344  1433  7833 E BluetoothHeadset: BluetoothHeadset service is binded
09-12 14:42:15.344  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-12 14:42:15.344  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-12 14:42:15.354  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-12 14:42:15.354  1019  1019 I InputMethodManagerService: [BT Setting State] State =12
09-12 14:42:15.354  1019  1019 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-12 14:42:15.354  1433  1433 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1e9c843f, true
,09-12 14:42:15.354  1433  1433 D BluetoothHeadset: registerMessageListener
,09-12 14:42:15.354  1183  1183 D BluetoothTile:  onBluetoothStateChange:
,09-12 14:42:15.364  1183  1183 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-12 14:42:15.364  1183  1183 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:42:15.364  1183  1183 D BluetoothTile:  getBluetoothState : 12
,09-12 14:42:15.364  1183  1710 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 14:42:15.364  1183  1710 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 14:42:15.364  1971  1971 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 14:42:15.364  4827  4827 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 14:42:15.364  1019  1032 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-12 14:42:15.364  1019  1489 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-12 14:42:15.364  1183  1183 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 14:42:15.374  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:15.374  3211  3363 D HeadsetService: registerMessageListener
,09-12 14:42:15.374  1183  1710 D BluetoothTile:  handleUpdatestate:false name:null
09-12 14:42:15.374  3211  3363 D HeadsetService: registerMessageListener
09-12 14:42:15.374  3211  7886 D HeadsetStateMachine: Disconnected process message: 70
09-12 14:42:15.374  3211  7886 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@26c25b78
,09-12 14:42:15.374  1433  1433 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,09-12 14:42:15.374  4827  4827 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,09-12 14:42:15.374  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-12 14:42:15.374  4827  4827 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-12 14:42:15.374  4827  4827 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-12 14:42:15.374  4827  4827 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-12 14:42:15.374  3211  7895 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-12 14:42:15.374  1433  1433 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-12 14:42:15.374  1433  1433 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-12 14:42:15.374  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-12 14:42:15.384  3211  7886 D HeadsetStateMachine: Disconnected process message: 9,
09-12 14:42:15.384  3211  7886 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-12 14:42:15.384   284   700 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-12 14:42:15.384   284   700 V voice   : voice_set_parameters: enter: A2dpSuspended=false
,09-12 14:42:15.384   284   700 V voice   : voice_set_parameters: exit with code(-2)
,09-12 14:42:15.384   284   700 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-12 14:42:15.384   284   700 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-12 14:42:15.384   284   700 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-12 14:42:15.384   284   700 V audio_hw_primary: adev_set_parameters: exit
,09-12 14:42:15.384  3211  7886 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-12 14:42:15.384  4827  4827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 14:42:15.384  1019  1341 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-12 14:42:15.384  3211  7895 D BluetoothSocket: bindListen(): myUserId = 0
09-12 14:42:15.384  3211  7895 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 14:42:15.384  1019  1341 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 14:42:15.384  1019  1341 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:42:15.394  1019  1341 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:15.394  1019  1341 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 14:42:15.394  3211  7895 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
,09-12 14:42:15.394  1639  1639 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 14:42:15.394  3211  7895 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 14:42:15.394  3211  7895 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 14:42:15.394  3211  7895 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f6fb251
09-12 14:42:15.394  3211  7895 D BluetoothSocket: channel: 5
,09-12 14:42:15.404  4827  4827 D DockEventReceiver: finishStartingService: stopping service
,09-12 14:42:15.404  4827  4827 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 14:42:15.404  1183  1183 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:42:15.404  1183  1183 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-12 14:42:15.414  3211  3211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a9e6b8b
,09-12 14:42:15.414  3211  3211 D BtConfig.SecureMode: isSecureModeOn:false
,09-12 14:42:15.414  1019  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 14:42:15.414  1019  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-12 14:42:15.414  1019  1489 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:42:15.414  1019  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 14:42:15.424  1019  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 14:42:15.434  1019  1504 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-12 14:42:15.444  3211  7900 D BluetoothSocket: bindListen(): myUserId = 0
,09-12 14:42:15.444  3211  7900 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 14:42:15.444  3211  7900 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
,09-12 14:42:15.444  3211  7900 D BluetoothSocket: bindListen(), new LocalSocket 
,09-12 14:42:15.444  3211  7900 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,09-12 14:42:15.444  3211  7900 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@222c228d
,09-12 14:42:15.444  3211  7900 D BluetoothSocket: channel: 12
,09-12 14:42:15.444  3211  7900 I BtOppRfcommListener: Accept thread started.
,09-12 14:42:15.954  7055  7256 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:15.954  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:15.954  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:15.954  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:42:15.954  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:42:15.954  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:15.954  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:15.954  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 14:42:15.954  7055  7256 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:42:15.954  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:42:15.954  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37e12c2 added. We now have 8 listener(s)
09-12 14:42:15.954  7055  7256 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 14:42:15.964  1019  1347 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-12 14:42:15.964  1019  1347 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-12 14:42:15.964  1019  1347 D SecContentProvider2: mCursor = null
,09-12 14:42:15.964  1019  1347 D WifiService: setWifiEnabled: false pid=7055, uid=10170
,09-12 14:42:15.964  1019  1347 D SettingsProvider: name = wifi_on
,09-12 14:42:15.974  7055  7256 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:15.974  1019  1507 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-12 14:42:15.974  1019  1507 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-12 14:42:15.974  1019  1507 D SecContentProvider2: mCursor = null
,09-12 14:42:15.974  1019  1507 D WifiService: setWifiEnabled: true pid=7055, uid=10170
,09-12 14:42:15.974  1019  1507 W ActivityManager: Permission Denial: getCurrentUser() from pid=7055, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-12 14:42:15.974  1019  1507 W WifiService: Failed getting userId using ActivityManagerNative
09-12 14:42:15.974  1019  1507 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7055, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-12 14:42:15.974  1019  1507 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-12 14:42:15.974  1019  1507 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 14:42:15.974  1019  1507 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 14:42:15.974  1019  1507 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-12 14:42:15.974  1019  1507 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-12 14:42:15.974  1019  1507 D SettingsProvider: name = wifi_on
,09-12 14:42:15.984  1019  1129 E WifiHW  : ##################### set firmware type 0 #####################
,09-12 14:42:16.334  1019  1046 D Tethering: interfaceAdded wlan0
,09-12 14:42:16.334  1019  1134 E Tethering: No numeric data
,09-12 14:42:16.334  1019  1126 V NetworkStats: performPollLocked(flags=0x1)
09-12 14:42:16.334  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 14:42:16.334  1019  1126 D NetworkStatsFactory: UpdateStatsForKnox updated,
09-12 14:42:16.334  1019  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-12 14:42:16.334  1183  1183 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-12 14:42:16.334  1019  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-12 14:42:16.334  1183  1183 D HotspotTile: updateTetherState():false, false
09-12 14:42:16.334  1019  1134 D Tethering: clearTetheredNotification()
,09-12 14:42:16.344  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 14:42:16.344  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 14:42:16.344  1019  1046 D Tethering: interfaceStatusChanged wlan0, false,
09-12 14:42:16.344  1019  1134 D Tethering: InitialState.processMessage what=4,
09-12 14:42:16.344  1019  1126 V NetworkStats: performPollLocked() took 14ms
09-12 14:42:16.344  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:16.344  1019  1134 E Tethering: No numeric data
09-12 14:42:16.344  1019  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 14:42:16.344  1019  1134 D Tethering: clearTetheredNotification(),
09-12 14:42:16.354  1019  1046 D Tethering: interfaceAdded p2p0
09-12 14:42:16.354  1019  1046 D Tethering: p2p0 is not a tetherable iface, ignoring,
,09-12 14:42:16.354  1183  1183 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
09-12 14:42:16.354  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 14:42:16.354  1183  1183 D HotspotTile: updateTetherState():false, false
09-12 14:42:16.354  1019  1126 V NetworkStats: performPollLocked(flags=0x1)
,09-12 14:42:16.354  1019  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 14:42:16.354  1019  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 14:42:16.364   279   986 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-12 14:42:16.364   279   986 D SoftapController: Softap fwReload - Ok
09-12 14:42:16.364  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 14:42:16.364  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:16.364  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:16.364  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 14:42:16.364  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
,09-12 14:42:16.374  1019  1126 V NetworkStats: performPollLocked() took 17ms
09-12 14:42:16.374  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:16.374   279   986 D CommandListener: Setting iface cfg
09-12 14:42:16.374   279   986 D CommandListener: Trying to bring down wlan0
,09-12 14:42:16.374  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:16.374  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 14:42:16.374   279   986 D CommandListener: Clearing all IP addresses on wlan0,
,09-12 14:42:16.384  1019  1129 E WifiHW  : supplicant_name : p2p_supplicant
09-12 14:42:16.384  1019  1129 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-12 14:42:16.384  1019  1129 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-12 14:42:16.394  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-12 14:42:16.394  1183  1183 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 14:42:16.394  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-12 14:42:16.394  1183  1710 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-12 14:42:16.394  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null,
09-12 14:42:16.394  1183  1183 D HotspotTile: onReceive : 2, 0
09-12 14:42:16.394  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:42:16.394  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:16.394  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:42:16.394  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:16.394  1183  1183 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 14:42:16.394  1183  1183 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-12 14:42:16.404  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:16.404  4827  4827 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 14:42:16.404  1019  1347 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 14:42:16.404  1019  1347 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 14:42:16.414  1019  1347 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:16.414  1019  1347 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:16.414  1019  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 14:42:16.424  2187  2187 I Hs20UtilService: Starting #19
,09-12 14:42:16.424  2187  2202 I Hs20UtilService: Message received 5011
,09-12 14:42:16.424  7432  7432 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-12 14:42:16.424  7432  7432 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 14:42:16.424  7432  7432 D SecurityLogAgent: StateMachine : Current State = 1
09-12 14:42:16.424  7432  7432 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 14:42:16.434  7914  7914 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-12 14:42:16.434  1019  1504 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-12 14:42:16.434  7914  7914 I wpa_supplicant: Successfully initialized wpa_supplicant
09-12 14:42:16.434  1019  1504 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4275, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-12 14:42:16.434  7914  7914 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
09-12 14:42:16.434  1019  1504 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-12 14:42:16.434  1019  1504 D BatteryService: stay LED for charging
,09-12 14:42:16.434  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-12 14:42:16.444  1019  1019 I MotionRecognitionService: Plugged
,09-12 14:42:16.444  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,09-12 14:42:16.444  7914  7914 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-12 14:42:16.444  1183  1183 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-12 14:42:16.444  1183  1183 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-12 14:42:16.444   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7914
09-12 14:42:16.444   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-12 14:42:16.444  7914  7914 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-12 14:42:16.444  7914  7914 I wpa_supplicant: ssSupport state is = 1
,09-12 14:42:16.454  7914  7914 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-12 14:42:16.454  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-12 14:42:16.454  7914  7914 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-12 14:42:16.454  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,09-12 14:42:16.454   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7914
09-12 14:42:16.454   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-12 14:42:16.464  3211  3211 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-12 14:42:16.464  3211  7886 D HeadsetStateMachine: Disconnected process message: 10
,09-12 14:42:16.474  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
09-12 14:42:16.474  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,09-12 14:42:16.474  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,09-12 14:42:16.594   370   370 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,09-12 14:42:16.594  7914  7914 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,09-12 14:42:16.644  7914  7914 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-12 14:42:16.644  7914  7914 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-12 14:42:16.654  7914  7914 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-12 14:42:16.654   370   370 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7914
09-12 14:42:16.654   370   370 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-12 14:42:16.654  7914  7914 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
09-12 14:42:16.654  7914  7914 I wpa_supplicant: ssSupport state is = 1
09-12 14:42:16.654  7914  7914 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 14:42:16.654  7914  7914 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 14:42:16.654  7914  7914 E wpa_supplicant: SIM READ ERROR
09-12 14:42:16.654  7914  7914 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-12 14:42:16.654  7914  7914 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 14:42:16.654  7914  7914 E wpa_supplicant: SIM READ ERROR
09-12 14:42:16.654  7914  7914 I wpa_supplicant: Blacklist: Clear (all) 
09-12 14:42:16.654  7914  7914 I wpa_supplicant: wpa_default_ap_write_once
09-12 14:42:16.654  7914  7914 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-12 14:42:16.654  7914  7914 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-12 14:42:16.654  7914  7914 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-12 14:42:16.654  7914  7914 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 14:42:16.654  7914  7914 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-12 14:42:16.654  7914  7914 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-12 14:42:16.654  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false,
09-12 14:42:16.654  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 14:42:16.654  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-12 14:42:16.714  7914  7914 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-12 14:42:16.864  7914  7914 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-12 14:42:16.864  7914  7914 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-12 14:42:16.874  7914  7914 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-12 14:42:16.874   370   370 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7914
09-12 14:42:16.874   370   370 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-12 14:42:16.874  7914  7914 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-12 14:42:16.874  7914  7914 I wpa_supplicant: ssSupport state is = 1
09-12 14:42:16.874  7914  7914 I wpa_supplicant: Ctrl_iface: loading cred from phone
,09-12 14:42:16.884  7914  7914 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-12 14:42:16.894  7914  7914 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-12 14:42:16.894   370   370 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7914
09-12 14:42:16.894   370   370 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,09-12 14:42:16.894  7914  7914 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
09-12 14:42:16.894  7914  7914 I wpa_supplicant: ssSupport state is = 1
09-12 14:42:16.894  7914  7914 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 14:42:16.894  7914  7914 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-12 14:42:16.894  7914  7914 E wpa_supplicant: SIM READ ERROR,
09-12 14:42:16.894  7914  7914 I wpa_supplicant: wpa_default_ap_write_once
09-12 14:42:16.894  7914  7914 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
,09-12 14:42:16.894  7914  7914 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-12 14:42:16.904  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false,
09-12 14:42:16.904  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 14:42:16.904  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
,09-12 14:42:16.904  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 14:42:16.904  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-12 14:42:16.904  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
,09-12 14:42:17.014  7914  7914 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-12 14:42:17.014  7914  7914 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-12 14:42:17.124  7914  7914 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-12 14:42:17.124  7914  7914 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,09-12 14:42:17.124  7914  7914 I wpa_supplicant: Skip scan - bUseNetwork false
,09-12 14:42:17.344  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false,
09-12 14:42:17.344  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-12 14:42:17.344  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
,09-12 14:42:17.374   289   289 E SMD     : DCD OFF,
,09-12 14:42:17.394  1019  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,09-12 14:42:17.394  1019  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21],
09-12 14:42:17.394  7914  7914 I wpa_supplicant: HOTSPOT20_ENABLE called,
09-12 14:42:17.394  7914  7914 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-12 14:42:17.394  7914  7914 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-12 14:42:17.394  7914  7914 E wpa_supplicant: SIM READ ERROR
,09-12 14:42:17.394  7914  7914 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 14:42:17.424  7914  7914 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-12 14:42:17.434  7914  7914 I wpa_supplicant: Skip scan - bUseNetwork false
,09-12 14:42:17.434  1019  1129 D WifiConfigStore: Loading config and enabling all networks 
,09-12 14:42:17.444  4827  4827 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 14:42:17.444  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 14:42:17.444  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 14:42:17.444  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-12 14:42:17.444  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:17.444  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:42:17.444  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:42:17.444  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:42:17.454  1183  1183 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 14:42:17.454  1183  1183 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-12 14:42:17.454  1183  1183 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 14:42:17.454  1183  1710 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 14:42:17.454  1183  1183 D HotspotTile: onReceive : 3, 0
,09-12 14:42:17.454  1019  1499 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 14:42:17.454  1019  1499 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 14:42:17.454  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:17.454  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:17.454  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:17.454  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:42:17.454  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:42:17.454  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:17.454  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:17.454  7055  7055 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 14:42:17.454  1019  1499 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:42:17.454  1019  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:17.454  1019  1129 E WifiConfigStore: Not a HS20
09-12 14:42:17.454  1019  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 14:42:17.464  2187  2187 I Hs20UtilService: Starting #20
,09-12 14:42:17.464  7055  7055 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 14:42:17.464  2187  2202 I Hs20UtilService: Message received 5011
,09-12 14:42:17.474  7432  7432 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 14:42:17.474  1019  1129 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-12 14:42:17.474  7432  7432 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-12 14:42:17.474  7432  7432 D SecurityLogAgent: StateMachine : Current State = 1
09-12 14:42:17.474  7432  7432 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 14:42:17.474  1019  1129 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-12 14:42:17.474  7914  7914 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-12 14:42:17.474  7914  7914 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-12 14:42:17.474  7914  7914 I wpa_supplicant: reset timer : RESET_TIMER 0
09-12 14:42:17.474  7914  7914 I wpa_supplicant: P2P: Current p2p state = IDLE
,09-12 14:42:17.474  7914  7914 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-12 14:42:17.474  7914  7914 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-12 14:42:17.474  7914  7914 I wpa_supplicant: First Scan Start
,09-12 14:42:17.474  7914  7914 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-12 14:42:17.484  1019  1129 D WifiNative-wlan0: Setting external_sim to 1
,09-12 14:42:17.484  1019  1129 D WifiStateMachine: Setting OUI to DA-A1-19
09-12 14:42:17.484  1019  1129 I WifiNative-HAL: startHal
09-12 14:42:17.484  1019  1129 E wifi    : getStaticLongField sWifiHalHandle 0x9f37088c
09-12 14:42:17.484  1019  1129 I WifiNative-HAL: Could not start hal
,09-12 14:42:17.484  1019  1129 E WifiNative-wlan0: do suspend true
,09-12 14:42:17.484  7377  7377 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 14:42:17.484  1019  1128 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-12 14:42:17.484  1019  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-12 14:42:17.484  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 3
,09-12 14:42:17.484  1019  1154 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 14:42:17.494  1019  1154 I WifiNative-HAL: startHal
09-12 14:42:17.494   279   986 D CommandListener: Setting iface cfg
09-12 14:42:17.494  1019  1154 E wifi    : getStaticLongField sWifiHalHandle 0x9e2329bc
09-12 14:42:17.494  1019  1154 I WifiNative-HAL: Could not start hal
09-12 14:42:17.494  1019  1154 E WifiScanningService: could not start HAL
09-12 14:42:17.494   279   986 D CommandListener: Trying to bring up p2p0
,09-12 14:42:17.494  1019  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207],
09-12 14:42:17.494  1019  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-12 14:42:17.494  1019  1128 D WifiP2pService: P2pEnablingState
09-12 14:42:17.494  1019  1129 E WifiNative-wlan0: invaild command id : 215
09-12 14:42:17.494  1019  1128 D WifiP2pService: P2pEnablingState{ what=147457 }
09-12 14:42:17.494  1019  1128 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-12 14:42:17.494  1019  1128 D WifiP2pService: P2p socket connection successful
,09-12 14:42:17.494  1019  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-12 14:42:17.494  1019  1128 D WifiP2pService: P2pEnabledState
09-12 14:42:17.494  1019  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-12 14:42:17.494  1019  1129 E WifiNative-wlan0: invaild command id : 215
,09-12 14:42:17.494  1019  1019 D RttService: SCAN_AVAILABLE : 3
,09-12 14:42:17.494  1019  1155 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:42:17.494  7914  7914 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-12 14:42:17.494  1019  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-12 14:42:17.494  7914  7914 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-12 14:42:17.494  1019  1131 E ConnectivityService: updateNetworkInfo()
09-12 14:42:17.494  1019  1051 I PowerManagerService: [PWL] Off : 75s ago
09-12 14:42:17.494  1019  1051 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-12 14:42:17.494  1019  1051 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-12 14:42:17.494  1019  1051 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1019, ws=null) (elapsedTime=20415)
,09-12 14:42:17.494  7914  7914 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,09-12 14:42:17.494  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-12 14:42:17.494  1019  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,09-12 14:42:17.494  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 14:42:17.494  1019  1049 D WifiDisplayController: disconnect
09-12 14:42:17.494  1019  1049 D WifiDisplayController: updateConnection
09-12 14:42:17.494  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false,
09-12 14:42:17.504  1019  1129 E WifiStateMachine: Failed to set frequency band 0
09-12 14:42:17.494  1019  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 14:42:17.504  1019  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 14:42:17.504  1019  1129 D SecContentProvider2: mCursor = null
,09-12 14:42:17.504  1019  1128 D WifiNative-p2p0: p2pGetDeviceAddress
,09-12 14:42:17.504  1019  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 14:42:17.504  1019  1049 D WifiDisplayAdapter: onP2pDisconnected
09-12 14:42:17.504  1019  1128 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
09-12 14:42:17.504  1019  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 14:42:17.504  1019  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
09-12 14:42:17.504  4827  4827 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-12 14:42:17.504  4827  4827 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 14:42:17.504  1019  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 14:42:17.504  1019  1129 D SecContentProvider2: mCursor = null
,09-12 14:42:17.504  1183  1183 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-12 14:42:17.504  1019  1347 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 14:42:17.504  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-12 14:42:17.504  1183  1183 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-12 14:42:17.514  1019  1128 D WifiP2pService: DeviceAddress: 0a:75:42
,09-12 14:42:17.514  1019  1049 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-12 14:42:17.514  1019  1049 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-12 14:42:17.514  1019  1049 D WifiDisplayController:  primary type: 10-0050F204-5
09-12 14:42:17.514  1019  1049 D WifiDisplayController:  secondary type: null
09-12 14:42:17.514  1019  1049 D WifiDisplayController:  wps: 0
09-12 14:42:17.514  1019  1049 D WifiDisplayController:  grpcapab: 0
09-12 14:42:17.514  1019  1049 D WifiDisplayController:  devcapab: 0
09-12 14:42:17.514  1019  1049 D WifiDisplayController:  status: 3
09-12 14:42:17.514  1019  1049 D WifiDisplayController:  wfdInfo: null
09-12 14:42:17.514  1019  1049 D WifiDisplayController:  groupownerAddress: null
09-12 14:42:17.514  1019  1049 D WifiDisplayController:  GOdeviceName: null
09-12 14:42:17.514  1019  1049 D WifiDisplayController:  interfaceAddress: 
09-12 14:42:17.514  1019  1049 D WifiDisplayController:  SConnectInfo : null
,09-12 14:42:17.514  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 14:42:17.514  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 14:42:17.514  4827  4827 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-12 14:42:17.514  4827  4902 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 14:42:17.514  7757  7757 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 14:42:17.514  7757  7757 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-12 14:42:17.514  7757  7757 D FileShare-Client: Outbound.stopDelayTimer - 
,09-12 14:42:17.524  7417  7417 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 14:42:17.534  1019  1128 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-12 14:42:17.534  1019  1128 D WifiP2pService: InactiveState
,09-12 14:42:17.534  1019  1128 D WifiP2pService: InactiveState{ what=143376 }
,09-12 14:42:17.534  1019  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-12 14:42:17.534  7914  7914 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-12 14:42:17.534  1019  1128 D WifiP2pService: InactiveState{ what=143376 }
,09-12 14:42:17.534  1019  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-12 14:42:18.004  7055  7256 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-12 14:42:18.004  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:18.004  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:18.004  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,09-12 14:42:18.004  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:42:18.004  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:18.004  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:18.004  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 14:42:18.004  7055  7256 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 14:42:18.004  7055  7256 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-12 14:42:18.004  7055  7256 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-12 14:42:18.004  7055  7256 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@15adbf1 Bundle[{}]
09-12 14:42:18.004  7055  7256 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 14:42:18.004  7055  7256 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-12 14:42:18.014  7055  7256 D io.jxcore.node.LifeCycleMonitor: onActivityStarted,
09-12 14:42:18.014  7055  7256 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-12 14:42:18.014  7055  7256 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-12 14:42:18.014  7055  7256 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 14:42:18.014  7055  7256 I System.out: Running OutgoingSocketThread
,09-12 14:42:18.024  7055  7923 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1424),
,09-12 14:42:18.024  7055  7923 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 46757
,09-12 14:42:18.024  7055  7923 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...,
,09-12 14:42:18.244  1019  1309 E Watchdog: !@Sync 4,
,09-12 14:42:18.724  7914  7914 I wpa_supplicant: nl80211: Received scan results (22 BSSes),
09-12 14:42:18.724  7914  7914 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
09-12 14:42:18.724  7914  7914 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-12 14:42:18.724  7914  7914 I wpa_supplicant: Trying to associate with  'G700'
09-12 14:42:18.724  7914  7914 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-12 14:42:18.724  7914  7914 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-12 14:42:18.724  1019  7920 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
,09-12 14:42:18.744  1019  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 14:42:18.744  1019  1129 D SecContentProvider2: mCursor = null
,09-12 14:42:18.874  7914  7914 E wpa_supplicant: Cmd 35605 not handled
,09-12 14:42:18.874  7914  7914 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-12 14:42:18.874  7914  7914 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-12 14:42:18.874  7914  7914 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-12 14:42:18.874  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 14:42:18.874  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 14:42:18.874  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
09-12 14:42:18.874  7914  7914 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-12 14:42:18.874  7914  7914 I wpa_supplicant: Associated with F4.99.3E
09-12 14:42:18.874  7914  7914 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-12 14:42:18.874  7914  7914 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-12 14:42:18.874  7914  7914 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-12 14:42:18.874  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 14:42:18.874  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,09-12 14:42:18.874  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-12 14:42:18.874  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 14:42:18.874  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 14:42:18.874  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-12 14:42:18.884  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, true
09-12 14:42:18.884  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-12 14:42:18.884  1019  1046 D Tethering: interfaceStatusChanged wlan0, true
,09-12 14:42:18.884  1019  1134 E Tethering: No numeric data,
09-12 14:42:18.884  1019  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-12 14:42:18.884  1019  1134 D Tethering: clearTetheredNotification()
09-12 14:42:18.884  1019  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 14:42:18.884  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:18.884  1019  1126 V NetworkStats: performPollLocked(flags=0x1)
,09-12 14:42:18.884  1019  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-12 14:42:18.884  1183  1183 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
,09-12 14:42:18.884  1019  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
09-12 14:42:18.884  1183  1183 D HotspotTile: updateTetherState():false, false
,09-12 14:42:18.884  1019  1129 D SecContentProvider2: mCursor = null
09-12 14:42:18.894  1019  1126 V NetworkStats: performPollLocked() took 8ms
09-12 14:42:18.894  1019  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-12 14:42:18.894  1019  1129 D SecContentProvider2: mCursor = null
09-12 14:42:18.894  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:18.894  7914  7914 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-12 14:42:18.894  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:18.894  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:18.894  7914  7914 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-12 14:42:18.894  7914  7914 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,09-12 14:42:18.904  7914  7914 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-12 14:42:18.904  7914  7914 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP],
09-12 14:42:18.904  7914  7914 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-12 14:42:18.904  7914  7914 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,09-12 14:42:18.904  7914  7914 I wpa_supplicant: Blacklist: Clear (temp) ,
,09-12 14:42:18.904  7914  7914 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-12 14:42:18.904  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-12 14:42:18.904  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, true
09-12 14:42:18.904  1019  1046 D Tethering: interfaceStatusChanged wlan0, true
,09-12 14:42:18.904  1019  1129 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-12 14:42:18.914  1019  1129 E WifiConfigStore: setLastSelectedConfiguration -1
,09-12 14:42:18.924  1019  1131 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-12 14:42:18.924  1019  1129 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-12 14:42:18.924  1019  1131 E ConnectivityService: updateNetworkInfo()
09-12 14:42:18.924  1019  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-12 14:42:18.924  1019  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 14:42:18.924  1019  4367 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 14:42:18.924  1019  4367 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 14:42:18.924  1019  4367 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:18.924  1019  4367 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:18.924  1019  4367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 14:42:18.924  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-12 14:42:18.924  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 14:42:18.924  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 14:42:18.924  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:18.924  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:18.924  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:42:18.924  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:18.924  2187  2187 I Hs20UtilService: Starting #21
,09-12 14:42:18.924  2187  2202 I Hs20UtilService: Message received 5007
,09-12 14:42:18.934  4827  4827 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-12 14:42:18.934  4827  4827 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 14:42:18.934  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 14:42:18.934  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-12 14:42:18.934  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 14:42:18.934  4827  4827 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 14:42:18.934  4827  4902 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 14:42:18.944  1019  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 14:42:18.954   279   986 D CommandListener: Setting iface cfg,
,09-12 14:42:18.954  1019  1129 E WifiStateMachine: Start Dhcp Watchdog 3
,09-12 14:42:18.954  1019  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-12 14:42:18.954  1019  1129 D SecContentProvider2: mCursor = null
,09-12 14:42:18.974  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 14:42:18.974  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 14:42:18.974  1019  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 14:42:18.974  1019  1129 D SecContentProvider2: mCursor = null
,09-12 14:42:18.974  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-12 14:42:18.974  1019  1129 E WifiNative-wlan0: do suspend false
,09-12 14:42:18.974  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:42:18.974  1019  1128 D WifiP2pService: InactiveState{ what=143375 }
,09-12 14:42:18.974  1019  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-12 14:42:18.984  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:42:18.984  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:42:18.984  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:42:19.024  7055  7256 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1425)
,09-12 14:42:19.024  7055  7256 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1425)
,09-12 14:42:19.024  7055  7256 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1430)
,09-12 14:42:19.024  7055  7256 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-12 14:42:19.024  7055  7256 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1431)
,09-12 14:42:19.024  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 14:42:19.024  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a7148d3 added. We now have 2 listener(s)
,09-12 14:42:19.024  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-12 14:42:19.024  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:42:19.024  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 14:42:19.034  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:42:19.034  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c9e7c10 added. We now have 9 listener(s)
09-12 14:42:19.034  7055  7256 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 14:42:19.034  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 14:42:19.034  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 14:42:19.034  7055  7256 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:42:19.034  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:19.034  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:19.034  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:42:19.034  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:42:19.034  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:19.034  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:19.034  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 14:42:19.034  7055  7256 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 14:42:19.034  7055  7256 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 14:42:19.044  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:19.044  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:19.044  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 14:42:19.044  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@299e990e added. We now have 3 listener(s)
,09-12 14:42:19.044  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-12 14:42:19.044  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 14:42:19.044  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 14:42:19.044  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:42:19.044  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39fd9f2f added. We now have 10 listener(s)
,09-12 14:42:19.044  7055  7256 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:42:19.044  7055  7256 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 14:42:19.044  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:42:19.044  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 14:42:19.044  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 14:42:19.054  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:19.054  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:42:19.054  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:42:19.054  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a7148d3 removed from the list
09-12 14:42:19.054  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:42:19.054  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c9e7c10 removed from the list
09-12 14:42:19.054  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:42:19.054  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:42:19.054  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:42:19.054  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:42:19.054  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 14:42:19.054  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:42:19.054  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 14:42:19.054  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c9e7c10 not in the list
,09-12 14:42:19.054  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:19.054  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:42:19.054  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-12 14:42:19.054  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:42:19.054  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:42:19.054  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39fd9f2f removed from the list
09-12 14:42:19.054  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:42:19.054  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-12 14:42:19.054  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:42:19.054  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:42:19.054  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@299e990e removed from the list
,09-12 14:42:19.054  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 14:42:19.054  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d7493c added. We now have 2 listener(s)
,09-12 14:42:19.054  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
09-12 14:42:19.054  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 14:42:19.054  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 14:42:19.054  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:42:19.054  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@862a6c5 added. We now have 9 listener(s)
09-12 14:42:19.054  7055  7256 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:42:19.054  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
,09-12 14:42:19.064  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 14:42:19.064  7055  7256 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-12 14:42:19.064  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:19.064  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:19.064  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:42:19.064  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:42:19.064  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:19.064  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:19.064  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 14:42:19.064  7055  7256 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
09-12 14:42:19.064  7055  7256 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 14:42:19.064  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 14:42:19.064  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f4eff4b added. We now have 3 listener(s)
09-12 14:42:19.064  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:42:19.064  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:19.074  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-12 14:42:19.074  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:42:19.074  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
09-12 14:42:19.074  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:42:19.074  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@356dbd28 added. We now have 10 listener(s)
09-12 14:42:19.074  7055  7256 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 14:42:19.074  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 14:42:19.074  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
09-12 14:42:19.074  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 14:42:19.074  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:42:19.074  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 14:42:19.074  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 14:42:19.074  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 14:42:19.074  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 14:42:19.074  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 14:42:19.084  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 14:42:19.084  7055  7256 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 14:42:19.084  3211  7835 D BtGatt.GattService: registerClient() - UUID=31d44ce4-b468-4941-934b-ccf7c3b1afe7
,09-12 14:42:19.124  3211  3286 D BtGatt.GattService: onClientRegistered() - UUID=31d44ce4-b468-4941-934b-ccf7c3b1afe7, clientIf=6
,09-12 14:42:19.124  7055  7069 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-12 14:42:19.124  3211  3346 D BtGatt.GattService: start scan with filters
,09-12 14:42:19.124  3211  3348 D BtGatt.ScanManager: handling starting scan
,09-12 14:42:19.134  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
09-12 14:42:19.134  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 14:42:19.134  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
09-12 14:42:19.134  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
,09-12 14:42:19.134  3211  3286 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
09-12 14:42:19.134  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 14:42:19.134  3211  3348 D BtGatt.ScanManager: allow scan with filters
09-12 14:42:19.134  3211  3348 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-12 14:42:19.134  3211  3348 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
09-12 14:42:19.134  3211  3286 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-12 14:42:19.134  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 14:42:19.134  3211  3348 D BtGatt.ScanManager: Starting BLE batch scan
09-12 14:42:19.134  3211  3348 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-12 14:42:19.134  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 14:42:19.134  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 14:42:19.134  7055  7055 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 14:42:19.134  3211  3286 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-12 14:42:19.134  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 14:42:19.134  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 14:42:19.144  3211  3286 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-12 14:42:19.144  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 14:42:19.144  7055  7256 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 14:42:19.144  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 14:42:19.144  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 14:42:19.144  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:19.144  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 14:42:19.144  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 14:42:19.144  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 14:42:19.144  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 14:42:19.144  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 14:42:19.144  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 14:42:19.144  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 14:42:19.144  3211  3224 D BtGatt.GattService: stopScan() - queue size =1
,09-12 14:42:19.144  3211  3348 D BtGatt.ScanManager: filter size is 1
,09-12 14:42:19.144  3211  3348 D BtGatt.ScanManager: delete FilterIndex - 6
,09-12 14:42:19.144  3211  3228 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 14:42:19.144  3211  3286 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-12 14:42:19.154  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 14:42:19.154  3211  3348 D BtGatt.ScanManager: stopping BLe Batch
09-12 14:42:19.154  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 14:42:19.154  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 14:42:19.154  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 14:42:19.154  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 14:42:19.154  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 14:42:19.154  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 14:42:19.154  3211  3286 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-12 14:42:19.154  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 14:42:19.154  3211  3348 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-12 14:42:19.154  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 14:42:19.154  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 14:42:19.154  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 14:42:19.154  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:42:19.154  3211  3286 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-12 14:42:19.154  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 14:42:19.154  7055  7055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 14:42:19.154  7055  7055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 14:42:19.154  7055  7055 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 14:42:19.164  7055  7256 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 14:42:19.164  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 14:42:19.164  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 14:42:19.164  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:42:19.164  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:42:19.164  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:42:19.164  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:42:19.164  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d7493c removed from the list
09-12 14:42:19.164  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:42:19.164  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@862a6c5 removed from the list
09-12 14:42:19.164  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:42:19.164  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:42:19.164  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:19.164  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:42:19.164  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 14:42:19.164  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:42:19.164  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:42:19.164  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@862a6c5 not in the list
,09-12 14:42:19.164  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:19.164  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:42:19.164  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:42:19.164  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 14:42:19.164  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:42:19.164  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@356dbd28 removed from the list
09-12 14:42:19.164  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 14:42:19.164  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:19.164  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:42:19.164  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:42:19.164  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f4eff4b removed from the list
09-12 14:42:19.164  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 14:42:19.164  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@327583d4 added. We now have 2 listener(s)
,09-12 14:42:19.164  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-12 14:42:19.164  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:42:19.164  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
09-12 14:42:19.164  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:42:19.164  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@142be97d added. We now have 9 listener(s)
,09-12 14:42:19.164  7055  7256 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 14:42:19.164  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 14:42:19.174  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 14:42:19.174  7055  7256 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:42:19.174  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:19.174  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:19.174  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:42:19.174  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:42:19.174  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:19.174  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:19.174  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 14:42:19.174  7055  7256 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
09-12 14:42:19.174  7055  7256 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 14:42:19.174  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
09-12 14:42:19.174  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f6e0cc3 added. We now have 3 listener(s)
,09-12 14:42:19.184  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:19.184  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:19.184  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
09-12 14:42:19.184  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:42:19.184  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
09-12 14:42:19.184  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:42:19.184  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b910940 added. We now have 10 listener(s)
,09-12 14:42:19.184  7055  7256 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:42:19.184  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 14:42:19.184  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
09-12 14:42:19.184  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 14:42:19.184  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
09-12 14:42:19.184  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:42:19.184  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 14:42:19.184  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,09-12 14:42:19.194  7927  7927 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-12 14:42:19.194  7927  7927 I dhcpcd  : version 5.5.6 starting,
09-12 14:42:19.194  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 14:42:19.194  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 14:42:19.194  7927  7927 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-12 14:42:19.214  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
09-12 14:42:19.214  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 14:42:19.214  7055  7256 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 14:42:19.214  3211  3363 D BtGatt.GattService: registerClient() - UUID=a42adad8-9993-4397-9bee-52492563cec1
,09-12 14:42:19.244  7927  7927 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,09-12 14:42:19.244  7927  7927 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-12 14:42:19.244  7927  7927 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-12 14:42:19.244  7927  7927 I dhcpcd  : bssid match
09-12 14:42:19.244  7927  7927 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,09-12 14:42:19.254  3211  3286 D BtGatt.GattService: onClientRegistered() - UUID=a42adad8-9993-4397-9bee-52492563cec1, clientIf=6,
09-12 14:42:19.254  7055  7069 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-12 14:42:19.254  3211  3228 D BtGatt.GattService: start scan with filters
09-12 14:42:19.254  3211  3348 D BtGatt.ScanManager: handling starting scan
09-12 14:42:19.254  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 14:42:19.254  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-12 14:42:19.254  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 14:42:19.254  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
09-12 14:42:19.254  3211  3286 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
,09-12 14:42:19.254  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 14:42:19.254  3211  3348 D BtGatt.ScanManager: allow scan with filters
,09-12 14:42:19.254  3211  3348 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-12 14:42:19.254  3211  3348 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,09-12 14:42:19.254  3211  3286 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-12 14:42:19.254  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 14:42:19.254  3211  3348 D BtGatt.ScanManager: Starting BLE batch scan,
09-12 14:42:19.254  3211  3348 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-12 14:42:19.264  3211  3286 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-12 14:42:19.264  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 14:42:19.264  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 14:42:19.264  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 14:42:19.264  7055  7055 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 14:42:19.264  3211  3286 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-12 14:42:19.264  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 14:42:19.264  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 14:42:19.274  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 14:42:19.274  7055  7256 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 14:42:19.274  7055  7256 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 14:42:19.274  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 14:42:19.274  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:42:19.274  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 14:42:19.274  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:19.274  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 14:42:19.274  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:42:19.274  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@327583d4 removed from the list
09-12 14:42:19.274  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:42:19.274  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@142be97d removed from the list
09-12 14:42:19.274  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:42:19.274  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 14:42:19.274  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:19.274  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-12 14:42:19.274  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:19.274  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 14:42:19.274  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:42:19.274  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:42:19.274  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:42:19.274  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@142be97d not in the list
09-12 14:42:19.274  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 14:42:19.274  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 14:42:19.274  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 14:42:19.274  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 14:42:19.274  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 14:42:19.274  3211  7835 D BtGatt.GattService: stopScan() - queue size =1
09-12 14:42:19.274  3211  3348 D BtGatt.ScanManager: filter size is 1
09-12 14:42:19.274  3211  3348 D BtGatt.ScanManager: delete FilterIndex - 7
,09-12 14:42:19.274  3211  3346 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 14:42:19.274  3211  3286 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-12 14:42:19.274  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 14:42:19.274  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 14:42:19.274  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 14:42:19.274  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 14:42:19.274  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 14:42:19.274  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 14:42:19.284  3211  3348 D BtGatt.ScanManager: stopping BLe Batch
,09-12 14:42:19.284  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
09-12 14:42:19.284  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 14:42:19.284  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
09-12 14:42:19.284  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 14:42:19.284  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:42:19.284  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
,09-12 14:42:19.284  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:42:19.284  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:42:19.284  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b910940 removed from the list
,09-12 14:42:19.284  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:42:19.284  7055  7055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 14:42:19.284  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:19.284  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:42:19.284  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:42:19.284  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f6e0cc3 removed from the list
,09-12 14:42:19.284  3211  3286 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-12 14:42:19.284  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 14:42:19.284  7055  7055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 14:42:19.284  7055  7055 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 14:42:19.284  3211  3348 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-12 14:42:19.284  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 14:42:19.284  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@261d796c added. We now have 2 listener(s)
09-12 14:42:19.284  3211  3286 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-12 14:42:19.284  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 14:42:19.284  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
09-12 14:42:19.284  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:42:19.284  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 14:42:19.284  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 14:42:19.284  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b13cb35 added. We now have 9 listener(s)
09-12 14:42:19.284  7055  7256 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:42:19.284  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 14:42:19.294  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 14:42:19.294  7055  7256 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:42:19.294  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:19.294  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,09-12 14:42:19.294  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:42:19.294  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:42:19.294  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:19.294  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:19.294  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 14:42:19.294  7055  7256 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:42:19.294  7055  7256 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 14:42:19.294  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 14:42:19.294  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c2513b added. We now have 3 listener(s)
,09-12 14:42:19.294  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:19.304  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:19.304  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-12 14:42:19.304  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:42:19.304  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 14:42:19.304  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:42:19.304  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e1ec058 added. We now have 10 listener(s)
09-12 14:42:19.304  7055  7256 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:42:19.304  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 14:42:19.304  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 14:42:19.304  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 14:42:19.304  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:42:19.304  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 14:42:19.304  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 14:42:19.304  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 14:42:19.314  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 14:42:19.314  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 14:42:19.314  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 14:42:19.314  7055  7256 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 14:42:19.314  3211  3363 D BtGatt.GattService: registerClient() - UUID=621d1c23-fe4e-4e2a-8a47-cd547cf1b457
,09-12 14:42:19.334  7927  7927 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1,
,09-12 14:42:19.354  3211  3286 D BtGatt.GattService: onClientRegistered() - UUID=621d1c23-fe4e-4e2a-8a47-cd547cf1b457, clientIf=6
,09-12 14:42:19.354  7055  7063 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-12 14:42:19.354  3211  3228 D BtGatt.GattService: start scan with filters
,09-12 14:42:19.364  3211  3348 D BtGatt.ScanManager: handling starting scan
,09-12 14:42:19.364  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 14:42:19.364  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 14:42:19.364  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 14:42:19.364  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 14:42:19.364  3211  3286 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-12 14:42:19.364  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 14:42:19.364  3211  3348 D BtGatt.ScanManager: allow scan with filters
09-12 14:42:19.364  3211  3348 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-12 14:42:19.364  3211  3348 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
,09-12 14:42:19.364  3211  3286 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-12 14:42:19.364  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 14:42:19.364  3211  3348 D BtGatt.ScanManager: Starting BLE batch scan
09-12 14:42:19.364  3211  3348 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-12 14:42:19.364  3211  3286 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-12 14:42:19.364  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 14:42:19.364  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 14:42:19.364  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 14:42:19.374  7055  7055 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 14:42:19.374  3211  3286 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-12 14:42:19.374  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 14:42:19.374  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 14:42:19.374  7055  7256 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 14:42:19.374  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 14:42:19.374  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 14:42:19.374  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 14:42:19.374  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:19.374  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 14:42:19.384  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:42:19.384  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@261d796c removed from the list,
09-12 14:42:19.384  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:42:19.384  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b13cb35 removed from the list
09-12 14:42:19.384  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:42:19.384  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:42:19.384  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:42:19.384  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-12 14:42:19.384  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:19.384  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 14:42:19.384  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 14:42:19.384  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:42:19.384  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 14:42:19.384  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b13cb35 not in the list
09-12 14:42:19.384  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 14:42:19.384  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 14:42:19.384  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 14:42:19.384  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 14:42:19.384  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 14:42:19.384   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 14:42:19.384  3211  3363 D BtGatt.GattService: stopScan() - queue size =1
,09-12 14:42:19.384  3211  3348 D BtGatt.ScanManager: filter size is 1
,09-12 14:42:19.384  3211  3348 D BtGatt.ScanManager: delete FilterIndex - 8
,09-12 14:42:19.384  3211  3228 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 14:42:19.384  3211  3286 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-12 14:42:19.384  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 14:42:19.384  3211  3348 D BtGatt.ScanManager: stopping BLe Batch
,09-12 14:42:19.384  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 14:42:19.384  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 14:42:19.384  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 14:42:19.384  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 14:42:19.384  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 14:42:19.394  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
09-12 14:42:19.394  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 14:42:19.394  7055  7256 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 14:42:19.394  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 14:42:19.394  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:42:19.394  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:42:19.394  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:42:19.394  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:42:19.394  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e1ec058 removed from the list
09-12 14:42:19.394  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:42:19.394  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:19.394  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:42:19.394  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:42:19.394  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c2513b removed from the list
09-12 14:42:19.394  7055  7055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 14:42:19.394  7055  7055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 14:42:19.394  7055  7055 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 14:42:19.394  3211  3286 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-12 14:42:19.394  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 14:42:19.394  3211  3348 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-12 14:42:19.394  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 14:42:19.394  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eb8a04 added. We now have 2 listener(s)
09-12 14:42:19.394  3211  3286 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-12 14:42:19.394  3211  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 14:42:19.394  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-12 14:42:19.394  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:42:19.394  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 14:42:19.394  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:42:19.394  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f2bed added. We now have 9 listener(s)
09-12 14:42:19.394  7055  7256 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 14:42:19.394  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 14:42:19.404  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 14:42:19.404  7055  7256 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:42:19.404  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:19.404  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:19.404  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:42:19.404  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:42:19.404  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:19.404  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:19.404  7055  7256 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 14:42:19.404  7055  7256 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 14:42:19.404  7055  7256 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 14:42:19.404  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 14:42:19.404  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dbacb3 added. We now have 3 listener(s)
,09-12 14:42:19.404  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:19.404  7055  7055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:19.414  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-12 14:42:19.414  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:42:19.414  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 14:42:19.414  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:42:19.414  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c994270 added. We now have 10 listener(s)
09-12 14:42:19.414  7055  7256 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 14:42:19.414  7055  7256 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:42:19.414  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:42:19.414  7055  7256 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:42:19.414  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:42:19.414  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:19.414  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:42:19.414  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:42:19.414  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9eb8a04 removed from the list
09-12 14:42:19.414  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:42:19.414  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f2bed removed from the list
09-12 14:42:19.414  7055  7256 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:42:19.414  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:42:19.414  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:19.414  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:42:19.414  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-12 14:42:19.414  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:42:19.414  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:42:19.414  7055  7256 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f2bed not in the list
09-12 14:42:19.414  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:19.414  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:42:19.414  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-12 14:42:19.414  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:42:19.414  7055  7256 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:42:19.414  7055  7256 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c994270 removed from the list
09-12 14:42:19.414  7055  7256 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:42:19.414  7055  7256 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:19.414  7055  7256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-12 14:42:19.414  7055  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:42:19.414  7055  7256 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dbacb3 removed from the list
09-12 14:42:19.414  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-12 14:42:19.414  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-12 14:42:19.414  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-12 14:42:19.414  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 14:42:19.414  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-12 14:42:19.414  7055  7256 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 14:42:19.424  7927  7927 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,09-12 14:42:19.424  7055  7936 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1438, name: My test thread name)
,09-12 14:42:19.424  7055  7936 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1438, thread name: My test thread name)
,09-12 14:42:19.424  7055  7936 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1438, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-12 14:42:19.434  7055  7939 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1440, name: My test thread name)
,09-12 14:42:19.434  7055  7939 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1440, thread name: My test thread name)
09-12 14:42:19.434  7055  7939 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1440, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-12 14:42:19.434  7055  7256 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80,
09-12 14:42:19.434  7055  7256 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-12 14:42:19.434  7055  7256 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0,
09-12 14:42:19.434  7055  7256 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-12 14:42:19.434  7055  7256 D com.test.thalitest.ThaliTestRunner: Total duration: 23201 ms
,09-12 14:42:19.434  7055  7256 I jxcore-log: *Native tests were executed*
09-12 14:42:19.434  7055  7256 I jxcore-log: 
09-12 14:42:19.434  7055  7256 I jxcore-log: Total number of executed tests:  80
09-12 14:42:19.434  7055  7256 I jxcore-log: 
09-12 14:42:19.434  7055  7256 I jxcore-log: Number of passed tests:  80,
09-12 14:42:19.434  7055  7256 I jxcore-log: 
09-12 14:42:19.434  7055  7256 I jxcore-log: Number of failed tests:  0
09-12 14:42:19.434  7055  7256 I jxcore-log: 
09-12 14:42:19.434  7055  7256 I jxcore-log: Number of ignored tests:  0,
09-12 14:42:19.434  7055  7256 I jxcore-log: 
09-12 14:42:19.434  7055  7256 I jxcore-log: Total duration:  23201
09-12 14:42:19.434  7055  7256 I jxcore-log: 
09-12 14:42:19.434  7055  7256 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-12 14:42:19.434  7055  7256 I jxcore-log: 
,09-12 14:42:19.434  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:42:19.434  7055  7256 I jxcore-log: 
09-12 14:42:19.444  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:42:19.444  7055  7256 I jxcore-log: 
09-12 14:42:19.444  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
09-12 14:42:19.444  7055  7256 I jxcore-log: 
09-12 14:42:19.444  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:42:19.444  7055  7256 I jxcore-log: 
09-12 14:42:19.444  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:42:19.444  7055  7256 I jxcore-log: 
09-12 14:42:19.444  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:42:19.444  7055  7256 I jxcore-log: 
,09-12 14:42:19.454  7055  7055 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-12 14:42:19.454  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:42:19.454  7055  7256 I jxcore-log: 
,09-12 14:42:19.454  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 14:42:19.454  7055  7256 I jxcore-log: 
,09-12 14:42:19.454  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 14:42:19.454  7055  7256 I jxcore-log: 
,09-12 14:42:19.454  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 14:42:19.454  7055  7256 I jxcore-log: 
,09-12 14:42:19.454  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"},
09-12 14:42:19.454  7055  7256 I jxcore-log: 
09-12 14:42:19.454  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 14:42:19.454  7055  7256 I jxcore-log: 
,09-12 14:42:19.454  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 14:42:19.454  7055  7256 I jxcore-log: 
,09-12 14:42:19.454  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 14:42:19.454  7055  7256 I jxcore-log: 
,09-12 14:42:19.464  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 14:42:19.464  7055  7256 I jxcore-log: 
,09-12 14:42:19.464  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 14:42:19.464  7055  7256 I jxcore-log: 
,09-12 14:42:19.464  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 14:42:19.464  7055  7256 I jxcore-log: 
,09-12 14:42:19.464  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 14:42:19.464  7055  7256 I jxcore-log: 
,09-12 14:42:19.464  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 14:42:19.464  7055  7256 I jxcore-log: 
,09-12 14:42:19.464  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 14:42:19.464  7055  7256 I jxcore-log: 
,09-12 14:42:19.464  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 14:42:19.464  7055  7256 I jxcore-log: 
,09-12 14:42:19.464  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 14:42:19.464  7055  7256 I jxcore-log: 
,09-12 14:42:19.464  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 14:42:19.464  7055  7256 I jxcore-log: 
,09-12 14:42:19.464  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 14:42:19.464  7055  7256 I jxcore-log: 
,09-12 14:42:19.464  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 14:42:19.464  7055  7256 I jxcore-log: 
,09-12 14:42:19.464  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 14:42:19.464  7055  7256 I jxcore-log: 
,09-12 14:42:19.464  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
09-12 14:42:19.464  7055  7256 I jxcore-log: 
,09-12 14:42:19.584  1019  1129 E WifiNative-wlan0: do suspend true
,09-12 14:42:19.614  1019  1128 D WifiP2pService: InactiveState{ what=143375 }
,09-12 14:42:19.614  1019  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-12 14:42:19.614  1019  1129 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK,
09-12 14:42:19.614  1019  1129 E WifiStateMachine: VerifyingLinkState enter
,09-12 14:42:19.614  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-12 14:42:19.614  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 14:42:19.614  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 14:42:19.614  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:42:19.614  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:19.614  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:42:19.614  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:42:19.624  1019  1131 E ConnectivityService: updateNetworkInfo()
,09-12 14:42:19.624  1019  1131 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,09-12 14:42:19.624  1019  1131 D ConnectivityService: Adding iface wlan0 to network 504
,09-12 14:42:19.624  1019  1148 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter,
,09-12 14:42:19.624  1019  1148 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-12 14:42:19.624  1019  1148 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
,09-12 14:42:19.624  1019  1148 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
09-12 14:42:19.624  1019  1148 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-12 14:42:19.644  1019  1507 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 14:42:19.644  1019  1507 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-12 14:42:19.644  1019  1507 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:19.644  1019  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:19.644  1019  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 14:42:19.644  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-12 14:42:19.644  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 14:42:19.644  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 14:42:19.644  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:19.644  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:19.644  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:19.644  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:19.644  2187  2187 I Hs20UtilService: Starting #22
09-12 14:42:19.644  2187  2202 I Hs20UtilService: Message received 5007
,09-12 14:42:19.644  4827  4827 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 14:42:19.644  1019  1131 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
09-12 14:42:19.644  4827  4827 I NearbySettings: MountReceiver.onReceive - Keep current state
09-12 14:42:19.644  1019  1131 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,09-12 14:42:19.644  1019  1131 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
09-12 14:42:19.654  1019  1129 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
09-12 14:42:19.654  1019  1131 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-12 14:42:19.654  1019  1131 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
,09-12 14:42:19.654  1019  1131 D ConnectivityService: LTETest block dns file not exists
,09-12 14:42:19.654  7055  7055 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 14:42:19.664  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 14:42:19.664  7055  7256 I jxcore-log: 
09-12 14:42:19.664  1019  1131 V NetworkStats: updateIfacesLocked()
09-12 14:42:19.664  1019  1131 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:19.664  1019  1131 V NetworkStats: performPollLocked(flags=0x1)
,09-12 14:42:19.664  1019  1131 D NetworkStatsFactory: UpdateStatsForKnox updated,
,09-12 14:42:19.664  1019  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-12 14:42:19.674  1019  1131 V NetworkStats: performPollLocked() took 8ms
09-12 14:42:19.674  1019  1131 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:19.674  1019  1131 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,09-12 14:42:19.674  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:19.674  1019  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 14:42:19.674  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:19.674  1019  1131 V NetworkStats: updateIfacesLocked()
09-12 14:42:19.674  1019  1131 E ConnectivityService: updateNetworkInfo()
09-12 14:42:19.674  1019  1131 V NetworkStats: performPollLocked(flags=0x1)
09-12 14:42:19.674  1019  1131 E ConnectivityService: updateNetworkInfo()
09-12 14:42:19.674  1019  1131 V NetworkStats: performPollLocked() took 3ms
09-12 14:42:19.674  1019  1131 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:19.674  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-12 14:42:19.674  1019  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 14:42:19.674  1019  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-12 14:42:19.674  1019  1131 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 14:42:19.684  1019  1129 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 14:42:19.684  1019  1129 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-12 14:42:19.684  1019  1131 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
,09-12 14:42:19.684  1019  1131 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-12 14:42:19.684  1019  7924 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:42:19.684  1019  7924 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-12 14:42:19.684  1019  7924 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-12 14:42:19.684  1019  7924 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
09-12 14:42:19.684  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-12 14:42:19.684  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 14:42:19.684  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 14:42:19.684  1019  7924 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-12 14:42:19.684  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:19.684  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:19.684  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:19.684  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:19.684  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-12 14:42:19.684  1019  1019 I WifiTrafficPoller: mBoosterFLAG : 0
09-12 14:42:19.684  1019  1019 I WifiTrafficPoller: current booster mode : FullMode,
09-12 14:42:19.684  1019  1131 D ConnectivityService:    accepting network in place of null
09-12 14:42:19.694   279   982 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-12 14:42:19.694   279   982 D Netd    : getNetworkForDns: using netid 504 for uid 1000
09-12 14:42:19.694  1019  1128 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-12 14:42:19.694  1452  1452 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-12 14:42:19.694  1452  1452 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 14:42:19.694  1019  1129 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,09-12 14:42:19.694  1019  1131 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-12 14:42:19.694  1019  1131 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
,09-12 14:42:19.694  1019  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-12 14:42:19.694  1183  1183 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 14:42:19.694  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-12 14:42:19.694  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:42:19.694  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:19.694  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:19.694  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:19.694  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:19.694  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:19.694  1019  4366 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 14:42:19.694  1019  4366 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 14:42:19.704  1019  4366 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:19.704  1019  4366 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:19.704  1019  4366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 14:42:19.704  2187  2187 I Hs20UtilService: Starting #23
09-12 14:42:19.704  2187  2202 I Hs20UtilService: Message received 5007
09-12 14:42:19.704  1019  1131 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,09-12 14:42:19.704  1019  1019 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-12 14:42:19.704  1019  1134 D Tethering: MasterInitialState.processMessage what=3
09-12 14:42:19.704  1019  1131 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-12 14:42:19.704  1019  1126 V NetworkStats: updateIfacesLocked()
09-12 14:42:19.704  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:19.704  1019  1126 V NetworkStats: performPollLocked(flags=0x1)
09-12 14:42:19.704  1019  1048 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-12 14:42:19.704  1019  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 14:42:19.704  1019  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-12 14:42:19.704  1183  1704 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-12 14:42:19.704  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:19.704  1019  1126 V NetworkStats: performPollLocked() took 4ms
,09-12 14:42:19.704  4827  4827 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-12 14:42:19.704  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:19.714  1019  1127 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-12 14:42:19.704  4827  4827 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-12 14:42:19.714  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:19.714  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:19.714  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:19.714  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,09-12 14:42:19.714  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 14:42:19.714  4827  4827 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
09-12 14:42:19.714  4827  4827 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-12 14:42:19.714  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:19.714  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 14:42:19.714  1183  1183 D StatusBar.NetworkController: EthernetConnected: false
09-12 14:42:19.714  1183  1183 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-12 14:42:19.714  1183  1183 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
,09-12 14:42:19.714  1183  1183 D StatusBar.NetworkController: updateDataNetType()
,09-12 14:42:19.714  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-12 14:42:19.714  1183  1183 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-12 14:42:19.714  1183  1183 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,09-12 14:42:19.714  1183  1183 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 22 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-12 14:42:19.714  1183  1183 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-12 14:42:19.714  1183  1183 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal,
09-12 14:42:19.714  1183  1183 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 14:42:19.714  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-12 14:42:19.724  1019  4367 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 14:42:19.714  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:19.724  1019  4367 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-12 14:42:19.714  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:19.724  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:19.724  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:19.724  7947  7947 D AndroidRuntime: 
09-12 14:42:19.724  7947  7947 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-12 14:42:19.724  1019  4367 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:19.724  1019  4367 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:19.724  1019  4367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 14:42:19.724  2187  2187 I Hs20UtilService: Starting #24
09-12 14:42:19.724  7947  7947 D AndroidRuntime: CheckJNI is OFF
,09-12 14:42:19.724  7947  7947 D AndroidRuntime: readGMSProperty: start
09-12 14:42:19.724  7947  7947 D AndroidRuntime: readGMSProperty: already setted!!
09-12 14:42:19.724  7947  7947 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-12 14:42:19.724  7947  7947 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-12 14:42:19.724  7947  7947 D AndroidRuntime: readGMSProperty: end
09-12 14:42:19.724  7947  7947 D AndroidRuntime: addProductProperty: start
09-12 14:42:19.724  2187  2202 I Hs20UtilService: Message received 5007
09-12 14:42:19.724  4827  4827 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 14:42:19.724  4827  4827 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-12 14:42:19.734  1019  3798 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-12 14:42:19.734  1019  1341 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-12 14:42:19.734  1019  1341 D SecContentProvider2: mCursor = null
,09-12 14:42:19.744  1019  4368 D SecContentProvider2: uri = 15 selection = getToastGravity
09-12 14:42:19.744  1019  4368 D SecContentProvider2: mCursor = null
,09-12 14:42:19.744  1019  4367 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
09-12 14:42:19.744  1019  4367 D SecContentProvider2: mCursor = null
,09-12 14:42:19.744  1019  1489 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-12 14:42:19.744  1019  1489 D SecContentProvider2: mCursor = null
,09-12 14:42:19.744  1019  1347 D SecContentProvider2: uri = 15 selection = getToastEnabledState
09-12 14:42:19.744  1019  1347 D SecContentProvider2: mCursor = null
,09-12 14:42:19.744  1019  4366 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
09-12 14:42:19.744  1019  4366 D SecContentProvider2: mCursor = null
,09-12 14:42:19.774   259   259 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,09-12 14:42:19.784  7055  7055 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-12 14:42:19.784  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 14:42:19.784  7055  7256 I jxcore-log: 
,09-12 14:42:19.784  1019  1507 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1019
,09-12 14:42:19.794  1183  1183 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
,09-12 14:42:19.804  1019  7924 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-12 14:42:19.854  7947  7947 E AffinityControl: AffinityControl: registerfunction enter
,09-12 14:42:19.854  1019  7924 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 12:42:19 GMT], X-Android-Received-Millis=[1473684139869], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473684139841]}
,09-12 14:42:19.854  1019  7924 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-12 14:42:19.854  1019  7924 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-12 14:42:19.854  1019  1131 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
09-12 14:42:19.854  1019  1131 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,09-12 14:42:19.854  1019  1131 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
,09-12 14:42:19.854  1183  1704 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-12 14:42:19.854  1019  1131 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-12 14:42:19.854  1019  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 14:42:19.864  1183  1183 D StatusBar.NetworkController: EthernetConnected: false
09-12 14:42:19.864  1183  1183 D StatusBar.NetworkController: getUpdateDataNetType(): 0,
09-12 14:42:19.864  1183  1183 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-12 14:42:19.864  1183  1183 D StatusBar.NetworkController: updateDataNetType()
,09-12 14:42:19.864  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-12 14:42:19.864  1183  1183 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-12 14:42:19.864  1183  1183 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,09-12 14:42:19.864  1183  1183 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 22 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-12 14:42:19.864  1183  1183 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-12 14:42:19.864  1183  1183 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal,
09-12 14:42:19.864  1183  1183 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 14:42:19.864  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-12 14:42:19.864  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:19.864  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:19.864  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 14:42:19.864  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 14:42:19.874  7947  7947 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-12 14:42:19.894  1019  1031 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
09-12 14:42:19.894  1019  1031 D PackageManager: START PACKAGE DELETE: observer{475552181}
09-12 14:42:19.894  1019  1031 D PackageManager: pkg{<packageName>}
09-12 14:42:19.894  1019  1031 D PackageManager: user{0}
,09-12 14:42:19.894  1019  1031 D PackageManager: caller{2000}
09-12 14:42:19.894  1019  1031 D PackageManager: flags{2}
09-12 14:42:19.894  1019  1031 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-12 14:42:19.894  1019  1031 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-12 14:42:19.894  7055  7055 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 14:42:19.894  7055  7256 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 14:42:19.894  7055  7256 I jxcore-log: 
09-12 14:42:19.894  1019  1031 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-12 14:42:19.894  1019  1031 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-12 14:42:19.894  1019  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,09-12 14:42:19.894  1019  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-12 14:42:19.894  1019  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-12 14:42:19.894  1019  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
09-12 14:42:19.894  1019  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-12 14:42:19.904  1019  1057 D PackageManager: !@killApplicatoin: 10170, uninstall pkg,
,09-12 14:42:19.914  1019  1044 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,09-12 14:42:19.914  1019  1044 I ActivityManager: Killing 7055:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-12 14:42:20.034  1019  1044 I ActivityManager:   Force finishing activity ActivityRecord{2fe5e55a u0 com.test.thalitest/.MainActivity t163}
,09-12 14:42:20.044   259  1100 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,09-12 14:42:20.044  1019  1266 I WindowState: WIN DEATH: Window{e973fe6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-12 14:42:20.044   259  1100 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,09-12 14:42:20.044  1019  1266 D InputDispatcher: Focus left window: 7055
,09-12 14:42:20.054  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-12 14:42:20.054  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-12 14:42:20.054  1019  1057 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,09-12 14:42:20.054  1019  1057 I ActivityManager:   Force finishing activity ActivityRecord{2fe5e55a u0 com.test.thalitest/.MainActivity t163 f}
,09-12 14:42:20.054  1019  1057 W ActivityManager: Duplicate finish request for ActivityRecord{2fe5e55a u0 com.test.thalitest/.MainActivity t163 f}
,09-12 14:42:20.084  1019  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-12 14:42:20.124  1019  1044 D InputDispatcher: Focused application released
09-12 14:42:20.124  2831  2831 I art     : Explicit concurrent mark sweep GC freed 16601(991KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 823us total 49.145ms
,09-12 14:42:20.154  1019  1102 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-12 14:42:20.164  1647  1869 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-12 14:42:20.164  1971  1971 E SamsungIME: mOCRHelper is null
,09-12 14:42:20.174  1019  1019 D RCPManagerService: PackageReceiver onReceive()
,09-12 14:42:20.174  1019  1019 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-12 14:42:20.174  1019  1019 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-12 14:42:20.174  1019  1019 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-12 14:42:20.174  1019  1019 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,09-12 14:42:20.184  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:20.184  1019  1126 V NetworkStats: removeUidsLocked() for UIDs [10170]
09-12 14:42:20.184  1019  1126 V NetworkStats: performPollLocked(flags=0x3)
,09-12 14:42:20.194  1019  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-12 14:42:20.194  1019  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 14:42:20.194  1019  1019 I OTPFW   : ProvisionData::getAllEntries Enter
,09-12 14:42:20.194  1019  1019 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-12 14:42:20.204  1019  1126 V NetworkStats: performPollLocked() took 12ms
09-12 14:42:20.204  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 14:42:20.204  1019  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 14:42:20.214  2815  2815 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Sep 12 14:42:20 GMT+02:00 2016
,09-12 14:42:20.224  1019  3798 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-12 14:42:20.234  1019  3798 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-12 14:42:20.234  1019  3798 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:20.234  1019  3798 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:20.234  1019  3798 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-12 14:42:20.234  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 14:42:20.234  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 14:42:20.234  1442  1442 D PersonaManager: isKioskContainerExistOnDevice
,09-12 14:42:20.244  1442  1442 D RegisteredServicesCache: empty dynamic service
,09-12 14:42:20.254  2815  2815 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
09-12 14:42:20.254  1019  1347 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
09-12 14:42:20.254  1019  1347 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-12 14:42:20.254  1019  1347 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-12 14:42:20.254  1019  1347 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.254  1019  1347 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.254  1019  1347 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.254  1019  1347 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:42:20.264  7978  7978 E Zygote  : MountEmulatedStorage()
09-12 14:42:20.274  7978  7978 E Zygote  : v2
09-12 14:42:20.274  7978  7978 I libpersona: KNOX_SDCARD checking this for 10090
09-12 14:42:20.274  7978  7978 I libpersona: KNOX_SDCARD not a persona
,09-12 14:42:20.274  7978  7978 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-12 14:42:20.274  7978  7978 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-12 14:42:20.274  7978  7978 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 14:42:20.284  1019  1347 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7978 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,09-12 14:42:20.284  2815  2815 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-12 14:42:20.284  1019  1507 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-12 14:42:20.284  1019  1507 D SecContentProvider2: mCursor = null
,09-12 14:42:20.284  2815  2815 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-12 14:42:20.284  1019  1044 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,09-12 14:42:20.294  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:42:20.294  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:42:20.294  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.294  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:42:20.304  7993  7993 E Zygote  : MountEmulatedStorage()
09-12 14:42:20.304  7993  7993 I libpersona: KNOX_SDCARD checking this for 10052
09-12 14:42:20.304  7993  7993 E Zygote  : v2
09-12 14:42:20.304  7993  7993 I libpersona: KNOX_SDCARD not a persona
,09-12 14:42:20.304  7993  7993 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-12 14:42:20.314  2815  2815 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
09-12 14:42:20.314  7978  7978 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:42:20.314  7993  7993 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 14:42:20.314  7978  7978 D ActivityThread: Added TimaKeyStore provider
,09-12 14:42:20.314  7993  7993 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-12 14:42:20.314  1019  1044 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7993 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
09-12 14:42:20.314  2815  7977 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-12 14:42:20.314  1019  1044 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,09-12 14:42:20.324  2815  7977 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
09-12 14:42:20.324  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.324  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.324  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.324  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:42:20.324  2815  7977 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,09-12 14:42:20.324  2815  7977 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-12 14:42:20.344  8003  8003 E Zygote  : MountEmulatedStorage(),
09-12 14:42:20.344  8003  8003 E Zygote  : v2
09-12 14:42:20.344  8003  8003 I libpersona: KNOX_SDCARD checking this for 10098
09-12 14:42:20.344  8003  8003 I libpersona: KNOX_SDCARD not a persona
09-12 14:42:20.344  8003  8003 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 14:42:20.344  8003  8003 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-12 14:42:20.344  1019  1044 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=8003 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-12 14:42:20.344  8003  8003 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-12 14:42:20.354  7993  7993 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:42:20.354  7993  7993 D ActivityThread: Added TimaKeyStore provider
,09-12 14:42:20.354  1019  1504 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-12 14:42:20.354  1019  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.354  1019  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.354  1019  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.354  1019  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:42:20.364  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-12 14:42:20.364  1019  1019 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-12 14:42:20.364  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-12 14:42:20.364  1019  1019 V EnterpriseBillingPolicy: uID is 10170
09-12 14:42:20.364  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
09-12 14:42:20.364  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-12 14:42:20.364  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-12 14:42:20.364  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-12 14:42:20.364  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-12 14:42:20.364  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-12 14:42:20.364  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-12 14:42:20.374  8003  8003 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 14:42:20.374  8022  8022 E Zygote  : MountEmulatedStorage()
09-12 14:42:20.374  8022  8022 E Zygote  : v2
09-12 14:42:20.374  8022  8022 I libpersona: KNOX_SDCARD checking this for 10032
09-12 14:42:20.374  8022  8022 I libpersona: KNOX_SDCARD not a persona
09-12 14:42:20.374  8003  8003 D ActivityThread: Added TimaKeyStore provider
,09-12 14:42:20.374   289   289 E SMD     : DCD OFF
09-12 14:42:20.374  8022  8022 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 14:42:20.374  8022  8022 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 14:42:20.374  8022  8022 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-12 14:42:20.374  1019  1504 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8022 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 14:42:20.384  1019  1057 I art     : Explicit concurrent mark sweep GC freed 65740(4MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 23MB/35MB, paused 3.475ms total 290.484ms
,09-12 14:42:20.384  1019  1029 I art     : WaitForGcToComplete blocked for 88.830ms for cause HeapTrim
,09-12 14:42:20.384  1019  1043 D EnterpriseDeviceManagerService: Package has changed for user 0
09-12 14:42:20.384  1019  1043 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,09-12 14:42:20.384   317   317 I ServiceManager: Waiting for service AtCmdFwd...
09-12 14:42:20.384  1019  1043 W TextServicesManagerService: no available spell checker services found
,09-12 14:42:20.394  1442  1442 D RegisteredComponentCache: Collect Tech packages for Knox
,09-12 14:42:20.394  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-12 14:42:20.394  1442  1442 D PersonaManager: isKioskContainerExistOnDevice
,09-12 14:42:20.404  1019  1019 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,09-12 14:42:20.404  1019  3350 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,09-12 14:42:20.414  1019  1165 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,09-12 14:42:20.414  1019  1057 D PackageManager: delete codoeFile: 
,09-12 14:42:20.434  8022  8022 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:42:20.434  1019  1057 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
09-12 14:42:20.434  8022  8022 D ActivityThread: Added TimaKeyStore provider
09-12 14:42:20.434  1019  1057 I AASA_removePackage: UID=10170 Target=com.test.thalitest
09-12 14:42:20.434  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 14:42:20.444  1019  1057 D PackageManager: result of delete: 1{475552181}
,09-12 14:42:20.454  1019  3798 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,09-12 14:42:20.464  1019  3798 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.464  1019  3798 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.464  1019  3798 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.464  1019  3798 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:42:20.474  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 14:42:20.474  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 14:42:20.474  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,09-12 14:42:20.474  8038  8038 E Zygote  : MountEmulatedStorage()
09-12 14:42:20.474  8038  8038 E Zygote  : v2
09-12 14:42:20.474  8038  8038 I libpersona: KNOX_SDCARD checking this for 1000
09-12 14:42:20.474  8038  8038 I libpersona: KNOX_SDCARD not a persona
,09-12 14:42:20.484  8038  8038 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-12 14:42:20.484  8038  8038 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 14:42:20.484  8038  8038 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-12 14:42:20.484  1019  3798 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=8038 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-12 14:42:20.484  7978  7978 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
09-12 14:42:20.484  1019  3798 I ActivityManager: Killing 7469:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
09-12 14:42:20.484  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED,
09-12 14:42:20.484  1019  1019 V EnterpriseBillingPolicy: uID is 10170
09-12 14:42:20.484  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
09-12 14:42:20.484  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-12 14:42:20.484  7978  7978 D elm:15121: ELMEngine.ELMEngine( context ).
09-12 14:42:20.494  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,09-12 14:42:20.494  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-12 14:42:20.494  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
,09-12 14:42:20.494  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-12 14:42:20.494  7978  7978 D elm:15121: MDMBridge.setEnterpriseBridge()
,09-12 14:42:20.494  1019  1139 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
09-12 14:42:20.494  1019  1139 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
09-12 14:42:20.494  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null,
09-12 14:42:20.494  1019  1139 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:20.494  1019  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:20.494  1019  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-12 14:42:20.494  7978  7978 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-12 14:42:20.514  7978  7978 D elm:15121: ElmAgentService : onCreate()
09-12 14:42:20.514  7978  8051 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
09-12 14:42:20.514  7978  8051 D elm:15121: MainReceiver.listeningToPackageRemoved()
09-12 14:42:20.514  7978  8051 D elm:15121: MDMBridge.getInstance()
09-12 14:42:20.514  7978  8051 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-12 14:42:20.514   304   304 I art     : Explicit concurrent mark sweep GC freed 8698(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 859us total 31.350ms,
,09-12 14:42:20.514  7978  8051 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-12 14:42:20.534  7947  7947 D AndroidRuntime: Shutting down VM,
,09-12 14:42:20.534   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 607us total 18.119ms,
09-12 14:42:20.534  8038  8038 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:42:20.534  8038  8038 D ActivityThread: Added TimaKeyStore provider
,09-12 14:42:20.544  2815  7977 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-12 14:42:20.544  7978  7978 D elm:15121: ElmAgentService : onDestroy().,
,09-12 14:42:20.554  1019  1341 I ActivityManager: Killing 7486:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,09-12 14:42:20.554   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 19.996ms
,09-12 14:42:20.564  1639  1639 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-12 14:42:20.564  1639  1639 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-12 14:42:20.564  2815  7977 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-12 14:42:20.574  2815  7977 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,09-12 14:42:20.574  2815  2815 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-12 14:42:20.584  1019  1489 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
09-12 14:42:20.584  1019  1489 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,09-12 14:42:20.584  1019  1489 W ActivityManager: userId = 0, bbcId = -10000
,09-12 14:42:20.584  1019  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:42:20.584  1019  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-12 14:42:20.594  8022  8056 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-12 14:42:20.594  8022  8056 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-12 14:42:20.604  1019  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-12 14:42:20.604  1019  1057 D PackageManager: userId{-1}
09-12 14:42:20.604  1019  1057 D PackageManager: andCode{true}
,09-12 14:42:20.604  3862  8058 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-12 14:42:20.604  3862  8058 D AccountUtils: Clearing selected account for com.test.thalitest
,09-12 14:42:20.604  8022  8056 D SPPClientService: PushLog.txt file is not deleted.
,09-12 14:42:20.614  8022  8056 D SPPClientService: PushLog.txt file is not deleted.
09-12 14:42:20.614  8022  8056 D SPPClientService: ============PushLog. stop!
,09-12 14:42:20.614  1019  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-12 14:42:20.624  1019  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-12 14:42:20.624  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 14:42:20.624  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 14:42:20.634  1019  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.634  1019  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.634  1019  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.634  1019  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:42:20.634  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 14:42:20.644  1019  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-12 14:42:20.644  1019  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 14:42:20.644  1019  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-12 14:42:20.644  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 14:42:20.644  8060  8060 E Zygote  : MountEmulatedStorage()
,09-12 14:42:20.644  8060  8060 E Zygote  : v2
09-12 14:42:20.644  8060  8060 I libpersona: KNOX_SDCARD checking this for 10003
09-12 14:42:20.644  8060  8060 I libpersona: KNOX_SDCARD not a persona
,09-12 14:42:20.644  8060  8060 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-12 14:42:20.654  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 14:42:20.654  1019  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8060 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-12 14:42:20.654  8060  8060 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 14:42:20.654  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 14:42:20.654  8060  8060 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 14:42:20.664  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 14:42:20.664  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-12 14:42:20.664  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 14:42:20.664  1019  1504 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
09-12 14:42:20.664  1019  1504 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:20.664  1019  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
09-12 14:42:20.664  1019  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 14:42:20.664  1019  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,09-12 14:42:20.664  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 14:42:20.664  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-12 14:42:20.674  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 14:42:20.674  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-12 14:42:20.674  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 14:42:20.674  1019  1499 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 14:42:20.684  8060  8060 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:42:20.684  1019  1499 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:20.684  1019  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:42:20.684  1019  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:42:20.684  8060  8060 D ActivityThread: Added TimaKeyStore provider
,09-12 14:42:20.694  1019  1341 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,09-12 14:42:20.694  1019  1341 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-12 14:42:20.694  1019  1341 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:20.694  1019  1341 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:42:20.694  1019  1341 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-12 14:42:20.704  1019  4367 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,09-12 14:42:20.704  1019  4367 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.704  1019  4367 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.704  1019  4367 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.704  1019  4367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:42:20.704  1019  1131 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-12 14:42:20.714  8078  8078 E Zygote  : MountEmulatedStorage()
09-12 14:42:20.714  8078  8078 E Zygote  : v2
09-12 14:42:20.714  8078  8078 I libpersona: KNOX_SDCARD checking this for 1000
09-12 14:42:20.714  8078  8078 I libpersona: KNOX_SDCARD not a persona
,09-12 14:42:20.714  8078  8078 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 14:42:20.714  8078  8078 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 14:42:20.724  8078  8078 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 14:42:20.724  1019  4367 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8078 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-12 14:42:20.724  1019  4367 I ActivityManager: Killing 7501:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
09-12 14:42:20.724  1019  1266 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,09-12 14:42:20.724  1019  1266 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-12 14:42:20.734  1019  1266 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:20.734  1019  1043 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-12 14:42:20.734  1019  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 14:42:20.734  1019  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-12 14:42:20.734  1019  4366 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,09-12 14:42:20.744  1019  4366 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.744  1019  4366 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.744  1019  4366 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.744  1019  4366 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:42:20.744  7947  7947 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-12 14:42:20.744  1019  1043 I CrashAnrDetector: onPackageRemoved : com.test.thalitest,
,09-12 14:42:20.754  1019  1043 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-12 14:42:20.754  8078  8078 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 14:42:20.754  8078  8078 D ActivityThread: Added TimaKeyStore provider
,09-12 14:42:20.764  8096  8096 E Zygote  : MountEmulatedStorage()
09-12 14:42:20.764  8096  8096 E Zygote  : v2
09-12 14:42:20.764  8096  8096 I libpersona: KNOX_SDCARD checking this for 10039
09-12 14:42:20.764  8096  8096 I libpersona: KNOX_SDCARD not a persona
,09-12 14:42:20.764  8096  8096 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 14:42:20.764  1019  4366 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=8096 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,09-12 14:42:20.764  8096  8096 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 14:42:20.764  8096  8096 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 14:42:20.774  1019  1504 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 14:42:20.774  1019  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
,09-12 14:42:20.774  1019  1504 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:20.774  1019  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:42:20.774  1019  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:42:20.784  1019  1347 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 14:42:20.784  1019  1347 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:20.784  1019  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:42:20.784  1019  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-12 14:42:20.784  1019  4366 I ActivityManager: Killing 7520:com.sec.android.soagent/u0a31 (adj 15): empty #21
,09-12 14:42:20.794  8096  8096 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 14:42:20.794  3862  8058 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
09-12 14:42:20.794  8096  8096 D ActivityThread: Added TimaKeyStore provider,
,09-12 14:42:20.814  7810  7810 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,09-12 14:42:20.814  1019  1266 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-12 14:42:20.814  1019  1266 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,09-12 14:42:20.824  1019  1266 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:20.824  1019  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:42:20.824  1019  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:42:20.834  3862  3862 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-12 14:42:20.834  3862  3862 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-12 14:42:20.834  1019  4367 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 14:42:20.834  1019  4367 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:20.834  1019  4367 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:42:20.834  1019  4367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:42:20.844  1019  1499 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
09-12 14:42:20.844  8096  8096 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-12 14:42:20.844  8096  8096 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 14:42:20.844  8096  8096 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 14:42:20.844  8096  8096 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,09-12 14:42:20.844  8096  8096 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-12 14:42:20.844  8096  8096 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-12 14:42:20.844  8096  8096 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-12 14:42:20.844  7810  7810 W FileUtils: Failed to chmod(/data/data/com.samsung.android.intelligenceservice/databases/predictor.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,09-12 14:42:20.844  7810  7810 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-12 14:42:20.844  7810  7810 E SQLiteLog: (3850) statement aborts at 39: [DELETE FROM enabled_place_category WHERE package_id='com.test.thalitest' AND place_category IN (1, 2, 3, 0)] disk I/O error
,09-12 14:42:20.854  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-12 14:42:20.854  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.854  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.854  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:42:20.854  7810  7810 D AndroidRuntime: Shutting down VM
,09-12 14:42:20.864  7810  7810 E AndroidRuntime: FATAL EXCEPTION: main
09-12 14:42:20.864  7810  7810 E AndroidRuntime: Process: com.samsung.android.intelligenceservice, PID: 7810
09-12 14:42:20.864  7810  7810 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 14:42:20.864  7810  7810 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 14:42:20.864  7810  7810 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
09-12 14:42:20.864  7810  7810 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 14:42:20.864  7810  7810 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 14:42:20.864  7810  7810 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
09-12 14:42:20.864  7810  7810 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlaceCategoryManager.removePlaceCategories(PlaceCategoryManager.java:66)
09-12 14:42:20.864  7810  7810 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removePlaceCategories(PlacePredictor.java:150)
09-12 14:42:20.864  7810  7810 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removeAllPlaceCategories(PlacePredictor.java:145)
09-12 14:42:20.864  7810  7810 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:79)
09-12 14:42:20.864  7810  7810 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 14:42:20.864  7810  7810 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 14:42:20.864  7810  7810 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
09-12 14:42:20.864  7810  7810 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 14:42:20.864  7810  7810 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:42:20.864  7810  7810 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 14:42:20.864  7810  7810 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 14:42:20.864  7810  7810 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 14:42:20.864  8113  8113 I libpersona: KNOX_SDCARD checking this for 1000
,09-12 14:42:20.864  8113  8113 E Zygote  : MountEmulatedStorage()
09-12 14:42:20.864  8113  8113 I libpersona: KNOX_SDCARD not a persona
09-12 14:42:20.864  8113  8113 E Zygote  : v2
,09-12 14:42:20.874  8078  8078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,09-12 14:42:20.874  1019  1499 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=8113 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-12 14:42:20.874  1019  1139 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 14:42:20.874  1019  1139 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,09-12 14:42:20.884  1019  1139 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:20.884  1019  1139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:42:20.884  1019  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-12 14:42:20.884  3862  8108 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/metrics.db" with flag (131138) and mode_t (0) due to error (30)
,09-12 14:42:20.884  1019  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.884  1019  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.884  1019  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.884  1019  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:42:20.884  3862  8108 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
09-12 14:42:20.884  3862  8108 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 14:42:20.884  3862  8108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 14:42:20.884  3862  8108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-12 14:42:20.884  3862  8108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-12 14:42:20.884  3862  8108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-12 14:42:20.884  3862  8108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-12 14:42:20.884  3862  8108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-12 14:42:20.884  3862  8108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-12 14:42:20.884  3862  8108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-12 14:42:20.884  3862  8108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-12 14:42:20.884  3862  8108 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-12 14:42:20.884  3862  8108 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-12 14:42:20.884  3862  8108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 14:42:20.884  3862  8108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 14:42:20.884  3862  8108 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
09-12 14:42:20.884  3862  8108 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
09-12 14:42:20.884  3862  8108 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
09-12 14:42:20.884  3862  8108 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
09-12 14:42:20.884  3862  8108 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-12 14:42:20.884  3862  8108 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:42:20.884  3862  8108 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-12 14:42:20.884  3862  8108 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 14:42:20.884  3862  8108 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
09-12 14:42:20.884  3862  8108 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 14:42:20.884  3862  8108 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 14:42:20.884  3862  8108 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-12 14:42:20.884  3862  8108 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-12 14:42:20.884  3862  8108 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-12 14:42:20.884  3862  8108 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-12 14:42:20.884  3862  8108 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-12 14:42:20.884  3862  8108 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-12 14:42:20.884  3862  8108 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-12 14:42:20.884  3862  8108 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-12 14:42:20.884  3862  8108 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-12 14:42:20.884  3862  8108 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-12 14:42:20.884  3862  8108 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 14:42:20.884  3862  8108 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 14:42:20.884  3862  8108 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
09-12 14:42:20.884  3862  8108 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
09-12 14:42:20.884  3862  8108 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
09-12 14:42:20.884  3862  8108 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
09-12 14:42:20.884  3862  8108 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-12 14:42:20.884  3862  8108 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:42:20.884  3862  8108 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-12 14:42:20.884  3862  8108 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 14:42:20.894  3862  8108 W SQLiteOpenHelper: Opened metrics.db in read-only mode
09-12 14:42:20.894  3862  8108 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
09-12 14:42:20.894  3862  8108 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
09-12 14:42:20.894  3862  8108 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
09-12 14:42:20.894  3862  8108 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,09-12 14:42:20.894  3862  8108 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
09-12 14:42:20.894  3862  8108 E AndroidRuntime: Process: com.google.android.gms, PID: 3862
09-12 14:42:20.894  3862  8108 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
09-12 14:42:20.894  3862  8108 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 14:42:20.894  3862  8108 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
09-12 14:42:20.894  3862  8108 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 14:42:20.894  3862  8108 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 14:42:20.894  3862  8108 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
09-12 14:42:20.894  3862  8108 E AndroidRuntime: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
09-12 14:42:20.894  3862  8108 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
09-12 14:42:20.894  3862  8108 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-12 14:42:20.894  3862  8108 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:42:20.894  3862  8108 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
09-12 14:42:20.894  3862  8108 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 14:42:20.904  8113  8113 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-12 14:42:20.904  8120  8120 E Zygote  : MountEmulatedStorage()
09-12 14:42:20.904  8120  8120 E Zygote  : v2
09-12 14:42:20.904  8120  8120 I libpersona: KNOX_SDCARD checking this for 10011
09-12 14:42:20.904  8120  8120 I libpersona: KNOX_SDCARD not a persona
,09-12 14:42:20.904  8120  8120 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-12 14:42:20.904  8113  8113 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-12 14:42:20.904  8113  8113 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 14:42:20.904  8120  8120 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-12 14:42:20.904  1019  1139 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=8120 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
09-12 14:42:20.904  1019  4366 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
09-12 14:42:20.904  8120  8120 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-12 14:42:20.904  1019  4366 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
09-12 14:42:20.904  1019  4366 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:20.904  1019  4366 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 14:42:20.904  1019  4366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,09-12 14:42:20.914  1019  1266 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-12 14:42:20.914  3862  8058 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
,09-12 14:42:20.914  1019  1266 W ActivityManager: userId = 0, bbcId = -10000
09-12 14:42:20.914  1019  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 14:42:20.914  1019  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 14:42:20.924  1019  1347 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,09-12 14:42:20.924  1019  1347 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.924  1019  1347 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.924  1019  1347 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 14:42:20.924  1019  1347 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 14:42:20.934  3862  8058 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
09-12 14:42:20.934  3862  8058 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 14:42:20.934  3862  8058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 14:42:20.934  3862  8058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-12 14:42:20.934  3862  8058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-12 14:42:20.934  3862  8058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-12 14:42:20.934  3862  8058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-12 14:42:20.934  3862  8058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-12 14:42:20.934  3862  8058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-12 14:42:20.934  3862  8058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-12 14:42:20.934  3862  8058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-12 14:42:20.934  3862  8058 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-12 14:42:20.934  3862  8058 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-12 14:42:20.934  3862  8058 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-12 14:42:20.934  3862  8058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 14:42:20.934  3862  8058 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 14:42:20.934  3862  8058 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-12 14:42:20.934  3862  8058 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-12 14:42:20.934  3862  8058 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:42:20.934  3862  8058 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-12 14:42:20.934  3862  8058 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 14:42:20.934  3862  8058 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-12 14:42:20.934  3862  8058 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 14:42:20.934  3862  8058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 14:42:20.934  3862  8058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-12 14:42:20.934  3862  8058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-12 14:42:20.934  3862  8058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-12 14:42:20.934  3862  8058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-12 14:42:20.934  3862  8058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-12 14:42:20.934  3862  8058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-12 14:42:20.934  3862  8058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-12 14:42:20.934  3862  8058 E S,QLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-12 14:42:20.934  3862  8058 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-12 14:42:20.934  3862  8058 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-12 14:42:20.934  3862  8058 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-12 14:42:20.934  3862  8058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 14:42:20.934  3862  8058 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 14:42:20.934  3862  8058 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-12 14:42:20.934  3862  8058 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-12 14:42:20.934  3862  8058 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:42:20.934  3862  8058 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-12 14:42:20.934  3862  8058 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 14:42:20.934  3862  8058 W SQLiteOpenHelper: Opened phenotype.db in read-only mode

```
