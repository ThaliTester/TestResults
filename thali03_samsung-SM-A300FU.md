#### Test 8359176442466a2_thali03_samsung-SM-A300FU Logs


```
--------- beginning of system
09-01 11:14:52.227  1019  1082 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
09-01 11:14:52.227  1019  1082 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:52.227  1019  1082 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:52.227  1019  1082 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:52.227  1019  1082 E ActivityManager: checkUser: useridlist=null, currentuser=0
--------- beginning of main
09-01 11:14:52.247  6956  6956 E Zygote  : MountEmulatedStorage()
09-01 11:14:52.247  6956  6956 E Zygote  : v2
09-01 11:14:52.247  6956  6956 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-01 11:14:52.247  6956  6956 I libpersona: KNOX_SDCARD checking this for 10148
09-01 11:14:52.247  6956  6956 I libpersona: KNOX_SDCARD not a persona
09-01 11:14:52.247  1019  1082 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6956 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
09-01 11:14:52.257  6956  6956 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 11:14:52.257  6956  6956 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-01 11:14:52.257  6905  6905 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
09-01 11:14:52.257  1019  1032 I ActivityManager: Killing 6529:com.wsomacp/u0a23 (adj 15): empty #21
09-01 11:14:52.267  1019  3288 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:14:52.267  1019  3288 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 11:14:52.267  1019  3288 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
09-01 11:14:52.267  1019  3288 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-01 11:14:52.277  6905  6905 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-01 11:14:52.287  6921  6921 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 163.811ms
09-01 11:14:52.287  1876  1891 W art     : Suspending all threads took: 6.713ms
09-01 11:14:52.287  6956  6956 D TimaKeyStoreProvider: TimaSignature is unavailable
09-01 11:14:52.287  6956  6956 D ActivityThread: Added TimaKeyStore provider
,09-01 11:14:52.327  6956  6956 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
09-01 11:14:52.337  1019  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-01 11:14:52.337  1019  1505 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:14:52.337  1019  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 11:14:52.337  1019  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-01 11:14:52.357  1019  1546 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-01 11:14:52.357  1019  1546 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-01 11:14:52.367  1019  1546 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:14:52.367  1019  1546 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 11:14:52.367  1019  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-01 11:14:52.367  1019  1032 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
09-01 11:14:52.367  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:52.367  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:52.367  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:52.367  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:52.377  6921  6981 D Mms/ArtClassLoader: init before art
09-01 11:14:52.387  1019  1032 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=6982 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-01 11:14:52.387  1019  1032 I ActivityManager: Killing 6544:com.sec.esdk.elm/u0a90 (adj 15): empty #21
09-01 11:14:52.407  6982  6982 E Zygote  : MountEmulatedStorage()
09-01 11:14:52.407  6982  6982 I libpersona: KNOX_SDCARD checking this for 1000
09-01 11:14:52.407  6982  6982 E Zygote  : v2
09-01 11:14:52.407  6982  6982 I libpersona: KNOX_SDCARD not a persona
09-01 11:14:52.407  6982  6982 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-01 11:14:52.407  6982  6982 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 11:14:52.407  6982  6982 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-01 11:14:52.407  6697  6770 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 570 ms] updated apps [took 569 ms] 
09-01 11:14:52.417  1019  1544 I ActivityManager: Killing 6278:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
09-01 11:14:52.427  6921  6921 D Mms/TelephonyPermission: start operation mode monitor
09-01 11:14:52.437  6982  6982 D TimaKeyStoreProvider: TimaSignature is unavailable
09-01 11:14:52.437  6982  6982 D ActivityThread: Added TimaKeyStore provider
09-01 11:14:52.457  6921  6921 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-01 11:14:52.467  6921  6921 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
09-01 11:14:52.467  6921  6921 D Mms/TelephonyPermission: isDefault true
09-01 11:14:52.467  6982  6982 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
09-01 11:14:52.477  6921  6921 D Mms/MmsApp: onCreate() com.android.mms
09-01 11:14:52.517  6905  6905 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-01 11:14:52.527  6905  6905 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-01 11:14:52.527  6905  6905 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-01 11:14:52.527  6905  6905 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-01 11:14:52.537  1019  1490 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
09-01 11:14:52.537  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:52.537  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:52.537  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:52.537  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:52.547  7008  7008 E Zygote  : MountEmulatedStorage()
09-01 11:14:52.557  7008  7008 E Zygote  : v2
09-01 11:14:52.557  1019  1490 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7008 uid=10152 gids={50152, 9997} abi=armeabi-v7a
09-01 11:14:52.557  1019  1490 I ActivityManager: Killing 6297:com.android.calendar/u0a131 (adj 15): empty #21
09-01 11:14:52.557  7008  7008 I libpersona: KNOX_SDCARD checking this for 10152
09-01 11:14:52.557  7008  7008 I libpersona: KNOX_SDCARD not a persona
09-01 11:14:52.557  7008  7008 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-01 11:14:52.567  7008  7008 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 11:14:52.567  6921  6921 D Mms/MmsApp: [start]    initCountryIso consume time = 501.48802
09-01 11:14:52.567  7008  7008 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-01 11:14:52.577  1019  1544 D CountryDetector: The first listener is added
09-01 11:14:52.577  6979  6979 D AndroidRuntime: 
09-01 11:14:52.577  6979  6979 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-01 11:14:52.577  6979  6979 D AndroidRuntime: CheckJNI is OFF
09-01 11:14:52.587  6979  6979 D AndroidRuntime: readGMSProperty: start
09-01 11:14:52.587  6979  6979 D AndroidRuntime: readGMSProperty: already setted!!
09-01 11:14:52.587  6979  6979 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-01 11:14:52.587  6979  6979 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-01 11:14:52.587  6979  6979 D AndroidRuntime: readGMSProperty: end
09-01 11:14:52.587  6979  6979 D AndroidRuntime: addProductProperty: start
09-01 11:14:52.587  6921  6921 D Mms/MmsApp: [end]    initCountryIso consume time = 17.506094
09-01 11:14:52.587  6921  6921 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.149844
09-01 11:14:52.587  6905  6905 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-01 11:14:52.597  7008  7008 D TimaKeyStoreProvider: TimaSignature is unavailable
09-01 11:14:52.597  7008  7008 D ActivityThread: Added TimaKeyStore provider
09-01 11:14:52.607  6905  6905 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-01 11:14:52.607  6905  6905 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-01 11:14:52.607  6921  6921 D Mms/MmsConfig: before partial update
09-01 11:14:52.617  6905  6905 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-01 11:14:52.627  6905  6905 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-01 11:14:52.627  6905  6905 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-01 11:14:52.627  6905  6905 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-01 11:14:52.627  6905  6905 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-01 11:14:52.637  6905  6905 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-01 11:14:52.637  6905  6905 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-01 11:14:52.637  6921  6921 D Mms/MmsConfig: Load Resize quality : 80
09-01 11:14:52.637  6905  6905 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-01 11:14:52.637  6905  6905 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-01 11:14:52.637  6905  6905 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
09-01 11:14:52.657  6921  6921 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
09-01 11:14:52.657  6921  6921 D EasySignUpManager_1.0.1: isAuth is false
09-01 11:14:52.657  6921  6921 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
09-01 11:14:52.657  1019  1031 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
09-01 11:14:52.657  7008  7008 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
09-01 11:14:52.657  7008  7008 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
09-01 11:14:52.677  6905  6905 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-01 11:14:52.687  1876  6772 I qtaguid : Untagging socket 100
09-01 11:14:52.697  6905  6905 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-01 11:14:52.717  1467  2482 D TP/MmsSmsProvider: query,matched:2117, calling pid = 6921
09-01 11:14:52.717  1467  2482 D TP/MmsSmsProvider: match 2117:Elapsed time : 0.872 ms
09-01 11:14:52.717  1876  1876 I ConfigFetchService: fetch service done; releasing wakelock
09-01 11:14:52.737  1876  1876 I ConfigFetchService: stopping self
09-01 11:14:52.737  6979  6979 E AffinityControl: AffinityControl: registerfunction enter
09-01 11:14:52.737  6921  6921 D EasySignUpManager_1.0.1: isAuth is false
09-01 11:14:52.737  6921  6921 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
09-01 11:14:52.737  7008  7008 I TapandpayWidget:Utils: Clear T&P info.
09-01 11:14:52.747  6921  6921 E CscParser: mps_code.dat does not exist
09-01 11:14:52.747  6921  6921 E CscParser: customer_path =/system/csc/customer.xml
09-01 11:14:52.747  6921  6921 E CscParser: fileName + /system/csc/customer.xml
09-01 11:14:52.747  6921  6921 E CscParser: mps_code.dat does not exist
09-01 11:14:52.747  6921  6921 E CscParser: customer_path =/system/csc/customer.xml
09-01 11:14:52.747  6921  6921 E CscParser: fileName + /system/csc/customer.xml
09-01 11:14:52.767  6979  6979 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-01 11:14:52.767  7008  7008 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
09-01 11:14:52.767  1019  1032 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
09-01 11:14:52.767  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:52.767  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:52.767  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:52.767  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:52.797  7038  7038 E Zygote  : MountEmulatedStorage()
09-01 11:14:52.797  7038  7038 E Zygote  : v2
09-01 11:14:52.797  7038  7038 I libpersona: KNOX_SDCARD checking this for 10009
09-01 11:14:52.797  7038  7038 I libpersona: KNOX_SDCARD not a persona
09-01 11:14:52.797  1019  1546 E PersonaManagerService: inState():  stateMachine is null !!
09-01 11:14:52.797  6905  6905 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-01 11:14:52.797  6921  6921 D CscParser: getInstance fileName =/system/csc/customer.xml
09-01 11:14:52.807  1019  3288 I art     : Explicit concurrent mark sweep GC freed 21115(1192KB) AllocSpace objects, 1(22KB) LOS objects, 33% free, 23MB/34MB, paused 3.046ms total 161.302ms
09-01 11:14:52.807  1019  1032 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7038 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
09-01 11:14:52.807  7038  7038 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-01 11:14:52.807  1019  1546 I PersonaManagerService: PersonaId don't exist
09-01 11:14:52.807  1019  1546 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-01 11:14:52.807  7038  7038 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 11:14:52.807  7038  7038 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-01 11:14:52.807  6905  6905 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-01 11:14:52.807  6905  6905 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-01 11:14:52.807  6921  6921 D Mms/MmsConfig:  enable multiwindow = false
09-01 11:14:52.817  1019  1032 I ActivityManager: Killing 6576:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
09-01 11:14:52.837  1019  1546 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-01 11:14:52.847  7038  7038 D TimaKeyStoreProvider: TimaSignature is unavailable
09-01 11:14:52.847  7038  7038 D ActivityThread: Added TimaKeyStore provider
09-01 11:14:52.857  6921  6921 E Mms/MessageUtils: setCountryDetector : update country detector info 
09-01 11:14:52.857  6921  6921 E Mms/MessageUtils: updateCountryIso : update country iso info 
09-01 11:14:52.857  6921  6921 D Mms/MmsConfig: [end]    init() consume time = 276.830416
09-01 11:14:52.867  6921  6921 D Mms/Contact: [start]    init() consume time = 1.318542
09-01 11:14:52.867  1019  1546 W ActivityManager: mDVFSHelper.acquire()
09-01 11:14:52.867  1019  1546 D FocusedStackFrame: Set to : 0
09-01 11:14:52.877  1019  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:52.877  1019  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:52.877  1019  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:52.877  1019  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:52.887  6826  6904 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-01 11:14:52.887  6826  6904 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-01 11:14:52.887  6826  6904 I GAv4    :   adb logcat -s GAv4
09-01 11:14:52.887  1019  1051 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-01 11:14:52.887  1019  1051 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-01 11:14:52.887  1467  3340 D TP/MmsSmsProvider: query,matched:13, calling pid = 6921
09-01 11:14:52.887  1467  3340 D TP/MmsSmsProvider: match 13:Elapsed time : 1.269 ms
09-01 11:14:52.897  6921  6921 D Mms/Contact: [end]    init consume time = 29.35599
09-01 11:14:52.897  6921  7057 D Mms/DraftCache: [start]    rebuildCache consume time = 4.755208
09-01 11:14:52.897  7058  7058 E Zygote  : MountEmulatedStorage()
09-01 11:14:52.897  7058  7058 E Zygote  : v2
09-01 11:14:52.897  7058  7058 I libpersona: KNOX_SDCARD checking this for 10170
09-01 11:14:52.897  7058  7058 I libpersona: KNOX_SDCARD not a persona
09-01 11:14:52.897  7058  7058 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-01 11:14:52.907  7058  7058 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 11:14:52.907  7058  7058 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-01 11:14:52.907  1019  1546 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7058 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-01 11:14:52.907  1019  1546 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-01 11:14:52.907  1019  1546 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-01 11:14:52.907  1019  1546 D InputDispatcher: Focused application set to: xxxx
09-01 11:14:52.907  1019  1546 D InputDispatcher: Focus left window: 1491
09-01 11:14:52.907  1019  1051 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-01 11:14:52.907  1019  1051 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-01 11:14:52.917   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
09-01 11:14:52.917  6979  6979 D AndroidRuntime: Shutting down VM
09-01 11:14:52.937  1019  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-01 11:14:52.937  1019  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
09-01 11:14:52.947  1019  1317 I ActivityManager: Killing 6594:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
09-01 11:14:52.947  7058  7058 D TimaKeyStoreProvider: TimaSignature is unavailable
09-01 11:14:52.947  7058  7058 D ActivityThread: Added TimaKeyStore provider
09-01 11:14:52.947  6826  6904 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
09-01 11:14:52.947  1019  1484 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-01 11:14:52.947  1019  1545 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
09-01 11:14:52.947  1019  1019 V ActivityManager: Display changed displayId=0
09-01 11:14:52.977  1467  1485 D TP/MmsSmsProvider: query,matched:12, calling pid = 6921
09-01 11:14:52.977  6921  6921 D Mms/MethodReflector: getSubId is called
09-01 11:14:52.977  6921  6921 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
09-01 11:14:52.987  1467  1485 D TP/MmsSmsProvider: match 12:Elapsed time : 10.081 ms
09-01 11:14:52.987  1019  1049 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-01 11:14:52.987  6921  6921 D Mms/MethodReflector: getTelephonyProperty is called
09-01 11:14:52.987  6921  6921 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-01 11:14:52.997  6921  6921 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-01 11:14:52.997  6921  6921 D Mms/DownloadManager: auto download without roaming -> true
09-01 11:14:52.997  6921  6921 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
09-01 11:14:52.997  6921  6921 D Mms/MethodReflector: getSubId is called
09-01 11:14:53.007  6921  6921 D Mms/MethodReflector: getDefaultSmsSubId is called
09-01 11:14:53.007  6921  6921 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
09-01 11:14:53.007  6921  6921 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
09-01 11:14:53.007  6921  6921 D Mms/MethodReflector: getTelephonyProperty is called
09-01 11:14:53.007  6921  6921 D Mms/DownloadManager: roaming -> false (slotId = 1)
09-01 11:14:53.007  6921  6921 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
09-01 11:14:53.007  6921  6921 D Mms/DownloadManager: auto download without roaming -> true
09-01 11:14:53.007  6921  6921 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
09-01 11:14:53.007  6921  6921 D Mms/DownloadManager: auto download during roaming secondary -> false
09-01 11:14:53.007  6921  6921 D Mms/DownloadManager: mAutoDownload ------> true
09-01 11:14:53.007  1491  1491 V ActivityThread: updateVisibility : ActivityRecord{3f0978d2 token=android.os.BinderProxy@368a1a03 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-01 11:14:53.017  1019  1484 D PersonaManager: isKioskContainerExistOnDevice
09-01 11:14:53.027  1491  1491 D Launcher: onTrimMemory. Level: 20
09-01 11:14:53.037   258   454 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
09-01 11:14:53.037   258   450 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
09-01 11:14:53.037  6921  7057 D Mms/DraftCache: [end]    rebuildCache consume time = 144.915677
09-01 11:14:53.057  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-01 11:14:53.087  6905  6905 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
09-01 11:14:53.087  1019  1490 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
09-01 11:14:53.087  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
09-01 11:14:53.087  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:14:53.087  1019  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 11:14:53.087  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
09-01 11:14:53.097  6826  6904 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
09-01 11:14:53.127  6979  6979 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-01 11:14:53.137  6905  7078 D Ads     : Skipping gmscore version check
,09-01 11:14:53.137  6905  6905 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-01 11:14:53.147  1019  1545 I ActivityManager: Killing 6610:com.qualcomm.timeservice/1000 (adj 15): empty #21
,09-01 11:14:53.157  6921  6921 D ComposerPerformance: 1472721293161 ms / [DONE] Composer constructor
,09-01 11:14:53.157  6921  6921 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,09-01 11:14:53.157  6921  6921 I Mms/ReservationManager: ReservationManager()
,09-01 11:14:53.157  6826  6904 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
09-01 11:14:53.157  6921  6921 I Mms/ReservationManager: resetAfterConnected()
,09-01 11:14:53.157  1467  1476 D TP/MmsSmsProvider: query,matched:7, calling pid = 6921
,09-01 11:14:53.167  1467  1476 D TP/MmsSmsProvider: match 7:Elapsed time : 2.578 ms
09-01 11:14:53.167  6826  7080 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-01 11:14:53.167  6921  6921 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,09-01 11:14:53.167  6921  6921 D Mms/MmsApp: [end]    onCreate() consume time = 129.385521
,09-01 11:14:53.177  6921  7081 D Mms/Conversation: [start]    init() consume time = 1.709271
,09-01 11:14:53.177  1467  3340 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,09-01 11:14:53.177  1467  3340 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,09-01 11:14:53.177  1019  1484 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 11:14:53.177  1876  6810 W art     : Verification of void com.google.android.gms.games.broker.GameAgent.addGameBadgeOps(com.google.android.gms.common.internal.ClientContext, com.google.android.gms.games.server.api.MarketInstance, java.lang.String, java.util.ArrayList, int) took 151.301ms
,09-01 11:14:53.177  1467  3340 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,09-01 11:14:53.177  1019  1484 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:14:53.177  1467  3340 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
09-01 11:14:53.177  1019  1484 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-01 11:14:53.187  1019  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-01 11:14:53.187  1467  3340 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
09-01 11:14:53.187  1467  3340 D TP/MmsSmsProvider: need read changed broadcast:false
09-01 11:14:53.187  6826  6854 W art     : Suspending all threads took: 14.893ms
,09-01 11:14:53.187  6921  7081 D Mms/Conversation: [end]    init consume time = 17.742083
,09-01 11:14:53.197  6921  7081 D Mms/MessagingNotification: [start]    init() consume time = 4.416458
,09-01 11:14:53.197  6921  7081 D Mms/MessagingNotification: [end]    init consume time = 2.137813
,09-01 11:14:53.207  6921  7082 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 10.36
,09-01 11:14:53.207  6921  7083 D Mms/Synchronizer: [start]    doSync consume time = 2.185521
,09-01 11:14:53.207  6921  6921 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
,09-01 11:14:53.217  6921  6921 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,09-01 11:14:53.217  6921  6981 D Mms/ArtClassLoader: init [DONE] art
,09-01 11:14:53.217  6921  6921 D Mms/MethodReflector: getSubId is called
09-01 11:14:53.217  6921  6921 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,09-01 11:14:53.217  6921  6921 D Mms/MethodReflector: getTelephonyProperty is called
09-01 11:14:53.217  6921  6921 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-01 11:14:53.217  6921  6921 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-01 11:14:53.217  6921  6921 D Mms/DownloadManager: auto download without roaming -> true
09-01 11:14:53.217  6921  6921 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
09-01 11:14:53.217  6921  6921 D Mms/DownloadManager: mAutoDownload ------> true
,09-01 11:14:53.217  1467  3339 D TP/MmsSmsProvider: query,matched:400, calling pid = 6921
,09-01 11:14:53.227  1467  1660 D TP/MmsSmsProvider: query,matched:0, calling pid = 6921
09-01 11:14:53.227  1467  1660 V TP/MmsSmsProvider: getSimpleConversations entered.
,09-01 11:14:53.227  1467  1660 D TP/MmsSmsProvider: match 0:Elapsed time : 1.103 ms
,09-01 11:14:53.227  1467  2482 D TP/MmsSmsProvider: update, matched:300, calling pid = 6921
09-01 11:14:53.227  1467  2482 V TP/MmsSmsProvider: syncDBData start
,09-01 11:14:53.227  6921  7082 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 13.597343
,09-01 11:14:53.227  1467  2482 V TP/MmsSmsProvider: syncDBData sms end
09-01 11:14:53.227  1467  2482 V TP/MmsSmsProvider: syncDBData mms end
09-01 11:14:53.227  1467  2482 V TP/MmsSmsProvider: syncDBData end
,09-01 11:14:53.227  6905  6905 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-01 11:14:53.227  6921  6921 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
,09-01 11:14:53.237  1019  1317 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
,09-01 11:14:53.237  6921  7083 D Mms/Synchronizer: [end]    doSync consume time = 10.336719
09-01 11:14:53.237  1019  1317 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
09-01 11:14:53.237  1019  1317 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:14:53.237  1019  1317 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:14:53.237  1019  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,09-01 11:14:53.247  1019  1546 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
,09-01 11:14:53.247  7058  7058 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-01 11:14:53.247  1019  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-01 11:14:53.247  1019  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:53.247  1019  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:53.247  1019  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:14:53.257  6921  7085 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
09-01 11:14:53.257  6921  7085 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
,09-01 11:14:53.267  7086  7086 E Zygote  : MountEmulatedStorage()
09-01 11:14:53.267  7086  7086 E Zygote  : v2
09-01 11:14:53.267  7086  7086 I libpersona: KNOX_SDCARD checking this for 10042
09-01 11:14:53.267  7086  7086 I libpersona: KNOX_SDCARD not a persona
,09-01 11:14:53.267  7086  7086 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 11:14:53.267  7086  7086 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 11:14:53.267  1019  1546 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7086 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
09-01 11:14:53.267  7086  7086 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
,09-01 11:14:53.267  1019  1032 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
09-01 11:14:53.277  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:53.277  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:53.277  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:53.277  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:14:53.287  7097  7097 E Zygote  : MountEmulatedStorage()
,09-01 11:14:53.287  7097  7097 E Zygote  : v2
09-01 11:14:53.287  7097  7097 I libpersona: KNOX_SDCARD checking this for 10068
09-01 11:14:53.287  7097  7097 I libpersona: KNOX_SDCARD not a persona
,09-01 11:14:53.287  7097  7097 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 11:14:53.297  7097  7097 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-01 11:14:53.297  7097  7097 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-01 11:14:53.297  1019  1032 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7097 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,09-01 11:14:53.297  1019  1031 I ActivityManager: Killing 6563:com.android.providers.calendar/u0a37 (adj 15): empty #21
,09-01 11:14:53.307  7086  7086 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-01 11:14:53.307  7086  7086 D ActivityThread: Added TimaKeyStore provider
,09-01 11:14:53.317   324   324 I art     : Explicit concurrent mark sweep GC freed 8708(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 617us total 20.682ms
,09-01 11:14:53.317  7097  7097 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:14:53.317  7097  7097 D ActivityThread: Added TimaKeyStore provider
,09-01 11:14:53.327  1019  6683 I ActivityManager: Killing 6382:com.android.defcontainer/u0a3 (adj 15): empty #21
,09-01 11:14:53.327   324   324 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 618us total 16.905ms
,09-01 11:14:53.337  7058  7058 I cr.library_loader: Time to load native libraries: 7 ms (timestamps 7434-7441)
,09-01 11:14:53.337  7058  7058 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-01 11:14:53.347  7086  7086 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-01 11:14:53.347  7086  7086 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-01 11:14:53.347  7086  7086 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-01 11:14:53.347   324   324 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 616us total 17.324ms
,09-01 11:14:53.357  7097  7097 D BadgeProvider: onCreate
09-01 11:14:53.357  7097  7097 D BadgeProvider: DatabaseHelper
,09-01 11:14:53.367   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7cb57c8
09-01 11:14:53.367   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
09-01 11:14:53.367   273   273 I rmt_storage: wakelock acquired: 1, error no: 42
09-01 11:14:53.367   273   312 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1211410296)
,09-01 11:14:53.387  6921  7081 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,09-01 11:14:53.397  7058  7058 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {444e61a}
09-01 11:14:53.397  7058  7058 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-01 11:14:53.397  1467  3339 D TP/SmsProvider: query,matched:26, calling pid = 6921
,09-01 11:14:53.397  1467  3339 D TP/SmsProvider: match 26:Elapsed time : 1.348 ms
,09-01 11:14:53.417  1467  3340 D TP/MmsSmsProvider: query,matched:6, calling pid = 6921
,09-01 11:14:53.417  1467  3340 D TP/MmsSmsProvider: match 6:Elapsed time : 1.977 ms
,09-01 11:14:53.437  1019  1490 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,09-01 11:14:53.437  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:53.437  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:53.437  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:53.437  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:14:53.447  7120  7120 E Zygote  : MountEmulatedStorage(),
09-01 11:14:53.447  7120  7120 E Zygote  : v2
09-01 11:14:53.447  7120  7120 I libpersona: KNOX_SDCARD checking this for 10023,
09-01 11:14:53.447  7120  7120 I libpersona: KNOX_SDCARD not a persona
,09-01 11:14:53.447   273   312 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
09-01 11:14:53.447   273   312 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
09-01 11:14:53.447   273   312 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1211410296) wakelock released: 1, error no: 0
09-01 11:14:53.447   273   312 I rmt_storage: 
,09-01 11:14:53.447  1019  1490 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7120 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,09-01 11:14:53.447   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7cb57c8
,09-01 11:14:53.457  7120  7120 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 11:14:53.457  7120  7120 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-01 11:14:53.457  7120  7120 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-01 11:14:53.477  7120  7120 D TimaKeyStoreProvider: TimaSignature is unavailable,
,09-01 11:14:53.477  7120  7120 D ActivityThread: Added TimaKeyStore provider
,09-01 11:14:53.477  1019  1545 I ActivityManager: Killing 6637:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21,
,09-01 11:14:53.497  1019  1082 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
,09-01 11:14:53.497  1019  1082 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:53.497  1019  1082 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:53.497  1019  1082 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:53.497  1019  1082 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:14:53.517  7058  7058 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-01 11:14:53.517  1019  1082 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7137 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-01 11:14:53.517  7137  7137 E Zygote  : MountEmulatedStorage()
09-01 11:14:53.517  1019  1046 W ActivityManager: Activity pause timeout for ActivityRecord{3504ae93 u0 com.test.thalitest/.MainActivity t163}
09-01 11:14:53.517  7137  7137 E Zygote  : v2,
09-01 11:14:53.517  7137  7137 I libpersona: KNOX_SDCARD checking this for 1000
09-01 11:14:53.517  7137  7137 I libpersona: KNOX_SDCARD not a persona
09-01 11:14:53.517  7137  7137 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-01 11:14:53.517  1019  1082 I ActivityManager: Killing 6652:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21,
09-01 11:14:53.527  7137  7137 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 11:14:53.527  7137  7137 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 11:14:53.537  7120  7120 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,09-01 11:14:53.547  7086  7086 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,09-01 11:14:53.557  7137  7137 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:14:53.557  7137  7137 D ActivityThread: Added TimaKeyStore provider
,09-01 11:14:53.557  6921  7081 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,09-01 11:14:53.567  1019  1061 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
,09-01 11:14:53.567  1019  1061 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-01 11:14:53.577  1019  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:53.577  1019  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:53.577  1019  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:53.577  1019  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:14:53.587  7120  7120 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
09-01 11:14:53.587  7120  7120 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
09-01 11:14:53.587  1876  4232 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
09-01 11:14:53.587  7120  7120 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
09-01 11:14:53.587  7120  7120 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
09-01 11:14:53.587  7120  7120 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,09-01 11:14:53.597  7058  7058 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-01 11:14:53.597  7120  7120 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,09-01 11:14:53.597  7120  7120 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false,
,09-01 11:14:53.597  7120  7120 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false,
,09-01 11:14:53.597  7120  7120 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,09-01 11:14:53.597  7120  7120 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,09-01 11:14:53.607  7120  7120 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,09-01 11:14:53.607  7120  7120 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,09-01 11:14:53.607  7058  7058 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-01 11:14:53.607  7153  7153 E Zygote  : MountEmulatedStorage()
09-01 11:14:53.607  7153  7153 I libpersona: KNOX_SDCARD checking this for 10003
09-01 11:14:53.607  7153  7153 E Zygote  : v2
09-01 11:14:53.607  7153  7153 I libpersona: KNOX_SDCARD not a persona
09-01 11:14:53.607  7120  7120 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,09-01 11:14:53.607  7153  7153 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 11:14:53.607  7153  7153 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 11:14:53.607  7153  7153 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 11:14:53.617  1019  1061 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7153 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-01 11:14:53.617  1019  3288 I ActivityManager: Killing 5065:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
,09-01 11:14:53.627  7058  7058 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-01 11:14:53.637  7153  7153 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:14:53.637  7153  7153 D ActivityThread: Added TimaKeyStore provider
,09-01 11:14:53.657  7137  7137 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
,09-01 11:14:53.657  7137  7137 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,09-01 11:14:53.657  1019  1317 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
09-01 11:14:53.657  1019  1317 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
,09-01 11:14:53.657  1019  1317 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:14:53.657  1019  1317 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 11:14:53.657  1019  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,09-01 11:14:53.657  1019  1544 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-01 11:14:53.657   284   284 E installd: system dir 0 : /system/app/
09-01 11:14:53.657   284   284 E installd: system dir 1 : /system/priv-app/
09-01 11:14:53.657   284   284 E installd: system dir 2 : /vendor/app/
09-01 11:14:53.657   284   284 E installd: system dir 3 : /oem/app/
,09-01 11:14:53.667  7137  7137 I FilterInstaller: FilterPackageService : ACTION_CHANGED,
09-01 11:14:53.667  1019  1046 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,09-01 11:14:53.667  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:53.667  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:53.667  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:53.667  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:14:53.677  7171  7171 E Zygote  : MountEmulatedStorage()
,09-01 11:14:53.677  7171  7171 E Zygote  : v2
09-01 11:14:53.677  7171  7171 I libpersona: KNOX_SDCARD checking this for 10130
09-01 11:14:53.677  7171  7171 I libpersona: KNOX_SDCARD not a persona
,09-01 11:14:53.677  7171  7171 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-01 11:14:53.677  1019  1046 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7171 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,09-01 11:14:53.687  7171  7171 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 11:14:53.687  1019  1061 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,09-01 11:14:53.687  6826  7135 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-01 11:14:53.687  7171  7171 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
09-01 11:14:53.687  6826  7135 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-01 11:14:53.687  7137  7170 E FilterInstaller: installFilters
,09-01 11:14:53.687  1876  4232 D Icing   : Loaded CLD2 Version V2.0 - 20141016
09-01 11:14:53.687  7137  7170 E FilterInstaller: There is no requred permission
,09-01 11:14:53.707  1019  3288 I ActivityManager: Killing 6667:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,09-01 11:14:53.717  7171  7171 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:14:53.717  7171  7171 D ActivityThread: Added TimaKeyStore provider
,09-01 11:14:53.727  7171  7171 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-01 11:14:53.727  7171  7171 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,09-01 11:14:53.737  6826  7135 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,09-01 11:14:53.747  7058  7058 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-01 11:14:53.747  7058  7058 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-01 11:14:53.747  7058  7058 I Adreno-EGL: Build Date: 04/06/15 Mon
09-01 11:14:53.747  7058  7058 I Adreno-EGL: Local Branch: 
09-01 11:14:53.747  7058  7058 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-01 11:14:53.747  7058  7058 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-01 11:14:53.747  7058  7058 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-01 11:14:53.747  1019  6811 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,09-01 11:14:53.757  1019  6811 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:53.757  1019  6811 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:53.757  1019  6811 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:14:53.757  1019  6811 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:14:53.767  7191  7191 E Zygote  : MountEmulatedStorage(),
09-01 11:14:53.767  7191  7191 E Zygote  : v2
09-01 11:14:53.767  7191  7191 I libpersona: KNOX_SDCARD checking this for 10131
09-01 11:14:53.767  7191  7191 I libpersona: KNOX_SDCARD not a persona
09-01 11:14:53.767  7191  7191 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 11:14:53.767  7191  7191 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 11:14:53.767  7191  7191 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 11:14:53.767  1876  4232 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
,09-01 11:14:53.767  1019  6811 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7191 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,09-01 11:14:53.777  1019  1484 I ActivityManager: Killing 6688:com.samsung.helphub/1000 (adj 15): empty #21
,09-01 11:14:53.797  7191  7191 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:14:53.797  7191  7191 D ActivityThread: Added TimaKeyStore provider
,09-01 11:14:53.797  6826  7135 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-01 11:14:53.797  6826  7135 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@540dfde: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-01 11:14:53.797  6826  7135 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-01 11:14:53.807   295   295 E SMD     : DCD OFF
,09-01 11:14:53.807  1019  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-01 11:14:53.807  1019  1505 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:14:53.807  1019  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 11:14:53.807  1019  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 11:14:53.817  7191  7191 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-01 11:14:53.817  7191  7191 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 11:14:53.817  7191  7191 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-01 11:14:53.827  7058  7058 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-01 11:14:53.847  7058  7058 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
09-01 11:14:53.847  7058  7058 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-01 11:14:53.857  7058  7058 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-01 11:14:53.857  7058  7058 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-01 11:14:53.867  1019  1546 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
09-01 11:14:53.867  1019  1546 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,09-01 11:14:53.867  1019  1546 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:14:53.867  1019  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:14:53.867  1019  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-01 11:14:53.867  2675  2689 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,09-01 11:14:53.877  1019  1031 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
09-01 11:14:53.877  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,09-01 11:14:53.877  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:14:53.887  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 11:14:53.887  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-01 11:14:53.897  1019  6811 I ActivityManager: Killing 6719:com.sec.spp.push/u0a32 (adj 15): empty #21
,09-01 11:14:53.967  7058  7058 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-01 11:14:53.977  7058  7058 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-01 11:14:53.987  7058  7058 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-01 11:14:53.987  7058  7058 D PhoneWindow: *FMB* installDecor flags : -2139027200
09-01 11:14:53.997  7058  7058 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
09-01 11:14:53.997  7058  7058 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-01 11:14:53.997  7058  7058 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-01 11:14:54.027  1019  3388 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-01 11:14:54.037  7058  7229 D OpenGLRenderer: Render dirty regions requested: true
09-01 11:14:54.047  1019  6811 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-01 11:14:54.047  1019  6811 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-01 11:14:54.047  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
09-01 11:14:54.047  1019  6811 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-01 11:14:54.047  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-01 11:14:54.047  7058  7058 V ActivityThread: updateVisibility : ActivityRecord{296191a5 token=android.os.BinderProxy@2747170f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-01 11:14:54.047  7058  7211 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
09-01 11:14:54.057  7058  7058 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-01 11:14:54.057  7058  7058 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-01 11:14:54.067   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
09-01 11:14:54.087  1019  3288 D InputDispatcher: Focus entered window: 7058
09-01 11:14:54.097  1019  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-01 11:14:54.097  1019  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
09-01 11:14:54.097  7058  7058 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-01 11:14:54.097  7058  7229 I OpenGLRenderer: Initialized EGL, version 1.4
09-01 11:14:54.097  7058  7229 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
09-01 11:14:54.097  7058  7229 D OpenGLRenderer: Enabling debug mode 0
09-01 11:14:54.117  1019  1317 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
09-01 11:14:54.127  1183  1183 D PanelView: There is/are notification(s) 
09-01 11:14:54.127  1019  7234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-01 11:14:54.137  1019  1051 I ActivityManager: Displayed Component not be shown by security: +1s116ms (total +1s255ms)
09-01 11:14:54.137  1019  1051 W ActivityManager: mDVFSHelper.release()
09-01 11:14:54.137  1019  1051 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3504ae93 u0 com.test.thalitest/.MainActivity t163} time:98244
09-01 11:14:54.137  7058  7058 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-01 11:14:54.137  7058  7058 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2747170f time:98247
09-01 11:14:54.137   258   450 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
09-01 11:14:54.137   258  1041 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
09-01 11:14:54.167  1986  1986 I SamsungIME: getCurrentCandidateView
09-01 11:14:54.177  1019  6683 I ActivityManager: Killing 6697:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
09-01 11:14:54.297  1986  1986 D SamsungIME: Dismiss ExpandCandiate
09-01 11:14:54.307  7058  7058 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7058
09-01 11:14:54.437  1986  1986 I SamsungIME: getDebugLevel  : 0x4f4c
09-01 11:14:54.477  1986  1986 I SamsungIME: getDebugLevel  : 0x4f4c
09-01 11:14:54.487  1986  1986 I SamsungIME: KeybaordView init() : load resources
09-01 11:14:54.507  7058  7058 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-01 11:14:54.517  1986  1986 I SamsungIME: getCurrentKeyboard
09-01 11:14:54.517  1986  1986 I SamsungIME: getTextKeyboard
09-01 11:14:54.537  1986  1986 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
09-01 11:14:54.597  7058  7236 D jxcore_app_log: JniHelper::setJavaVM(0xb76292b0), pthread_self() = -1212454856
09-01 11:14:54.607  7058  7236 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-01 11:14:54.607  7058  7236 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-01 11:14:54.607  7058  7236 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-01 11:14:54.607  7058  7236 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-01 11:14:54.607  7058  7236 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-01 11:14:54.607  7058  7236 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f5f45a0 added. We now have 1 listener(s)
09-01 11:14:54.617  7058  7236 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
09-01 11:14:54.617  7058  7236 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-01 11:14:54.617  7058  7236 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:14:54.617  7058  7236 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:14:54.617  7058  7236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-01 11:14:54.617  7058  7236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-01 11:14:54.617  7058  7236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-01 11:14:54.617  7058  7236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
09-01 11:14:54.617  7058  7236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-01 11:14:54.617  7058  7236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-01 11:14:54.617  7058  7236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-01 11:14:54.617  7058  7236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-01 11:14:54.617  7058  7236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-01 11:14:54.617  7058  7236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-01 11:14:54.617  7058  7236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-01 11:14:54.617  7058  7236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-01 11:14:54.617  7058  7236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-01 11:14:54.617  7058  7236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-01 11:14:54.617  7058  7236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ba1e1ff added. We now have 1 listener(s)
09-01 11:14:54.617  7058  7236 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:14:54.627  7058  7236 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:14:54.627  7058  7236 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-01 11:14:54.627  7058  7236 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-01 11:14:54.627  7058  7236 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-01 11:14:54.627  7058  7236 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-01 11:14:54.627  7058  7236 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:14:54.637  7058  7236 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
09-01 11:14:54.637  7058  7236 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-01 11:14:54.637  7058  7236 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:14:54.637  7058  7236 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:14:54.637  7058  7236 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:14:54.637  7058  7236 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:14:54.637  7058  7236 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:14:54.637  7058  7236 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:14:54.637  7058  7236 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:14:54.637  7058  7236 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:14:54.637  7058  7236 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-01 11:14:54.637  7058  7236 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:14:54.647  7058  7236 I io.jxcore.node.LifeCycleMonitor: start: OK
09-01 11:14:54.647  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:14:54.647  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:14:54.667  7058  7058 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-01 11:14:55.177  6921  6921 I Mms/MmsApp:  start initViewCache mms
,09-01 11:14:55.177  6921  6921 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1938.507447
09-01 11:14:55.177  6921  6921 D Mms/ComposeMessageFragment: fillCache, easy = false
,09-01 11:14:55.237  7058  7244 W jxcore-log: Initializing JXcore engine
09-01 11:14:55.237  7058  7244 W jxcore-log: JXcore engine is ready
,09-01 11:14:55.277  6921  6921 D AbsListView: Get MotionRecognitionManager
,09-01 11:14:55.277  1019  1032 D MotionRecognitionService:  ssp status : false
,09-01 11:14:55.287  6921  6921 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 112.011042
,09-01 11:14:55.287  2010  2010 E audit   : type=1400 msg=audit(1472721295.287:205): avc:  denied  { ioctl } for  pid=7244 comm="Thread-1341" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-01 11:14:55.297  2010  2010 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051,
09-01 11:14:55.297  2010  2010 E audit   : type=1300 msg=audit(1472721295.287:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9cc658f8 items=0 ppid=324 ppcomm=main pid=7244 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1341" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
,09-01 11:14:55.297  2010  2010 E audit   : type=1320 msg=audit(1472721295.287:205): 
,09-01 11:14:55.307  7058  7244 W jxcore-log: Starting JXcore engine
,09-01 11:14:55.377  6921  6921 D Mms/BubbleViewCache: fillCache bubble = 1
,09-01 11:14:55.417  7058  7244 W jxcore-log: Platform android
09-01 11:14:55.417  7058  7244 W jxcore-log: 
09-01 11:14:55.417  7058  7244 W jxcore-log: Process ARCH arm
09-01 11:14:55.417  7058  7244 W jxcore-log: 
,09-01 11:14:55.617  7058  7244 I jxcore-log: JXcore Cordova bridge is ready!
09-01 11:14:55.617  7058  7244 I jxcore-log: 
,09-01 11:14:55.617  7058  7244 W jxcore-log: JXcore engine is started
,09-01 11:14:55.617  7058  7236 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-01 11:14:55.617  7058  7058 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-01 11:14:56.807   295   295 E SMD     : DCD OFF
,09-01 11:14:57.387  1019  3365 D SSRM:n  : SIOP:: AP = 410
,09-01 11:14:57.737  1688  1688 I ConfigService: onDestroy
,09-01 11:14:59.027  1019  3388 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-01 11:14:59.807   295   295 E SMD     : DCD OFF,
,09-01 11:14:59.997  1019  1100 V AlarmManager: waitForAlarm result :8,
,09-01 11:15:01.827  1019  1082 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-01 11:15:01.827  1019  1082 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-01 11:15:01.827  1019  1082 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-01 11:15:01.827  1019  1082 D BatteryService: stay LED for charging
09-01 11:15:01.827  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-01 11:15:01.827  1019  1019 I MotionRecognitionService: Plugged
,09-01 11:15:01.837  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,09-01 11:15:01.837  1183  1183 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-01 11:15:01.837  1183  1183 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-01 11:15:01.837  1424  1424 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-01 11:15:01.847  1424  1424 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-01 11:15:01.857  3228  3228 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-01 11:15:01.857  3228  3369 D HeadsetStateMachine: Disconnected process message: 10
,09-01 11:15:01.867  1183  1183 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-01 11:15:01.867  1183  1183 D SViewCoverView: level :100 plugged : 2
,09-01 11:15:01.867  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-01 11:15:01.867  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-01 11:15:01.867  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-01 11:15:02.807   295   295 E SMD     : DCD OFF,
,09-01 11:15:02.927  1019  1061 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,09-01 11:15:03.687  1019  1061 D PackageManager: [MSG] MCS_UNBIND
,09-01 11:15:03.697  1019  6683 I ActivityManager: Killing 6747:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,09-01 11:15:03.967  1019  1310 E Watchdog: !@Sync 3
,09-01 11:15:04.817   334   334 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-01 11:15:04.817   334   334 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-01 11:15:05.807   295   295 E SMD     : DCD OFF
,09-01 11:15:07.417  1019  3365 D SSRM:n  : SIOP:: AP = 380
,09-01 11:15:07.577  1019  1053 I PowerManagerService: [PWL] Off : 50s ago,
,09-01 11:15:07.837  1019  1100 V AlarmManager: waitForAlarm result :4,
09-01 11:15:07.837  1019  1100 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,09-01 11:15:07.847  1019  1019 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,09-01 11:15:07.857  1019  1019 V AlarmManagerEXT: <AppSync3 Whitelist>
,09-01 11:15:07.857  1019  1019 V AlarmManagerEXT: (AppSync) ### 0 added ###
,09-01 11:15:07.857  1183  1183 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-01 11:15:07.857  1183  1183 D KeyguardUpdateMonitor: handleTimeUpdate
,09-01 11:15:07.867  1183  1183 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-01 11:15:07.877  1183  1183 D SecKeyguardClockView: HomeTimezone(): 1
,09-01 11:15:07.887  1183  1183 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-01 11:15:07.887  1183  1183 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
09-01 11:15:07.887  1183  1183 I KeyguardEffectViewController: *** don't update sliding image ***
09-01 11:15:07.887  1183  1183 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,09-01 11:15:07.917  1183  1183 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-01 11:15:07.927  1183  1183 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-01 11:15:07.927  1183  1183 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-01 11:15:07.937  1183  1183 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-01 11:15:07.937  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-01 11:15:07.937  7058  7244 I jxcore-log: 
,09-01 11:15:07.947  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-01 11:15:07.947  7058  7244 I jxcore-log: 
,09-01 11:15:07.957  7058  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:15:07.957  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:07.957  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:07.957  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:07.957  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:07.957  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:07.957  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:15:07.957  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:15:07.957  7058  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 11:15:07.957  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-01 11:15:07.957  7058  7244 I jxcore-log: 
,09-01 11:15:07.957  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-01 11:15:07.957  7058  7244 I jxcore-log: 
,09-01 11:15:08.127  6905  7031 D Finsky  : [1304] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,09-01 11:15:08.127  6905  6905 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,09-01 11:15:08.627  7058  7244 D executeNativeTests: Running unit tests
,09-01 11:15:08.717  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:15:08.717  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23757470 added. We now have 2 listener(s)
,09-01 11:15:08.727  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-01 11:15:08.727  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:15:08.727  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:15:08.727  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:08.727  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 added. We now have 2 listener(s)
09-01 11:15:08.727  7058  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:15:08.727  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 11:15:08.727  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:15:08.737  7058  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:15:08.737  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:08.737  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:08.737  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:08.737  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:08.737  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:08.737  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:15:08.737  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:15:08.737  7058  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 11:15:08.737  7058  7244 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 11:15:08.737  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:08.737  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-01 11:15:08.737  7058  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 11:15:08.737  7058  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-01 11:15:08.737  7058  7244 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-01 11:15:08.737  7058  7244 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-01 11:15:08.737  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 11:15:08.737  7058  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 11:15:08.737  7058  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 11:15:08.737  7058  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 11:15:08.737  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:08.737  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 11:15:08.747  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 11:15:08.747  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:08.747  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 11:15:08.747  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-01 11:15:08.747  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23757470 removed from the list
09-01 11:15:08.747  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:08.747  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 removed from the list
,09-01 11:15:08.747  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:08.747  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:08.747  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:15:08.747  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:08.747  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:15:08.747  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 11:15:08.747  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 11:15:08.747  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:08.747  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:08.747  7058  7244 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-01 11:15:08.747  7058  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 11:15:08.747  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:08.747  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:08.747  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:08.747  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:08.747  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:15:08.747  7058  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23757470 not in the list
09-01 11:15:08.747  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:08.747  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:08.747  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:08.747  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:08.747  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:15:08.747  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:08.747  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:15:08.757  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:08.757  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:08.757  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 11:15:08.757  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
,09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910],
09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-01 11:15:08.757  7058  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:08.757  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:08.757  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:08.757  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:08.757  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:08.757  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:08.757  7058  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23757470 not in the list
,09-01 11:15:08.757  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:08.757  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:08.757  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:08.757  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:08.757  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:08.757  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:08.757  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:08.757  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:08.757  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 11:15:08.757  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:08.757  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:08.757  7058  7244 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-01 11:15:08.767  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:15:08.767  7058  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:15:08.767  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:08.767  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:08.767  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:08.767  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:08.767  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:08.767  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:15:08.767  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:15:08.767  7058  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:08.767  7058  7244 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 11:15:08.767  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-01 11:15:08.767  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:15:08.767  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-01 11:15:08.767  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:15:08.767  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:15:08.767  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:08.777  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:08.777  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,09-01 11:15:08.777  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-01 11:15:08.787  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,09-01 11:15:08.787  7058  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-01 11:15:08.787  7058  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-01 11:15:08.797  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-01 11:15:08.797  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 11:15:08.797  7058  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-01 11:15:08.797  3228  3393 D BtGatt.GattService: registerClient() - UUID=4541b581-0a19-4ffd-8a95-3d4bfa62dbca
,09-01 11:15:08.817   295   295 E SMD     : DCD OFF
,09-01 11:15:08.847  3228  3309 D BtGatt.GattService: onClientRegistered() - UUID=4541b581-0a19-4ffd-8a95-3d4bfa62dbca, clientIf=6
,09-01 11:15:08.847  7058  7071 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-01 11:15:08.847  3228  3246 D BtGatt.GattService: start scan with filters
,09-01 11:15:08.847  3228  3368 D BtGatt.ScanManager: handling starting scan
,09-01 11:15:08.847  3228  3368 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
,09-01 11:15:08.857  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-01 11:15:08.857  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 11:15:08.857  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-01 11:15:08.857  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-01 11:15:08.857  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 11:15:08.857  7058  7058 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 11:15:08.857  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-01 11:15:08.857  3228  3309 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-01 11:15:08.857  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:08.867  3228  3368 D BtGatt.ScanManager: allow scan with filters,
09-01 11:15:08.867  3228  3368 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-01 11:15:08.867  3228  3368 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
09-01 11:15:08.867  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-01 11:15:08.867  7058  7244 I io.jxcore.node.ConnectionHelper: start: OK
,09-01 11:15:08.867  3228  3309 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-01 11:15:08.867  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:08.867  3228  3368 D BtGatt.ScanManager: Starting BLE batch scan
,09-01 11:15:08.867  3228  3368 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-01 11:15:08.877  7058  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 11:15:08.877  7058  7244 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-01 11:15:08.877  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:08.877  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-01 11:15:08.877  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:08.877  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 11:15:08.877  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 11:15:08.877  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 11:15:08.877  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 11:15:08.877  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-01 11:15:08.877  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 11:15:08.877  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-01 11:15:08.877  3228  3309 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-01 11:15:08.877  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:08.877  3228  3392 D BtGatt.GattService: stopScan() - queue size =1
,09-01 11:15:08.877  3228  3393 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-01 11:15:08.887  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:15:08.887  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 11:15:08.887  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 11:15:08.887  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 11:15:08.887  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-01 11:15:08.887  3228  3309 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-01 11:15:08.887  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 11:15:08.887  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 11:15:08.887  3228  3368 D BtGatt.ScanManager: filter size is 1
,09-01 11:15:08.887  3228  3368 D BtGatt.ScanManager: delete FilterIndex - 3
,09-01 11:15:08.897  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-01 11:15:08.897  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 11:15:08.897  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-01 11:15:08.897  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 11:15:08.897  7058  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 11:15:08.897  7058  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 11:15:08.897  7058  7058 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:15:08.897  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:08.897  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:08.897  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:15:08.897  7058  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23757470 not in the list
09-01 11:15:08.897  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:08.897  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:08.897  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:08.897  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:08.897  7058  7244 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-01 11:15:08.897  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:15:08.897  3228  3309 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-01 11:15:08.897  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:08.897  3228  3368 D BtGatt.ScanManager: stopping BLe Batch
,09-01 11:15:08.907  7058  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:15:08.907  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:08.907  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:08.907  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:08.907  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:08.907  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:08.907  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:15:08.907  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:15:08.907  7058  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 11:15:08.907  7058  7244 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 11:15:08.907  3228  3309 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-01 11:15:08.907  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:08.907  3228  3368 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-01 11:15:08.917  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:15:08.917  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:15:08.917  3228  3309 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-01 11:15:08.917  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:15:08.917  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 11:15:08.917  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:15:08.917  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-01 11:15:08.917  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:08.917  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:08.917  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-01 11:15:08.917  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-01 11:15:08.927  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 11:15:08.927  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-01 11:15:08.927  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-01 11:15:08.927  7058  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-01 11:15:08.927  3228  3393 D BtGatt.GattService: registerClient() - UUID=39bb59ce-767d-45b4-8cd4-b5f91df35016
,09-01 11:15:08.967  3228  3309 D BtGatt.GattService: onClientRegistered() - UUID=39bb59ce-767d-45b4-8cd4-b5f91df35016, clientIf=6,
09-01 11:15:08.967  7058  7071 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-01 11:15:08.967  3228  3246 D BtGatt.GattService: start scan with filters
09-01 11:15:08.977  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-01 11:15:08.977  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
09-01 11:15:08.977  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-01 11:15:08.977  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-01 11:15:08.977  3228  3368 D BtGatt.ScanManager: handling starting scan
,09-01 11:15:08.977  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 11:15:08.977  7058  7058 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 11:15:08.977  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-01 11:15:08.977  3228  3309 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-01 11:15:08.977  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:08.977  3228  3368 D BtGatt.ScanManager: allow scan with filters
09-01 11:15:08.977  3228  3368 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-01 11:15:08.977  3228  3368 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-01 11:15:08.987  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,09-01 11:15:08.987  3228  3309 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-01 11:15:08.987  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:08.987  3228  3368 D BtGatt.ScanManager: Starting BLE batch scan
09-01 11:15:08.987  3228  3368 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-01 11:15:08.987  7058  7244 I io.jxcore.node.ConnectionHelper: start: OK
,09-01 11:15:08.997  7058  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 11:15:08.997  7058  7244 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-01 11:15:08.997  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-01 11:15:08.997  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-01 11:15:08.997  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:15:08.997  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 11:15:08.997  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-01 11:15:08.997  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 11:15:08.997  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-01 11:15:08.997  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-01 11:15:08.997  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 11:15:08.997  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-01 11:15:08.997  3228  3309 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-01 11:15:08.997  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:09.007  3228  3392 D BtGatt.GattService: stopScan() - queue size =1
,09-01 11:15:09.007  3228  3393 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-01 11:15:09.007  3228  3309 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-01 11:15:09.007  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:09.007  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:15:09.007  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 11:15:09.007  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 11:15:09.007  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-01 11:15:09.007  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-01 11:15:09.007  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 11:15:09.017  3228  3368 D BtGatt.ScanManager: filter size is 1,
09-01 11:15:09.017  3228  3368 D BtGatt.ScanManager: delete FilterIndex - 4
09-01 11:15:09.017  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-01 11:15:09.017  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 11:15:09.017  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-01 11:15:09.017  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 11:15:09.017  7058  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 11:15:09.017  7058  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 11:15:09.017  7058  7058 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:15:09.017  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:09.017  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.017  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:15:09.017  7058  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23757470 not in the list
09-01 11:15:09.017  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.017  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.017  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:09.017  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.017  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.017  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:15:09.017  3228  3309 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-01 11:15:09.017  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:09.017  3228  3368 D BtGatt.ScanManager: stopping BLe Batch
,09-01 11:15:09.017  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:09.017  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 11:15:09.017  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.017  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
,09-01 11:15:09.027  7058  7244 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-01 11:15:09.027  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:15:09.027  3228  3309 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-01 11:15:09.027  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:09.027  3228  3368 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-01 11:15:09.027  7058  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:15:09.027  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:09.027  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:09.027  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:09.027  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:09.027  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:09.027  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:15:09.027  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:15:09.037  3228  3309 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-01 11:15:09.037  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:09.037  7058  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 11:15:09.037  7058  7244 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 11:15:09.037  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:09.037  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:15:09.037  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:15:09.037  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:15:09.037  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:15:09.037  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-01 11:15:09.037  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-01 11:15:09.037  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-01 11:15:09.047  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-01 11:15:09.047  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 11:15:09.047  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-01 11:15:09.047  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 11:15:09.047  7058  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-01 11:15:09.047  3228  3246 D BtGatt.GattService: registerClient() - UUID=1aff44f9-4159-40ce-b1c6-4bef59185ffd
,09-01 11:15:09.087  3228  3309 D BtGatt.GattService: onClientRegistered() - UUID=1aff44f9-4159-40ce-b1c6-4bef59185ffd, clientIf=6
,09-01 11:15:09.097  7058  7066 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-01 11:15:09.097  3228  3242 D BtGatt.GattService: start scan with filters
,09-01 11:15:09.097  3228  3368 D BtGatt.ScanManager: handling starting scan
,09-01 11:15:09.097  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-01 11:15:09.097  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-01 11:15:09.097  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-01 11:15:09.097  3228  3309 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-01 11:15:09.097  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:09.097  3228  3368 D BtGatt.ScanManager: allow scan with filters
09-01 11:15:09.097  3228  3368 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-01 11:15:09.097  3228  3368 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-01 11:15:09.107  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-01 11:15:09.107  3228  3309 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-01 11:15:09.107  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:09.107  3228  3368 D BtGatt.ScanManager: Starting BLE batch scan
09-01 11:15:09.107  3228  3368 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-01 11:15:09.107  3228  3309 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-01 11:15:09.107  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:09.117  3228  3309 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-01 11:15:09.117  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:09.117  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 11:15:09.117  7058  7058 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 11:15:09.117  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-01 11:15:09.127  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-01 11:15:09.127  7058  7244 I io.jxcore.node.ConnectionHelper: start: OK
,09-01 11:15:09.127  7058  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 11:15:09.127  7058  7244 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-01 11:15:09.127  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:09.127  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-01 11:15:09.127  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.127  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 11:15:09.127  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-01 11:15:09.127  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 11:15:09.127  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 11:15:09.127  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-01 11:15:09.127  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 11:15:09.127  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-01 11:15:09.137  3228  3246 D BtGatt.GattService: stopScan() - queue size =1
,09-01 11:15:09.137  3228  3368 D BtGatt.ScanManager: filter size is 1
,09-01 11:15:09.137  3228  3368 D BtGatt.ScanManager: delete FilterIndex - 5
,09-01 11:15:09.137  3228  3242 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-01 11:15:09.137  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:15:09.137  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 11:15:09.137  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 11:15:09.137  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 11:15:09.137  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-01 11:15:09.137  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 11:15:09.137  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-01 11:15:09.137  3228  3309 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
09-01 11:15:09.137  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 11:15:09.147  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 11:15:09.147  3228  3368 D BtGatt.ScanManager: stopping BLe Batch
09-01 11:15:09.147  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-01 11:15:09.147  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 11:15:09.147  7058  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 11:15:09.147  7058  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:15:09.147  7058  7058 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 11:15:09.147  7058  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:09.147  7058  7244 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-01 11:15:09.147  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:09.147  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:09.147  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:09.147  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.147  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:15:09.147  7058  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23757470 not in the list
09-01 11:15:09.147  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.147  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.147  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:09.147  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.147  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.147  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:15:09.147  3228  3309 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-01 11:15:09.147  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:09.147  3228  3368 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-01 11:15:09.147  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 11:15:09.147  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:09.147  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 11:15:09.147  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
,09-01 11:15:09.157  7058  7244 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-01 11:15:09.157  7058  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 11:15:09.157  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-01 11:15:09.157  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:09.157  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:09.157  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.157  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.157  7058  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23757470 not in the list
09-01 11:15:09.157  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.157  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.157  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:09.157  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.157  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.157  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.157  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:15:09.157  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:09.157  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:09.157  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.157  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
,09-01 11:15:09.157  3228  3309 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-01 11:15:09.157  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:09.157  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-01 11:15:09.157  7058  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:09.157  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:09.157  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:09.157  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:09.157  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.157  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.157  7058  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23757470 not in the list
09-01 11:15:09.157  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.157  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.157  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:09.157  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.157  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.157  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.157  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:15:09.157  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:09.157  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:09.157  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.157  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
,09-01 11:15:09.157  7058  7244 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-01 11:15:09.157  7058  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:09.157  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:09.157  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:09.157  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:09.157  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.157  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.157  7058  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23757470 not in the list
09-01 11:15:09.157  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.157  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.157  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:09.157  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.157  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.157  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.157  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:15:09.157  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:09.157  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:09.157  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.157  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
,09-01 11:15:09.167  7058  7244 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-01 11:15:09.167  7058  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:09.167  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:09.167  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:09.167  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:09.167  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.167  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.167  7058  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23757470 not in the list
09-01 11:15:09.167  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.167  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.167  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:09.167  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.167  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.167  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.167  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:15:09.167  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:09.167  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-01 11:15:09.167  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.167  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.167  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-01 11:15:09.167  7058  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 11:15:09.167  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 11:15:09.167  7058  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 11:15:09.167  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-01 11:15:09.167  7058  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-01 11:15:09.167  7058  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:09.167  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:09.167  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:09.167  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:09.167  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:15:09.167  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.167  7058  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23757470 not in the list
09-01 11:15:09.167  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-01 11:15:09.167  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.167  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:09.167  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.167  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:15:09.167  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.167  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.167  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:09.167  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:09.167  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 11:15:09.167  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.167  7058  7244 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:15:09.167  7058  7244 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-01 11:15:09.167  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
09-01 11:15:09.167  7058  7244 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-01 11:15:09.167  7058  7244 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer,
,09-01 11:15:09.167  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010],
09-01 11:15:09.167  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-01 11:15:09.167  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-01 11:15:09.167  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-01 11:15:09.167  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-01 11:15:09.167  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510],
09-01 11:15:09.167  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-01 11:15:09.167  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-01 11:15:09.167  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-01 11:15:09.167  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-01 11:15:09.167  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-01 11:15:09.167  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-01 11:15:09.167  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210],
09-01 11:15:09.167  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-01 11:15:09.167  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-01 11:15:09.167  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-01 11:15:09.167  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-01 11:15:09.167  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-01 11:15:09.167  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-01 11:15:09.177  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-01 11:15:09.177  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-01 11:15:09.177  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-01 11:15:09.177  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-01 11:15:09.177  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-01 11:15:09.177  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-01 11:15:09.177  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-01 11:15:09.177  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-01 11:15:09.177  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-01 11:15:09.177  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-01 11:15:09.177  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-01 11:15:09.177  7058  7244 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-01 11:15:09.177  7058  7244 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 11:15:09.177  7058  7244 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-01 11:15:09.177  7058  7244 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:15:09.177  7058  7244 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 11:15:09.177  7058  7244 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-01 11:15:09.177  7058  7244 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:15:09.177  7058  7244 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 11:15:09.177  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-01 11:15:09.177  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-01 11:15:09.177  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-01 11:15:09.177  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-01 11:15:09.177  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-01 11:15:09.177  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-01 11:15:09.177  7058  7244 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-01 11:15:09.177  7058  7244 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 11:15:09.177  7058  7244 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-01 11:15:09.177  7058  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:09.177  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:09.177  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:09.177  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:09.177  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.177  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.177  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-01 11:15:09.177  7058  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1405)
09-01 11:15:09.177  7058  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23757470 not in the list
09-01 11:15:09.177  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.177  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.177  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:09.177  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.177  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.177  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.177  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.177  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:09.177  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:09.177  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.177  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.177  7058  7244 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-01 11:15:09.177  7058  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:09.177  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:09.177  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:09.177  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:09.177  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.177  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.177  7058  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23757470 not in the list
09-01 11:15:09.177  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.177  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.177  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:09.177  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.177  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.177  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.177  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.187  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:09.187  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:09.187  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.187  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.187  7058  7244 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-01 11:15:09.187  7058  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:09.187  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:09.187  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:09.187  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:09.187  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.187  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.187  7058  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23757470 not in the list
09-01 11:15:09.187  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.187  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.187  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:09.187  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.187  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.187  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.187  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.187  7058  7257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1405
09-01 11:15:09.187  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:09.187  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:09.187  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.187  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.187  7058  7244 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-01 11:15:09.187  7058  7244 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-01 11:15:09.187  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 11:15:09.187  7058  7244 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-01 11:15:09.187  7058  7244 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-01 11:15:09.187  7058  7244 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-01 11:15:09.187  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 11:15:09.187  7058  7244 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-01 11:15:09.187  7058  7244 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-01 11:15:09.187  7058  7244 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-01 11:15:09.187  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 11:15:09.187  7058  7244 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-01 11:15:09.187  7058  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:09.187  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:09.187  7058  7256 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-01 11:15:09.187  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:09.187  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:09.187  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.187  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.187  7058  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23757470 not in the list
09-01 11:15:09.187  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.187  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.187  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:09.187  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.187  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.187  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.187  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.187  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:09.187  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:09.187  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.187  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.187  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:09.187  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.187  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.187  7058  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23757470 not in the list
09-01 11:15:09.187  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.187  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.187  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:09.187  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.187  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.187  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.187  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.187  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:09.187  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.187  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.187  7058  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23757470 not in the list
09-01 11:15:09.187  7058  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:09.187  7058  7256 D BluetoothSocket: connect(): myUserId = 0
09-01 11:15:09.187  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:09.187  7058  7256 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:15:09.187  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:09.187  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:09.187  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.187  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.187  7058  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23757470 not in the list
09-01 11:15:09.187  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.187  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.187  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:09.187  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.187  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.187  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.187  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.187  3228  3246 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:15:09.197  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:09.197  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:09.197  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.197  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.197  7058  7256 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
09-01 11:15:09.197  7058  7244 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-01 11:15:09.197  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:15:09.197  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-01 11:15:09.197  7058  7244 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-01 11:15:09.197  7058  7244 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-01 11:15:09.197  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-01 11:15:09.197  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 11:15:09.197  7058  7058 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-01 11:15:09.197  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:09.197  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-01 11:15:09.197  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-01 11:15:09.197  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-01 11:15:09.197  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.197  7058  7244 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-01 11:15:09.197  7058  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23757470 not in the list
09-01 11:15:09.197  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.197  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 11:15:09.197  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 11:15:09.197  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 11:15:09.197  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.197  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.197  7058  7058 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-01 11:15:09.197  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:15:09.197  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.197  7058  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:09.207  7058  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:15:09.207  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:09.207  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:09.207  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:09.207  7058  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:15:09.207  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.207  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.207  7058  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23757470 not in the list
09-01 11:15:09.207  7058  7058 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:15:09.207  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.207  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.207  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:09.207  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.207  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.207  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.207  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.207  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:09.207  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:09.207  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.207  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.207  7058  7258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-01 11:15:09.207  7058  7258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-01 11:15:09.207  7058  7244 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-01 11:15:09.207  7058  7244 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-01 11:15:09.207  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 11:15:09.207  7058  7058 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-01 11:15:09.207  7058  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 11:15:09.207  7058  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:09.207  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:09.207  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:09.207  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:09.207  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.207  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.207  7058  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23757470 not in the list
09-01 11:15:09.207  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.207  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.207  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:09.207  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.207  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.207  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.207  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.207  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:09.207  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:09.207  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.207  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.207  7058  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:09.207  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:09.207  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:09.207  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:09.207  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.207  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.207  7058  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23757470 not in the list
09-01 11:15:09.207  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.207  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.207  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:09.207  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.207  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.207  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.207  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.207  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:09.207  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:09.207  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.207  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.217  7058  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:09.217  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:09.217  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:09.217  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:09.217  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.217  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.217  7058  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23757470 not in the list
09-01 11:15:09.217  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.217  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.217  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:09.217  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.217  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:09.217  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:09.217  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:15:09.217  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:09.217  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:09.217  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:09.217  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@211ce3e9 not in the list
09-01 11:15:09.217  7058  7244 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-01 11:15:09.217  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 11:15:09.217  7058  7244 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-01 11:15:09.217  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 11:15:09.217  7058  7244 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-01 11:15:09.217  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 11:15:09.217  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-01 11:15:09.217  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-01 11:15:09.217  7058  7244 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-01 11:15:09.217  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-01 11:15:09.217  7058  7244 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-01 11:15:09.217  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-01 11:15:09.217  7058  7244 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-01 11:15:09.217  7058  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-01 11:15:09.217  7058  7244 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-01 11:15:09.217  7058  7244 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-01 11:15:09.217  7058  7244 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-01 11:15:09.217  7058  7244 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-01 11:15:09.217  7058  7244 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-01 11:15:09.217  7058  7244 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-01 11:15:09.217  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:09.217  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a5162a3 added. We now have 2 listener(s)
09-01 11:15:09.217  7058  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:15:09.217  7058  7244 D BluetoothAdapter: enable()
09-01 11:15:09.227  7058  7244 D BluetoothAdapter: enable(): BT is already enabled..!
09-01 11:15:09.227  1019  1544 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-01 11:15:09.227  1019  1544 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-01 11:15:09.227  1019  1544 D SecContentProvider2: mCursor = null
09-01 11:15:09.227  1019  1544 D WifiService: setWifiEnabled: true pid=7058, uid=10170
09-01 11:15:09.227  1019  1544 W ActivityManager: Permission Denial: getCurrentUser() from pid=7058, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-01 11:15:09.227  1019  1544 W WifiService: Failed getting userId using ActivityManagerNative
09-01 11:15:09.227  1019  1544 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7058, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-01 11:15:09.227  1019  1544 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-01 11:15:09.227  1019  1544 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-01 11:15:09.227  1019  1544 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-01 11:15:09.227  1019  1544 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-01 11:15:09.227  1019  1544 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-01 11:15:09.227  1019  1544 D SettingsProvider: name = wifi_on
09-01 11:15:09.237  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:09.237  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1dc6d9a0 added. We now have 3 listener(s)
09-01 11:15:09.237  7058  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:15:09.237  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:09.237  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@35b99959 added. We now have 4 listener(s)
09-01 11:15:09.237  7058  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:15:09.237  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:09.237  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2095991e added. We now have 5 listener(s)
09-01 11:15:09.237  7058  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:15:09.237  1019  3288 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-01 11:15:09.237  1019  3288 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-01 11:15:09.237  1019  3288 D SecContentProvider2: mCursor = null
09-01 11:15:09.237  1019  3288 D WifiService: setWifiEnabled: false pid=7058, uid=10170
09-01 11:15:09.237  1019  3288 D SettingsProvider: name = wifi_on
09-01 11:15:09.247  1019  1132 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-01 11:15:09.247  7058  7244 D BluetoothAdapter: disable()
09-01 11:15:09.247  1019  1344 D SettingsProvider: name = bluetooth_on
09-01 11:15:09.247  1383  1383 I wpa_supplicant: reset timer : RESET_TIMER 0
09-01 11:15:09.247  1383  1383 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-01 11:15:09.257  1383  1383 I wpa_supplicant: P2P: Current p2p state = IDLE
09-01 11:15:09.257  1383  1383 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-01 11:15:09.257  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:15:09.257  3228  3306 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
09-01 11:15:09.257  1019  1082 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 11:15:09.257  3228  3306 D BluetoothAdapterProperties: Setting state to 13
09-01 11:15:09.257  1019  1082 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-01 11:15:09.257  3228  3306 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-01 11:15:09.257  3228  3306 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-01 11:15:09.257  3228  3306 D BluetoothAdapterService: updateAdapterState state is 13
,09-01 11:15:09.267  1383  1383 I wpa_supplicant: Scan aborted because the firmware maybe busy.
09-01 11:15:09.267  1383  1383 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
09-01 11:15:09.267  1383  1383 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
,09-01 11:15:09.267  1019  1082 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:09.267  1019  1082 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:09.267  1019  1082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:09.267  3228  3306 D BluetoothAdapterService: Autoconnection is available 
09-01 11:15:09.267  3228  3306 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-01 11:15:09.267  3228  3306 D BluetoothAdapterService: terminating service from this receiver
09-01 11:15:09.267  1019  1132 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 11:15:09.267  1019  1546 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-01 11:15:09.267  1019  1546 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:09.267  1019  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:09.267  1019  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:09.267  3228  3228 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-01 11:15:09.267  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:09.267  7058  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:15:09.267  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:09.267  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:09.267  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:09.267  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:09.267  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:09.267  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:15:09.267  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:15:09.267  3228  3228 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@205cc685, channel: 19, state: LISTENING
09-01 11:15:09.267  3228  3228 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@205cc685, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@e093f82, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1bdb3cdamSocket: android.net.LocalSocket@137f850b impl:android.net.LocalSocketImpl@19572fe8 fd:FileDescriptor[82]
,09-01 11:15:09.267  3228  3306 D BluetoothAdapterProperties: onBluetoothDisable()
09-01 11:15:09.267  3228  3306 D BluetoothAdapterProperties: mDiscovering is false
,09-01 11:15:09.267  1019  1490 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-01 11:15:09.267  3228  3228 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@137f850b impl:android.net.LocalSocketImpl@19572fe8 fd:FileDescriptor[82],
09-01 11:15:09.267  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 11:15:09.277  7058  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:09.277  3228  3306 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-01 11:15:09.277  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-01 11:15:09.277  7058  7244 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:15:09.277  1019  1019 I InputMethodManagerService: [BT Setting State] State =13
,09-01 11:15:09.277  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:09.277  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:09.277  1183  1183 D BluetoothTile:  onBluetoothStateChange:
,09-01 11:15:09.287  1183  1183 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED,
09-01 11:15:09.287  1183  1183 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-01 11:15:09.287  1183  1183 D BluetoothTile:  getBluetoothState : 13
,09-01 11:15:09.287  1019  1132 E WifiNative-wlan0: do suspend true
,09-01 11:15:09.287  1986  1986 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-01 11:15:09.287  1019  1505 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-01 11:15:09.287  1183  1729 D BluetoothTile:  handleUpdatestate:false name:null,
,09-01 11:15:09.287  1019  1032 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-01 11:15:09.287  1183  1183 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-01 11:15:09.297  1183  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 11:15:09.297  1183  1729 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-01 11:15:09.297  4723  4723 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:15:09.297  3228  3309 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-01 11:15:09.297  3228  3309 D BluetoothAdapterProperties: Scan Mode:20
,09-01 11:15:09.307  3228  3306 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-01 11:15:09.307  3228  3306 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
09-01 11:15:09.307  7058  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:09.307  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:09.307  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:09.307  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:09.307  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:09.307  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:09.307  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 11:15:09.307  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 11:15:09.307  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 11:15:09.307  3228  3306 E bt-btif : cmd socket is not created
,09-01 11:15:09.307  7058  7256 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@104fefcc, channel: -1, state: INIT
09-01 11:15:09.307  7058  7256 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@104fefcc, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10e17215, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@31fe292amSocket: android.net.LocalSocket@3a3e831b impl:android.net.LocalSocketImpl@1a723cb8 fd:FileDescriptor[106]
09-01 11:15:09.307  7058  7256 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3a3e831b impl:android.net.LocalSocketImpl@1a723cb8 fd:FileDescriptor[106]
09-01 11:15:09.307  3228  5235 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 11:15:09.307  7058  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1405)
,09-01 11:15:09.307  3228  3306 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-01 11:15:09.307  3228  3228 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@10284601, channel: 5, state: LISTENING
09-01 11:15:09.307  3228  3228 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@10284601, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@45c0acd, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@c404ca6mSocket: android.net.LocalSocket@3d1f66e7 impl:android.net.LocalSocketImpl@15636294 fd:FileDescriptor[80]
09-01 11:15:09.307  3228  3228 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3d1f66e7 impl:android.net.LocalSocketImpl@15636294 fd:FileDescriptor[80]
09-01 11:15:09.307  3228  3310 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
09-01 11:15:09.307  3228  3228 I BtOppRfcommListener: stopping Accept Thread
09-01 11:15:09.307  3228  3228 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@35d2413d, channel: 12, state: LISTENING
09-01 11:15:09.307  3228  3228 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@35d2413d, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@76b0ffc, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2c948d32mSocket: android.net.LocalSocket@24f18a83 impl:android.net.LocalSocketImpl@375e1400 fd:FileDescriptor[85]
09-01 11:15:09.307  3228  3228 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@24f18a83 impl:android.net.LocalSocketImpl@375e1400 fd:FileDescriptor[85]
,09-01 11:15:09.307  3228  5235 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-01 11:15:09.307  7058  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:09.307  7058  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 11:15:09.317  3228  3228 V BluetoothOppManager: cleanUp...
,09-01 11:15:09.317  3228  3310 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:15:09.317  3228  3310 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:15:09.317  3228  3310 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:15:09.317  3228  3310 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:15:09.317  3228  3310 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:15:09.317  3228  3310 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:15:09.317  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:09.317  4723  4723 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-01 11:15:09.317  1019  1545 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-01 11:15:09.317  1019  1545 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-01 11:15:09.317  1019  1545 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:09.317  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:09.317  1019  1545 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 11:15:09.317  1019  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-01 11:15:09.317  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:09.317  3228  3310 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
09-01 11:15:09.317  3228  3310 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
09-01 11:15:09.317  3228  3310 W bt-btif : invalid rfc slot id: 4
,09-01 11:15:09.327  4723  4723 D BluetoothPbap: Proxy object disconnected
09-01 11:15:09.327  4723  4723 D PbapServerProfile: Bluetooth service disconnected
,09-01 11:15:09.327  1688  1688 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 11:15:09.327  4723  4723 D DockEventReceiver: finishStartingService: stopping service
,09-01 11:15:09.337  4723  4723 D BluetoothNotiBroadcastReceiver: onReceive
,09-01 11:15:09.337  1183  1183 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:15:09.337  1183  1183 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-01 11:15:09.337  1019  6683 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-01 11:15:09.337  1019  1131 D WifiP2pService: InactiveState{ what=143375 },
09-01 11:15:09.337  1019  1131 D WifiP2pService: P2pEnabledState{ what=143375 }
09-01 11:15:09.337  1019  6683 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:09.337  1019  6683 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:09.337  1019  6683 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:09.337  1019  6683 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:09.357  7264  7264 E Zygote  : MountEmulatedStorage(),
09-01 11:15:09.357  7264  7264 E Zygote  : v2,
09-01 11:15:09.357  7264  7264 I libpersona: KNOX_SDCARD checking this for 10055
09-01 11:15:09.357  7264  7264 I libpersona: KNOX_SDCARD not a persona
09-01 11:15:09.357  1019  6683 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7264 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
,09-01 11:15:09.357  7264  7264 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-01 11:15:09.357   278  1013 D CommandListener: Clearing all IP addresses on wlan0
09-01 11:15:09.357  7264  7264 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 11:15:09.367  7264  7264 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-01 11:15:09.367  1688  2532 V NativeCrypto: Read error: ssl=0xb7b5b2e0: I/O error during system call, Connection timed out
,09-01 11:15:09.367  1688  2532 V NativeCrypto: SSL shutdown failed: ssl=0xb7b5b2e0: I/O error during system call, Broken pipe
,09-01 11:15:09.367  1019  1134 E ConnectivityService: updateNetworkInfo()
09-01 11:15:09.367  1019  1134 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 11:15:09.367  1019  1134 E ConnectivityService: updateNetworkInfo()
09-01 11:15:09.367  1019  1134 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
09-01 11:15:09.367  1183  1183 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 11:15:09.367  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-01 11:15:09.367  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:09.367  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:09.367  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:09.367  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:09.367  1019  1131 D WifiP2pService: InactiveState{ what=131204 }
09-01 11:15:09.367  1019  1131 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-01 11:15:09.367  1019  1131 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-01 11:15:09.367  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-01 11:15:09.377  1019  1132 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-01 11:15:09.377  1019  1082 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,09-01 11:15:09.377  1019  1765 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:15:09.377  1019  1765 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:15:09.377  1019  1765 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-01 11:15:09.377  1019  1765 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:15:09.377  1019  1765 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,09-01 11:15:09.377  1019  1765 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 11:15:09.387  1019  1765 I qtaguid : Tagging socket 347 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1019, getuid(): 1000
,09-01 11:15:09.387  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-01 11:15:09.387  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 11:15:09.387  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 11:15:09.387  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:09.397  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:09.397  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:09.397  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:09.397  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 1
09-01 11:15:09.397  1019  1019 D RttService: SCAN_AVAILABLE : 1
09-01 11:15:09.397  1019  1154 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:15:09.397  1019  1155 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 11:15:09.397  1019  1765 I qtaguid : Untagging socket 347
,09-01 11:15:09.397  1019  1765 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 11:15:09.397  1019  1051 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:15:09.397  1019  1051 D WifiDisplayAdapter: onP2pDisconnected
,09-01 11:15:09.407  1019  1131 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-01 11:15:09.407  1019  1131 D WifiP2pService: P2pDisablingState
09-01 11:15:09.407  1019  1131 D WifiP2pService: P2pDisablingState{ what=147458 }
09-01 11:15:09.407  1019  1131 D WifiP2pService: p2p socket connection lost
09-01 11:15:09.407  1019  1131 D WifiP2pService: P2pDisabledState
,09-01 11:15:09.407  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-01 11:15:09.407  1019  1132 E WifiNative-wlan0: do suspend true
09-01 11:15:09.407  1019  1051 D IpRemoteDisplayController: disconnectWfdBridgeServer
,09-01 11:15:09.407  1019  1051 D IpRemoteDisplayController: WfdBridgeServer is already null
09-01 11:15:09.407  1019  1051 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-01 11:15:09.407  1019  1051 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-01 11:15:09.407  1019  1051 D WifiDisplayController: disconnect
09-01 11:15:09.407  1019  1051 D WifiDisplayController: updateConnection
09-01 11:15:09.407  1019  1051 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-01 11:15:09.407  1019  1051 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-01 11:15:09.417  1019  1051 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,09-01 11:15:09.417  1019  1051 D WifiDisplayAdapter: onP2pDisconnected
09-01 11:15:09.417  1019  1051 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-01 11:15:09.417  1019  1051 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-01 11:15:09.417  7264  7264 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:09.417  1183  1183 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-01 11:15:09.427  7264  7264 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:09.427  1019  1317 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
09-01 11:15:09.427  1183  1183 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-01 11:15:09.447  1019  1131 D WifiP2pService: P2pDisabledState{ what=143375 }
09-01 11:15:09.447  1019  1131 D WifiP2pService: DefaultState{ what=143375 }
,09-01 11:15:09.447  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-01 11:15:09.447  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 11:15:09.447  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 11:15:09.447  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:09.447  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:09.447  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:09.447  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:09.457   278  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-01 11:15:09.457   278  1009 D Netd    : getNetworkForDns: using netid 0 for uid 1000
09-01 11:15:09.457   278  1013 D CommandListener: Clearing all IP addresses on wlan0
,09-01 11:15:09.457  1019  1134 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-01 11:15:09.457  1019  1134 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 11:15:09.457  1019  1134 V NetworkStats: updateIfacesLocked()
09-01 11:15:09.457  1019  1134 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 11:15:09.457  1019  1134 V NetworkStats: performPollLocked(flags=0x1)
09-01 11:15:09.457  1019  1134 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 11:15:09.467  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-01 11:15:09.467  1019  1134 V NetworkStats: performPollLocked() took 4ms
09-01 11:15:09.467  1019  1134 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:09.467  1383  1383 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-01 11:15:09.467  1019  1765 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-01 11:15:09.467  1019  1765 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-01 11:15:09.467  1019  1134 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,09-01 11:15:09.477  1019  1765 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:15:09.477  1019  1134 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:15:09.477  1183  1685 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-01 11:15:09.477  1019  1134 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-01 11:15:09.477  1019  1131 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-01 11:15:09.477  1019  1134 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-01 11:15:09.477  1467  1467 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-01 11:15:09.477  1019  1134 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-01 11:15:09.477  1467  1467 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-01 11:15:09.477  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit,
09-01 11:15:09.477  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 11:15:09.477  1019  1050 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-01 11:15:09.477  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 11:15:09.477  1019  1132 D SecContentProvider2: mCursor = null
,09-01 11:15:09.487  7264  7264 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
09-01 11:15:09.487  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-01 11:15:09.487  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 11:15:09.487  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 11:15:09.487  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:09.487  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:09.487  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:09.487  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:09.487  4723  4723 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-01 11:15:09.487  1019  1132 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-01 11:15:09.487  1019  1134 D ConnectivityService: nai.networkMonitor.doQuit()
09-01 11:15:09.487  1019  1134 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-01 11:15:09.487  1019  1134 E ConnectivityService: updateNetworkInfo()
09-01 11:15:09.487  1019  1134 E ConnectivityService: updateNetworkInfo()
09-01 11:15:09.487  1019  1134 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-01 11:15:09.497  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-01 11:15:09.497  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 11:15:09.497  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-01 11:15:09.497  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:09.497  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:09.497  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:09.497  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:09.497  1183  1183 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 11:15:09.497  1183  1183 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 11:15:09.497  1183  1183 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-01 11:15:09.497  1019  1019 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-01 11:15:09.497  1019  1135 D Tethering: MasterInitialState.processMessage what=3
,09-01 11:15:09.497  1183  1729 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-01 11:15:09.497  1183  1183 D HotspotTile: onReceive : 0, 0
,09-01 11:15:09.497  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:09.497  1019  1129 V NetworkStats: updateIfacesLocked()
09-01 11:15:09.497  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-01 11:15:09.497  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
09-01 11:15:09.497  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 11:15:09.497  1019  1050 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-01 11:15:09.497  7058  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:09.497  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:09.497  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:09.497  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:09.497  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:15:09.497  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:09.497  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:09.497  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:09.497  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 11:15:09.497  1183  1183 D StatusBar.NetworkController: EthernetConnected: false
09-01 11:15:09.497  1183  1183 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-01 11:15:09.497  1183  1183 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-01 11:15:09.497  1183  1183 D StatusBar.NetworkController: updateDataNetType()
,09-01 11:15:09.497  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:09.497  1019  1129 V NetworkStats: performPollLocked() took 6ms
09-01 11:15:09.507  7058  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:09.507  7058  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:15:09.507  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:09.507  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:09.507  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:09.507  1019  1130 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-01 11:15:09.507  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:09.507  7058  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:09.507  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:09.507  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:09.507  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:09.507  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:15:09.507  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:09.507  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:09.507  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:09.507  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:15:09.507  7058  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:09.507  7058  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:15:09.507  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 11:15:09.507  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 11:15:09.507  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-01 11:15:09.507  1183  1183 E StatusBar.NetworkController: updateLTEICONDataNetType:0,
,09-01 11:15:09.507  3228  3306 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-01 11:15:09.507  3228  3306 D BtConfig.SecureMode: isSecureModeOn:false
09-01 11:15:09.507  3228  3306 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-01 11:15:09.507  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
09-01 11:15:09.507  3228  3306 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
09-01 11:15:09.507  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-01 11:15:09.507  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-01 11:15:09.507  1183  1183 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-01 11:15:09.507  1183  1183 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 19 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-01 11:15:09.507  3228  3306 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-01 11:15:09.507  1183  1183 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-01 11:15:09.517  1019  1317 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 11:15:09.517  1019  1317 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-01 11:15:09.517  1183  1183 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
09-01 11:15:09.517  1019  1317 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:09.517  1019  1317 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:09.517  1019  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:09.517  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-01 11:15:09.517  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-01 11:15:09.517  3228  3306 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-01 11:15:09.517  3228  3228 D HeadsetService: Received stop request...Stopping profile...
09-01 11:15:09.517  1019  1484 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 11:15:09.517  1019  1484 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-01 11:15:09.517  1019  1484 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:09.517  1019  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:09.517  1019  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:09.517  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-01 11:15:09.517  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-01 11:15:09.517  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
,09-01 11:15:09.517  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-01 11:15:09.517  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 11:15:09.517  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-01 11:15:09.517  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:09.517  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:09.517  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:09.517  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:09.517  3228  3306 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-01 11:15:09.527  7264  7264 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
09-01 11:15:09.527  1019  6811 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 11:15:09.527  1019  6811 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-01 11:15:09.527  7264  7264 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-01 11:15:09.527  7264  7264 D UserAnalysis: Create SecureDbHelper
,09-01 11:15:09.527  1019  6811 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:09.527  1019  6811 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:09.527  1019  6811 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:09.527  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-01 11:15:09.527  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-01 11:15:09.527  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-01 11:15:09.527  3228  3306 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-01 11:15:09.527  3228  3228 D A2dpService: Received stop request...Stopping profile...
09-01 11:15:09.527  3228  3376 D A2dpStateMachine: Exit Disconnected: -1
09-01 11:15:09.527  4723  4723 D HeadsetProfile: Bluetooth service disconnected
,09-01 11:15:09.527  1019  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 11:15:09.527  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-01 11:15:09.537  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:09.537  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:09.537  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:09.537  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-01 11:15:09.537  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-01 11:15:09.537  3228  3306 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-01 11:15:09.537  1019  1317 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 11:15:09.537  1019  1317 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-01 11:15:09.537  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
,09-01 11:15:09.537  1019  1317 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:09.537  1019  1317 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 11:15:09.537  1019  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:09.537  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,09-01 11:15:09.537  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-01 11:15:09.547  3228  3306 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-01 11:15:09.547  1019  1019 D BluetoothA2dp: Proxy object disconnected
09-01 11:15:09.547  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-01 11:15:09.547  7264  7264 D IntelligenceServiceApplication: onCreate()
,09-01 11:15:09.547  1019  1545 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 11:15:09.547  1019  1545 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-01 11:15:09.547  1019  1545 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:09.547  1019  1545 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 11:15:09.547  1019  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:09.547  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-01 11:15:09.547  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-01 11:15:09.547  3228  3306 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-01 11:15:09.547  4723  4723 D BluetoothA2dp: Proxy object disconnected
,09-01 11:15:09.557  4723  4723 D A2dpProfile: Bluetooth service disconnected
09-01 11:15:09.557  1019  1484 I ActivityManager: Killing 6181:com.samsung.android.sm/1000 (adj 15): empty #21
,09-01 11:15:09.557  7264  7264 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-01 11:15:09.557  1019  1317 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 11:15:09.557  1019  1317 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-01 11:15:09.557  1019  1317 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:09.557  1019  1317 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:09.557  1019  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:09.557  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-01 11:15:09.557  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-01 11:15:09.557  3228  3306 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-01 11:15:09.557  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,09-01 11:15:09.557  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-01 11:15:09.557  3228  3306 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-01 11:15:09.557  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-01 11:15:09.557  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-01 11:15:09.567  3228  3306 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,09-01 11:15:09.567  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-01 11:15:09.567  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-01 11:15:09.567  1019  1505 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
09-01 11:15:09.567  3228  3306 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-01 11:15:09.567  3228  3306 D BluetoothAdapterState: Stopping profile services that were post enabled
09-01 11:15:09.567  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-01 11:15:09.567  3228  3228 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-01 11:15:09.567  3228  3228 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-01 11:15:09.567  7264  7264 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-01 11:15:09.567  3228  3228 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-01 11:15:09.567  3228  3228 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-01 11:15:09.567  3228  3228 D HidService: Received stop request...Stopping profile...
09-01 11:15:09.567  3228  3228 D HidService: Stopping Bluetooth HidService
09-01 11:15:09.567  3228  3228 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-01 11:15:09.567  3228  3228 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-01 11:15:09.567  3228  3228 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-01 11:15:09.567  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
,09-01 11:15:09.577  4723  4723 D BluetoothInputDevice: Proxy object disconnected
09-01 11:15:09.577  4723  4723 D HidProfile: Bluetooth service disconnected
,09-01 11:15:09.577  3228  3228 D HealthService: Received stop request...Stopping profile...
09-01 11:15:09.577  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
,09-01 11:15:09.577  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-01 11:15:09.577  3228  3228 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-01 11:15:09.577  3228  3228 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-01 11:15:09.577  3228  3228 D PanService: Received stop request...Stopping profile...
,09-01 11:15:09.577  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
,09-01 11:15:09.577  7264  7264 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-01 11:15:09.577  4723  4723 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-01 11:15:09.577  4723  4723 D PanProfile: Bluetooth service disconnected
09-01 11:15:09.577  3228  3228 D BluetoothA2dp: Proxy object disconnected
09-01 11:15:09.577  3228  3228 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-01 11:15:09.577  3228  3378 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-01 11:15:09.577  3228  3228 I GKI_LINUX: GKI_exit_task 2 done
09-01 11:15:09.577  3228  3228 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-01 11:15:09.577  1019  1019 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-01 11:15:09.577  3228  3228 D BluetoothMapService: Received stop request...Stopping profile...
,09-01 11:15:09.587  1383  1383 I wpa_supplicant: Blacklist: Clear (all) 
09-01 11:15:09.587  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
,09-01 11:15:09.587  4723  4723 D BluetoothMap: Proxy object disconnected
09-01 11:15:09.587  4723  4723 D MapProfile: Bluetooth service disconnected
,09-01 11:15:09.587  3228  3228 D SapService: Received stop request...Stopping profile...
09-01 11:15:09.587  3228  3228 D SapService: Stopping Bluetooth SapService
09-01 11:15:09.587  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
,09-01 11:15:09.587  1019  1545 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-01 11:15:09.587  1019  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:09.587  1019  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:09.587  1019  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:09.587  1019  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:09.597  7287  7287 E Zygote  : MountEmulatedStorage(),
09-01 11:15:09.597  7287  7287 I libpersona: KNOX_SDCARD checking this for 10105
09-01 11:15:09.597  7287  7287 E Zygote  : v2
,09-01 11:15:09.597  7287  7287 I libpersona: KNOX_SDCARD not a persona
09-01 11:15:09.607  7287  7287 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 11:15:09.607  7287  7287 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 11:15:09.607  1019  1545 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7287 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-01 11:15:09.607  7287  7287 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-01 11:15:09.607  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-01 11:15:09.607  3228  3228 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-01 11:15:09.607  3228  3228 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 11:15:09.607  3228  3228 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-01 11:15:09.607  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-01 11:15:09.607  3228  3228 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-01 11:15:09.607  3228  3228 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 11:15:09.607  3228  3228 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-01 11:15:09.607  3228  3228 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-01 11:15:09.607  3228  3228 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-01 11:15:09.607  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-01 11:15:09.607  3228  3228 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-01 11:15:09.607  3228  3228 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 11:15:09.607  3228  3228 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-01 11:15:09.607  3228  3228 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-01 11:15:09.607  3228  3228 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-01 11:15:09.607  4723  4723 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-01 11:15:09.607  4723  4723 D SapProfile: Bluetooth service disconnected
,09-01 11:15:09.617  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-01 11:15:09.617  3228  3228 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-01 11:15:09.617  3228  3228 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-01 11:15:09.617  3228  3228 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-01 11:15:09.617  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-01 11:15:09.617  3228  3228 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-01 11:15:09.617  3228  3228 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-01 11:15:09.617  3228  3228 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-01 11:15:09.617  3228  3306 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-01 11:15:09.617  3228  3306 D BluetoothAdapterProperties: Setting state to 10
09-01 11:15:09.617  3228  3306 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-01 11:15:09.617  3228  3306 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-01 11:15:09.617  3228  3306 D BluetoothAdapterService: updateAdapterState state is 10
,09-01 11:15:09.617  3228  3306 D BluetoothAdapterService: Autoconnection is available 
09-01 11:15:09.617  3228  3393 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-01 11:15:09.617  3228  3306 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-01 11:15:09.617  3228  3306 I BluetoothAdapterState: Entering OffState
,09-01 11:15:09.627  1688  1706 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 11:15:09.627  1688  1706 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 11:15:09.627  4723  4732 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-01 11:15:09.627  4723  7261 D Bluetoothsap: onBluetoothStateChange: up=false
,09-01 11:15:09.627  4723  7261 D Bluetoothsap: Unbinding service...
,09-01 11:15:09.627  4723  4731 D BluetoothPbap: onBluetoothStateChange: up=false
,09-01 11:15:09.627  1019  1050 D BluetoothAdapter: onBluetoothStateChange: up=false,
09-01 11:15:09.627  1019  1050 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-01 11:15:09.627  4723  4732 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-01 11:15:09.637  1443  7285 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 11:15:09.637  1443  7285 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 11:15:09.637  3228  3246 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 11:15:09.637  3228  3246 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-01 11:15:09.637  1183  1212 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-01 11:15:09.637  1183  1212 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 11:15:09.647  1467  1467 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 11:15:09.647  1467  3339 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-01 11:15:09.647  1467  3339 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-01 11:15:09.647  1458  1478 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 11:15:09.647  1458  1478 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-01 11:15:09.647  1019  1050 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 11:15:09.647  7058  7066 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 11:15:09.647  7058  7066 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-01 11:15:09.647  7058  7066 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-01 11:15:09.647  7058  7066 D BluetoothLeAdvertiser: Exit stop advertising
09-01 11:15:09.647  7058  7066 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-01 11:15:09.647  7058  7066 D BluetoothLeScanner: Exiting stopAllScan
,09-01 11:15:09.647  1467  1467 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-01 11:15:09.647  1467  1467 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-01 11:15:09.647  1696  1705 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 11:15:09.647  1696  1705 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 11:15:09.647  1467  1467 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-01 11:15:09.647  4723  4731 D BluetoothMap: onBluetoothStateChange: up=false
09-01 11:15:09.647  4723  4732 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 11:15:09.647  4723  4732 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-01 11:15:09.647  7287  7287 D TimaKeyStoreProvider: TimaSignature is unavailable
09-01 11:15:09.647  1467  1467 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-01 11:15:09.647  7287  7287 D ActivityThread: Added TimaKeyStore provider
09-01 11:15:09.647  1467  1467 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-01 11:15:09.647  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:15:09.647  1467  1467 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-01 11:15:09.647  1019  1019 I InputMethodManagerService: [BT Setting State] State =10
09-01 11:15:09.647  1019  1019 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-01 11:15:09.657  1467  1467 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-01 11:15:09.657  1467  1467 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 11:15:09.657  1467  1467 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-01 11:15:09.657  1467  1467 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 11:15:09.657  1467  1467 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-01 11:15:09.657  1183  1183 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-01 11:15:09.657  1467  1467 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-01 11:15:09.657  1183  1183 D BluetoothTile:  getBluetoothState : 10
09-01 11:15:09.657  1183  1183 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:15:09.657  1986  1986 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
09-01 11:15:09.657  1467  1467 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-01 11:15:09.657  1467  1467 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 11:15:09.667  1019  1484 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-01 11:15:09.667  4723  4723 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:15:09.667  1467  1467 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-01 11:15:09.667  1019  1505 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-01 11:15:09.667  1467  1467 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 11:15:09.667  1183  1183 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-01 11:15:09.677  1183  1183 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-01 11:15:09.677  7058  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:09.677  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:09.677  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:09.677  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:09.677  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:15:09.677  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:09.677  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:09.677  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:09.677  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:15:09.677  1467  1467 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-01 11:15:09.677  1467  1467 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 11:15:09.677  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:09.677  1383  1383 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-01 11:15:09.677  1019  1048 D Tethering: interfaceLinkStateChanged p2p0, false
09-01 11:15:09.677  1019  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-01 11:15:09.677  1019  1048 D Tethering: interfaceStatusChanged p2p0, false
,09-01 11:15:09.677  1467  1467 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-01 11:15:09.677  1467  1467 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 11:15:09.687  1467  1467 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-01 11:15:09.687  1467  1467 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 11:15:09.687  1467  1467 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-01 11:15:09.687  1467  1467 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 11:15:09.687  1467  1467 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-01 11:15:09.687  1467  1467 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 11:15:09.687  1467  1467 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-01 11:15:09.687  1467  1467 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 11:15:09.687  1467  1467 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-01 11:15:09.697  1383  1383 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-01 11:15:09.707  1383  1383 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-01 11:15:09.707  1383  1383 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-01 11:15:09.707  1383  1383 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-01 11:15:09.707  1383  1383 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-01 11:15:09.707  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-01 11:15:09.707  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 11:15:09.707  1019  1048 D Tethering: interfaceStatusChanged wlan0, false,
09-01 11:15:09.707  1019  1135 D Tethering: InitialState.processMessage what=4
09-01 11:15:09.707  7058  7058 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-01 11:15:09.707  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 11:15:09.707  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 11:15:09.707  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
,09-01 11:15:09.707  1019  1135 E Tethering: No numeric data
,09-01 11:15:09.707  1019  1135 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-01 11:15:09.707  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
,09-01 11:15:09.707  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 11:15:09.707  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 11:15:09.707  1183  1183 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-01 11:15:09.707  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-01 11:15:09.707  1183  1183 D HotspotTile: updateTetherState():false, false
,09-01 11:15:09.707  1019  1135 D Tethering: clearTetheredNotification()
09-01 11:15:09.717  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 11:15:09.717  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 11:15:09.717  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
09-01 11:15:09.717  1019  1129 V NetworkStats: performPollLocked() took 5ms
09-01 11:15:09.717  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 11:15:09.717  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 11:15:09.717  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 11:15:09.777   257   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-01 11:15:09.777   257   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 11:15:09.777  7287  7320 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-01 11:15:09.787   257   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-01 11:15:09.787   257   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 11:15:09.787  7287  7320 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-01 11:15:09.817   334   334 I ServiceManager: Waiting for service AtCmdFwd...
,09-01 11:15:09.867  1383  1383 I wpa_supplicant: Blacklist: Clear (all) 
,09-01 11:15:09.927  7287  7287 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.io.File.exists(File.java:363)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-01 11:15:09.927  7287  7287 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 11:15:09.927  7287  7287 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 11:15:09.927  7287  7287 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.q.e.b(PG:170)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09,-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 11:15:09.927  7287  7287 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.q.k.d(PG:583)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.q.e.b(PG:170)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 11:15:09.927  7287  7287 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.io.File.exists(File.java:363)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 11:15:09.927  7287  7287 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.io.File.exists(File.java:363)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 11:15:09.927  7287  7287 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 11:15:09.927  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 11:15:09.937  1019  6811 I ActivityManager: Killing 6777:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
09-01 11:15:09.937  1019  1490 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 11:15:09.937  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-01 11:15:09.937  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:09.937  1019  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:09.937  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-01 11:15:09.937  1635  1635 I Hs20UtilService: Starting #8
09-01 11:15:09.947  1635  1673 I Hs20UtilService: Message received 5007
09-01 11:15:09.947  4723  4723 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-01 11:15:09.947  4723  4723 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-01 11:15:09.957  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-01 11:15:09.957  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-01 11:15:09.957  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-01 11:15:09.957  4723  4723 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-01 11:15:09.957  4723  4806 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-01 11:15:09.967  1019  6811 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:09.967  1019  6811 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 11:15:09.967  1019  6811 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
09-01 11:15:09.967  1019  6811 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
09-01 11:15:09.967  1383  1383 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-01 11:15:09.967  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 11:15:09.967  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 11:15:09.967  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
09-01 11:15:09.967  1019  6811 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:09.967  1019  6811 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:09.967  1019  6811 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:09.967  1019  6811 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:09.987  7331  7331 E Zygote  : MountEmulatedStorage()
09-01 11:15:09.987  7331  7331 I libpersona: KNOX_SDCARD checking this for 10102
09-01 11:15:09.987  7331  7331 E Zygote  : v2
09-01 11:15:09.987  7331  7331 I libpersona: KNOX_SDCARD not a persona
09-01 11:15:09.987  7331  7331 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-01 11:15:09.987  1019  6811 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7331 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-01 11:15:09.987  7331  7331 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 11:15:09.987  7331  7331 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-01 11:15:09.987  1019  1134 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-01 11:15:09.997  1019  1019 I ApplicationPolicy: updateDataUsageMap
09-01 11:15:09.997  7287  7330 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-01 11:15:10.017  7331  7331 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:10.017  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:10.017  7331  7331 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:10.027  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:10.047  7331  7331 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-01 11:15:10.047  1019  1045 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:15:10.077  1019  1132 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-01 11:15:10.077  1019  1132 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-01 11:15:10.087  1696  2181 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 11:15:10.087  4723  4723 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-01 11:15:10.097  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-01 11:15:10.097  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 11:15:10.097  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-01 11:15:10.097  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:10.097  1183  1183 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 11:15:10.097  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:10.097  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:10.097  1183  1729 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-01 11:15:10.097  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:10.097  1183  1183 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 11:15:10.097  1183  1183 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-01 11:15:10.097  1183  1183 D HotspotTile: onReceive : 1, 0
,09-01 11:15:10.097  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:10.097  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:10.227  1019  1490 I art     : Explicit concurrent mark sweep GC freed 47165(2MB) AllocSpace objects, 12(240KB) LOS objects, 33% free, 23MB/34MB, paused 2.393ms total 171.538ms
,09-01 11:15:10.227  1019  1317 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 11:15:10.227  1019  1317 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:10.227  1019  1317 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 11:15:10.227  1019  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-01 11:15:10.397  7331  7354 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-01 11:15:10.397  7331  7354 I Babel_SMS: MmsConfig.loadMmsSettings
09-01 11:15:10.397  7331  7354 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
09-01 11:15:10.397  7331  7354 I Babel_SMS: MmsConfig.loadFromDatabase
,09-01 11:15:10.417  7331  7354 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-01 11:15:10.417  7331  7354 I Babel_SMS: MmsConfig.loadFromResources
,09-01 11:15:10.427  7331  7354 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-01 11:15:10.427  7331  7354 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-01 11:15:10.437  1019  1032 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,09-01 11:15:10.437  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-01 11:15:10.437  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:10.437  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 11:15:10.437  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-01 11:15:10.457  7331  7331 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 11:15:10.457  7331  7331 I Babel_Crash: startup - clean
,09-01 11:15:10.497  4723  4723 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-01 11:15:10.497  4723  4723 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-01 11:15:10.497  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-01 11:15:10.497  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-01 11:15:10.497  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-01 11:15:10.497  4723  4723 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-01 11:15:10.497  7331  7331 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-01 11:15:10.497  4723  4806 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 11:15:10.497  1019  1544 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-01 11:15:10.507  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:10.507  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:10.507  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:10.507  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:10.507  7331  7331 W AudioCapabilities: Unsupported mime audio/evrc,
,09-01 11:15:10.507  7331  7331 W AudioCapabilities: Unsupported mime audio/qcelp
09-01 11:15:10.507  7331  7331 W AudioCapabilities: Unsupported mime audio/mpeg-L1
09-01 11:15:10.507  7331  7331 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-01 11:15:10.517  7357  7357 E Zygote  : MountEmulatedStorage()
,09-01 11:15:10.517  7357  7357 E Zygote  : v2,
09-01 11:15:10.517  7357  7357 I libpersona: KNOX_SDCARD checking this for 10064
09-01 11:15:10.517  7357  7357 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-01 11:15:10.517  7357  7357 I libpersona: KNOX_SDCARD not a persona
09-01 11:15:10.517  7331  7331 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-01 11:15:10.517  1019  1544 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7357 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-01 11:15:10.517  7331  7331 W AudioCapabilities: Unsupported mime audio/x-ima
09-01 11:15:10.517  7331  7331 W AudioCapabilities: Unsupported mime audio/qcelp
,09-01 11:15:10.527  7331  7331 W AudioCapabilities: Unsupported mime audio/evrc,
,09-01 11:15:10.527  7357  7357 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-01 11:15:10.527  7357  7357 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 11:15:10.537  7331  7331 W VideoCapabilities: Unsupported mime video/wvc1,
,09-01 11:15:10.537  7331  7331 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-01 11:15:10.547  7357  7357 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:10.547  7331  7331 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
09-01 11:15:10.547  7357  7357 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:10.547  7331  7331 W VideoCapabilities: Unsupported mime video/wvc1
,09-01 11:15:10.557  7331  7331 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-01 11:15:10.557  7331  7331 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-01 11:15:10.557  7331  7331 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-01 11:15:10.567  7331  7331 W VideoCapabilities: Unsupported mime video/mp43
,09-01 11:15:10.567  7357  7357 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-01 11:15:10.567  7331  7331 W VideoCapabilities: Unsupported mime video/sorenson
,09-01 11:15:10.577  7331  7331 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-01 11:15:10.587  7357  7357 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
09-01 11:15:10.587  7357  7357 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-01 11:15:10.597  7331  7331 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-01 11:15:10.617  7357  7357 D FileShare-Client: Outbound.stopDelayTimer - ,
09-01 11:15:10.617  1019  1546 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-01 11:15:10.617  1019  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:10.617  1019  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:10.617  1019  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:10.617  1019  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:10.617  7331  7331 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-01 11:15:10.627  7331  7331 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-01 11:15:10.627  7331  7331 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-01 11:15:10.627  7331  7331 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,09-01 11:15:10.637  7372  7372 E Zygote  : MountEmulatedStorage()
,09-01 11:15:10.637  7372  7372 E Zygote  : v2
09-01 11:15:10.637  7372  7372 I libpersona: KNOX_SDCARD checking this for 10065
09-01 11:15:10.637  7372  7372 I libpersona: KNOX_SDCARD not a persona
,09-01 11:15:10.637  7372  7372 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 11:15:10.637  7372  7372 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 11:15:10.637  1019  1546 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7372 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-01 11:15:10.637  7372  7372 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-01 11:15:10.637  1019  1546 I ActivityManager: Killing 6826:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,09-01 11:15:10.637  7331  7331 I vclib   : onServiceConnected
09-01 11:15:10.637  1019  1546 I ActivityManager: Killing 6816:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,09-01 11:15:10.657  7372  7372 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:10.657  7372  7372 D ActivityThread: Added TimaKeyStore provider,
,09-01 11:15:10.677  7372  7372 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-01 11:15:10.687  1019  1484 I ActivityManager: Killing 6884:com.sec.pcw.device/1000 (adj 15): empty #21
,09-01 11:15:10.687  1019  1048 D Tethering: interfaceRemoved wlan0
09-01 11:15:10.687  1019  1048 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-01 11:15:10.687  1019  1544 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 11:15:10.687  1019  1544 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 11:15:10.687  1019  1544 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:10.687  1019  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:10.687  1019  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 11:15:10.697  1635  1635 I Hs20UtilService: Starting #9
,09-01 11:15:10.697  1635  1673 I Hs20UtilService: Message received 5007
,09-01 11:15:10.697  4723  4723 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-01 11:15:10.697  4723  4723 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-01 11:15:10.697  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-01 11:15:10.697  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-01 11:15:10.697  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-01 11:15:10.697  4723  4723 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-01 11:15:10.697  4723  4806 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 11:15:10.707  1019  1317 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-01 11:15:10.707  1019  1317 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 11:15:10.707  1019  1317 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:10.707  1019  1317 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:10.707  1019  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 11:15:10.707  1635  1635 I Hs20UtilService: Starting #10
,09-01 11:15:10.707  1019  1544 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
09-01 11:15:10.707  1635  1673 I Hs20UtilService: Message received 5011
,09-01 11:15:10.707  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:10.707  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:10.707  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:10.707  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:10.727  7387  7387 E Zygote  : MountEmulatedStorage(),
,09-01 11:15:10.727  1019  1544 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7387 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
09-01 11:15:10.727  7387  7387 E Zygote  : v2
09-01 11:15:10.727  7387  7387 I libpersona: KNOX_SDCARD checking this for 1000
09-01 11:15:10.727  7387  7387 I libpersona: KNOX_SDCARD not a persona
,09-01 11:15:10.737  7387  7387 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 11:15:10.737  7387  7387 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 11:15:10.737  7387  7387 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-01 11:15:10.757   324   324 I art     : Explicit concurrent mark sweep GC freed 8703(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 25.798ms
,09-01 11:15:10.757  7387  7387 D TimaKeyStoreProvider: TimaSignature is unavailable
09-01 11:15:10.757  7387  7387 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:10.767   324   324 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 16.354ms
,09-01 11:15:10.787   324   324 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 639us total 18.078ms,
,09-01 11:15:10.797  7387  7387 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-01 11:15:10.797  7387  7387 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-01 11:15:10.797  7387  7387 D SecurityLogAgent: StateMachine : Current State = 1
,09-01 11:15:10.797  7387  7387 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-01 11:15:10.797  1019  1031 I ActivityManager: Killing 6794:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,09-01 11:15:10.807  1019  1484 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:10.807  1019  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:10.807  1019  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 11:15:10.807  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:10.807  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:10.807  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 11:15:10.817  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:10.817  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:10.817  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 11:15:10.817   334   334 I ServiceManager: Waiting for service AtCmdFwd...
,09-01 11:15:10.827  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:10.827  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:10.827  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 11:15:10.827  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:10.827  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:10.827  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 11:15:10.827  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:10.827  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:10.827  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 11:15:10.827  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:10.827  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:10.827  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system,
,09-01 11:15:10.837  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:10.837  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 11:15:10.837  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 11:15:10.837  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:10.837  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 11:15:10.837  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 11:15:10.847  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:10.847  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 11:15:10.847  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 11:15:10.847  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:10.847  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:10.847  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 11:15:10.847  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:10.847  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:10.847  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 11:15:10.857  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:10.857  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:10.857  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
09-01 11:15:10.857  1019  1048 D Tethering: interfaceRemoved p2p0
09-01 11:15:10.857  1019  1048 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-01 11:15:10.857  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:10.857  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:10.857  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 11:15:10.857  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:10.857  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:10.857  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 11:15:10.867  4723  4723 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-01 11:15:10.867  1019  6811 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-01 11:15:10.867  1019  6811 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-01 11:15:10.867  1019  6811 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:10.867  1019  6811 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:10.867  1019  6811 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-01 11:15:10.877  4723  4723 D DockEventReceiver: finishStartingService: stopping service
,09-01 11:15:10.877  1688  1688 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 11:15:10.877  4723  4723 D BluetoothNotiBroadcastReceiver: onReceive
,09-01 11:15:10.887  1183  1183 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:15:10.887  1183  1183 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-01 11:15:10.897  1019  1484 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-01 11:15:10.897  1019  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:10.897  1019  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:10.897  1019  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:10.897  1019  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:10.907  7405  7405 E Zygote  : MountEmulatedStorage()
09-01 11:15:10.907  7405  7405 E Zygote  : v2
09-01 11:15:10.907  7405  7405 I libpersona: KNOX_SDCARD checking this for 1000
09-01 11:15:10.907  7405  7405 I libpersona: KNOX_SDCARD not a persona
,09-01 11:15:10.907  7405  7405 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-01 11:15:10.907  1019  1484 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7405 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-01 11:15:10.917  7405  7405 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 11:15:10.917  7405  7405 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 11:15:10.937  7405  7405 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:10.937  7405  7405 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:10.957  7405  7405 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-01 11:15:10.957  7405  7405 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,09-01 11:15:10.957  7405  7405 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-01 11:15:10.977  7405  7405 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-01 11:15:10.977  7405  7405 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-01 11:15:10.977  7405  7405 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,09-01 11:15:10.977  7405  7405 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:15:10.977  1019  1545 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,09-01 11:15:10.977  1019  1545 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
09-01 11:15:10.977  1019  1545 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
09-01 11:15:10.977  1019  1545 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,09-01 11:15:10.987  7405  7420 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-01 11:15:10.987  1019  1545 I ActivityManager: Killing 6956:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,09-01 11:15:10.987  1019  1019 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-01 11:15:10.997  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:10.997  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:10.997  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:10.997  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:11.007  7422  7422 E Zygote  : MountEmulatedStorage()
,09-01 11:15:11.007  7422  7422 E Zygote  : v2
09-01 11:15:11.007  7422  7422 I libpersona: KNOX_SDCARD checking this for 10001
09-01 11:15:11.007  7422  7422 I libpersona: KNOX_SDCARD not a persona
,09-01 11:15:11.007  7422  7422 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 11:15:11.017  1019  1019 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7422 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-01 11:15:11.017  7422  7422 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 11:15:11.017  7422  7422 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 11:15:11.027  7422  7422 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:11.027  7422  7422 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:11.107  1019  1317 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-01 11:15:11.107  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:11.107  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:11.107  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:11.107  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:11.127  7439  7439 E Zygote  : MountEmulatedStorage(),
09-01 11:15:11.127  7439  7439 E Zygote  : v2
09-01 11:15:11.127  7439  7439 I libpersona: KNOX_SDCARD checking this for 1000,
09-01 11:15:11.127  7439  7439 I libpersona: KNOX_SDCARD not a persona
09-01 11:15:11.127  7439  7439 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 11:15:11.127  7439  7439 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-01 11:15:11.127  1019  1317 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7439 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-01 11:15:11.127  7439  7439 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-01 11:15:11.127  1019  1317 I ActivityManager: Killing 6982:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,09-01 11:15:11.157  7439  7439 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:11.157  7439  7439 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:11.197  7439  7439 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-01 11:15:11.317  7439  7439 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-01 11:15:11.327  7439  7439 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-01 11:15:11.327  7439  7439 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:15:11.327  7439  7439 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-01 11:15:11.327  7439  7439 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-01 11:15:11.327  7439  7439 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-01 11:15:11.337  1019  1031 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-01 11:15:11.337  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:11.337  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:11.337  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:11.337  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:11.347  7454  7454 E Zygote  : MountEmulatedStorage()
,09-01 11:15:11.347  7454  7454 I libpersona: KNOX_SDCARD checking this for 10008
09-01 11:15:11.347  7454  7454 E Zygote  : v2
09-01 11:15:11.347  7454  7454 I libpersona: KNOX_SDCARD not a persona
09-01 11:15:11.347  7454  7454 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-01 11:15:11.347  7454  7454 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 11:15:11.347  7454  7454 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-01 11:15:11.357  1019  1031 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7454 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-01 11:15:11.357  1019  1031 I ActivityManager: Killing 7008:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21,
,09-01 11:15:11.367  7454  7454 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:11.367  7454  7454 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:11.427  1019  6811 I ActivityManager: Killing 7038:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,09-01 11:15:11.427  1019  1032 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
09-01 11:15:11.427  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-01 11:15:11.437  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:11.437  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 11:15:11.437  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-01 11:15:11.447  1876  1876 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-01 11:15:11.447  1876  2800 I iu.UploadsManager: num queued entries: 0
,09-01 11:15:11.457  1876  2800 I iu.UploadsManager: num updated entries: 0
09-01 11:15:11.457  1019  3288 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-01 11:15:11.457  1019  3288 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,09-01 11:15:11.457  1876  2800 I iu.SyncManager: NEXT; no task
09-01 11:15:11.457  1019  3288 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:11.457  1019  3288 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 11:15:11.457  1019  3288 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 11:15:11.467  1876  1876 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-01 11:15:11.467  1876  1876 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,09-01 11:15:11.477  2804  2804 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Sep 01 11:15:11 GMT+02:00 2016
,09-01 11:15:11.477  1019  1505 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-01 11:15:11.477  1019  1505 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-01 11:15:11.477  1019  1505 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:11.487  1019  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:11.487  1019  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-01 11:15:11.487  2804  2804 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-01 11:15:11.497  1019  1082 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-01 11:15:11.497  1019  1082 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:11.497  1019  1082 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:11.497  1019  1082 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:11.497  1019  1082 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:11.507  2804  2804 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-01 11:15:11.517  2804  2804 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true,
,09-01 11:15:11.517  7471  7471 E Zygote  : MountEmulatedStorage(),
09-01 11:15:11.527  7471  7471 E Zygote  : v2
09-01 11:15:11.527  1019  1082 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7471 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
09-01 11:15:11.527  7471  7471 I libpersona: KNOX_SDCARD checking this for 10031
09-01 11:15:11.527  7471  7471 I libpersona: KNOX_SDCARD not a persona
09-01 11:15:11.527  7471  7471 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-01 11:15:11.527  2804  2804 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-01 11:15:11.527  7471  7471 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 11:15:11.527  7471  7471 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 11:15:11.527  2804  7470 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) },
,09-01 11:15:11.537  2804  7470 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-01 11:15:11.537  2804  7470 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-01 11:15:11.547  2804  7470 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-01 11:15:11.547  2804  2804 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-01 11:15:11.547  7471  7471 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:11.547  7471  7471 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:11.587  1019  1132 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-01 11:15:11.587  7471  7471 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-01 11:15:11.597  1019  1031 I ActivityManager: Killing 6921:com.android.mms/u0a41 (adj 15): empty #21
,09-01 11:15:11.607  1019  1545 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-01 11:15:11.607  1019  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:11.607  1019  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:11.617  1019  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:11.617  1019  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:11.617  2742  7486 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-01 11:15:11.617  2742  7486 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-01 11:15:11.627  2742  7486 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable,
09-01 11:15:11.627  2742  7486 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
09-01 11:15:11.627  2742  7486 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-01 11:15:11.627  1019  1545 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7487 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-01 11:15:11.637  7487  7487 E Zygote  : MountEmulatedStorage()
,09-01 11:15:11.637  7487  7487 E Zygote  : v2
09-01 11:15:11.637  7487  7487 I libpersona: KNOX_SDCARD checking this for 10032
09-01 11:15:11.637  7487  7487 I libpersona: KNOX_SDCARD not a persona
,09-01 11:15:11.637  7487  7487 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 11:15:11.637  7487  7487 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 11:15:11.637  7487  7487 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-01 11:15:11.667  7487  7487 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:11.667  7487  7487 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:11.727  1019  1032 D CountryDetector: No listener is left
,09-01 11:15:11.727  7487  7502 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
09-01 11:15:11.727  7487  7502 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-01 11:15:11.727  7487  7487 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-01 11:15:11.727  1019  1082 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,09-01 11:15:11.727  1019  1082 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:11.727  7487  7502 D SPPClientService: PushLog.txt file is not deleted.
09-01 11:15:11.727  7487  7502 D SPPClientService: PushLog.txt file is not deleted.
09-01 11:15:11.727  7487  7502 D SPPClientService: ============PushLog. stop!
09-01 11:15:11.727  1019  1082 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:11.737  1019  1082 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:11.737  1019  1082 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:11.747  7504  7504 E Zygote  : MountEmulatedStorage()
09-01 11:15:11.747  1019  1082 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7504 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-01 11:15:11.747  7504  7504 E Zygote  : v2,
09-01 11:15:11.747  1019  1032 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-01 11:15:11.747  7504  7504 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-01 11:15:11.747  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0,
09-01 11:15:11.747  7504  7504 I libpersona: KNOX_SDCARD checking this for 10036
09-01 11:15:11.747  7504  7504 I libpersona: KNOX_SDCARD not a persona
,09-01 11:15:11.757  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:11.757  1019  1032 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-01 11:15:11.757  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
09-01 11:15:11.757  7504  7504 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 11:15:11.757  7504  7504 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,09-01 11:15:11.777  7504  7504 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:11.777  7504  7504 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:11.797  7487  7513 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-01 11:15:11.807  1019  1545 I ActivityManager: Killing 7086:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,09-01 11:15:11.817   295   295 E SMD     : DCD OFF
,09-01 11:15:11.827  7504  7504 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@248400c2
09-01 11:15:11.837   334   334 I ServiceManager: Waiting for service AtCmdFwd...
,09-01 11:15:11.837  7504  7504 I SA      : [SSP] onCreated
,09-01 11:15:11.847  7504  7504 I SA      : [TPM] There is no property file
,09-01 11:15:11.857  7504  7504 I SA      : [SCU] isHaveSA() - false
,09-01 11:15:11.857  7504  7504 I SA      : [TPM] getModelProperty : null
09-01 11:15:11.857  7504  7504 I SA      : [TPM] getCSCProperty : null
,09-01 11:15:11.857  7504  7504 I SA      : [DM] FLOATING AMOLED FEATURE: true
09-01 11:15:11.857  7504  7504 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-01 11:15:11.857  7504  7504 I SA      : [DM] TFT FEATURE: false
,09-01 11:15:11.857  7504  7504 I SA      : [DM] init START
,09-01 11:15:11.867  7504  7504 I SA      : [DM] This device is not a Vodafone
,09-01 11:15:11.867  7504  7504 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,09-01 11:15:11.867  7504  7504 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,09-01 11:15:11.867  7504  7504 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
09-01 11:15:11.867  7504  7504 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
09-01 11:15:11.867  7504  7504 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
09-01 11:15:11.867  7504  7504 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
09-01 11:15:11.867  7504  7504 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
09-01 11:15:11.877  7504  7504 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-01 11:15:11.877  7504  7504 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,09-01 11:15:11.877  7504  7504 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,09-01 11:15:11.877  7504  7504 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,09-01 11:15:11.877  7504  7504 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,09-01 11:15:11.877  7504  7504 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
09-01 11:15:11.877  7504  7504 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,09-01 11:15:11.877  7504  7504 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
09-01 11:15:11.877  7504  7504 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,09-01 11:15:11.877  7504  7504 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
09-01 11:15:11.877  7504  7504 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,09-01 11:15:11.877  7504  7504 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,09-01 11:15:11.877  7504  7504 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
09-01 11:15:11.877  7504  7504 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-01 11:15:11.877  7504  7504 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
09-01 11:15:11.877  7504  7504 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,09-01 11:15:11.877  7504  7504 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
09-01 11:15:11.877  7504  7504 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
09-01 11:15:11.877  7504  7504 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
09-01 11:15:11.877  7504  7504 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
09-01 11:15:11.877  7504  7504 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-01 11:15:11.887  1019  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-01 11:15:11.887  7504  7504 I SA      : [SCU] isHaveSA() - false
09-01 11:15:11.887  7504  7504 I SA      : support phone number id : false
09-01 11:15:11.887  7504  7504 I SA      : [DM] Supports Ref Jpn : true
,09-01 11:15:11.887  7504  7504 I SA      : [DM] init END
,09-01 11:15:11.887  7504  7504 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-01 11:15:11.887  1019  1031 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-01 11:15:11.887  1019  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-01 11:15:11.887  1019  1031 D BatteryService: stay LED for charging
,09-01 11:15:11.887  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-01 11:15:11.887  7504  7504 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-01 11:15:11.887  7504  7504 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-01 11:15:11.897  1019  1019 I MotionRecognitionService: Plugged
,09-01 11:15:11.897  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,09-01 11:15:11.897  7504  7504 I SA      : [SLFUCHKMGR] constructor called
,09-01 11:15:11.897  1183  1183 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-01 11:15:11.897  1183  1183 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-01 11:15:11.907  1424  1424 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-01 11:15:11.907  1424  1424 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-01 11:15:11.907  7504  7504 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-01 11:15:11.907  7504  7504 I SA      : [OR] == isSIMCardReady false ==
,09-01 11:15:11.917  7504  7504 I SA      : [SCU] == networkStateCheck == false
,09-01 11:15:11.917  7504  7504 I SA      : [OR] onReceive END
,09-01 11:15:11.917  1019  1317 I ActivityManager: Killing 7097:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,09-01 11:15:11.917  1234  1234 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:15:11.927  1183  1183 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-01 11:15:11.927  1183  1183 D SViewCoverView: level :100 plugged : 2
,09-01 11:15:11.927  1829  1829 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-01 11:15:11.927  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-01 11:15:11.927  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-01 11:15:11.927  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-01 11:15:11.937  2675  2685 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,09-01 11:15:11.937  1829  1829 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-01 11:15:11.937  1829  1829 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
09-01 11:15:11.937  1829  1829 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,09-01 11:15:11.937  1829  1829 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-01 11:15:11.947  1829  1829 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-01 11:15:11.947  1829  1829 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-01 11:15:11.947  1019  1031 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-01 11:15:11.947  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:11.947  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:11.947  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:11.947  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:11.967  1019  1031 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7526 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
09-01 11:15:11.967  7526  7526 E Zygote  : MountEmulatedStorage()
09-01 11:15:11.967  7526  7526 I libpersona: KNOX_SDCARD checking this for 10077
09-01 11:15:11.967  7526  7526 E Zygote  : v2
09-01 11:15:11.967  7526  7526 I libpersona: KNOX_SDCARD not a persona
,09-01 11:15:11.967  7526  7526 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 11:15:11.977  7526  7526 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-01 11:15:11.977  7526  7526 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL,
,09-01 11:15:11.997  7526  7526 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:11.997  7526  7526 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:12.207  1019  6683 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-01 11:15:12.207  1019  6683 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-01 11:15:12.207  1019  6683 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:12.207  1019  6683 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 11:15:12.207  1019  6683 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-01 11:15:12.217  1019  6811 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-01 11:15:12.217  1019  6811 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:12.217  1019  6811 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:12.217  1019  6811 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:12.217  1019  6811 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:12.237  1019  6811 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7546 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-01 11:15:12.237  7546  7546 E Zygote  : MountEmulatedStorage()
09-01 11:15:12.237  7546  7546 E Zygote  : v2
09-01 11:15:12.237  7546  7546 I libpersona: KNOX_SDCARD checking this for 10110,
09-01 11:15:12.237  7546  7546 I libpersona: KNOX_SDCARD not a persona
09-01 11:15:12.237  7546  7546 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 11:15:12.237  1019  3288 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk,
09-01 11:15:12.237  1019  3288 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-01 11:15:12.237  1019  3288 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:12.237  7546  7546 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 11:15:12.237  1019  3288 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 11:15:12.237  1019  3288 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-01 11:15:12.237  7546  7546 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-01 11:15:12.247  7331  7545 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-01 11:15:12.257  1019  1082 I ActivityManager: Killing 7120:com.wsomacp/u0a23 (adj 15): empty #21
,09-01 11:15:12.267  7546  7546 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:12.267  7546  7546 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:12.277  1019  1031 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-01 11:15:12.277  1019  1031 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-01 11:15:12.277  1019  1031 D SecContentProvider2: mCursor = null
,09-01 11:15:12.277  1019  1031 D WifiService: setWifiEnabled: true pid=7058, uid=10170
,09-01 11:15:12.277  1019  1031 W ActivityManager: Permission Denial: getCurrentUser() from pid=7058, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-01 11:15:12.277  1019  1031 W WifiService: Failed getting userId using ActivityManagerNative
09-01 11:15:12.277  1019  1031 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7058, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-01 11:15:12.277  1019  1031 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-01 11:15:12.277  1019  1031 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-01 11:15:12.277  1019  1031 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-01 11:15:12.277  1019  1031 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-01 11:15:12.277  1019  1031 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-01 11:15:12.277  1019  1031 D SettingsProvider: name = wifi_on
,09-01 11:15:12.287  1019  1132 E WifiHW  : ##################### set firmware type 0 #####################
,09-01 11:15:12.447  1019  3288 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-01 11:15:12.487  1019  1100 V AlarmManager: waitForAlarm result :4
,09-01 11:15:12.587  7546  7546 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-01 11:15:12.587  7546  7546 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-01 11:15:12.587  7546  7546 I GAv4    :   adb logcat -s GAv4
,09-01 11:15:12.597   257   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-01 11:15:12.597   257   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 11:15:12.597  7546  7572 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-01 11:15:12.607   257   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-01 11:15:12.607   257   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 11:15:12.607  7546  7572 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-01 11:15:12.607  7546  7546 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-01 11:15:12.607  1019  1082 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-01 11:15:12.617   257   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-01 11:15:12.617   257   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 11:15:12.617  7546  7574 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-01 11:15:12.617   257   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-01 11:15:12.617   257   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 11:15:12.617  7546  7574 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-01 11:15:12.637  7546  7546 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-01 11:15:12.637  7546  7575 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-01 11:15:12.657  1019  1048 D Tethering: interfaceAdded wlan0
,09-01 11:15:12.667  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 11:15:12.667  1019  1135 E Tethering: No numeric data
,09-01 11:15:12.667  1019  1135 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-01 11:15:12.667  1019  1135 D Tethering: clearTetheredNotification()
09-01 11:15:12.667  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false,
09-01 11:15:12.667  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
09-01 11:15:12.667  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
09-01 11:15:12.667  1019  1135 D Tethering: InitialState.processMessage what=4
09-01 11:15:12.667  1183  1183 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-01 11:15:12.667  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:12.667  1183  1183 D HotspotTile: updateTetherState():false, false,
09-01 11:15:12.667  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 11:15:12.667  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 11:15:12.677   278  1013 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-01 11:15:12.677   278  1013 D SoftapController: Softap fwReload - Ok
,09-01 11:15:12.677  1019  1135 E Tethering: No numeric data
,09-01 11:15:12.677  1019  1135 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-01 11:15:12.677  1019  1135 D Tethering: clearTetheredNotification()
09-01 11:15:12.677  1019  1129 V NetworkStats: performPollLocked() took 12ms
09-01 11:15:12.677  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:12.677  1019  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-01 11:15:12.677  1019  1048 D Tethering: interfaceLinkStateChanged p2p0, false
09-01 11:15:12.677  1019  1048 D Tethering: interfaceStatusChanged p2p0, false
,09-01 11:15:12.677  1019  1048 D Tethering: interfaceAdded p2p0
,09-01 11:15:12.677   278  1013 D CommandListener: Setting iface cfg
,09-01 11:15:12.677   278  1013 D CommandListener: Trying to bring down wlan0
09-01 11:15:12.677  1183  1183 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-01 11:15:12.677  1019  1048 D Tethering: p2p0 is not a tetherable iface, ignoring
09-01 11:15:12.677  1183  1183 D HotspotTile: updateTetherState():false, false
09-01 11:15:12.677   278  1013 D CommandListener: Clearing all IP addresses on wlan0
,09-01 11:15:12.687  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:12.687  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
09-01 11:15:12.687  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit,
09-01 11:15:12.687  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:12.687  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 11:15:12.687  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 11:15:12.687  1019  1132 E WifiHW  : supplicant_name : p2p_supplicant
09-01 11:15:12.687  1019  1129 V NetworkStats: performPollLocked() took 3ms
09-01 11:15:12.687  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 11:15:12.687  1019  1132 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
09-01 11:15:12.687  1019  1132 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-01 11:15:12.697  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-01 11:15:12.697  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 11:15:12.697  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-01 11:15:12.697  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-01 11:15:12.697  1183  1183 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
09-01 11:15:12.697  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:12.697  1183  1729 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-01 11:15:12.697  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:12.697  1183  1183 D HotspotTile: onReceive : 2, 0
09-01 11:15:12.697  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:12.697  1183  1183 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 11:15:12.697  1183  1183 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-01 11:15:12.707  4723  4723 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-01 11:15:12.707  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:12.707  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:12.707  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 11:15:12.707  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:12.767  7577  7577 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
09-01 11:15:12.767  7577  7577 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-01 11:15:12.777  7577  7577 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-01 11:15:12.797  7577  7577 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-01 11:15:12.807   403   403 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7577
09-01 11:15:12.807   403   403 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
09-01 11:15:12.807  7577  7577 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-01 11:15:12.807  7577  7577 I wpa_supplicant: ssSupport state is = 1
09-01 11:15:12.807  7577  7577 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-01 11:15:12.807  7577  7577 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-01 11:15:12.807   403   403 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7577
,09-01 11:15:12.807   403   403 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,09-01 11:15:12.837   334   334 I ServiceManager: Waiting for service AtCmdFwd...
,09-01 11:15:12.967  1019  3288 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 11:15:12.967  1019  3288 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:12.967  1019  3288 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 11:15:12.967  1019  3288 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-01 11:15:12.997  7546  7546 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-01 11:15:13.007   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,09-01 11:15:13.007  7546  7546 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 7116-7119)
,09-01 11:15:13.017  7546  7546 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-01 11:15:13.017  7577  7577 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed,
,09-01 11:15:13.047  7546  7546 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {205cc685},
09-01 11:15:13.047  7546  7546 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-01 11:15:13.047  7546  7546 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-01 11:15:13.067  7546  7546 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-01 11:15:13.067  7546  7546 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-01 11:15:13.067  7577  7577 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-01 11:15:13.067  7577  7577 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-01 11:15:13.067  7546  7546 E SysUtils: ApplicationContext is null in ApplicationStatus,
,09-01 11:15:13.077  7577  7577 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-01 11:15:13.077   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7577
09-01 11:15:13.077   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-01 11:15:13.077  7577  7577 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-01 11:15:13.077  7577  7577 I wpa_supplicant: ssSupport state is = 1
,09-01 11:15:13.087  7577  7577 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-01 11:15:13.087  7577  7577 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-01 11:15:13.087  7577  7577 E wpa_supplicant: SIM READ ERROR
09-01 11:15:13.087  7577  7577 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 11:15:13.087  7577  7577 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-01 11:15:13.087  7577  7577 E wpa_supplicant: SIM READ ERROR
09-01 11:15:13.087  7577  7577 I wpa_supplicant: Blacklist: Clear (all) 
09-01 11:15:13.087  7577  7577 I wpa_supplicant: wpa_default_ap_write_once
09-01 11:15:13.087  7577  7577 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-01 11:15:13.087  7577  7577 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 11:15:13.087  7577  7577 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-01 11:15:13.087  7577  7577 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 11:15:13.087  7577  7577 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-01 11:15:13.087  7577  7577 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-01 11:15:13.087  7546  7546 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
,09-01 11:15:13.087  7546  7546 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-01 11:15:13.087  7546  7546 I Adreno-EGL: Build Date: 04/06/15 Mon
09-01 11:15:13.087  7546  7546 I Adreno-EGL: Local Branch: 
09-01 11:15:13.087  7546  7546 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-01 11:15:13.087  7546  7546 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-01 11:15:13.087  7546  7546 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
09-01 11:15:13.087  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 11:15:13.087  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 11:15:13.087  1019  1048 D Tethering: interfaceStatusChanged wlan0, false,
,09-01 11:15:13.157  7546  7546 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-01 11:15:13.157  7546  7607 W cr.media: Requires BLUETOOTH permission
,09-01 11:15:13.167  7577  7577 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-01 11:15:13.167  7546  7546 I NSApplication: Starting up...
,09-01 11:15:13.167  1019  6683 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-01 11:15:13.177  1019  1544 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-01 11:15:13.177  1019  6811 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-01 11:15:13.177  1019  6811 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:13.177  1019  6811 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:13.177  1019  6811 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:13.177  1019  6811 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:13.197  7612  7612 E Zygote  : MountEmulatedStorage(),
09-01 11:15:13.197  7612  7612 E Zygote  : v2
09-01 11:15:13.197  7612  7612 I libpersona: KNOX_SDCARD checking this for 10117
09-01 11:15:13.197  7612  7612 I libpersona: KNOX_SDCARD not a persona
,09-01 11:15:13.197  7612  7612 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 11:15:13.197  1019  6811 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7612 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-01 11:15:13.197  7612  7612 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 11:15:13.197  1019  6811 I ActivityManager: Killing 7137:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
09-01 11:15:13.197  7612  7612 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-01 11:15:13.227  7612  7612 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:13.227  7612  7612 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:13.237  7612  7612 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-01 11:15:13.407  7577  7577 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-01 11:15:13.417  7577  7577 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-01 11:15:13.427  7577  7577 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-01 11:15:13.427   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7577
09-01 11:15:13.427   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,09-01 11:15:13.427  7577  7577 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-01 11:15:13.427  7577  7577 I wpa_supplicant: ssSupport state is = 1
,09-01 11:15:13.427  7577  7577 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-01 11:15:13.427  7577  7577 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-01 11:15:13.437  7577  7577 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-01 11:15:13.437   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7577
09-01 11:15:13.437   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,09-01 11:15:13.437  7577  7577 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-01 11:15:13.437  7577  7577 I wpa_supplicant: ssSupport state is = 1
,09-01 11:15:13.437  7577  7577 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-01 11:15:13.437  7577  7577 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-01 11:15:13.447  1019  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-01 11:15:13.437  7577  7577 E wpa_supplicant: SIM READ ERROR
09-01 11:15:13.447  1019  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-01 11:15:13.437  7577  7577 I wpa_supplicant: wpa_default_ap_write_once
09-01 11:15:13.437  7577  7577 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
09-01 11:15:13.437  7577  7577 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-01 11:15:13.447  1019  1048 D Tethering: interfaceLinkStateChanged p2p0, false
09-01 11:15:13.447  1019  1048 D Tethering: interfaceStatusChanged p2p0, false
09-01 11:15:13.447  1019  1048 D Tethering: interfaceLinkStateChanged p2p0, false
09-01 11:15:13.447  1019  1048 D Tethering: interfaceStatusChanged p2p0, false
,09-01 11:15:13.497  5889  5889 D FactoryTest: Not factory mode
09-01 11:15:13.497  5889  5889 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-01 11:15:13.497  5889  5889 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
09-01 11:15:13.497  5889  5889 D MTPRx   : still no open session command from host, so toast
,09-01 11:15:13.497  5889  5889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,09-01 11:15:13.497  5889  5889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,09-01 11:15:13.507  5889  5889 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:117610
,09-01 11:15:13.507  1019  1505 E PersonaManagerService: inState():  stateMachine is null !!
,09-01 11:15:13.507  1019  1505 I PersonaManagerService: PersonaId don't exist
,09-01 11:15:13.507  1019  1505 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-01 11:15:13.507  1019  1505 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-01 11:15:13.507  1019  1505 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:13.507  1019  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:13.507  1019  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-01 11:15:13.517  1019  1505 W ActivityManager: mDVFSHelper.acquire()
,09-01 11:15:13.547  1019  1505 D PersonaManager: isKioskContainerExistOnDevice
,09-01 11:15:13.547  7577  7577 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-01 11:15:13.547  7577  7577 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-01 11:15:13.557  1019  1505 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-01 11:15:13.557  1019  1505 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-01 11:15:13.557  1019  1505 D InputDispatcher: Focused application set to: xxxx
,09-01 11:15:13.557  1019  1505 D InputDispatcher: Focus left window: 7058
,09-01 11:15:13.557  5889  5889 E MTPRx   : started activity for popup
,09-01 11:15:13.557  1019  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-01 11:15:13.557  1019  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-01 11:15:13.597  5889  5889 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,09-01 11:15:13.597  5889  5889 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-01 11:15:13.597  5889  5889 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-01 11:15:13.597  5889  5889 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 11:15:13.597  5889  5889 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-01 11:15:13.597  5889  5889 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-01 11:15:13.637  7577  7577 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-01 11:15:13.637  7577  7577 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-01 11:15:13.637  7577  7577 I wpa_supplicant: Skip scan - bUseNetwork false
,09-01 11:15:13.647  1019  6683 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast,
09-01 11:15:13.647  1019  6683 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:13.647  1019  6683 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:13.647  1019  6683 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:13.647  1019  6683 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:13.657  5889  5889 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-01 11:15:13.657  7637  7637 E Zygote  : MountEmulatedStorage()
,09-01 11:15:13.657  7637  7637 E Zygote  : v2
09-01 11:15:13.657  7637  7637 I libpersona: KNOX_SDCARD checking this for 10121
09-01 11:15:13.657  7637  7637 I libpersona: KNOX_SDCARD not a persona
09-01 11:15:13.667  1019  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-01 11:15:13.667  1019  1048 D Tethering: interfaceLinkStateChanged p2p0, false
09-01 11:15:13.667  1019  1048 D Tethering: interfaceStatusChanged p2p0, false
09-01 11:15:13.667  1019  6683 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7637 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,09-01 11:15:13.667  1019  6683 I ActivityManager: Killing 7171:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
09-01 11:15:13.667  7637  7637 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 11:15:13.667  7637  7637 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 11:15:13.667  7637  7637 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 11:15:13.677  1019  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
09-01 11:15:13.677  1019  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-01 11:15:13.677  1019  1031 D InputDispatcher: Focused application set to: xxxx
09-01 11:15:13.677  1019  1031 D InputDispatcher: Focus entered window: 7058
,09-01 11:15:13.677  1019  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-01 11:15:13.677  1019  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-01 11:15:13.687  1019  3288 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-01 11:15:13.687  1019  3288 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@38d863e0 attribute=null, token = android.os.BinderProxy@d205451
,09-01 11:15:13.697  1019  1132 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-01 11:15:13.697  1019  1132 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-01 11:15:13.697  7577  7577 I wpa_supplicant: HOTSPOT20_ENABLE called
09-01 11:15:13.697  7577  7577 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 11:15:13.697  7577  7577 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-01 11:15:13.697  7577  7577 E wpa_supplicant: SIM READ ERROR
09-01 11:15:13.697  7577  7577 I wpa_supplicant: Blacklist: Clear (all) 
09-01 11:15:13.697   324   324 I art     : Explicit concurrent mark sweep GC freed 8684(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 641us total 32.436ms
,09-01 11:15:13.707  7577  7577 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-01 11:15:13.707  7637  7637 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-01 11:15:13.707  7637  7637 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:13.717   324   324 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 576us total 19.438ms
,09-01 11:15:13.727  7577  7577 I wpa_supplicant: Skip scan - bUseNetwork false
09-01 11:15:13.727  1019  1132 D WifiConfigStore: Loading config and enabling all networks 
,09-01 11:15:13.737  7637  7637 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 11:15:13.737  7637  7637 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-01 11:15:13.737  7637  7637 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-01 11:15:13.737   324   324 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 17.839ms
,09-01 11:15:13.747  4723  4723 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-01 11:15:13.757  7058  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:13.757  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:13.757  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:13.757  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:13.757  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:13.757  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:13.757  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:13.757  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:13.757  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:15:13.757  7058  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:13.757  7058  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:15:13.757  1019  1132 E WifiConfigStore: Not a HS20
,09-01 11:15:13.757  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-01 11:15:13.757  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 11:15:13.757  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 11:15:13.757  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:13.757  7058  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:13.757  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:13.757  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:13.757  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:13.757  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:13.757  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:13.757  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:13.757  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:13.757  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:15:13.757  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:13.757  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:13.757  7058  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:13.757  7058  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:15:13.767  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:13.767  1183  1183 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 11:15:13.767  1183  1183 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-01 11:15:13.767  1183  1183 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-01 11:15:13.767  1183  1729 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-01 11:15:13.767  1183  1183 D HotspotTile: onReceive : 3, 0
,09-01 11:15:13.767  7637  7637 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:15:13.767  1019  1132 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-01 11:15:13.777  5889  5889 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-01 11:15:13.777  7637  7637 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
09-01 11:15:13.777  1019  1132 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-01 11:15:13.777  7577  7577 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-01 11:15:13.777  7577  7577 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-01 11:15:13.777  7577  7577 I wpa_supplicant: reset timer : RESET_TIMER 0
09-01 11:15:13.777  7577  7577 I wpa_supplicant: P2P: Current p2p state = IDLE
09-01 11:15:13.777  7577  7577 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-01 11:15:13.777  7577  7577 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-01 11:15:13.777  7577  7577 I wpa_supplicant: First Scan Start
,09-01 11:15:13.777  7331  7331 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
09-01 11:15:13.777  5889  5889 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-01 11:15:13.777  5889  5889 D PhoneWindow: *FMB* installDecor flags : 8388610
09-01 11:15:13.777  7577  7577 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-01 11:15:13.787  1019  1132 D WifiNative-wlan0: Setting external_sim to 1
09-01 11:15:13.787  1019  1132 D WifiStateMachine: Setting OUI to DA-A1-19
09-01 11:15:13.787  1019  1132 I WifiNative-HAL: startHal
09-01 11:15:13.787  1019  1132 E wifi    : getStaticLongField sWifiHalHandle 0x9f0a688c
09-01 11:15:13.787  1019  1132 I WifiNative-HAL: Could not start hal
09-01 11:15:13.787  7637  7637 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-01 11:15:13.787  1019  1490 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,09-01 11:15:13.787  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-01 11:15:13.787  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:13.787  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:13.787  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:13.787  1019  1132 E WifiNative-wlan0: do suspend true
,09-01 11:15:13.797  1019  1131 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-01 11:15:13.797   278  1013 D CommandListener: Setting iface cfg,
09-01 11:15:13.797   278  1013 D CommandListener: Trying to bring up p2p0
,09-01 11:15:13.797  1019  1131 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-01 11:15:13.797  1019  1131 D WifiP2pService: P2pEnablingState
,09-01 11:15:13.797  1019  1131 D WifiP2pService: P2pEnablingState{ what=147457 }
09-01 11:15:13.797  1019  1131 D WifiP2pService: P2p socket connection successful
09-01 11:15:13.797  1019  1131 D WifiP2pService: P2pEnabledState
,09-01 11:15:13.807  7657  7657 E Zygote  : MountEmulatedStorage()
,09-01 11:15:13.807  7657  7657 E Zygote  : v2
09-01 11:15:13.807  7657  7657 I libpersona: KNOX_SDCARD checking this for 10141
09-01 11:15:13.807  7657  7657 I libpersona: KNOX_SDCARD not a persona
,09-01 11:15:13.807  7657  7657 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 11:15:13.807  1019  1490 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7657 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,09-01 11:15:13.817  1019  1490 I ActivityManager: Killing 7191:com.android.calendar/u0a131 (adj 15): empty #21,
09-01 11:15:13.817  7657  7657 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 11:15:13.817  1019  1132 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-01 11:15:13.817  1019  1131 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-01 11:15:13.817  1019  1134 E ConnectivityService: updateNetworkInfo()
09-01 11:15:13.817  1019  1051 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-01 11:15:13.817  7657  7657 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-01 11:15:13.817  1019  1051 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-01 11:15:13.817  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-01 11:15:13.817  1019  1051 D WifiDisplayController: disconnect
09-01 11:15:13.817  1019  1132 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-01 11:15:13.817  1019  1051 D WifiDisplayController: updateConnection
09-01 11:15:13.817  1019  1132 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-01 11:15:13.817  1019  1051 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-01 11:15:13.817  1019  1132 E WifiNative-wlan0: invaild command id : 215
09-01 11:15:13.817  1019  1051 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-01 11:15:13.817  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 3
09-01 11:15:13.817  1019  1154 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:15:13.817  1019  1154 I WifiNative-HAL: startHal
09-01 11:15:13.817  1019  1154 E wifi    : getStaticLongField sWifiHalHandle 0x9e0669bc
09-01 11:15:13.817  1019  1154 I WifiNative-HAL: Could not start hal
09-01 11:15:13.817  1019  1154 E WifiScanningService: could not start HAL
09-01 11:15:13.817  1019  1019 D RttService: SCAN_AVAILABLE : 3
09-01 11:15:13.817  1019  1155 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:15:13.817  7577  7577 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-01 11:15:13.827  7577  7577 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
09-01 11:15:13.827  1019  1051 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:15:13.827  1019  1051 D WifiDisplayAdapter: onP2pDisconnected
09-01 11:15:13.827  1019  1051 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-01 11:15:13.827  1019  1051 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-01 11:15:13.827  7577  7577 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-01 11:15:13.827  1183  1183 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-01 11:15:13.827  1019  1132 E WifiStateMachine: Failed to set frequency band 0
09-01 11:15:13.827  1019  1545 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-01 11:15:13.827  1183  1183 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-01 11:15:13.827  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 11:15:13.827  1019  1132 D SecContentProvider2: mCursor = null
09-01 11:15:13.827  1019  1131 D WifiNative-p2p0: p2pGetDeviceAddress
09-01 11:15:13.827  1019  1131 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,09-01 11:15:13.837   334   334 I ServiceManager: Waiting for service AtCmdFwd...
,09-01 11:15:13.837  1019  1131 D WifiP2pService: DeviceAddress: 0a:75:42
,09-01 11:15:13.847  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 11:15:13.847  1019  1132 D SecContentProvider2: mCursor = null
,09-01 11:15:13.847  1019  1051 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-01 11:15:13.847  1019  1051 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-01 11:15:13.847  1019  1051 D WifiDisplayController:  primary type: 10-0050F204-5
09-01 11:15:13.847  1019  1051 D WifiDisplayController:  secondary type: null
09-01 11:15:13.847  1019  1051 D WifiDisplayController:  wps: 0
09-01 11:15:13.847  1019  1051 D WifiDisplayController:  grpcapab: 0
09-01 11:15:13.847  1019  1051 D WifiDisplayController:  devcapab: 0
09-01 11:15:13.847  1019  1051 D WifiDisplayController:  status: 3
09-01 11:15:13.847  1019  1051 D WifiDisplayController:  wfdInfo: null
09-01 11:15:13.847  1019  1051 D WifiDisplayController:  groupownerAddress: null
09-01 11:15:13.847  1019  1051 D WifiDisplayController:  GOdeviceName: null
09-01 11:15:13.847  1019  1051 D WifiDisplayController:  interfaceAddress: 
09-01 11:15:13.847  1019  1051 D WifiDisplayController:  SConnectInfo : null
,09-01 11:15:13.847  7058  7058 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-01 11:15:13.847  7058  7058 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
09-01 11:15:13.847  7058  7058 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-01 11:15:13.847  7058  7058 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-01 11:15:13.847  1019  3288 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-01 11:15:13.847  1019  3288 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-01 11:15:13.847  1019  3288 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-01 11:15:13.847  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-01 11:15:13.847  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,09-01 11:15:13.847  7657  7657 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:13.857  7657  7657 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:13.857  7058  7058 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-01 11:15:13.857  7058  7058 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-01 11:15:13.867  7058  7058 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@bf2e73b Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3f741a91, 16908290=android.view.AbsSavedState$1@3f741a91}, android:focusedViewId=100}]}]
09-01 11:15:13.867  7058  7058 V ActivityThread: updateVisibility : ActivityRecord{296191a5 token=android.os.BinderProxy@2747170f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-01 11:15:13.867  7058  7058 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-01 11:15:13.867  7058  7058 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-01 11:15:13.867  7058  7058 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-01 11:15:13.867  7058  7058 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2747170f time:117974
,09-01 11:15:13.867  1019  1131 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-01 11:15:13.877  1019  1131 D WifiP2pService: InactiveState
,09-01 11:15:13.877  1019  1131 D WifiP2pService: InactiveState{ what=143376 }
09-01 11:15:13.877  1019  1131 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-01 11:15:13.877  7577  7577 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-01 11:15:13.877  1019  1131 D WifiP2pService: InactiveState{ what=143376 }
09-01 11:15:13.877  1019  1131 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-01 11:15:13.877  1019  1082 D PersonaManager: isKioskContainerExistOnDevice
,09-01 11:15:13.887  7657  7657 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-01 11:15:13.887  7657  7657 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 11:15:13.887  7657  7657 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-01 11:15:13.887  7657  7657 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-01 11:15:13.927  1019  1546 D RCPManagerService: exchangeData() failure , invalid userId
,09-01 11:15:13.947  1019  1031 D RCPManagerService: exchangeData() failure , invalid userId
,09-01 11:15:13.967  1019  1505 D RCPManagerService: exchangeData() failure , invalid userId
,09-01 11:15:13.977  1019  3288 D RCPManagerService: exchangeData() failure , invalid userId
,09-01 11:15:14.017  1019  6811 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,09-01 11:15:14.017  1019  6811 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:14.017  1019  6811 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:14.017  1019  6811 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:14.017  1019  6811 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:14.027  7679  7679 E Zygote  : MountEmulatedStorage(),
09-01 11:15:14.037  7679  7679 E Zygote  : v2
09-01 11:15:14.037  1019  6811 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7679 uid=10068 gids={50068, 9997} abi=armeabi-v7a,
09-01 11:15:14.037  7679  7679 I libpersona: KNOX_SDCARD checking this for 10068
09-01 11:15:14.037  7679  7679 I libpersona: KNOX_SDCARD not a persona
,09-01 11:15:14.037  7679  7679 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 11:15:14.037  7679  7679 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-01 11:15:14.037  7679  7679 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-01 11:15:14.037  1019  1317 D RCPManagerService: exchangeData() failure , invalid userId
,09-01 11:15:14.047  1019  1031 D RCPManagerService: exchangeData() failure , invalid userId
,09-01 11:15:14.057  7679  7679 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:14.057  7679  7679 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:14.067  1019  1484 D RCPManagerService: exchangeData() failure , invalid userId
,09-01 11:15:14.067  1019  1317 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-01 11:15:14.077  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:14.077  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:14.077  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:14.077  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:14.087  7679  7679 D BadgeProvider: onCreate
,09-01 11:15:14.087  7679  7679 D BadgeProvider: DatabaseHelper
,09-01 11:15:14.087  7695  7695 E Zygote  : MountEmulatedStorage()
,09-01 11:15:14.087  7695  7695 I libpersona: KNOX_SDCARD checking this for 10009
09-01 11:15:14.087  7695  7695 E Zygote  : v2
09-01 11:15:14.087  7695  7695 I libpersona: KNOX_SDCARD not a persona
,09-01 11:15:14.087  7695  7695 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 11:15:14.087  1019  1317 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7695 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,09-01 11:15:14.097  7695  7695 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 11:15:14.097  1019  1317 I ActivityManager: Killing 6905:com.android.vending/u0a26 (adj 15): empty #21
09-01 11:15:14.097  7695  7695 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-01 11:15:14.097  1019  1317 I ActivityManager: Killing 7153:com.android.defcontainer/u0a3 (adj 15): empty #22
,09-01 11:15:14.107  7679  7689 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-01 11:15:14.127  7679  7689 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-01 11:15:14.127  7679  7689 D BadgeProvider: sendNotify, [notify] : null
09-01 11:15:14.127  7679  7689 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-01 11:15:14.127  7679  7689 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-01 11:15:14.127  7679  7689 D BadgeProvider: update, [UpdateCount] : 1
,09-01 11:15:14.127  1491  1491 D Launcher.Model: reloadBadges entered.
,09-01 11:15:14.127  7695  7695 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:14.137  7695  7695 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:14.207  1019  1545 I ActivityManager: Killing 7357:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,09-01 11:15:14.217  1019  6683 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 11:15:14.217  1019  6683 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 11:15:14.217  1019  6683 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:14.217  1019  6683 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:14.217  1019  6683 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 11:15:14.217  1635  1635 I Hs20UtilService: Starting #11
,09-01 11:15:14.217  1635  1673 I Hs20UtilService: Message received 5011
,09-01 11:15:14.217  7387  7387 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-01 11:15:14.217  7387  7387 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-01 11:15:14.217  7387  7387 D SecurityLogAgent: StateMachine : Current State = 1
09-01 11:15:14.217  7387  7387 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-01 11:15:14.237   278  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-01 11:15:14.237   278  1009 D Netd    : getNetworkForDns: using netid 0 for uid 10011
09-01 11:15:14.237  1019  1545 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 11:15:14.237  1019  1545 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-01 11:15:14.237  1019  1545 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:14.237  1019  1545 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 11:15:14.237  1019  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 11:15:14.237  1635  1635 I Hs20UtilService: Starting #12
,09-01 11:15:14.237  1635  1673 I Hs20UtilService: Message received 5011
,09-01 11:15:14.247  7387  7387 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-01 11:15:14.247  7387  7387 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-01 11:15:14.247  7387  7387 D SecurityLogAgent: StateMachine : Current State = 1
,09-01 11:15:14.247  7387  7387 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-01 11:15:14.257  1019  1317 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-01 11:15:14.257  1019  1317 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 11:15:14.257  1019  1317 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:14.257  1019  1317 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:14.257  1019  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 11:15:14.267  1019  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,09-01 11:15:14.267  1019  1544 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-01 11:15:14.267  1635  1635 I Hs20UtilService: Starting #13
,09-01 11:15:14.267  1635  1673 I Hs20UtilService: Message received 5011
,09-01 11:15:14.267  1019  1132 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-01 11:15:14.267  1019  1132 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-01 11:15:14.267  1019  1132 E WifiNative-wlan0: invaild command id : 215
,09-01 11:15:14.267  1019  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-01 11:15:14.267  7387  7387 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-01 11:15:14.267  7387  7387 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-01 11:15:14.267  7387  7387 D SecurityLogAgent: StateMachine : Current State = 1
,09-01 11:15:14.267  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
09-01 11:15:14.277  7387  7387 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-01 11:15:14.277  4723  4723 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-01 11:15:14.277  4723  4723 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-01 11:15:14.277  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-01 11:15:14.287  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-01 11:15:14.287  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-01 11:15:14.287  4723  4723 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-01 11:15:14.287  4723  4806 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 11:15:14.287  1019  1544 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-01 11:15:14.287  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:14.287  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:14.287  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:14.287  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:14.297  1019  1544 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7714 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
09-01 11:15:14.297  7714  7714 E Zygote  : MountEmulatedStorage()
09-01 11:15:14.297  7714  7714 I libpersona: KNOX_SDCARD checking this for 10064
09-01 11:15:14.297  7714  7714 E Zygote  : v2
,09-01 11:15:14.297  7714  7714 I libpersona: KNOX_SDCARD not a persona
09-01 11:15:14.297  7714  7714 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 11:15:14.307  7714  7714 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-01 11:15:14.307  7714  7714 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-01 11:15:14.317  7714  7714 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:14.317  7714  7714 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:14.337  7714  7714 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-01 11:15:14.347  7714  7714 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-01 11:15:14.347  7714  7714 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-01 11:15:14.367  7714  7714 D FileShare-Client: Outbound.stopDelayTimer - 
,09-01 11:15:14.377  7372  7372 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-01 11:15:14.377  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:14.377  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 11:15:14.377  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,09-01 11:15:14.387  1019  1031 I ActivityManager: Killing 7264:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,09-01 11:15:14.817   295   295 E SMD     : DCD OFF
,09-01 11:15:14.837   334   334 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-01 11:15:14.977  7577  7577 I wpa_supplicant: nl80211: Received scan results (22 BSSes),
09-01 11:15:14.977  7577  7577 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-01 11:15:14.977  7577  7577 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-01 11:15:14.977  7577  7577 I wpa_supplicant: Trying to associate with  'G700'
09-01 11:15:14.977  7577  7577 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,09-01 11:15:14.977  7577  7577 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,09-01 11:15:14.977  1019  7650 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
,09-01 11:15:14.997  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-01 11:15:14.997  1019  1132 D SecContentProvider2: mCursor = null
,09-01 11:15:15.087  7577  7577 E wpa_supplicant: Cmd 35605 not handled
,09-01 11:15:15.087  7577  7577 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-01 11:15:15.087  7577  7577 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-01 11:15:15.087  7577  7577 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-01 11:15:15.087  7577  7577 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-01 11:15:15.087  7577  7577 I wpa_supplicant: Associated with F4.99.3E
09-01 11:15:15.087  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 11:15:15.087  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 11:15:15.087  7577  7577 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-01 11:15:15.087  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
09-01 11:15:15.087  7577  7577 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-01 11:15:15.087  7577  7577 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-01 11:15:15.097  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false,
09-01 11:15:15.097  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 11:15:15.097  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
,09-01 11:15:15.097  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false,
,09-01 11:15:15.097  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 11:15:15.097  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
09-01 11:15:15.097  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-01 11:15:15.097  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, true
09-01 11:15:15.097  1019  1048 D Tethering: interfaceStatusChanged wlan0, true
09-01 11:15:15.097  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 11:15:15.097  1019  1132 D SecContentProvider2: mCursor = null
09-01 11:15:15.097  7577  7577 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-01 11:15:15.097  7577  7577 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE,
09-01 11:15:15.097  7577  7577 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-01 11:15:15.097  7577  7577 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,09-01 11:15:15.097  7577  7577 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-01 11:15:15.097  7577  7577 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,09-01 11:15:15.097  7577  7577 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-01 11:15:15.107  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-01 11:15:15.097  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 11:15:15.097  1019  1132 D SecContentProvider2: mCursor = null
09-01 11:15:15.097  7577  7577 I wpa_supplicant: Blacklist: Clear (temp) 
09-01 11:15:15.097  7577  7577 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-01 11:15:15.107  1019  1135 E Tethering: No numeric data
09-01 11:15:15.107  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, true
09-01 11:15:15.107  1019  1048 D Tethering: interfaceStatusChanged wlan0, true
09-01 11:15:15.107  1019  1135 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-01 11:15:15.107  1019  1135 D Tethering: clearTetheredNotification(),
09-01 11:15:15.107  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:15.107  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
09-01 11:15:15.107  1183  1183 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-01 11:15:15.107  1183  1183 D HotspotTile: updateTetherState():false, false
,09-01 11:15:15.107  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 11:15:15.107  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 11:15:15.107  1019  1132 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-01 11:15:15.107  1019  1132 E WifiConfigStore: setLastSelectedConfiguration -1
,09-01 11:15:15.117  1019  1132 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} },
09-01 11:15:15.117  1019  1134 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,09-01 11:15:15.117  1019  1134 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 11:15:15.117  1019  1134 E ConnectivityService: updateNetworkInfo(),
09-01 11:15:15.117  1019  1129 V NetworkStats: performPollLocked() took 13ms
09-01 11:15:15.117  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 11:15:15.117  1019  1132 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 11:15:15.117  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:15.117  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:15.117  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-01 11:15:15.117  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 11:15:15.117  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 11:15:15.117  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:15.117  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:15.117  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:15.127  1019  1505 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 11:15:15.117  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:15.127  1019  1505 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 11:15:15.127  1019  1505 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:15.127  1019  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:15.127  1019  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 11:15:15.127  1635  1635 I Hs20UtilService: Starting #14
09-01 11:15:15.127  1635  1673 I Hs20UtilService: Message received 5007
,09-01 11:15:15.127  4723  4723 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-01 11:15:15.127  4723  4723 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-01 11:15:15.127  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-01 11:15:15.127  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-01 11:15:15.127  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-01 11:15:15.127  4723  4723 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-01 11:15:15.127  4723  4806 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 11:15:15.137  1019  1132 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 11:15:15.147   278  1013 D CommandListener: Setting iface cfg,
09-01 11:15:15.147  1019  1132 E WifiStateMachine: Start Dhcp Watchdog 2
,09-01 11:15:15.147  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 11:15:15.147  1019  1132 D SecContentProvider2: mCursor = null
,09-01 11:15:15.157  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-01 11:15:15.157  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-01 11:15:15.157  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-01 11:15:15.157  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:15.157  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:15.167  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:15.167  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:15.167  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-01 11:15:15.167  1019  1132 D SecContentProvider2: mCursor = null
,09-01 11:15:15.167  1019  1132 E WifiNative-wlan0: do suspend false
,09-01 11:15:15.177  1019  1131 D WifiP2pService: InactiveState{ what=143375 }
,09-01 11:15:15.177  1019  1131 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-01 11:15:15.287  1019  1317 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-01 11:15:15.287  1019  1317 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-01 11:15:15.287  1019  1317 D SecContentProvider2: mCursor = null
,09-01 11:15:15.287  1019  1317 D WifiService: setWifiEnabled: false pid=7058, uid=10170
09-01 11:15:15.287  1019  1317 D SettingsProvider: name = wifi_on
,09-01 11:15:15.297  1019  1132 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 11:15:15.307  1019  1132 E WifiNative-wlan0: do suspend true
,09-01 11:15:15.327  1019  1131 D WifiP2pService: InactiveState{ what=143375 },
09-01 11:15:15.327  1019  1131 D WifiP2pService: P2pEnabledState{ what=143375 },
,09-01 11:15:15.327  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-01 11:15:15.337  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 11:15:15.337  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 11:15:15.337  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:15.337  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:15.337  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:15.337  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:15.337   278  1013 D CommandListener: Clearing all IP addresses on wlan0
,09-01 11:15:15.337  1019  1134 E ConnectivityService: updateNetworkInfo()
,09-01 11:15:15.337  1019  1134 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-01 11:15:15.337  1019  1134 E ConnectivityService: updateNetworkInfo()
09-01 11:15:15.337  1019  1134 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,09-01 11:15:15.337   278  1013 E Netd    : no such netId 503
,09-01 11:15:15.337  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling,
09-01 11:15:15.347  1019  1134 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
09-01 11:15:15.347  1019  1134 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,09-01 11:15:15.347  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-01 11:15:15.347  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-01 11:15:15.347  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-01 11:15:15.347  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:15.357  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:15.357  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:15.357  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:15.357  1019  1134 V NetworkStats: updateIfacesLocked()
09-01 11:15:15.357  1019  1134 V NetworkStats: performPollLocked(flags=0x1)
09-01 11:15:15.357  1019  1134 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 11:15:15.357  1019  1134 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-01 11:15:15.357  1019  1134 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 11:15:15.357  1019  1134 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:15.357  1019  1134 V NetworkStats: performPollLocked() took 3ms
09-01 11:15:15.357  1019  1132 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-01 11:15:15.357  1019  1131 D WifiP2pService: InactiveState{ what=131204 }
09-01 11:15:15.357  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 1
09-01 11:15:15.357  1019  1131 D WifiP2pService: P2pEnabledState{ what=131204 }
09-01 11:15:15.357  1019  1154 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:15:15.357  1019  1131 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-01 11:15:15.357  1019  1019 D RttService: SCAN_AVAILABLE : 1
09-01 11:15:15.357  1019  1155 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 11:15:15.357  1019  1134 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
09-01 11:15:15.357  1019  7729 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:15:15.357  1019  1134 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-01 11:15:15.357  1019  1134 D ConnectivityService: nai.networkMonitor.doQuit()
09-01 11:15:15.357  1019  1134 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-01 11:15:15.357  1019  1134 E ConnectivityService: updateNetworkInfo()
,09-01 11:15:15.357  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:15.357  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:15.357  1019  7729 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,09-01 11:15:15.367  1019  1051 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
09-01 11:15:15.367  1019  1051 D WifiDisplayAdapter: onP2pDisconnected
09-01 11:15:15.367  1019  1051 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-01 11:15:15.367  1019  1051 D IpRemoteDisplayController: WfdBridgeServer is already null
09-01 11:15:15.367  1019  1484 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 11:15:15.367  1019  1484 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 11:15:15.367  1019  1484 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:15.367  1019  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:15.367  1019  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 11:15:15.367  1019  1131 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-01 11:15:15.367  1019  1134 E ConnectivityService: updateNetworkInfo()
,09-01 11:15:15.367  1019  1131 D WifiP2pService: P2pDisablingState
,09-01 11:15:15.367  1019  1131 D WifiP2pService: P2pDisablingState{ what=147458 }
09-01 11:15:15.367  1019  1131 D WifiP2pService: p2p socket connection lost
09-01 11:15:15.367  1635  1635 I Hs20UtilService: Starting #15
,09-01 11:15:15.367  1019  1131 D WifiP2pService: P2pDisabledState
09-01 11:15:15.367  1019  1132 E WifiNative-wlan0: do suspend true
09-01 11:15:15.367  1635  1673 I Hs20UtilService: Message received 5007
09-01 11:15:15.367  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-01 11:15:15.367  1019  1051 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-01 11:15:15.367  1019  1051 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-01 11:15:15.367  1019  1051 D WifiDisplayController: disconnect
,09-01 11:15:15.367  1019  1051 D WifiDisplayController: updateConnection
09-01 11:15:15.367  1019  1051 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-01 11:15:15.367  1019  1051 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-01 11:15:15.377  4723  4723 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-01 11:15:15.377  4723  4723 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-01 11:15:15.377  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-01 11:15:15.377  1019  1051 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-01 11:15:15.377  1019  1051 D WifiDisplayAdapter: onP2pDisconnected
09-01 11:15:15.377  1019  1051 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-01 11:15:15.377  1019  1051 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-01 11:15:15.377  1183  1183 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-01 11:15:15.377  1019  1032 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-01 11:15:15.387  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-01 11:15:15.387  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-01 11:15:15.387  4723  4723 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-01 11:15:15.387  1183  1183 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-01 11:15:15.387  4723  4806 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 11:15:15.387  7732  7732 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-01 11:15:15.397  7732  7732 I dhcpcd  : version 5.5.6 starting
,09-01 11:15:15.397  4723  4723 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE,
09-01 11:15:15.397  4723  4723 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-01 11:15:15.397  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-01 11:15:15.397  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-01 11:15:15.397  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-01 11:15:15.397  7732  7732 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-01 11:15:15.397  1019  1131 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-01 11:15:15.397  1019  1131 D WifiP2pService: DefaultState{ what=143375 }
09-01 11:15:15.397  4723  4723 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-01 11:15:15.397  4723  4806 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 11:15:15.397   278  1013 D CommandListener: Clearing all IP addresses on wlan0
,09-01 11:15:15.407  7714  7714 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
09-01 11:15:15.407  7714  7714 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-01 11:15:15.407  7714  7714 D FileShare-Client: Outbound.stopDelayTimer - 
,09-01 11:15:15.407  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-01 11:15:15.407  7577  7577 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
09-01 11:15:15.407  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-01 11:15:15.407  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 11:15:15.407  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 11:15:15.407  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:15.407  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:15.407  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:15.407  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:15.427  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 11:15:15.427  1019  1132 D SecContentProvider2: mCursor = null
09-01 11:15:15.427  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-01 11:15:15.427  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 11:15:15.427  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 11:15:15.427  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:15.427  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:15.427  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:15.427  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:15.437  4723  4723 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-01 11:15:15.437  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-01 11:15:15.437  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 11:15:15.437  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-01 11:15:15.437  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:15.437  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:15.437  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:15.437  7372  7372 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-01 11:15:15.437  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:15.437  1183  1183 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 11:15:15.437  1183  1183 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-01 11:15:15.437  1183  1729 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-01 11:15:15.437  1183  1183 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-01 11:15:15.437  1183  1183 D HotspotTile: onReceive : 0, 0
,09-01 11:15:15.437  7058  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 11:15:15.437  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:15.437  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:15.437  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:15.437  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:15:15.437  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:15.437  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:15.437  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:15.437  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:15:15.437  7058  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:15.437  7058  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:15:15.447  7058  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:15.447  1019  1082 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 11:15:15.447  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:15.447  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:15.447  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:15.447  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:15:15.447  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:15.447  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:15.447  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false,
09-01 11:15:15.447  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:15:15.447  1019  1082 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
09-01 11:15:15.447  7058  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:15.447  7058  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:15:15.447  1019  1082 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:15.447  1019  1082 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:15.447  1019  1082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 11:15:15.457  1635  1635 I Hs20UtilService: Starting #16
09-01 11:15:15.457  1635  1673 I Hs20UtilService: Message received 5007
09-01 11:15:15.457  4723  4723 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-01 11:15:15.457  4723  4723 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-01 11:15:15.457  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-01 11:15:15.457  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-01 11:15:15.457  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-01 11:15:15.457  4723  4723 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-01 11:15:15.457  4723  4806 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 11:15:15.467  1019  1505 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 11:15:15.467  1019  1505 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 11:15:15.467  1019  1505 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:15.467  1019  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:15.467  1019  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 11:15:15.467  1635  1635 I Hs20UtilService: Starting #17
09-01 11:15:15.467  1635  1673 I Hs20UtilService: Message received 5011
,09-01 11:15:15.467  7732  7732 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-01 11:15:15.467  7732  7732 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-01 11:15:15.467  7732  7732 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-01 11:15:15.467  7732  7732 I dhcpcd  : bssid match
09-01 11:15:15.467  7387  7387 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-01 11:15:15.467  7387  7387 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-01 11:15:15.467  7387  7387 D SecurityLogAgent: StateMachine : Current State = 1
09-01 11:15:15.467  7732  7732 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116,
09-01 11:15:15.467  7387  7387 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-01 11:15:15.577  7732  7732 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1,
,09-01 11:15:15.607  7577  7577 I wpa_supplicant: Blacklist: Clear (all) 
,09-01 11:15:15.757  7732  7732 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
09-01 11:15:15.757  7577  7577 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
,09-01 11:15:15.757  1019  1048 D Tethering: interfaceLinkStateChanged p2p0, false
09-01 11:15:15.757  1019  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-01 11:15:15.757  1019  1048 D Tethering: interfaceStatusChanged p2p0, false
,09-01 11:15:15.787  7577  7577 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-01 11:15:15.787  7577  7577 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-01 11:15:15.787  7577  7577 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-01 11:15:15.787  7577  7577 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-01 11:15:15.787  7577  7577 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-01 11:15:15.787  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 11:15:15.787  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 11:15:15.787  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
,09-01 11:15:15.787  1019  1135 D Tethering: InitialState.processMessage what=4
09-01 11:15:15.797  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 11:15:15.797  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 11:15:15.797  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
,09-01 11:15:15.797  1019  1135 E Tethering: No numeric data,
09-01 11:15:15.797  1019  1135 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-01 11:15:15.797  1019  1135 D Tethering: clearTetheredNotification()
,09-01 11:15:15.797  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:15.797  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
09-01 11:15:15.797  1183  1183 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-01 11:15:15.807  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 11:15:15.797  1183  1183 D HotspotTile: updateTetherState():false, false
09-01 11:15:15.807  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-01 11:15:15.807  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 11:15:15.807  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 11:15:15.807  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
09-01 11:15:15.807  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:15.807  1019  1129 V NetworkStats: performPollLocked() took 4ms
,09-01 11:15:15.807  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit,
09-01 11:15:15.807  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 11:15:16.087  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false,
09-01 11:15:16.087  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 11:15:16.087  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
,09-01 11:15:16.207  7577  7577 I wpa_supplicant: Blacklist: Clear (all) 
,09-01 11:15:16.267  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false,
09-01 11:15:16.267  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 11:15:16.267  1019  1048 D Tethering: interfaceStatusChanged wlan0, false,
09-01 11:15:16.267  7577  7577 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-01 11:15:16.377  1019  1132 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0,
09-01 11:15:16.377  1019  1132 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-01 11:15:16.377  7331  7331 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,09-01 11:15:16.397  4723  4723 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,09-01 11:15:16.397  1019  1546 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-01 11:15:16.407  1019  1546 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 11:15:16.407  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-01 11:15:16.407  1019  1546 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:16.407  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:16.407  1019  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 11:15:16.407  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:16.407  1019  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-01 11:15:16.407  1696  2181 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 11:15:16.407  1635  1635 I Hs20UtilService: Starting #18
09-01 11:15:16.407  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-01 11:15:16.407  1635  1673 I Hs20UtilService: Message received 5011
,09-01 11:15:16.407  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-01 11:15:16.407  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:16.407  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:16.417  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:16.417  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:16.417  1183  1183 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-01 11:15:16.417  1183  1183 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-01 11:15:16.417  1183  1183 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-01 11:15:16.417  1183  1729 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-01 11:15:16.417  1183  1183 D HotspotTile: onReceive : 1, 0
,09-01 11:15:16.417  7387  7387 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-01 11:15:16.417  7387  7387 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-01 11:15:16.417  7387  7387 D SecurityLogAgent: StateMachine : Current State = 1
,09-01 11:15:16.427  7387  7387 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-01 11:15:16.517  1019  1046 W ActivityManager: mDVFSHelper.release()
,09-01 11:15:17.047   278  1007 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,09-01 11:15:17.047  1019  1048 D Tethering: interfaceRemoved wlan0
,09-01 11:15:17.047  1019  1048 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-01 11:15:17.247  1019  1048 D Tethering: interfaceRemoved p2p0
,09-01 11:15:17.247  1019  1048 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-01 11:15:17.427  1019  3365 D SSRM:n  : SIOP:: AP = 370
,09-01 11:15:17.817   295   295 E SMD     : DCD OFF,
,09-01 11:15:18.027  1019  1132 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1,
,09-01 11:15:18.297  7058  7244 D BluetoothAdapter: enable()
,09-01 11:15:18.297  1019  1317 W ActivityManager: Permission Denial: getCurrentUser() from pid=7058, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-01 11:15:18.307  1019  1317 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
09-01 11:15:18.307  1019  1317 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7058, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-01 11:15:18.307  1019  1317 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-01 11:15:18.307  1019  1317 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-01 11:15:18.307  1019  1317 W BluetoothManagerService: ,	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-01 11:15:18.307  1019  1317 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-01 11:15:18.307  1019  1317 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-01 11:15:18.307  1019  1317 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-01 11:15:18.307  1019  1317 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-01 11:15:18.307  1019  1317 D SettingsProvider: name = bluetooth_on,
,09-01 11:15:18.317  1019  1050 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
09-01 11:15:18.317  1019  1050 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
,09-01 11:15:18.317  1019  1050 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-01 11:15:18.327  3228  3306 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-01 11:15:18.327  3228  3306 D BluetoothAdapterProperties: Setting state to 11
,09-01 11:15:18.327  3228  3306 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-01 11:15:18.327  3228  3306 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-01 11:15:18.327  3228  3306 D BluetoothAdapterService: updateAdapterState state is 11
,09-01 11:15:18.327  3228  3306 D BluetoothAdapterService: Autoconnection is available 
,09-01 11:15:18.327  3228  3306 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-01 11:15:18.327  3228  3306 D BtConfig.SecureMode: isSecureModeOn:false
09-01 11:15:18.327  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-01 11:15:18.327  3228  3306 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,09-01 11:15:18.327  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-01 11:15:18.327  3228  3306 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
,09-01 11:15:18.337  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-01 11:15:18.337  3228  3306 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-01 11:15:18.337  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-01 11:15:18.337  3228  3306 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-01 11:15:18.337  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-01 11:15:18.337  3228  3306 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-01 11:15:18.337  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-01 11:15:18.337  3228  3306 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-01 11:15:18.337  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 11:15:18.337  3228  3306 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-01 11:15:18.337  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-01 11:15:18.337  3228  3306 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-01 11:15:18.337  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-01 11:15:18.337  3228  3306 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-01 11:15:18.337  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-01 11:15:18.337  3228  3306 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-01 11:15:18.337  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-01 11:15:18.337  3228  3306 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-01 11:15:18.337  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-01 11:15:18.337  3228  3306 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-01 11:15:18.337  3228  3306 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-01 11:15:18.337  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-01 11:15:18.337  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-01 11:15:18.337  3228  3306 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-01 11:15:18.337  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:15:18.337  1019  1019 I InputMethodManagerService: [BT Setting State] State =11
,09-01 11:15:18.347  1183  1183 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-01 11:15:18.347  1183  1183 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:15:18.347  1183  1183 D BluetoothTile:  getBluetoothState : 11
,09-01 11:15:18.357  1183  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 11:15:18.357  1183  1729 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-01 11:15:18.357  4723  4723 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:15:18.357  1019  1082 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-01 11:15:18.357  1019  6683 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-01 11:15:18.357  1183  1183 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-01 11:15:18.357  1986  1986 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-01 11:15:18.367  1019  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 11:15:18.367  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-01 11:15:18.367  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:18.367  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:18.367  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:18.367  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:18.367  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:18.367  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-01 11:15:18.367  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-01 11:15:18.367  3228  3306 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-01 11:15:18.367  1019  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 11:15:18.367  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-01 11:15:18.367  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:18.367  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:18.367  3228  3228 D HeadsetService: Received start request. Starting profile...
09-01 11:15:18.367  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-01 11:15:18.367  3228  3228 D HeadsetService: start()
09-01 11:15:18.367  3228  3228 D HeadsetStateMachine: make
,09-01 11:15:18.377  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-01 11:15:18.377  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-01 11:15:18.377  3228  3306 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-01 11:15:18.377  1019  1317 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 11:15:18.377  1019  1317 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-01 11:15:18.377  1019  1317 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:18.377  1019  1317 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:18.377  1019  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:18.377  3228  3228 E HeadsetStateMachine: # of Max HF connection is 2
,09-01 11:15:18.377  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,09-01 11:15:18.377  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-01 11:15:18.377  3228  3306 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-01 11:15:18.377  1019  6811 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 11:15:18.387  1019  6811 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-01 11:15:18.387  1019  6811 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:18.387  1019  6811 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:18.387  1019  6811 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:18.387  1019  1505 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-01 11:15:18.387  1019  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-01 11:15:18.387  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService,
09-01 11:15:18.387  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-01 11:15:18.387  1019  1082 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 11:15:18.387  3228  3306 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-01 11:15:18.387  1019  1082 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-01 11:15:18.387  1019  1505 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:18.387  1019  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:18.387  1019  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-01 11:15:18.387  1019  1082 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:18.387  1019  1082 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:18.387  1019  1082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:18.387  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-01 11:15:18.387  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 11:15:18.387  3228  3306 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-01 11:15:18.397  1688  1688 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 11:15:18.397  1019  1546 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:18.397  1019  1546 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 11:15:18.397  1019  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:18.397  1019  1546 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-01 11:15:18.397  1019  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:18.397  1019  3288 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-01 11:15:18.397  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-01 11:15:18.397  1019  3288 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
09-01 11:15:18.397  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-01 11:15:18.397  3228  3306 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-01 11:15:18.397  1019  3288 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:18.397  1019  3288 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:18.397  1019  3288 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-01 11:15:18.397  3228  3228 I bluedroid: get_profile_interface handsfree,
,09-01 11:15:18.407  1019  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 11:15:18.407  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-01 11:15:18.407  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:18.407  1019  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:18.407  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
09-01 11:15:18.407  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-01 11:15:18.407  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-01 11:15:18.407  3228  3306 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-01 11:15:18.407  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-01 11:15:18.407  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-01 11:15:18.407  3228  3306 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-01 11:15:18.407  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-01 11:15:18.407  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-01 11:15:18.407  3228  3306 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-01 11:15:18.407  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-01 11:15:18.407  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-01 11:15:18.407  3228  3306 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-01 11:15:18.407  3228  3306 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-01 11:15:18.407  4723  4723 D BluetoothNotiBroadcastReceiver: onReceive
,09-01 11:15:18.417  1183  1183 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED,
09-01 11:15:18.417  1183  1183 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-01 11:15:18.417  3228  3228 E DualScoManager: Dual Sco Manager already instantiated,
09-01 11:15:18.417  3228  3228 I DualScoManager: Set HeadsetServiceHelper
09-01 11:15:18.417  3228  3228 D BluetoothAtMessage: createCMTIContentObservers
09-01 11:15:18.417  1019  1545 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-01 11:15:18.417  1019  1545 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-01 11:15:18.417  1019  1545 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 11:15:18.417  1019  1545 D SettingsProvider: selectionArgs: false
09-01 11:15:18.417  1019  1545 D SettingsProvider: selectionArgs: 1002
09-01 11:15:18.417  1019  1545 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 11:15:18.417  1019  1545 D SettingsProvider: ret = -1
,09-01 11:15:18.417  3228  7763 D HeadsetStateMachine: Enter Disconnected: -2
09-01 11:15:18.417  1019  1544 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-01 11:15:18.417  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:18.417  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:18.417  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:18.417  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:18.427  7764  7764 E Zygote  : MountEmulatedStorage()
,09-01 11:15:18.427  7764  7764 E Zygote  : v2
09-01 11:15:18.427  7764  7764 I libpersona: KNOX_SDCARD checking this for 10055
09-01 11:15:18.437  7764  7764 I libpersona: KNOX_SDCARD not a persona
09-01 11:15:18.437  7764  7764 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 11:15:18.437  1019  1544 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7764 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-01 11:15:18.437  7764  7764 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 11:15:18.437  7764  7764 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-01 11:15:18.437  3228  3228 D HeadsetService: mStartError = false
09-01 11:15:18.437  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
,09-01 11:15:18.437  3228  7763 D HeadsetStateMachine: Clear mHeadsetBrsf
09-01 11:15:18.437  3228  7763 D HeadsetStateMachine: map size, before remove : 0
09-01 11:15:18.437  3228  7763 D HeadsetStateMachine: map size, after remove: 0
09-01 11:15:18.437  3228  3228 D A2dpService: Received start request. Starting profile...
09-01 11:15:18.437  3228  3228 D A2dpService: start()
09-01 11:15:18.437  3228  3228 I bluedroid: get_profile_interface avrcp
,09-01 11:15:18.447  3228  3228 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-01 11:15:18.447  3228  3228 D Avrcp   : Initialize Media Controller
09-01 11:15:18.447  3228  3228 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-01 11:15:18.447  3228  3228 E Avrcp   : getActiveSessions
,09-01 11:15:18.447  3228  3228 D Avrcp   : pick active media Controller
09-01 11:15:18.447  3228  3228 D Avrcp   : Get the active Media Controller 
,09-01 11:15:18.447  3228  3228 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-01 11:15:18.447  3228  3228 D A2dpStateMachine: make
,09-01 11:15:18.457  3228  7771 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-01 11:15:18.467  3228  7771 D BluetoothMediaBrowser: no now playing list
09-01 11:15:18.467  3228  7771 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-01 11:15:18.467  3228  3228 I bluedroid: get_profile_interface a2dp
,09-01 11:15:18.467  3228  7776 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-01 11:15:18.467  3228  3228 E bt-btif : warning : media task started media_task_refcnt 1 
,09-01 11:15:18.467  3228  3228 D A2dpService: mStartError = false
09-01 11:15:18.467  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
09-01 11:15:18.467  3228  3228 D HidService: Received start request. Starting profile...
09-01 11:15:18.467  3228  3228 D HidService: start()
09-01 11:15:18.467  3228  3228 I bluedroid: get_profile_interface hidhost
09-01 11:15:18.467  3228  7773 D A2dpStateMachine: Enter Disconnected: -2
,09-01 11:15:18.467  3228  3228 D HidService: setHidService(): set to: null
09-01 11:15:18.467  3228  3228 D HidService: mStartError = false
09-01 11:15:18.467  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
09-01 11:15:18.467  3228  3228 D HealthService: Received start request. Starting profile...
09-01 11:15:18.467  3228  3228 D HealthService: start()
,09-01 11:15:18.467  3228  3228 I bluedroid: get_profile_interface health
,09-01 11:15:18.467  3228  3228 D HealthService: mStartError = false
09-01 11:15:18.467  1443  7285 I Telecom : BluetoothPhoneService: queryPhoneState
09-01 11:15:18.467  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
09-01 11:15:18.467  3228  3228 D HeadsetStateMachine: Try to query the phonestate on bind
,09-01 11:15:18.477  1443  1443 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0,
09-01 11:15:18.477  1443  1443 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-01 11:15:18.477  1443  7285 I Telecom : BluetoothPhoneService: Result of Message : true
,09-01 11:15:18.477  3228  3228 D PanService: Received start request. Starting profile...
,09-01 11:15:18.477  3228  3228 D PanService: start()
09-01 11:15:18.477  3228  3228 D BluetoothPanServiceJni: initializeNative(L110): pan
09-01 11:15:18.477  3228  3228 I bluedroid: get_profile_interface pan
09-01 11:15:18.477  3228  3228 D PanService: mStartError = false
09-01 11:15:18.477  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
,09-01 11:15:18.477  3228  3228 D BluetoothMapService: Received start request. Starting profile...
09-01 11:15:18.477  3228  3228 D BluetoothMapService: start()
,09-01 11:15:18.477  3228  3228 D BluetoothMapService: mStartError = false
,09-01 11:15:18.477  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
09-01 11:15:18.477  3228  3228 D HeadsetStateMachine: Proxy object connected
09-01 11:15:18.477  3228  3228 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-01 11:15:18.477  3228  7763 D HeadsetStateMachine: Disconnected process message: 11
,09-01 11:15:18.477  3228  3228 D SapService: Received start request. Starting profile...
09-01 11:15:18.477  3228  3228 D SapService: start()
09-01 11:15:18.477  3228  3228 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-01 11:15:18.477  3228  3228 I bluedroid: get_profile_interface sap
09-01 11:15:18.477  3228  3228 D SapService: mStartError = false
09-01 11:15:18.477  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
09-01 11:15:18.477  3228  3228 D HeadsetPhoneState: sendDeviceDataStateChanged
09-01 11:15:18.477  3228  3228 D HeadsetPhoneState: Signal level : previous=0 curr=4
09-01 11:15:18.477  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-01 11:15:18.477  3228  3228 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-01 11:15:18.477  3228  7763 D HeadsetStateMachine: Disconnected process message: 18
09-01 11:15:18.477  3228  7763 D HeadsetStateMachine: Disconnected process message: 10
09-01 11:15:18.477  3228  7763 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-01 11:15:18.477  3228  7763 D HeadsetStateMachine: Disconnected process message: 11
,09-01 11:15:18.487  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-01 11:15:18.487  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-01 11:15:18.487  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-01 11:15:18.487  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-01 11:15:18.497  7764  7764 D TimaKeyStoreProvider: TimaSignature is unavailable,
,09-01 11:15:18.497  7764  7764 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:18.497  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
09-01 11:15:18.497  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-01 11:15:18.507  3228  3306 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-01 11:15:18.507  3228  3306 I bluedroid: enable
,09-01 11:15:18.507  3228  3309 E bt-btif : Calling BTA_HhEnable
,09-01 11:15:18.507  3228  3309 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-01 11:15:18.507  3228  3309 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-01 11:15:18.507  3228  3309 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
09-01 11:15:18.507  3228  3309 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
09-01 11:15:18.507  3228  3309 E BluetoothServiceJni: populateRssiValuesNative
09-01 11:15:18.507  3228  3309 I bluedroid: getModelRssiValues
09-01 11:15:18.507  3228  3309 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-01 11:15:18.507  3228  3309 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-01 11:15:18.517  3228  3309 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-01 11:15:18.517  1019  1019 D SettingsProvider: name = bluetooth_name
,09-01 11:15:18.517  7764  7764 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-01 11:15:18.517  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:18.527  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:18.527  3228  3309 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-01 11:15:18.527  3228  3309 D BluetoothAdapterProperties: Scan Mode:20
09-01 11:15:18.527  3228  3309 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-01 11:15:18.527  3228  3309 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
09-01 11:15:18.527  3228  3309 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
09-01 11:15:18.527  3228  3309 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
09-01 11:15:18.527  3228  3309 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,09-01 11:15:18.527  3228  3309 E bt-btif : JVenable fails
,09-01 11:15:18.527  3228  3309 D bte_conf: Device ID record 1 : primary
09-01 11:15:18.527  3228  3309 D bte_conf:   vendorId            = 0075
09-01 11:15:18.527  3228  3309 D bte_conf:   vendorIdSource      = 0001
,09-01 11:15:18.527  3228  3309 D bte_conf:   product             = 0100
09-01 11:15:18.527  3228  3309 D bte_conf:   version             = 0200
09-01 11:15:18.527  3228  3309 D bte_conf:   clientExecutableURL = 
09-01 11:15:18.527  3228  3309 D bte_conf:   serviceDescription  = 
09-01 11:15:18.527  3228  3309 D bte_conf:   documentationURL    = 
09-01 11:15:18.527  3228  3309 D bte_conf: bte_load_did_conf no section named DID2.
09-01 11:15:18.527  3228  3309 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-01 11:15:18.527  3228  3309 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-01 11:15:18.527  3228  3306 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-01 11:15:18.537  3228  3306 D BluetoothAdapterProperties: ScanMode =  20
09-01 11:15:18.537  3228  3306 D BluetoothAdapterProperties: State =  11
,09-01 11:15:18.537  1019  6683 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-01 11:15:18.537  3228  3306 D BluetoothAdapterProperties: Setting state to 12
09-01 11:15:18.537  3228  3306 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-01 11:15:18.537  3228  3309 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-01 11:15:18.537  3228  3309 D BluetoothAdapterProperties: Scan Mode:21
09-01 11:15:18.537  3228  3309 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-01 11:15:18.537  1019  3288 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-01 11:15:18.537  1019  3288 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 11:15:18.537  1019  3288 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 11:15:18.537  1019  3288 D SettingsProvider: selectionArgs: false
09-01 11:15:18.537  1019  3288 D SettingsProvider: selectionArgs: 1002
09-01 11:15:18.537  1019  3288 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 11:15:18.537  1019  3288 D SettingsProvider: ret = -1
09-01 11:15:18.537  3228  3306 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-01 11:15:18.537  3228  3306 D BluetoothAdapterService: updateAdapterState state is 12
,09-01 11:15:18.537  1019  1317 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 11:15:18.537  1019  1317 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-01 11:15:18.547  1019  1317 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:18.547  1019  1317 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:18.547  1019  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:18.547  3228  3306 D BluetoothAdapterService: Autoconnection is available 
,09-01 11:15:18.547  3228  3306 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-01 11:15:18.547  3228  3306 D BluetoothAdapterService: starting service from this receiver
,09-01 11:15:18.547  3228  3392 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-01 11:15:18.547  1019  1505 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 11:15:18.547  1019  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-01 11:15:18.547  7764  7764 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
09-01 11:15:18.547  1019  1505 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:18.547  1019  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:18.547  1019  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:18.557  3228  3392 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-01 11:15:18.557  7764  7764 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-01 11:15:18.557  7764  7764 D UserAnalysis: Create SecureDbHelper
,09-01 11:15:18.557  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:18.557  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:18.557  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:18.557  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:15:18.557  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:18.557  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:18.557  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:18.557  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:15:18.557  3228  3228 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
09-01 11:15:18.557  1019  1050 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-01 11:15:18.557  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-01 11:15:18.557  3228  3306 I BluetoothAdapterState: Entering On State from state = 11
09-01 11:15:18.557  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:18.557  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:18.557  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:18.557  4723  7261 D BluetoothPan: Binding service...
,09-01 11:15:18.557  7058  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
,09-01 11:15:18.557  7764  7764 D IntelligenceServiceApplication: onCreate()
,09-01 11:15:18.567  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:18.567  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:18.567  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:18.567  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:15:18.567  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:18.567  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:18.567  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:18.567  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:15:18.567  7058  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:15:18.567  7764  7764 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-01 11:15:18.707  1019  1050 I art     : Explicit concurrent mark sweep GC freed 74973(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 23MB/34MB, paused 2.352ms total 149.767ms
09-01 11:15:18.707  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-01 11:15:18.707  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-01 11:15:18.707  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:18.707  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:18.707  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-01 11:15:18.707  1019  1082 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-01 11:15:18.717  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-01 11:15:18.717  1443  1452 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 11:15:18.717  1019  3288 I ActivityManager: Killing 7287:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,09-01 11:15:18.717  1019  1050 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-01 11:15:18.717  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 11:15:18.717  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:18.717  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:18.717  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:18.717  1443  1452 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 11:15:18.727  1688  1775 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 11:15:18.727  1688  1775 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 11:15:18.727  4723  7261 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-01 11:15:18.727  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-01 11:15:18.727  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-01 11:15:18.727  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:18.727  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:18.727  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:18.727  4723  7261 D Bluetoothsap: onBluetoothStateChange: up=true
09-01 11:15:18.727  4723  7261 D Bluetoothsap: Binding service...
,09-01 11:15:18.727  3228  3228 I BluetoothPbapService: Handler(): got msg=1
,09-01 11:15:18.727  1019  1031 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-01 11:15:18.727  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-01 11:15:18.737  4723  7261 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-01 11:15:18.737  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-01 11:15:18.737  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-01 11:15:18.737  3228  7788 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-01 11:15:18.737  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:18.737  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:18.737  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:18.737  4723  7261 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-01 11:15:18.737  4723  4731 D BluetoothPbap: onBluetoothStateChange: up=true
,09-01 11:15:18.737  4723  4723 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 11:15:18.737  4723  4723 D PanProfile: Bluetooth service connected
,09-01 11:15:18.747  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-01 11:15:18.747  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-01 11:15:18.747  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:18.747  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:18.747  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:18.747  3228  3228 D BluetoothA2dp: Proxy object connected
,09-01 11:15:18.747  3228  3228 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-01 11:15:18.747  3228  7788 D BluetoothSocket: bindListen(): myUserId = 0
,09-01 11:15:18.747  3228  7788 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 11:15:18.747  1019  1050 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 11:15:18.747  1019  1050 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-01 11:15:18.747  4723  4731 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-01 11:15:18.747  3228  7788 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-01 11:15:18.747  3228  7788 D BluetoothSocket: bindListen(), new LocalSocket 
09-01 11:15:18.757  3228  7788 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-01 11:15:18.757  3228  7788 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2230cb6
09-01 11:15:18.757  4723  4723 D BluetoothInputDevice: Proxy object connected
09-01 11:15:18.757  4723  4723 D HidProfile: Bluetooth service connected
,09-01 11:15:18.757  4723  4731 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-01 11:15:18.757  3228  7788 D BluetoothSocket: channel: 19
09-01 11:15:18.757  3228  7788 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-01 11:15:18.757  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-01 11:15:18.757  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-01 11:15:18.757  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:18.757  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:18.757  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:18.757  1443  7285 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 11:15:18.757  1443  7285 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 11:15:18.757  3228  3242 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 11:15:18.757  3228  3242 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 11:15:18.757  1467  1660 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 11:15:18.757  4723  4723 D Bluetoothsap: BluetoothSAP Proxy object connected
09-01 11:15:18.757  1019  1050 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-01 11:15:18.757  4723  4723 D SapProfile: Bluetooth service connected
09-01 11:15:18.757  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-01 11:15:18.757  4723  4723 D Bluetoothsap: getConnectedDevices()
,09-01 11:15:18.757  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:18.757  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:18.757  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:18.757  1467  1660 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 11:15:18.757  1183  1973 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 11:15:18.757  1183  1973 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 11:15:18.757  4723  4732 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 11:15:18.757  4723  4723 D BluetoothPbap: Proxy object connected
,09-01 11:15:18.767  4723  4723 D PbapServerProfile: Bluetooth service connected
09-01 11:15:18.767  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-01 11:15:18.767  4723  4723 D BluetoothA2dp: Proxy object connected
09-01 11:15:18.767  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-01 11:15:18.767  4723  4723 D A2dpProfile: Bluetooth service connected
,09-01 11:15:18.767  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:18.767  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:18.767  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:18.767  4723  4732 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 11:15:18.767  4723  4723 D HeadsetProfile: Bluetooth service connected
,09-01 11:15:18.857  1019  1050 E BluetoothManagerService: Unable to call onBluetoothStateChange() on callback #14,
09-01 11:15:18.857  1019  1050 E BluetoothManagerService: android.os.DeadObjectException
09-01 11:15:18.857  1019  1050 E BluetoothManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
09-01 11:15:18.857  1019  1050 E BluetoothManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
09-01 11:15:18.857  1019  1050 E BluetoothManagerService: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub$Proxy.onBluetoothStateChange(IBluetoothStateChangeCallback.java:84)
09-01 11:15:18.857  1019  1050 E BluetoothManagerService: 	,at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:1053)
09-01 11:15:18.857  1019  1050 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2007)
09-01 11:15:18.857  1019  1050 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
09-01 11:15:18.857  1019  1050 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1576)
09-01 11:15:18.857  1019  1050 E BluetoothManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:18.857  1019  1050 E BluetoothManagerService: 	at android.os.Looper.loop(Looper.java:145)
09-01 11:15:18.857  1019  1050 E BluetoothManagerService: 	,at android.os.HandlerThread.run(HandlerThread.java:61)
09-01 11:15:18.857  1019  1050 E BluetoothManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-01 11:15:18.857  1019  1050 D BluetoothPan: Binding service...
09-01 11:15:18.857  1019  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-01 11:15:18.857  1019  1019 D BluetoothPan: BluetoothPAN Proxy object connected
,09-01 11:15:18.857  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-01 11:15:18.857  1467  3339 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 11:15:18.857  1019  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-01 11:15:18.857  1467  3339 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-01 11:15:18.857  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-01 11:15:18.857  1458  1478 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 11:15:18.857  1458  1478 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-01 11:15:18.857  1019  1050 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 11:15:18.857  1019  1050 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-01 11:15:18.857  7058  7071 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 11:15:18.857  7058  7071 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on,
09-01 11:15:18.867  1019  1019 D BluetoothA2dp: Proxy object connected
09-01 11:15:18.867  1443  1452 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 11:15:18.867  1019  1050 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-01 11:15:18.867  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 11:15:18.867  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:18.867  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-01 11:15:18.867  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth,
,09-01 11:15:18.867  1443  1452 E BluetoothHeadset: BluetoothHeadset service is binded
09-01 11:15:18.867  1443  7285 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 11:15:18.867  1019  1050 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-01 11:15:18.867  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 11:15:18.867  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:18.867  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-01 11:15:18.867  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-01 11:15:18.867  1443  7285 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 11:15:18.877  1696  1705 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 11:15:18.877  1019  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-01 11:15:18.877  1696  1705 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-01 11:15:18.877  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-01 11:15:18.877  1019  1050 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 11:15:18.877  1019  1050 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 11:15:18.877  4723  7261 D BluetoothMap: onBluetoothStateChange: up=true
,09-01 11:15:18.877  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-01 11:15:18.877  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-01 11:15:18.887  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:18.887  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:18.887  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:18.887  4723  4731 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-01 11:15:18.887  4723  4731 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-01 11:15:18.887  4723  4723 D BluetoothMap: Proxy object connected
,09-01 11:15:18.887  4723  4723 D MapProfile: Bluetooth service connected
09-01 11:15:18.887  4723  4723 D BluetoothMap: getConnectedDevices()
09-01 11:15:18.887  1019  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-01 11:15:18.887  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-01 11:15:18.887  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
09-01 11:15:18.887  1019  1019 I InputMethodManagerService: [BT Setting State] State =12
09-01 11:15:18.887  1019  1019 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-01 11:15:18.897  1183  1183 D BluetoothTile:  onBluetoothStateChange:
,09-01 11:15:18.897  1443  1443 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@f5f45a0, true
,09-01 11:15:18.897  1183  1183 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:15:18.897  1183  1183 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-01 11:15:18.897  1183  1183 D BluetoothTile:  getBluetoothState : 12
,09-01 11:15:18.897  1443  1443 D BluetoothHeadset: registerMessageListener
09-01 11:15:18.897  1986  1986 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
09-01 11:15:18.897  1183  1729 D BluetoothTile:  handleUpdatestate:false name:null
09-01 11:15:18.907  4723  4723 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:15:18.907  3228  3246 D HeadsetService: registerMessageListener
,09-01 11:15:18.907  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:18.907  3228  3246 D HeadsetService: registerMessageListener
09-01 11:15:18.907  3228  7763 D HeadsetStateMachine: Disconnected process message: 70
09-01 11:15:18.907  3228  7763 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@21900db7
,09-01 11:15:18.907  1019  1317 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-01 11:15:18.907  1443  1443 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-01 11:15:18.907  1443  1443 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-01 11:15:18.917  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:18.917  4723  4723 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,09-01 11:15:18.917  1019  1344 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
09-01 11:15:18.917  4723  4723 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-01 11:15:18.917  1183  1183 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-01 11:15:18.917  4723  4723 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,09-01 11:15:18.917  4723  4723 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-01 11:15:18.917  1443  1443 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-01 11:15:18.917  1183  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 11:15:18.917  1443  1443 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-01 11:15:18.917  1183  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 11:15:18.917  1443  1443 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-01 11:15:18.927  3228  7791 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-01 11:15:18.927  3228  7763 D HeadsetStateMachine: Disconnected process message: 9
,09-01 11:15:18.927  3228  7763 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-01 11:15:18.927   283   706 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-01 11:15:18.927   283   706 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-01 11:15:18.927   283   706 V voice   : voice_set_parameters: exit with code(-2)
09-01 11:15:18.927   283   706 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-01 11:15:18.927   283   706 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-01 11:15:18.927   283   706 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-01 11:15:18.927   283   706 V audio_hw_primary: adev_set_parameters: exit
09-01 11:15:18.927  3228  7763 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-01 11:15:18.927  3228  7791 D BluetoothSocket: bindListen(): myUserId = 0
09-01 11:15:18.927  3228  7791 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 11:15:18.937  3228  7791 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
09-01 11:15:18.937  4723  4723 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-01 11:15:18.937  3228  7791 D BluetoothSocket: bindListen(), new LocalSocket 
09-01 11:15:18.937  1019  1546 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-01 11:15:18.937  3228  7791 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-01 11:15:18.937  1019  1546 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-01 11:15:18.937  3228  7791 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10dc924
09-01 11:15:18.937  3228  7791 D BluetoothSocket: channel: 5
,09-01 11:15:18.937  1019  1546 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:18.937  1019  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:18.937  1019  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-01 11:15:18.947  1688  1688 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 11:15:18.947  4723  4723 D DockEventReceiver: finishStartingService: stopping service
,09-01 11:15:18.947  4723  4723 D BluetoothNotiBroadcastReceiver: onReceive
,09-01 11:15:18.957  1183  1183 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:15:18.957  1183  1183 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-01 11:15:18.967  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
,09-01 11:15:18.967  3228  3228 D BtConfig.SecureMode: isSecureModeOn:false
,09-01 11:15:18.967  1019  1344 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 11:15:18.967  1019  1344 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-01 11:15:18.967  1019  1344 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:18.967  1019  1344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:18.967  1019  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:18.977  1019  1317 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-01 11:15:18.977  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:18.977  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:18.977  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:18.977  1019  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:18.997  7794  7794 E Zygote  : MountEmulatedStorage(),
09-01 11:15:18.997  7794  7794 E Zygote  : v2
09-01 11:15:18.997  7794  7794 I libpersona: KNOX_SDCARD checking this for 10105
,09-01 11:15:18.997  7794  7794 I libpersona: KNOX_SDCARD not a persona
,09-01 11:15:18.997  7794  7794 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-01 11:15:18.997  7794  7794 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-01 11:15:18.997  1019  1317 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7794 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-01 11:15:19.007  7794  7794 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-01 11:15:19.007  1019  1545 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy,
,09-01 11:15:19.017  3228  7805 D BluetoothSocket: bindListen(): myUserId = 0
09-01 11:15:19.017  3228  7805 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 11:15:19.017  3228  7805 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
,09-01 11:15:19.017  3228  7805 D BluetoothSocket: bindListen(), new LocalSocket 
09-01 11:15:19.017  3228  7805 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-01 11:15:19.017  3228  7805 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2df05390
09-01 11:15:19.017  3228  7805 D BluetoothSocket: channel: 12
09-01 11:15:19.017  3228  7805 I BtOppRfcommListener: Accept thread started.
,09-01 11:15:19.027  1019  3388 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-01 11:15:19.027  7794  7794 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:19.027  7794  7794 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:19.197   257   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-01 11:15:19.197   257   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 11:15:19.197  7794  7816 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-01 11:15:19.207   257   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-01 11:15:19.207   257   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 11:15:19.207  7794  7816 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-01 11:15:19.377  7794  7794 D StrictMode: StrictMode policy violation; ~duration=178 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.io.File.exists(File.java:363)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 11:15:19.377  7794  7794 D StrictMode: StrictMode policy violation; ~duration=177 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 11:15:19.377  7794  7794 D StrictMode: StrictMode policy violation; ~duration=176 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 11:15:19.377  7794  7794 D StrictMode: StrictMode policy violation; ~duration=174 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.q.e.b(PG:170)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 11:15:19.377  7794  7794 D StrictMode: StrictMode policy violation; ~duration=169 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.q.k.d(PG:583)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.q.e.b(PG:170)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 11:15:19.377  7794  7794 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.io.File.exists(File.java:363)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 11:15:19.377  1019  3288 I ActivityManager: Killing 7405:com.sec.pcw.device/1000 (adj 15): empty #21
09-01 11:15:19.377  7794  7794 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.io.File.exists(File.java:363)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 11:15:19.377  7794  7794 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 11:15:19.377  7794  7794 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-01 11:15:19.457  7794  7825 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-01 11:15:19.487  1019  3288 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 11:15:19.487  1019  3288 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:19.487  1019  3288 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 11:15:19.487  1019  3288 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-01 11:15:19.837   334   334 I ServiceManager: Waiting for service AtCmdFwd...,
,09-01 11:15:20.457  1019  1100 V AlarmManager: waitForAlarm result :4
,09-01 11:15:20.467   278  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-01 11:15:20.467   278  1009 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-01 11:15:20.477  1019  1046 W ActivityManager: userId = 0, bbcId = -10000,
09-01 11:15:20.477  1019  1046 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 11:15:20.477  1019  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,09-01 11:15:20.817   295   295 E SMD     : DCD OFF,
,09-01 11:15:20.837   334   334 I ServiceManager: Waiting for service AtCmdFwd...,
,09-01 11:15:21.317  7058  7244 D BluetoothAdapter: disable(),
,09-01 11:15:21.317  1019  1484 D SettingsProvider: name = bluetooth_on,
,09-01 11:15:21.327  3228  3306 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF,
09-01 11:15:21.327  3228  3306 D BluetoothAdapterProperties: Setting state to 13
09-01 11:15:21.327  3228  3306 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-01 11:15:21.327  1019  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 11:15:21.327  3228  3306 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-01 11:15:21.327  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-01 11:15:21.327  3228  3306 D BluetoothAdapterService: updateAdapterState state is 13
,09-01 11:15:21.327  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:21.327  1019  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:21.327  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:21.327  3228  3228 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-01 11:15:21.337  3228  3306 D BluetoothAdapterService: Autoconnection is available 
09-01 11:15:21.337  3228  3306 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-01 11:15:21.337  3228  3306 D BluetoothAdapterService: terminating service from this receiver
09-01 11:15:21.337  1019  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-01 11:15:21.337  1019  1505 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:21.337  3228  3228 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3a29a489, channel: 19, state: LISTENING
09-01 11:15:21.337  3228  3228 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3a29a489, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2230cb6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3ed2fc8emSocket: android.net.LocalSocket@2c9cfcaf impl:android.net.LocalSocketImpl@322f18bc fd:FileDescriptor[80]
09-01 11:15:21.337  3228  3228 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2c9cfcaf impl:android.net.LocalSocketImpl@322f18bc fd:FileDescriptor[80]
09-01 11:15:21.337  1019  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:21.337  1019  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:21.337  3228  3306 D BluetoothAdapterProperties: onBluetoothDisable(),
09-01 11:15:21.337  3228  3306 D BluetoothAdapterProperties: mDiscovering is false
,09-01 11:15:21.337  1019  1546 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-01 11:15:21.337  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-01 11:15:21.337  1019  1019 I InputMethodManagerService: [BT Setting State] State =13
09-01 11:15:21.337  3228  3306 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-01 11:15:21.347  1183  1183 D BluetoothTile:  onBluetoothStateChange:
,09-01 11:15:21.347  1183  1183 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-01 11:15:21.347  1183  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 11:15:21.347  1183  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 11:15:21.347  1183  1183 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:15:21.347  1183  1183 D BluetoothTile:  getBluetoothState : 13
,09-01 11:15:21.357  1183  1729 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-01 11:15:21.357  1019  1505 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-01 11:15:21.357  1019  1546 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-01 11:15:21.357  1183  1183 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-01 11:15:21.357  1986  1986 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-01 11:15:21.367  4723  4723 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:15:21.367  7058  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 11:15:21.367  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-01 11:15:21.367  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:21.367  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:21.367  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false,
09-01 11:15:21.367  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:21.367  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:21.367  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:21.367  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 11:15:21.367  7058  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 11:15:21.367  7058  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:15:21.377  3228  3309 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-01 11:15:21.377  3228  3309 D BluetoothAdapterProperties: Scan Mode:20
09-01 11:15:21.377  3228  3306 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-01 11:15:21.377  3228  3306 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-01 11:15:21.377  3228  3306 E bt-btif : cmd socket is not created
09-01 11:15:21.377  3228  7805 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-01 11:15:21.377  3228  3310 W bt-btif : HAL bt_hal_cbacks->log_collector_cb
09-01 11:15:21.377  3228  3306 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-01 11:15:21.387  3228  3228 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@14ff0045, channel: 5, state: LISTENING
,09-01 11:15:21.387  3228  3228 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@14ff0045, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10dc924, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1d06539amSocket: android.net.LocalSocket@c46b4cb impl:android.net.LocalSocketImpl@253304a8 fd:FileDescriptor[82]
,09-01 11:15:21.387  3228  3228 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@c46b4cb impl:android.net.LocalSocketImpl@253304a8 fd:FileDescriptor[82]
,09-01 11:15:21.387  3228  3228 I BtOppRfcommListener: stopping Accept Thread
09-01 11:15:21.387  3228  3228 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@24145bc1, channel: 12, state: LISTENING
,09-01 11:15:21.387  3228  3228 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@24145bc1, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2df05390, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@8e60f66mSocket: android.net.LocalSocket@3189d2a7 impl:android.net.LocalSocketImpl@2a07c354 fd:FileDescriptor[86]
09-01 11:15:21.387  3228  3228 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3189d2a7 impl:android.net.LocalSocketImpl@2a07c354 fd:FileDescriptor[86]
,09-01 11:15:21.387  3228  7805 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-01 11:15:21.387  7058  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 11:15:21.387  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:21.387  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:21.387  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:21.387  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:15:21.387  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 11:15:21.387  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:21.387  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:21.387  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:15:21.387  7058  7058 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 11:15:21.397  7058  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:15:21.397  3228  3310 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-01 11:15:21.397  3228  3310 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:15:21.397  3228  3310 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 11:15:21.397  3228  3310 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 11:15:21.397  3228  3310 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 11:15:21.397  3228  3310 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-01 11:15:21.397  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:21.397  4723  4723 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-01 11:15:21.397  1019  1545 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-01 11:15:21.397  1019  1545 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-01 11:15:21.397  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:21.397  1019  1545 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:21.397  1019  1545 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:21.397  1019  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-01 11:15:21.407  3228  3228 V BluetoothOppManager: cleanUp...
,09-01 11:15:21.407  1688  1688 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 11:15:21.407  4723  4723 D BluetoothPbap: Proxy object disconnected
,09-01 11:15:21.407  4723  4723 D PbapServerProfile: Bluetooth service disconnected
,09-01 11:15:21.417  4723  4723 D DockEventReceiver: finishStartingService: stopping service
,09-01 11:15:21.417  4723  4723 D BluetoothNotiBroadcastReceiver: onReceive
,09-01 11:15:21.417  1183  1183 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:15:21.417  1183  1183 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-01 11:15:21.577  3228  3306 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-01 11:15:21.577  3228  3306 D BtConfig.SecureMode: isSecureModeOn:false
09-01 11:15:21.577  3228  3306 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-01 11:15:21.577  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
09-01 11:15:21.577  3228  3306 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
09-01 11:15:21.577  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-01 11:15:21.577  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-01 11:15:21.577  1019  1544 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 11:15:21.577  3228  3306 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-01 11:15:21.577  1019  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-01 11:15:21.577  1019  1544 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:21.587  1019  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 11:15:21.587  1019  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:21.587  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,09-01 11:15:21.587  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-01 11:15:21.587  3228  3306 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-01 11:15:21.587  1019  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 11:15:21.587  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-01 11:15:21.587  3228  3228 D HeadsetService: Received stop request...Stopping profile...
,09-01 11:15:21.587  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:21.587  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 11:15:21.587  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:21.597  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,09-01 11:15:21.597  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-01 11:15:21.597  3228  3306 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-01 11:15:21.597  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5,
09-01 11:15:21.597  1019  1505 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 11:15:21.597  1019  1505 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:21.597  1019  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-01 11:15:21.597  1019  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:21.597  1019  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:21.597  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-01 11:15:21.597  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-01 11:15:21.597  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-01 11:15:21.597  3228  3306 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-01 11:15:21.607  3228  3228 D A2dpService: Received stop request...Stopping profile...
09-01 11:15:21.607  1019  6811 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 11:15:21.607  3228  7773 D A2dpStateMachine: Exit Disconnected: -1
09-01 11:15:21.607  1019  6811 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-01 11:15:21.607  1019  6811 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:21.607  1019  6811 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:21.607  1019  6811 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-01 11:15:21.607  4723  4723 D HeadsetProfile: Bluetooth service disconnected
09-01 11:15:21.607  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-01 11:15:21.607  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-01 11:15:21.607  3228  3306 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-01 11:15:21.607  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
,09-01 11:15:21.607  1019  6811 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 11:15:21.607  1019  6811 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-01 11:15:21.607  1019  6811 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:21.607  1019  6811 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 11:15:21.607  1019  6811 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:21.617  1019  1019 D BluetoothA2dp: Proxy object disconnected
09-01 11:15:21.617  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-01 11:15:21.617  4723  4723 D BluetoothA2dp: Proxy object disconnected
09-01 11:15:21.617  4723  4723 D A2dpProfile: Bluetooth service disconnected
,09-01 11:15:21.617  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,09-01 11:15:21.617  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 11:15:21.617  3228  3306 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-01 11:15:21.617  1019  1545 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 11:15:21.617  1019  1545 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0,
09-01 11:15:21.617  1019  1545 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:21.617  1019  1545 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 11:15:21.617  1019  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:21.617  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,09-01 11:15:21.617  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-01 11:15:21.617  3228  3306 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-01 11:15:21.617  1019  1317 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 11:15:21.617  1019  1317 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-01 11:15:21.627  1019  1317 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:21.627  1019  1317 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 11:15:21.627  1019  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:21.627  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-01 11:15:21.627  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-01 11:15:21.627  3228  3306 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-01 11:15:21.627  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,09-01 11:15:21.627  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-01 11:15:21.627  3228  3306 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,09-01 11:15:21.627  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-01 11:15:21.627  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-01 11:15:21.627  3228  3306 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-01 11:15:21.627  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService,
09-01 11:15:21.627  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-01 11:15:21.627  3228  3306 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-01 11:15:21.627  3228  3306 D BluetoothAdapterState: Stopping profile services that were post enabled
09-01 11:15:21.627  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-01 11:15:21.627  3228  3228 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-01 11:15:21.627  3228  3228 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-01 11:15:21.627  3228  3228 D HidService: Received stop request...Stopping profile...
09-01 11:15:21.627  3228  3228 D HidService: Stopping Bluetooth HidService
09-01 11:15:21.627  3228  3228 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-01 11:15:21.627  3228  3228 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-01 11:15:21.627  3228  3228 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-01 11:15:21.627  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
,09-01 11:15:21.637  3228  3228 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-01 11:15:21.637  3228  3228 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-01 11:15:21.637  3228  3228 D HealthService: Received stop request...Stopping profile...
,09-01 11:15:21.637  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
,09-01 11:15:21.637  4723  4723 D BluetoothInputDevice: Proxy object disconnected
09-01 11:15:21.637  4723  4723 D HidProfile: Bluetooth service disconnected
,09-01 11:15:21.637  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-01 11:15:21.637  3228  3228 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-01 11:15:21.637  3228  3228 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-01 11:15:21.637  3228  3228 D PanService: Received stop request...Stopping profile...
09-01 11:15:21.637  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
,09-01 11:15:21.637  3228  3228 D BluetoothA2dp: Proxy object disconnected
09-01 11:15:21.637  1019  1019 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-01 11:15:21.637  3228  3228 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-01 11:15:21.637  3228  7776 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-01 11:15:21.637  3228  3228 I GKI_LINUX: GKI_exit_task 2 done
09-01 11:15:21.637  3228  3228 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-01 11:15:21.637  4723  4723 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-01 11:15:21.637  4723  4723 D PanProfile: Bluetooth service disconnected
09-01 11:15:21.637  3228  3228 D BluetoothMapService: Received stop request...Stopping profile...
,09-01 11:15:21.647  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
,09-01 11:15:21.647  3228  3228 D SapService: Received stop request...Stopping profile...
09-01 11:15:21.647  3228  3228 D SapService: Stopping Bluetooth SapService
09-01 11:15:21.647  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
,09-01 11:15:21.647  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-01 11:15:21.647  3228  3228 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-01 11:15:21.647  3228  3228 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 11:15:21.647  3228  3228 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-01 11:15:21.647  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-01 11:15:21.647  3228  3228 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-01 11:15:21.647  3228  3228 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 11:15:21.647  3228  3228 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-01 11:15:21.647  3228  3228 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-01 11:15:21.647  3228  3228 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-01 11:15:21.647  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
,09-01 11:15:21.647  3228  3228 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-01 11:15:21.647  3228  3228 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 11:15:21.647  3228  3228 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-01 11:15:21.647  3228  3228 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-01 11:15:21.647  3228  3228 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-01 11:15:21.647  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-01 11:15:21.647  3228  3228 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-01 11:15:21.647  3228  3228 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-01 11:15:21.647  3228  3228 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-01 11:15:21.657  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-01 11:15:21.657  4723  4723 D BluetoothMap: Proxy object disconnected,
09-01 11:15:21.657  3228  3228 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-01 11:15:21.657  4723  4723 D MapProfile: Bluetooth service disconnected
09-01 11:15:21.657  4723  4723 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-01 11:15:21.657  4723  4723 D SapProfile: Bluetooth service disconnected
09-01 11:15:21.657  3228  3228 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,09-01 11:15:21.657  3228  3228 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-01 11:15:21.657  3228  3306 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-01 11:15:21.657  3228  3306 D BluetoothAdapterProperties: Setting state to 10
09-01 11:15:21.657  3228  3306 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-01 11:15:21.657  3228  3306 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-01 11:15:21.657  3228  3306 D BluetoothAdapterService: updateAdapterState state is 10
,09-01 11:15:21.657  3228  3306 D BluetoothAdapterService: Autoconnection is available 
09-01 11:15:21.657  3228  3306 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-01 11:15:21.657  3228  3306 I BluetoothAdapterState: Entering OffState
09-01 11:15:21.657  3228  7790 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-01 11:15:21.657  7794  7804 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 11:15:21.657  7794  7804 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 11:15:21.657  1688  1775 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 11:15:21.657  1688  1775 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 11:15:21.657  4723  4731 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-01 11:15:21.657  4723  4732 D Bluetoothsap: onBluetoothStateChange: up=false
09-01 11:15:21.657  4723  4732 D Bluetoothsap: Unbinding service...
,09-01 11:15:21.657  4723  7261 D BluetoothPbap: onBluetoothStateChange: up=false
,09-01 11:15:21.657  1019  1050 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-01 11:15:21.667  1019  1050 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 11:15:21.667  4723  4731 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-01 11:15:21.667  1443  7285 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-01 11:15:21.667  1443  7285 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 11:15:21.667  3228  7789 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-01 11:15:21.667  3228  7789 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 11:15:21.667  1183  1973 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-01 11:15:21.667  1183  1973 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 11:15:21.667  1467  1660 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-01 11:15:21.667  1467  1660 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 11:15:21.667  1458  1478 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-01 11:15:21.667  1458  1478 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 11:15:21.667  1019  1050 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-01 11:15:21.677  7058  7066 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-01 11:15:21.677  7058  7066 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 11:15:21.677  7058  7066 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-01 11:15:21.677  7058  7066 D BluetoothLeAdvertiser: Exit stop advertising
,09-01 11:15:21.677  7058  7066 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-01 11:15:21.677  7058  7066 D BluetoothLeScanner: Exiting stopAllScan
,09-01 11:15:21.677  1696  1705 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-01 11:15:21.677  1696  1705 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 11:15:21.677  4723  7261 D BluetoothMap: onBluetoothStateChange: up=false
,09-01 11:15:21.677  4723  4731 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 11:15:21.677  4723  4731 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 11:15:21.687  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:15:21.687  1019  1019 I InputMethodManagerService: [BT Setting State] State =10
,09-01 11:15:21.687  1019  1019 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-01 11:15:21.687  1183  1183 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-01 11:15:21.687  1183  1183 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED,
09-01 11:15:21.687  1183  1183 D BluetoothTile:  getBluetoothState : 10
,09-01 11:15:21.697  1986  1986 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-01 11:15:21.697  1019  3288 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-01 11:15:21.697  4723  4723 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:15:21.697  1019  1032 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-01 11:15:21.697  1183  1183 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-01 11:15:21.697  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:21.697  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:21.707  4723  4723 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-01 11:15:21.707  1019  6811 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-01 11:15:21.707  1019  6811 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-01 11:15:21.707  1019  6811 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:21.707  1019  6811 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:21.707  1019  6811 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-01 11:15:21.717  1688  1688 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 11:15:21.717  4723  4723 D DockEventReceiver: finishStartingService: stopping service
,09-01 11:15:21.717  4723  4723 D BluetoothNotiBroadcastReceiver: onReceive
,09-01 11:15:21.727  1183  1183 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:15:21.727  1183  1183 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-01 11:15:21.837   334   334 I ServiceManager: Waiting for service AtCmdFwd...
,09-01 11:15:21.937  1019  1484 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-01 11:15:21.947  1019  1484 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4285, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-01 11:15:21.947  1019  1484 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-01 11:15:21.947  1019  1484 D BatteryService: stay LED for charging
,09-01 11:15:21.947  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-01 11:15:21.947  1019  1019 I MotionRecognitionService: Plugged
,09-01 11:15:21.947  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,09-01 11:15:21.957  1183  1183 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-01 11:15:21.957  1183  1183 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-01 11:15:21.957  1424  1424 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-01 11:15:21.957  1424  1424 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-01 11:15:21.977  1183  1183 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-01 11:15:21.977  1183  1183 D SViewCoverView: level :100 plugged : 2
,09-01 11:15:21.977  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-01 11:15:21.977  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
,09-01 11:15:21.987  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-01 11:15:22.837   334   334 I ServiceManager: Waiting for service AtCmdFwd...,
,09-01 11:15:23.817   295   295 E SMD     : DCD OFF,
,09-01 11:15:23.837   334   334 I ServiceManager: Waiting for service AtCmdFwd...,
,09-01 11:15:24.327  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 11:15:24.327  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:15:24.837   334   334 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,09-01 11:15:26.827   295   295 E SMD     : DCD OFF,
,09-01 11:15:27.337  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 11:15:27.337  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1adadf6 added. We now have 6 listener(s)
,09-01 11:15:27.337  7058  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:15:27.337  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 11:15:27.337  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@243835f7 added. We now have 7 listener(s)
,09-01 11:15:27.337  7058  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:15:27.337  7058  7244 I System.out: IsBluetoothEnabled
,09-01 11:15:27.347  7058  7244 D BluetoothAdapter: disable()
,09-01 11:15:27.347  1019  1544 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-01 11:15:27.347  7058  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:27.347  7058  7244 D BluetoothAdapter: enable()
,09-01 11:15:27.357  1019  1546 W ActivityManager: Permission Denial: getCurrentUser() from pid=7058, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-01 11:15:27.357  1019  1546 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-01 11:15:27.357  1019  1546 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7058, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-01 11:15:27.357  1019  1546 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-01 11:15:27.357  1019  1546 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-01 11:15:27.357  1019  1546 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-01 11:15:27.357  1019  1546 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-01 11:15:27.357  1019  1546 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-01 11:15:27.357  1019  1546 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-01 11:15:27.357  1019  1546 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-01 11:15:27.367  1019  1546 D SettingsProvider: name = bluetooth_on,
,09-01 11:15:27.377  1019  1050 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
09-01 11:15:27.377  1019  1050 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-01 11:15:27.387  1019  1050 D SecContentProvider: uri = 3 selection = isBluetoothEnabled,
,09-01 11:15:27.387  3228  3306 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
09-01 11:15:27.387  3228  3306 D BluetoothAdapterProperties: Setting state to 11,
09-01 11:15:27.387  3228  3306 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11,
09-01 11:15:27.387  3228  3306 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-01 11:15:27.387  3228  3306 D BluetoothAdapterService: updateAdapterState state is 11
09-01 11:15:27.387  3228  3306 D BluetoothAdapterService: Autoconnection is available 
09-01 11:15:27.387  3228  3306 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-01 11:15:27.387  3228  3306 D BtConfig.SecureMode: isSecureModeOn:false
09-01 11:15:27.387  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-01 11:15:27.387  3228  3306 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
09-01 11:15:27.387  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-01 11:15:27.387  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-01 11:15:27.387  3228  3306 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
09-01 11:15:27.387  1019  1019 I InputMethodManagerService: [BT Setting State] State =11
09-01 11:15:27.387  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-01 11:15:27.387  3228  3306 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-01 11:15:27.387  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-01 11:15:27.387  3228  3306 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-01 11:15:27.387  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-01 11:15:27.387  3228  3306 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-01 11:15:27.387  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-01 11:15:27.387  3228  3306 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-01 11:15:27.387  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 11:15:27.387  3228  3306 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-01 11:15:27.387  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-01 11:15:27.387  3228  3306 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-01 11:15:27.387  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-01 11:15:27.387  3228  3306 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-01 11:15:27.387  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-01 11:15:27.387  3228  3306 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-01 11:15:27.387  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-01 11:15:27.387  3228  3306 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-01 11:15:27.387  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-01 11:15:27.387  3228  3306 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-01 11:15:27.387  3228  3306 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-01 11:15:27.387  3228  3306 W BluetoothAdapterService: check For Quiet mode, profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-01 11:15:27.387  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-01 11:15:27.387  3228  3306 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-01 11:15:27.397  1183  1183 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-01 11:15:27.397  1986  1986 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-01 11:15:27.397  1183  1183 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:15:27.397  4723  4723 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:15:27.397  1183  1183 D BluetoothTile:  getBluetoothState : 11
,09-01 11:15:27.397  1019  3288 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-01 11:15:27.397  1019  1484 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-01 11:15:27.397  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:27.397  1019  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 11:15:27.407  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-01 11:15:27.407  1183  1183 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-01 11:15:27.407  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:27.407  1019  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:27.407  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:27.407  1183  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 11:15:27.407  1183  1729 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-01 11:15:27.407  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-01 11:15:27.407  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-01 11:15:27.407  3228  3306 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-01 11:15:27.407  3228  3228 D HeadsetService: Received start request. Starting profile...
09-01 11:15:27.407  3228  3228 D HeadsetService: start()
09-01 11:15:27.407  3228  3228 D HeadsetStateMachine: make
,09-01 11:15:27.407  1688  1688 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 11:15:27.417  1019  1545 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 11:15:27.417  1019  1545 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-01 11:15:27.417  1019  1545 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:27.417  1019  1545 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:27.417  1019  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:27.417  3228  3228 E HeadsetStateMachine: # of Max HF connection is 2
,09-01 11:15:27.417  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,09-01 11:15:27.417  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-01 11:15:27.417  3228  3306 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-01 11:15:27.417  1019  1344 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-01 11:15:27.417  1019  1344 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-01 11:15:27.427  1019  1344 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:27.427  1019  1344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:27.427  1019  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-01 11:15:27.427  1019  1505 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 11:15:27.427  1019  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-01 11:15:27.427  1019  1505 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:27.427  1019  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:27.427  1019  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:27.427  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,09-01 11:15:27.427  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-01 11:15:27.427  3228  3306 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-01 11:15:27.427  4723  4723 D BluetoothNotiBroadcastReceiver: onReceive
,09-01 11:15:27.437  1183  1183 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:15:27.437  1019  6683 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 11:15:27.437  1183  1183 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
09-01 11:15:27.437  1019  6683 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-01 11:15:27.437  1019  6683 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:27.437  1019  6683 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:27.437  1019  6683 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:27.437  1019  1484 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-01 11:15:27.437  1019  1484 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-01 11:15:27.437  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-01 11:15:27.437  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-01 11:15:27.437  3228  3306 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-01 11:15:27.437  1019  1484 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:27.437  1019  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:27.437  1019  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-01 11:15:27.447  3228  3228 I bluedroid: get_profile_interface handsfree
,09-01 11:15:27.447  1019  1544 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 11:15:27.447  1019  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-01 11:15:27.447  1019  1544 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:27.447  1019  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:27.447  1019  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:27.457  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,09-01 11:15:27.457  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 11:15:27.457  3228  3306 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-01 11:15:27.457  1019  1344 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 11:15:27.467  1019  1344 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-01 11:15:27.467  1019  1344 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:27.467  1019  1344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 11:15:27.467  1019  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:27.467  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-01 11:15:27.467  1019  3365 D SSRM:n  : SIOP:: AP = 330
,09-01 11:15:27.467  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-01 11:15:27.467  3228  3306 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-01 11:15:27.467  3228  3228 E DualScoManager: Dual Sco Manager already instantiated
,09-01 11:15:27.467  3228  3228 I DualScoManager: Set HeadsetServiceHelper
09-01 11:15:27.467  3228  3228 D BluetoothAtMessage: createCMTIContentObservers
,09-01 11:15:27.467  1019  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 11:15:27.467  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-01 11:15:27.477  1019  6811 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-01 11:15:27.477  1019  6811 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 11:15:27.477  1019  6811 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-01 11:15:27.477  1019  6811 D SettingsProvider: selectionArgs: false
09-01 11:15:27.477  1019  6811 D SettingsProvider: selectionArgs: 1002
,09-01 11:15:27.477  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:27.477  1019  6811 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 11:15:27.477  1019  6811 D SettingsProvider: ret = -1
09-01 11:15:27.477  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:27.477  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:27.477  3228  7842 D HeadsetStateMachine: Enter Disconnected: -2
,09-01 11:15:27.477  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-01 11:15:27.477  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-01 11:15:27.477  3228  3306 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-01 11:15:27.477  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-01 11:15:27.477  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-01 11:15:27.477  3228  3306 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,09-01 11:15:27.477  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-01 11:15:27.477  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-01 11:15:27.477  3228  3306 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-01 11:15:27.477  3228  3306 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
,09-01 11:15:27.477  3228  3306 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-01 11:15:27.477  3228  3306 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,09-01 11:15:27.477  3228  3306 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-01 11:15:27.477  3228  3228 D HeadsetService: mStartError = false
09-01 11:15:27.477  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
09-01 11:15:27.487  3228  3228 D A2dpService: Received start request. Starting profile...
09-01 11:15:27.487  3228  3228 D A2dpService: start()
09-01 11:15:27.487  3228  3228 I bluedroid: get_profile_interface avrcp
,09-01 11:15:27.487  3228  7842 D HeadsetStateMachine: Clear mHeadsetBrsf
,09-01 11:15:27.487  3228  7842 D HeadsetStateMachine: map size, before remove : 0
09-01 11:15:27.487  3228  7842 D HeadsetStateMachine: map size, after remove: 0
,09-01 11:15:27.487  3228  3228 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-01 11:15:27.487  3228  3228 D Avrcp   : Initialize Media Controller
09-01 11:15:27.487  3228  3228 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-01 11:15:27.487  3228  3228 E Avrcp   : getActiveSessions
,09-01 11:15:27.487  3228  3228 D Avrcp   : pick active media Controller
09-01 11:15:27.487  3228  3228 D Avrcp   : Get the active Media Controller 
,09-01 11:15:27.497  3228  3228 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-01 11:15:27.497  3228  3228 D A2dpStateMachine: make
,09-01 11:15:27.497  3228  7843 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-01 11:15:27.497  3228  3228 I bluedroid: get_profile_interface a2dp
09-01 11:15:27.497  3228  7845 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-01 11:15:27.497  3228  3228 E bt-btif : warning : media task started media_task_refcnt 1 
,09-01 11:15:27.497  3228  3228 D A2dpService: mStartError = false
09-01 11:15:27.497  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
09-01 11:15:27.497  3228  3228 D HeadsetStateMachine: Try to query the phonestate on bind
09-01 11:15:27.497  1443  1453 I Telecom : BluetoothPhoneService: queryPhoneState
09-01 11:15:27.497  3228  7844 D A2dpStateMachine: Enter Disconnected: -2
,09-01 11:15:27.497  1443  1443 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-01 11:15:27.497  1443  1443 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-01 11:15:27.507  1443  1453 I Telecom : BluetoothPhoneService: Result of Message : true
,09-01 11:15:27.507  3228  3228 D HidService: Received start request. Starting profile...
,09-01 11:15:27.507  3228  3228 D HidService: start()
09-01 11:15:27.507  3228  3228 I bluedroid: get_profile_interface hidhost
09-01 11:15:27.507  3228  3228 D HidService: setHidService(): set to: null
09-01 11:15:27.507  3228  3228 D HidService: mStartError = false
09-01 11:15:27.507  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
,09-01 11:15:27.507  3228  3228 D HealthService: Received start request. Starting profile...
09-01 11:15:27.507  3228  3228 D HealthService: start()
,09-01 11:15:27.507  3228  3228 I bluedroid: get_profile_interface health
09-01 11:15:27.507  3228  3228 D HealthService: mStartError = false
09-01 11:15:27.507  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
09-01 11:15:27.507  3228  3228 D HeadsetStateMachine: Proxy object connected
09-01 11:15:27.507  3228  3228 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-01 11:15:27.507  3228  7842 D HeadsetStateMachine: Disconnected process message: 11
09-01 11:15:27.507  3228  3228 D PanService: Received start request. Starting profile...
09-01 11:15:27.507  3228  3228 D PanService: start()
09-01 11:15:27.507  3228  3228 D BluetoothPanServiceJni: initializeNative(L110): pan
09-01 11:15:27.507  3228  3228 I bluedroid: get_profile_interface pan
09-01 11:15:27.507  3228  3228 D PanService: mStartError = false
09-01 11:15:27.507  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
09-01 11:15:27.507  3228  3228 D HeadsetPhoneState: sendDeviceDataStateChanged
09-01 11:15:27.507  3228  3228 D HeadsetPhoneState: Signal level : previous=0 curr=4
,09-01 11:15:27.507  3228  7842 D HeadsetStateMachine: Disconnected process message: 18
09-01 11:15:27.507  3228  3228 D BluetoothMapService: Received start request. Starting profile...
09-01 11:15:27.507  3228  3228 D BluetoothMapService: start()
,09-01 11:15:27.517  3228  3228 D BluetoothMapService: mStartError = false
09-01 11:15:27.517  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
,09-01 11:15:27.517  3228  3228 D SapService: Received start request. Starting profile...
,09-01 11:15:27.517  3228  3228 D SapService: start()
09-01 11:15:27.517  3228  3228 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-01 11:15:27.517  3228  3228 I bluedroid: get_profile_interface sap
09-01 11:15:27.517  3228  3228 D SapService: mStartError = false
,09-01 11:15:27.517  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
09-01 11:15:27.517  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-01 11:15:27.517  3228  3228 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-01 11:15:27.517  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-01 11:15:27.517  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true,
09-01 11:15:27.517  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-01 11:15:27.517  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
09-01 11:15:27.517  3228  7842 D HeadsetStateMachine: Disconnected process message: 10
,09-01 11:15:27.517  3228  7842 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-01 11:15:27.517  3228  7842 D HeadsetStateMachine: Disconnected process message: 11
,09-01 11:15:27.517  3228  7843 D BluetoothMediaBrowser: no now playing list
09-01 11:15:27.517  3228  7843 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-01 11:15:27.527  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-01 11:15:27.527  3228  3228 E BluetoothAdapterService(531254469): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-01 11:15:27.537  3228  3306 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false,
09-01 11:15:27.537  3228  3306 I bluedroid: enable
,09-01 11:15:27.537  3228  3309 E bt-btif : Calling BTA_HhEnable
,09-01 11:15:27.537  3228  3309 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-01 11:15:27.537  3228  3309 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-01 11:15:27.537  3228  3309 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-01 11:15:27.537  3228  3309 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
,09-01 11:15:27.537  3228  3309 E BluetoothServiceJni: populateRssiValuesNative
09-01 11:15:27.537  3228  3309 I bluedroid: getModelRssiValues
,09-01 11:15:27.547  3228  3309 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-01 11:15:27.547  3228  3309 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-01 11:15:27.547  1019  1019 D SettingsProvider: name = bluetooth_name
,09-01 11:15:27.547  3228  3309 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-01 11:15:27.547  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:27.547  3228  3309 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-01 11:15:27.557  3228  3309 D BluetoothAdapterProperties: Scan Mode:20
09-01 11:15:27.557  3228  3309 D BluetoothAdapterProperties: Discoverable Timeout:120
09-01 11:15:27.557  3228  3309 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
09-01 11:15:27.557  3228  3309 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
09-01 11:15:27.557  3228  3309 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,09-01 11:15:27.557  3228  3309 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-01 11:15:27.557  3228  3309 E bt-btif : JVenable fails
,09-01 11:15:27.557  3228  3309 D bte_conf: Device ID record 1 : primary
09-01 11:15:27.557  3228  3309 D bte_conf:   vendorId            = 0075
09-01 11:15:27.557  3228  3309 D bte_conf:   vendorIdSource      = 0001
,09-01 11:15:27.557  3228  3309 D bte_conf:   product             = 0100
09-01 11:15:27.557  3228  3309 D bte_conf:   version             = 0200
09-01 11:15:27.557  3228  3309 D bte_conf:   clientExecutableURL = 
09-01 11:15:27.557  3228  3309 D bte_conf:   serviceDescription  = 
,09-01 11:15:27.557  3228  3309 D bte_conf:   documentationURL    = 
,09-01 11:15:27.557  3228  3309 D bte_conf: bte_load_did_conf no section named DID2.
,09-01 11:15:27.557  3228  3306 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-01 11:15:27.557  3228  3306 D BluetoothAdapterProperties: ScanMode =  20
09-01 11:15:27.557  3228  3306 D BluetoothAdapterProperties: State =  11
,09-01 11:15:27.557  3228  3309 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-01 11:15:27.557  1019  1544 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-01 11:15:27.557  3228  3309 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-01 11:15:27.557  3228  3306 D BluetoothAdapterProperties: Setting state to 12
09-01 11:15:27.557  3228  3306 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-01 11:15:27.557  3228  3309 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-01 11:15:27.557  3228  3309 D BluetoothAdapterProperties: Scan Mode:21
09-01 11:15:27.557  3228  3309 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-01 11:15:27.567  1019  1031 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-01 11:15:27.567  1019  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 11:15:27.567  1019  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 11:15:27.567  1019  1031 D SettingsProvider: selectionArgs: false
09-01 11:15:27.567  1019  1031 D SettingsProvider: selectionArgs: 1002
,09-01 11:15:27.567  1019  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 11:15:27.567  1019  1031 D SettingsProvider: ret = -1
,09-01 11:15:27.567  3228  3306 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-01 11:15:27.567  3228  3306 D BluetoothAdapterService: updateAdapterState state is 12
09-01 11:15:27.567  1019  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 11:15:27.567  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-01 11:15:27.567  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:27.567  1019  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:27.567  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:27.567  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:27.567  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:27.567  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:27.567  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:15:27.567  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:27.567  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:27.567  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:27.567  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:15:27.567  3228  3306 D BluetoothAdapterService: Autoconnection is available 
09-01 11:15:27.567  3228  3306 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-01 11:15:27.567  3228  3306 D BluetoothAdapterService: starting service from this receiver
,09-01 11:15:27.567  3228  3393 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-01 11:15:27.577  3228  3228 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12,
,09-01 11:15:27.577  3228  3228 I BluetoothPbapService: Handler(): got msg=1
,09-01 11:15:27.577  3228  3393 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-01 11:15:27.577  1019  1344 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 11:15:27.577  1019  1344 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-01 11:15:27.577  1019  1546 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-01 11:15:27.577  1019  1344 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:27.577  1019  1344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:27.577  1019  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:27.577  7058  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:15:27.587  1019  1050 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-01 11:15:27.587  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-01 11:15:27.587  3228  3306 I BluetoothAdapterState: Entering On State from state = 11
,09-01 11:15:27.587  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:27.587  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:27.587  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:27.587  7794  7808 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-01 11:15:27.587  7794  7808 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 11:15:27.587  4723  4732 D BluetoothPan: Binding service...
,09-01 11:15:27.587  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-01 11:15:27.587  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-01 11:15:27.587  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:27.587  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:27.587  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:27.587  1443  7285 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 11:15:27.597  3228  7850 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-01 11:15:27.597  1019  1050 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-01 11:15:27.597  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 11:15:27.597  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:27.597  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:27.597  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:27.597  1443  7285 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 11:15:27.597  1688  1706 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 11:15:27.597  1688  1706 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 11:15:27.597  3228  7850 D BluetoothSocket: bindListen(): myUserId = 0,
09-01 11:15:27.597  3228  7850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 11:15:27.597  4723  7261 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-01 11:15:27.597  3228  7850 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-01 11:15:27.597  3228  7850 D BluetoothSocket: bindListen(), new LocalSocket 
09-01 11:15:27.597  3228  7850 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-01 11:15:27.597  3228  7850 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@30a28d4c
,09-01 11:15:27.597  3228  7850 D BluetoothSocket: channel: 19
09-01 11:15:27.597  3228  7850 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-01 11:15:27.597  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-01 11:15:27.607  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-01 11:15:27.607  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:27.607  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:27.607  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:27.607  4723  4723 D BluetoothPan: BluetoothPAN Proxy object connected
,09-01 11:15:27.607  4723  4732 D Bluetoothsap: onBluetoothStateChange: up=true
09-01 11:15:27.607  4723  4732 D Bluetoothsap: Binding service...
,09-01 11:15:27.607  3228  3228 D BluetoothA2dp: Proxy object connected
09-01 11:15:27.607  3228  3228 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-01 11:15:27.607  4723  4723 D PanProfile: Bluetooth service connected
,09-01 11:15:27.607  4723  4732 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-01 11:15:27.607  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-01 11:15:27.607  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-01 11:15:27.617  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:27.617  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:27.617  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:27.617  4723  4732 D Bluetoothsap: bindService called to Bluetooth SAP Service
09-01 11:15:27.617  4723  4731 D BluetoothPbap: onBluetoothStateChange: up=true
,09-01 11:15:27.617  4723  4723 D BluetoothInputDevice: Proxy object connected
09-01 11:15:27.617  4723  4723 D HidProfile: Bluetooth service connected
,09-01 11:15:27.617  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-01 11:15:27.617  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-01 11:15:27.617  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:27.617  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:27.617  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:27.617  1019  1050 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 11:15:27.617  1019  1050 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 11:15:27.617  4723  4732 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-01 11:15:27.617  4723  4723 D Bluetoothsap: BluetoothSAP Proxy object connected
09-01 11:15:27.617  4723  4732 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-01 11:15:27.617  4723  4723 D SapProfile: Bluetooth service connected
09-01 11:15:27.617  4723  4723 D Bluetoothsap: getConnectedDevices()
,09-01 11:15:27.617  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-01 11:15:27.617  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-01 11:15:27.617  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:27.617  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:27.617  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:27.617  1443  1453 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-01 11:15:27.617  1443  1453 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 11:15:27.617  3228  7789 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 11:15:27.617  3228  7789 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 11:15:27.627  1467  1660 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 11:15:27.627  4723  4723 D BluetoothPbap: Proxy object connected
09-01 11:15:27.627  1019  1050 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-01 11:15:27.627  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 11:15:27.627  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:27.627  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:27.627  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:27.627  1467  1660 E BluetoothHeadset: BluetoothHeadset service is binded
09-01 11:15:27.627  4723  4723 D PbapServerProfile: Bluetooth service connected
09-01 11:15:27.627  4723  4723 D BluetoothA2dp: Proxy object connected
09-01 11:15:27.627  4723  4723 D A2dpProfile: Bluetooth service connected
,09-01 11:15:27.627  1183  4811 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-01 11:15:27.627  1183  4811 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 11:15:27.627  4723  4731 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 11:15:27.627  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-01 11:15:27.627  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 11:15:27.627  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:27.627  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 11:15:27.627  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:27.627  4723  4723 D HeadsetProfile: Bluetooth service connected
,09-01 11:15:27.637  4723  4731 E BluetoothHeadset: BluetoothHeadset service is binded
09-01 11:15:27.637  1019  1050 D BluetoothPan: Binding service...
,09-01 11:15:27.637  1019  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-01 11:15:27.637  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-01 11:15:27.637  1019  1019 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 11:15:27.637  1467  3339 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-01 11:15:27.637  1467  3339 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-01 11:15:27.637  1458  1470 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 11:15:27.637  1458  1470 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-01 11:15:27.637  1019  1050 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 11:15:27.637  1019  1050 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-01 11:15:27.637  1019  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-01 11:15:27.637  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-01 11:15:27.637  7058  7071 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 11:15:27.637  7058  7071 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 11:15:27.637  1019  1019 D BluetoothA2dp: Proxy object connected
,09-01 11:15:27.637  1443  7285 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 11:15:27.637  1019  1050 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-01 11:15:27.637  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 11:15:27.637  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:27.637  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 11:15:27.637  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:27.637  1443  7285 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 11:15:27.637  1443  1453 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 11:15:27.647  1019  1050 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-01 11:15:27.647  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 11:15:27.647  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:27.647  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 11:15:27.647  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:27.647  1443  1453 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 11:15:27.647  1696  1705 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-01 11:15:27.647  1696  1705 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-01 11:15:27.647  1019  1050 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 11:15:27.647  1019  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-01 11:15:27.647  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 11:15:27.647  1019  1050 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 11:15:27.647  4723  4732 D BluetoothMap: onBluetoothStateChange: up=true,
09-01 11:15:27.647  1019  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-01 11:15:27.657  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-01 11:15:27.657  1019  1050 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:27.657  1019  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 11:15:27.657  1019  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:27.657  4723  4731 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 11:15:27.657  4723  4723 D BluetoothMap: Proxy object connected
09-01 11:15:27.657  4723  4723 D MapProfile: Bluetooth service connected
09-01 11:15:27.657  4723  4723 D BluetoothMap: getConnectedDevices()
,09-01 11:15:27.657  4723  4731 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 11:15:27.657  1019  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-01 11:15:27.657  1019  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-01 11:15:27.657  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:15:27.657  1019  1019 I InputMethodManagerService: [BT Setting State] State =12
,09-01 11:15:27.657  1019  1019 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-01 11:15:27.667  1183  1183 D BluetoothTile:  onBluetoothStateChange:
,09-01 11:15:27.667  1443  1443 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@c879559, true
,09-01 11:15:27.667  1443  1443 D BluetoothHeadset: registerMessageListener
,09-01 11:15:27.667  1183  1183 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-01 11:15:27.667  1183  1183 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-01 11:15:27.667  1183  1183 D BluetoothTile:  getBluetoothState : 12
,09-01 11:15:27.677  1183  1729 D BluetoothTile:  handleUpdatestate:false name:null
09-01 11:15:27.677  1986  1986 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-01 11:15:27.677  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:27.677  1019  3288 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-01 11:15:27.677  1019  1317 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-01 11:15:27.677  1183  1183 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-01 11:15:27.687  1183  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 11:15:27.687  1183  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 11:15:27.687  3228  3393 D HeadsetService: registerMessageListener
,09-01 11:15:27.687  4723  4723 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:15:27.687  3228  3393 D HeadsetService: registerMessageListener
09-01 11:15:27.687  3228  7842 D HeadsetStateMachine: Disconnected process message: 70
,09-01 11:15:27.687  1443  1443 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,09-01 11:15:27.687  3228  7842 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@119fc2aa
09-01 11:15:27.687  1443  1443 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-01 11:15:27.687  1443  1443 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-01 11:15:27.687  1443  1443 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-01 11:15:27.687  1443  1443 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-01 11:15:27.687  3228  7851 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-01 11:15:27.687  4723  4723 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,09-01 11:15:27.687  4723  4723 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-01 11:15:27.687  4723  4723 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-01 11:15:27.687  4723  4723 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-01 11:15:27.697  3228  7842 D HeadsetStateMachine: Disconnected process message: 9,
09-01 11:15:27.697  3228  7842 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-01 11:15:27.697  3228  7851 D BluetoothSocket: bindListen(): myUserId = 0
09-01 11:15:27.697  3228  7851 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 11:15:27.697   283   707 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-01 11:15:27.697   283   707 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-01 11:15:27.697   283   707 V voice   : voice_set_parameters: exit with code(-2)
,09-01 11:15:27.697   283   707 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-01 11:15:27.697   283   707 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-01 11:15:27.697  3228  7851 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
09-01 11:15:27.697  3228  7851 D BluetoothSocket: bindListen(), new LocalSocket 
09-01 11:15:27.697  3228  7851 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-01 11:15:27.697  3228  7851 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@27d1de9b
,09-01 11:15:27.697   283   707 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-01 11:15:27.697   283   707 V audio_hw_primary: adev_set_parameters: exit
09-01 11:15:27.697  3228  7851 D BluetoothSocket: channel: 5
09-01 11:15:27.697  3228  7842 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-01 11:15:27.697  4723  4723 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-01 11:15:27.697  1019  3288 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-01 11:15:27.697  1019  3288 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:27.697  1019  3288 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-01 11:15:27.697  1019  3288 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:27.697  1019  3288 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-01 11:15:27.707  1688  1688 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 11:15:27.707  4723  4723 D DockEventReceiver: finishStartingService: stopping service
,09-01 11:15:27.707  4723  4723 D BluetoothNotiBroadcastReceiver: onReceive
,09-01 11:15:27.717  1183  1183 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 11:15:27.717  1183  1183 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-01 11:15:27.717  3228  3228 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1faa4cc5
,09-01 11:15:27.717  3228  3228 D BtConfig.SecureMode: isSecureModeOn:false
,09-01 11:15:27.727  1019  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 11:15:27.727  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-01 11:15:27.727  1019  1032 W ActivityManager: userId = 0, bbcId = -10000,
09-01 11:15:27.727  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:27.727  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 11:15:27.737  1019  1344 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-01 11:15:27.747  3228  7856 D BluetoothSocket: bindListen(): myUserId = 0
09-01 11:15:27.747  3228  7856 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 11:15:27.747  3228  7856 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
09-01 11:15:27.747  3228  7856 D BluetoothSocket: bindListen(), new LocalSocket 
09-01 11:15:27.747  3228  7856 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-01 11:15:27.747  3228  7856 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a65c977
,09-01 11:15:27.747  3228  7856 D BluetoothSocket: channel: 12
09-01 11:15:27.747  3228  7856 I BtOppRfcommListener: Accept thread started.
,09-01 11:15:28.387  7058  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:28.387  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:28.387  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:28.387  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 11:15:28.387  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:28.387  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:28.387  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:28.387  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:15:28.387  7058  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:15:28.387  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 11:15:28.387  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6a6c64 added. We now have 8 listener(s)
,09-01 11:15:28.387  7058  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:15:28.397  1019  1317 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-01 11:15:28.397  1019  1317 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-01 11:15:28.397  1019  1317 D SecContentProvider2: mCursor = null
,09-01 11:15:28.397  1019  1317 D WifiService: setWifiEnabled: false pid=7058, uid=10170
,09-01 11:15:28.397  1019  1317 D SettingsProvider: name = wifi_on
,09-01 11:15:28.397  7058  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:28.397  1019  6811 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-01 11:15:28.397  1019  6811 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-01 11:15:28.407  1019  6811 D SecContentProvider2: mCursor = null
,09-01 11:15:28.407  1019  6811 D WifiService: setWifiEnabled: true pid=7058, uid=10170
,09-01 11:15:28.407  1019  6811 W ActivityManager: Permission Denial: getCurrentUser() from pid=7058, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-01 11:15:28.407  1019  6811 W WifiService: Failed getting userId using ActivityManagerNative
09-01 11:15:28.407  1019  6811 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7058, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-01 11:15:28.407  1019  6811 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-01 11:15:28.407  1019  6811 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-01 11:15:28.407  1019  6811 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-01 11:15:28.407  1019  6811 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-01 11:15:28.407  1019  6811 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-01 11:15:28.407  1019  6811 D SettingsProvider: name = wifi_on
,09-01 11:15:28.417  1019  1132 E WifiHW  : ##################### set firmware type 0 #####################
,09-01 11:15:28.737  1019  1048 D Tethering: interfaceAdded wlan0
,09-01 11:15:28.757  1019  1135 E Tethering: No numeric data
09-01 11:15:28.757  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 11:15:28.757  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 11:15:28.757  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
,09-01 11:15:28.757  1019  1135 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-01 11:15:28.767  1019  1048 D Tethering: interfaceAdded p2p0
09-01 11:15:28.767  1019  1135 D Tethering: clearTetheredNotification()
09-01 11:15:28.767  1019  1135 D Tethering: InitialState.processMessage what=4
,09-01 11:15:28.767  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
09-01 11:15:28.767  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 11:15:28.777  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated,
09-01 11:15:28.777  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
,09-01 11:15:28.777   278  1013 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-01 11:15:28.777   278  1013 D SoftapController: Softap fwReload - Ok
09-01 11:15:28.777  1183  1183 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-01 11:15:28.777  1019  1135 E Tethering: No numeric data
09-01 11:15:28.777  1183  1183 D HotspotTile: updateTetherState():false, false
09-01 11:15:28.777  1019  1048 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-01 11:15:28.777  1019  1135 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-01 11:15:28.777  1019  1135 D Tethering: clearTetheredNotification()
09-01 11:15:28.787  1019  1129 V NetworkStats: performPollLocked() took 15ms
,09-01 11:15:28.787  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:28.787   278  1013 D CommandListener: Setting iface cfg
09-01 11:15:28.787   278  1013 D CommandListener: Trying to bring down wlan0
,09-01 11:15:28.787   278  1013 D CommandListener: Clearing all IP addresses on wlan0
09-01 11:15:28.787  1019  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-01 11:15:28.787  1019  1048 D Tethering: interfaceLinkStateChanged p2p0, false
09-01 11:15:28.787  1019  1048 D Tethering: interfaceStatusChanged p2p0, false
,09-01 11:15:28.787  1183  1183 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-01 11:15:28.787  1183  1183 D HotspotTile: updateTetherState():false, false
,09-01 11:15:28.797  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
,09-01 11:15:28.797  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:28.797  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 11:15:28.797  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 11:15:28.797  1019  1132 E WifiHW  : supplicant_name : p2p_supplicant
,09-01 11:15:28.797  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-01 11:15:28.797  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 11:15:28.797  1019  1132 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-01 11:15:28.807  1019  1129 V NetworkStats: performPollLocked() took 12ms
09-01 11:15:28.807  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 11:15:28.817  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-01 11:15:28.817  1183  1729 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-01 11:15:28.817  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 11:15:28.817  1183  1183 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 11:15:28.817  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-01 11:15:28.817  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:28.817  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:28.817  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:28.817  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:28.817  1183  1183 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 11:15:28.817  1183  1183 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-01 11:15:28.817  1183  1183 D HotspotTile: onReceive : 2, 0
,09-01 11:15:28.827  4723  4723 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-01 11:15:28.837  1019  1317 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 11:15:28.837  1019  1317 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 11:15:28.837  1019  1317 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:28.837  1019  1317 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:28.837  1019  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-01 11:15:28.837  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:28.837  1635  1635 I Hs20UtilService: Starting #19
09-01 11:15:28.837  1635  1673 I Hs20UtilService: Message received 5011
,09-01 11:15:28.837  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:28.837  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 11:15:28.837  7387  7387 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-01 11:15:28.837  7387  7387 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-01 11:15:28.837  7387  7387 D SecurityLogAgent: StateMachine : Current State = 1
09-01 11:15:28.837  7387  7387 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-01 11:15:28.847  7868  7868 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-01 11:15:28.847  7868  7868 I wpa_supplicant: Successfully initialized wpa_supplicant
09-01 11:15:28.847  7868  7868 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-01 11:15:28.867  7868  7868 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,09-01 11:15:28.867   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7868,
09-01 11:15:28.867   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-01 11:15:28.867  7868  7868 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-01 11:15:28.867  7868  7868 I wpa_supplicant: ssSupport state is = 1,
09-01 11:15:28.867  7868  7868 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-01 11:15:28.867  7868  7868 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,09-01 11:15:28.867   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7868,
09-01 11:15:28.867   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-01 11:15:29.037   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,09-01 11:15:29.037  7868  7868 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,09-01 11:15:29.087  7868  7868 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-01 11:15:29.087  7868  7868 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-01 11:15:29.097  7868  7868 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-01 11:15:29.097   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7868
09-01 11:15:29.097   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-01 11:15:29.097  7868  7868 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
09-01 11:15:29.097  7868  7868 I wpa_supplicant: ssSupport state is = 1
09-01 11:15:29.097  7868  7868 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 11:15:29.097  7868  7868 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-01 11:15:29.097  7868  7868 E wpa_supplicant: SIM READ ERROR
09-01 11:15:29.097  7868  7868 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-01 11:15:29.097  7868  7868 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-01 11:15:29.097  7868  7868 E wpa_supplicant: SIM READ ERROR
09-01 11:15:29.097  7868  7868 I wpa_supplicant: Blacklist: Clear (all) 
09-01 11:15:29.097  7868  7868 I wpa_supplicant: wpa_default_ap_write_once
09-01 11:15:29.097  7868  7868 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-01 11:15:29.097  7868  7868 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-01 11:15:29.097  7868  7868 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-01 11:15:29.097  7868  7868 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 11:15:29.097  7868  7868 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-01 11:15:29.097  7868  7868 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-01 11:15:29.097  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false,
09-01 11:15:29.097  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 11:15:29.097  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
,09-01 11:15:29.157  7868  7868 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-01 11:15:29.337  7868  7868 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-01 11:15:29.337  7868  7868 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-01 11:15:29.347  7868  7868 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-01 11:15:29.347   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7868
09-01 11:15:29.347   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-01 11:15:29.357  7868  7868 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-01 11:15:29.357  7868  7868 I wpa_supplicant: ssSupport state is = 1,
09-01 11:15:29.357  7868  7868 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-01 11:15:29.357  7868  7868 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-01 11:15:29.367  7868  7868 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-01 11:15:29.367   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7868
09-01 11:15:29.367   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-01 11:15:29.367  7868  7868 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
09-01 11:15:29.367  7868  7868 I wpa_supplicant: ssSupport state is = 1
09-01 11:15:29.367  7868  7868 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 11:15:29.367  7868  7868 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-01 11:15:29.367  7868  7868 E wpa_supplicant: SIM READ ERROR
09-01 11:15:29.367  7868  7868 I wpa_supplicant: wpa_default_ap_write_once
,09-01 11:15:29.377  1019  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
09-01 11:15:29.367  7868  7868 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-01 11:15:29.377  1019  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-01 11:15:29.367  7868  7868 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-01 11:15:29.377  1019  1048 D Tethering: interfaceLinkStateChanged p2p0, false
09-01 11:15:29.377  1019  1048 D Tethering: interfaceStatusChanged p2p0, false
09-01 11:15:29.377  1019  1048 D Tethering: interfaceLinkStateChanged p2p0, false
,09-01 11:15:29.377  1019  1048 D Tethering: interfaceStatusChanged p2p0, false
,09-01 11:15:29.447  7868  7868 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-01 11:15:29.447  7868  7868 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-01 11:15:29.507  7868  7868 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-01 11:15:29.507  7868  7868 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,09-01 11:15:29.507  7868  7868 I wpa_supplicant: Skip scan - bUseNetwork false
,09-01 11:15:29.517  1019  1132 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,09-01 11:15:29.517  1019  1132 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-01 11:15:29.517  7868  7868 I wpa_supplicant: HOTSPOT20_ENABLE called
,09-01 11:15:29.517  7868  7868 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 11:15:29.517  7868  7868 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-01 11:15:29.517  7868  7868 E wpa_supplicant: SIM READ ERROR
,09-01 11:15:29.517  7868  7868 I wpa_supplicant: Blacklist: Clear (all) 
,09-01 11:15:29.537  7868  7868 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-01 11:15:29.547  7868  7868 I wpa_supplicant: Skip scan - bUseNetwork false
,09-01 11:15:29.557  1019  1132 D WifiConfigStore: Loading config and enabling all networks ,
,09-01 11:15:29.557  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-01 11:15:29.557  1183  1183 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 11:15:29.557  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-01 11:15:29.567  1183  1729 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-01 11:15:29.557  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 11:15:29.557  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:29.557  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:29.557  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:29.557  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:29.557  1183  1183 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 11:15:29.557  1183  1183 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-01 11:15:29.567  4723  4723 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-01 11:15:29.567  1183  1183 D HotspotTile: onReceive : 3, 0
,09-01 11:15:29.577  1019  1132 E WifiConfigStore: Not a HS20
,09-01 11:15:29.577  1019  6683 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 11:15:29.577  1019  6683 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 11:15:29.577  1019  6683 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:29.577  1019  6683 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:29.577  1019  6683 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-01 11:15:29.577  1019  1132 D WifiNative-wlan0: callSECApiInt - ID [65]
09-01 11:15:29.577  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:29.577  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:29.577  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:29.577  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:29.577  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:29.577  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:29.577  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:29.577  7058  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:15:29.577  7058  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:15:29.577  1635  1635 I Hs20UtilService: Starting #20
,09-01 11:15:29.577  1019  1132 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-01 11:15:29.577  7868  7868 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-01 11:15:29.577  7868  7868 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-01 11:15:29.577  7868  7868 I wpa_supplicant: reset timer : RESET_TIMER 0
09-01 11:15:29.577  7868  7868 I wpa_supplicant: P2P: Current p2p state = IDLE
09-01 11:15:29.577  7868  7868 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-01 11:15:29.577  7868  7868 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-01 11:15:29.577  7868  7868 I wpa_supplicant: First Scan Start
09-01 11:15:29.577  7868  7868 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-01 11:15:29.587  1635  1673 I Hs20UtilService: Message received 5011
,09-01 11:15:29.587  7387  7387 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-01 11:15:29.587  7387  7387 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-01 11:15:29.587  7387  7387 D SecurityLogAgent: StateMachine : Current State = 1
09-01 11:15:29.587  7387  7387 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-01 11:15:29.587  1019  1132 D WifiNative-wlan0: Setting external_sim to 1
,09-01 11:15:29.587  1019  1132 D WifiStateMachine: Setting OUI to DA-A1-19
09-01 11:15:29.587  7331  7331 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 11:15:29.587  1019  1132 I WifiNative-HAL: startHal
09-01 11:15:29.587  1019  1132 E wifi    : getStaticLongField sWifiHalHandle 0x9f0a688c
09-01 11:15:29.587  1019  1132 I WifiNative-HAL: Could not start hal
,09-01 11:15:29.587  1019  1132 E WifiNative-wlan0: do suspend true
,09-01 11:15:29.597  1019  1131 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-01 11:15:29.597   278  1013 D CommandListener: Setting iface cfg
09-01 11:15:29.597   278  1013 D CommandListener: Trying to bring up p2p0
,09-01 11:15:29.597  1019  1131 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-01 11:15:29.597  1019  1131 D WifiP2pService: P2pEnablingState
,09-01 11:15:29.597  1019  1131 D WifiP2pService: P2pEnablingState{ what=147457 }
09-01 11:15:29.597  1019  1131 D WifiP2pService: P2p socket connection successful
09-01 11:15:29.597  1019  1131 D WifiP2pService: P2pEnabledState
,09-01 11:15:29.597  1019  1132 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-01 11:15:29.597  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 3
09-01 11:15:29.597  1019  1154 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:15:29.597  1019  1154 I WifiNative-HAL: startHal
09-01 11:15:29.597  1019  1154 E wifi    : getStaticLongField sWifiHalHandle 0x9e0669bc
09-01 11:15:29.597  1019  1154 I WifiNative-HAL: Could not start hal
09-01 11:15:29.597  1019  1154 E WifiScanningService: could not start HAL
,09-01 11:15:29.607  1019  1019 D RttService: SCAN_AVAILABLE : 3,
09-01 11:15:29.607  1019  1155 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 11:15:29.607  1019  1132 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-01 11:15:29.607  1019  1132 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-01 11:15:29.607  1019  1132 E WifiNative-wlan0: invaild command id : 215
,09-01 11:15:29.607  1019  1132 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-01 11:15:29.607  1019  1132 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-01 11:15:29.607  1019  1132 E WifiNative-wlan0: invaild command id : 215
,09-01 11:15:29.607  1019  1131 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-01 11:15:29.607  1019  1134 E ConnectivityService: updateNetworkInfo()
,09-01 11:15:29.607  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-01 11:15:29.607  7868  7868 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,09-01 11:15:29.607  1019  1051 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-01 11:15:29.607  7868  7868 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-01 11:15:29.607  1019  1051 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-01 11:15:29.607  1019  1051 D WifiDisplayController: disconnect
,09-01 11:15:29.607  1019  1051 D WifiDisplayController: updateConnection
09-01 11:15:29.607  1019  1051 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-01 11:15:29.607  1019  1051 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-01 11:15:29.607  7868  7868 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,09-01 11:15:29.617  1019  1132 E WifiStateMachine: Failed to set frequency band 0
,09-01 11:15:29.617  1019  1051 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 11:15:29.617  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 11:15:29.617  1019  1051 D WifiDisplayAdapter: onP2pDisconnected
09-01 11:15:29.617  1019  1132 D SecContentProvider2: mCursor = null
09-01 11:15:29.617  1019  1051 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-01 11:15:29.617  1019  1131 D WifiNative-p2p0: p2pGetDeviceAddress
,09-01 11:15:29.617  1019  1051 D IpRemoteDisplayController: WfdBridgeServer is already null
09-01 11:15:29.617  1019  1131 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,09-01 11:15:29.617  1183  1183 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-01 11:15:29.617  1019  1082 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-01 11:15:29.617  1183  1183 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-01 11:15:29.617  4723  4723 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-01 11:15:29.627  4723  4723 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-01 11:15:29.627  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 11:15:29.627  1019  1132 D SecContentProvider2: mCursor = null
,09-01 11:15:29.627  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-01 11:15:29.627  1019  1131 D WifiP2pService: DeviceAddress: 0a:75:42
,09-01 11:15:29.627  1019  1051 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-01 11:15:29.627  1019  1051 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-01 11:15:29.627  1019  1051 D WifiDisplayController:  primary type: 10-0050F204-5
09-01 11:15:29.627  1019  1051 D WifiDisplayController:  secondary type: null
09-01 11:15:29.627  1019  1051 D WifiDisplayController:  wps: 0
09-01 11:15:29.627  1019  1051 D WifiDisplayController:  grpcapab: 0
09-01 11:15:29.627  1019  1051 D WifiDisplayController:  devcapab: 0
09-01 11:15:29.627  1019  1051 D WifiDisplayController:  status: 3
09-01 11:15:29.627  1019  1051 D WifiDisplayController:  wfdInfo: null
09-01 11:15:29.627  1019  1051 D WifiDisplayController:  groupownerAddress: null
09-01 11:15:29.627  1019  1051 D WifiDisplayController:  GOdeviceName: null
09-01 11:15:29.627  1019  1051 D WifiDisplayController:  interfaceAddress: 
09-01 11:15:29.627  1019  1051 D WifiDisplayController:  SConnectInfo : null
,09-01 11:15:29.627  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-01 11:15:29.627  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-01 11:15:29.627  4723  4723 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-01 11:15:29.627  4723  4806 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 11:15:29.627  7714  7714 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-01 11:15:29.637  7714  7714 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-01 11:15:29.637  7714  7714 D FileShare-Client: Outbound.stopDelayTimer - 
09-01 11:15:29.637  7372  7372 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-01 11:15:29.647  1019  1131 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-01 11:15:29.647  1019  1131 D WifiP2pService: InactiveState
,09-01 11:15:29.647  1019  1131 D WifiP2pService: InactiveState{ what=143376 }
,09-01 11:15:29.647  1019  1131 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-01 11:15:29.647  7868  7868 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,09-01 11:15:29.647  1019  1131 D WifiP2pService: InactiveState{ what=143376 }
,09-01 11:15:29.647  1019  1131 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-01 11:15:29.757  1019  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-01 11:15:29.757  1019  1048 D Tethering: interfaceLinkStateChanged p2p0, false
09-01 11:15:29.757  1019  1048 D Tethering: interfaceStatusChanged p2p0, false
,09-01 11:15:29.827   295   295 E SMD     : DCD OFF,
,09-01 11:15:30.427  7058  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 11:15:30.427  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:30.427  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:30.427  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:30.427  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:30.427  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:30.427  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:30.427  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:15:30.437  7058  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:15:30.437  7058  7244 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-01 11:15:30.437  7058  7244 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-01 11:15:30.437  7058  7244 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@bf2e73b Bundle[{}]
09-01 11:15:30.437  7058  7244 I io.jxcore.node.LifeCycleMonitor: start: OK
09-01 11:15:30.437  7058  7244 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-01 11:15:30.437  7058  7244 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-01 11:15:30.437  7058  7244 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-01 11:15:30.437  7058  7244 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-01 11:15:30.437  7058  7244 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-01 11:15:30.447  7058  7244 I System.out: Running OutgoingSocketThread
,09-01 11:15:30.447  7058  7876 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1436)
,09-01 11:15:30.457  7058  7876 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 36553
,09-01 11:15:30.457  7058  7876 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-01 11:15:30.927  7868  7868 I wpa_supplicant: nl80211: Received scan results (28 BSSes)
09-01 11:15:30.927  7868  7868 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
09-01 11:15:30.927  7868  7868 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,09-01 11:15:30.927  7868  7868 I wpa_supplicant: Trying to associate with  'G700'
09-01 11:15:30.927  7868  7868 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-01 11:15:30.927  7868  7868 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,09-01 11:15:30.927  1019  7873 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-01 11:15:30.947  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-01 11:15:30.947  1019  1132 D SecContentProvider2: mCursor = null
,09-01 11:15:31.067  7868  7868 E wpa_supplicant: Cmd 35605 not handled
,09-01 11:15:31.067  7868  7868 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-01 11:15:31.067  7868  7868 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-01 11:15:31.067  7868  7868 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-01 11:15:31.067  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 11:15:31.067  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 11:15:31.067  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 11:15:31.067  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
09-01 11:15:31.067  7868  7868 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-01 11:15:31.067  7868  7868 I wpa_supplicant: Associated with F4.99.3E
09-01 11:15:31.067  7868  7868 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-01 11:15:31.067  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 11:15:31.067  7868  7868 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-01 11:15:31.067  7868  7868 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
09-01 11:15:31.067  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 11:15:31.067  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
,09-01 11:15:31.067  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 11:15:31.067  1019  1048 D Tethering: interfaceStatusChanged wlan0, false
09-01 11:15:31.067  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, true
,09-01 11:15:31.067  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-01 11:15:31.067  1019  1048 D Tethering: interfaceStatusChanged wlan0, true
09-01 11:15:31.077  1019  1135 E Tethering: No numeric data
09-01 11:15:31.077  1019  1135 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-01 11:15:31.077  1019  1135 D Tethering: clearTetheredNotification()
09-01 11:15:31.077  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:31.077  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
,09-01 11:15:31.077  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 11:15:31.077  1183  1183 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-01 11:15:31.077  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-01 11:15:31.077  1183  1183 D HotspotTile: updateTetherState():false, false
09-01 11:15:31.077  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 11:15:31.077  1019  1132 D SecContentProvider2: mCursor = null
09-01 11:15:31.077  7868  7868 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-01 11:15:31.077  7868  7868 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-01 11:15:31.077  7868  7868 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-01 11:15:31.077  7868  7868 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-01 11:15:31.077  7868  7868 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-01 11:15:31.077  7868  7868 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-01 11:15:31.077  7868  7868 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-01 11:15:31.077  7868  7868 I wpa_supplicant: Blacklist: Clear (temp) 
,09-01 11:15:31.077  7868  7868 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-01 11:15:31.077  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 11:15:31.077  1019  1132 D SecContentProvider2: mCursor = null
09-01 11:15:31.077  1019  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-01 11:15:31.077  1019  1048 D Tethering: interfaceLinkStateChanged wlan0, true
09-01 11:15:31.077  1019  1048 D Tethering: interfaceStatusChanged wlan0, true
,09-01 11:15:31.077  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:31.077  1019  1129 V NetworkStats: performPollLocked() took 7ms
,09-01 11:15:31.077  1019  1132 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-01 11:15:31.087  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:31.087  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 11:15:31.087  1019  1132 E WifiConfigStore: setLastSelectedConfiguration -1
,09-01 11:15:31.087  1019  1134 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-01 11:15:31.087  1019  1132 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-01 11:15:31.087  1019  1134 E ConnectivityService: updateNetworkInfo()
09-01 11:15:31.087  1019  1134 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-01 11:15:31.097  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-01 11:15:31.097  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 11:15:31.097  1019  1132 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 11:15:31.097  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 11:15:31.097  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:31.097  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:31.097  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:31.097  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:31.097  1019  1546 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-01 11:15:31.097  1019  1546 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 11:15:31.097  1019  1546 W ActivityManager: userId = 0, bbcId = -10000,
09-01 11:15:31.097  1019  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:31.097  1019  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-01 11:15:31.097  1635  1635 I Hs20UtilService: Starting #21
09-01 11:15:31.097  1019  1132 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 11:15:31.097  1635  1673 I Hs20UtilService: Message received 5007
,09-01 11:15:31.107  4723  4723 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-01 11:15:31.107  4723  4723 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-01 11:15:31.107  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-01 11:15:31.107  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-01 11:15:31.107  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-01 11:15:31.107  4723  4723 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-01 11:15:31.107  4723  4806 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 11:15:31.117   278  1013 D CommandListener: Setting iface cfg
,09-01 11:15:31.117  1019  1132 E WifiStateMachine: Start Dhcp Watchdog 3
,09-01 11:15:31.127  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-01 11:15:31.127  1019  1132 D SecContentProvider2: mCursor = null
,09-01 11:15:31.127  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-01 11:15:31.137  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 11:15:31.137  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-01 11:15:31.137  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:31.137  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:31.137  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:31.137  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:31.137  1019  1132 E WifiNative-wlan0: do suspend false
,09-01 11:15:31.137  1019  1131 D WifiP2pService: InactiveState{ what=143375 }
,09-01 11:15:31.147  1019  1131 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-01 11:15:31.147  1019  1132 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 11:15:31.147  1019  1132 D SecContentProvider2: mCursor = null
,09-01 11:15:31.357  7879  7879 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-01 11:15:31.357  7879  7879 I dhcpcd  : version 5.5.6 starting,
,09-01 11:15:31.367  7879  7879 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-01 11:15:31.417  7879  7879 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-01 11:15:31.417  7879  7879 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-01 11:15:31.417  7879  7879 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-01 11:15:31.417  7879  7879 I dhcpcd  : bssid match,
09-01 11:15:31.417  7879  7879 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,09-01 11:15:31.447  7058  7244 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1437),
09-01 11:15:31.447  7058  7244 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1437)
,09-01 11:15:31.457  7058  7244 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1442)
09-01 11:15:31.457  7058  7244 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-01 11:15:31.457  7058  7244 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1443)
09-01 11:15:31.457  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:15:31.457  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13aececd added. We now have 2 listener(s)
,09-01 11:15:31.457  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-01 11:15:31.457  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:15:31.457  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:15:31.457  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:31.457  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23feb382 added. We now have 9 listener(s)
09-01 11:15:31.457  7058  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:15:31.457  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 11:15:31.457  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:15:31.467  7058  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,09-01 11:15:31.467  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:31.467  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:31.467  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,09-01 11:15:31.467  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:31.467  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:31.467  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:31.467  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:15:31.467  7058  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:15:31.467  7058  7244 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:15:31.467  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:15:31.467  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b93ead0 added. We now have 3 listener(s)
,09-01 11:15:31.467  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:31.467  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-01 11:15:31.467  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-01 11:15:31.467  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:15:31.467  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-01 11:15:31.467  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:31.467  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c668ac9 added. We now have 10 listener(s)
09-01 11:15:31.467  7058  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:15:31.467  7058  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:31.467  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-01 11:15:31.467  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:31.467  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:31.467  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:31.467  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:15:31.467  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-01 11:15:31.467  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13aececd removed from the list,
09-01 11:15:31.467  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-01 11:15:31.467  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23feb382 removed from the list
09-01 11:15:31.467  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 11:15:31.467  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-01 11:15:31.467  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:31.467  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:31.467  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-01 11:15:31.467  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:31.467  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:31.467  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23feb382 not in the list,
,09-01 11:15:31.477  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:31.477  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:31.477  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 11:15:31.477  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:31.477  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 11:15:31.477  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c668ac9 removed from the list
09-01 11:15:31.477  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:31.477  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,09-01 11:15:31.477  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:31.477  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:15:31.477  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b93ead0 removed from the list
09-01 11:15:31.477  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:15:31.477  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266885ce added. We now have 2 listener(s)
,09-01 11:15:31.477  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-01 11:15:31.477  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:15:31.477  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:15:31.477  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:31.477  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e99ecef added. We now have 9 listener(s)
09-01 11:15:31.477  7058  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:15:31.477  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 11:15:31.477  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:15:31.487  7058  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-01 11:15:31.487  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:31.487  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:31.487  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:31.487  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:31.487  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:31.487  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:31.487  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:15:31.487  7058  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:15:31.487  7058  7244 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:15:31.487  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:15:31.487  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26c40a85 added. We now have 3 listener(s)
,09-01 11:15:31.487  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:31.487  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:31.487  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-01 11:15:31.487  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:15:31.487  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:15:31.487  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:31.487  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@248b30da added. We now have 10 listener(s)
09-01 11:15:31.487  7058  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:15:31.487  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:15:31.487  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:15:31.487  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:15:31.487  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:15:31.487  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-01 11:15:31.497  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-01 11:15:31.497  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-01 11:15:31.497  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 11:15:31.497  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-01 11:15:31.497  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 11:15:31.497  7058  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-01 11:15:31.507  3228  7790 D BtGatt.GattService: registerClient() - UUID=f8f0add1-7307-48da-a510-0dfe4285bd74
,09-01 11:15:31.517  7879  7879 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,09-01 11:15:31.547  3228  3309 D BtGatt.GattService: onClientRegistered() - UUID=f8f0add1-7307-48da-a510-0dfe4285bd74, clientIf=6
,09-01 11:15:31.547  7058  7066 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-01 11:15:31.547  3228  3242 D BtGatt.GattService: start scan with filters
,09-01 11:15:31.547  3228  3368 D BtGatt.ScanManager: handling starting scan
09-01 11:15:31.547  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-01 11:15:31.547  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 11:15:31.547  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
09-01 11:15:31.547  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
,09-01 11:15:31.557  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 11:15:31.557  3228  3309 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-01 11:15:31.557  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:31.557  3228  3368 D BtGatt.ScanManager: allow scan with filters
09-01 11:15:31.557  3228  3368 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-01 11:15:31.557  3228  3368 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
,09-01 11:15:31.567  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-01 11:15:31.567  7058  7058 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 11:15:31.567  3228  3309 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-01 11:15:31.567  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:31.567  3228  3368 D BtGatt.ScanManager: Starting BLE batch scan
09-01 11:15:31.567  3228  3368 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-01 11:15:31.567  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-01 11:15:31.567  3228  3309 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-01 11:15:31.567  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:31.577  3228  3309 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-01 11:15:31.577  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:31.577  7058  7244 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-01 11:15:31.577  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-01 11:15:31.577  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-01 11:15:31.577  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:15:31.577  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 11:15:31.587  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-01 11:15:31.587  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 11:15:31.587  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-01 11:15:31.587  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-01 11:15:31.587  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-01 11:15:31.587  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-01 11:15:31.587  3228  3246 D BtGatt.GattService: stopScan() - queue size =1
,09-01 11:15:31.587  3228  3368 D BtGatt.ScanManager: filter size is 1
,09-01 11:15:31.587  3228  3368 D BtGatt.ScanManager: delete FilterIndex - 6
,09-01 11:15:31.587  3228  7789 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-01 11:15:31.587  3228  3309 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-01 11:15:31.587  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 11:15:31.597  3228  3368 D BtGatt.ScanManager: stopping BLe Batch
,09-01 11:15:31.597  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:15:31.597  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 11:15:31.597  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 11:15:31.597  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 11:15:31.597  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-01 11:15:31.597  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 11:15:31.597  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-01 11:15:31.597  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 11:15:31.597  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-01 11:15:31.597  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 11:15:31.597  3228  3309 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-01 11:15:31.597  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 11:15:31.597  3228  3368 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-01 11:15:31.597  7879  7879 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
09-01 11:15:31.597  3228  3309 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-01 11:15:31.597  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:31.607  7058  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-01 11:15:31.607  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-01 11:15:31.607  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:31.607  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:31.607  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:31.607  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:15:31.607  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:15:31.607  7058  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 11:15:31.607  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@266885ce removed from the list
09-01 11:15:31.607  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:31.607  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e99ecef removed from the list
09-01 11:15:31.607  7058  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:15:31.607  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:31.607  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-01 11:15:31.607  7058  7058 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:15:31.607  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:31.607  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:15:31.617  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 11:15:31.617  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:31.617  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:31.617  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e99ecef not in the list
09-01 11:15:31.617  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:31.617  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:31.617  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:31.617  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:31.617  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:31.617  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@248b30da removed from the list
09-01 11:15:31.617  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:31.617  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:31.617  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:31.617  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:15:31.617  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26c40a85 removed from the list
09-01 11:15:31.617  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:15:31.617  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21fb80a6 added. We now have 2 listener(s)
,09-01 11:15:31.627  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-01 11:15:31.627  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-01 11:15:31.627  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-01 11:15:31.627  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-01 11:15:31.627  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fac8ae7 added. We now have 9 listener(s)
09-01 11:15:31.627  7058  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
09-01 11:15:31.627  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 11:15:31.637  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:15:31.647  7058  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:15:31.647  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:31.647  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:31.647  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:31.647  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
09-01 11:15:31.647  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:31.647  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:31.647  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:15:31.647  7058  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 11:15:31.647  7058  7244 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 11:15:31.657  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:15:31.657  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@315e053d added. We now have 3 listener(s)
09-01 11:15:31.657  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:31.657  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-01 11:15:31.657  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-01 11:15:31.657  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:15:31.657  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:31.657  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34cf0132 added. We now have 10 listener(s)
,09-01 11:15:31.657  7058  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:15:31.657  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
09-01 11:15:31.657  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-01 11:15:31.657  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:15:31.657  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:31.657  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-01 11:15:31.657  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:15:31.657  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-01 11:15:31.667  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,09-01 11:15:31.677  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-01 11:15:31.677  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 11:15:31.677  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-01 11:15:31.677  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 11:15:31.677  7058  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-01 11:15:31.687  3228  7789 D BtGatt.GattService: registerClient() - UUID=b61ab181-6acd-4878-8e86-544b1adba516
,09-01 11:15:31.727  3228  3309 D BtGatt.GattService: onClientRegistered() - UUID=b61ab181-6acd-4878-8e86-544b1adba516, clientIf=6
,09-01 11:15:31.727  7058  7071 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-01 11:15:31.727  3228  3392 D BtGatt.GattService: start scan with filters
09-01 11:15:31.727  3228  3368 D BtGatt.ScanManager: handling starting scan
09-01 11:15:31.727  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-01 11:15:31.727  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 11:15:31.727  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-01 11:15:31.727  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-01 11:15:31.737  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 11:15:31.737  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-01 11:15:31.737  7058  7058 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 11:15:31.737  3228  3309 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-01 11:15:31.737  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:31.737  3228  3368 D BtGatt.ScanManager: allow scan with filters
09-01 11:15:31.737  3228  3368 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-01 11:15:31.737  3228  3368 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,09-01 11:15:31.737  3228  3309 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
09-01 11:15:31.737  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 11:15:31.737  3228  3368 D BtGatt.ScanManager: Starting BLE batch scan
09-01 11:15:31.737  3228  3368 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-01 11:15:31.737  3228  3309 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-01 11:15:31.737  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:31.737  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-01 11:15:31.747  3228  3309 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-01 11:15:31.747  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:31.747  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:15:31.747  7058  7244 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-01 11:15:31.747  7058  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:31.747  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:31.747  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:31.747  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:31.747  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:31.747  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 11:15:31.747  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:15:31.747  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21fb80a6 removed from the list
09-01 11:15:31.747  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:31.747  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fac8ae7 removed from the list
09-01 11:15:31.747  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:31.747  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 11:15:31.757  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:31.757  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-01 11:15:31.757  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:31.757  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 11:15:31.757  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-01 11:15:31.757  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-01 11:15:31.757  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 11:15:31.757  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fac8ae7 not in the list
09-01 11:15:31.757  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 11:15:31.757  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
09-01 11:15:31.757  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 11:15:31.757  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 11:15:31.757  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-01 11:15:31.757  3228  7790 D BtGatt.GattService: stopScan() - queue size =1
,09-01 11:15:31.757  3228  3242 D BtGatt.GattService: unregisterClient() - clientIf=6
09-01 11:15:31.757  3228  3368 D BtGatt.ScanManager: filter size is 1
09-01 11:15:31.757  3228  3368 D BtGatt.ScanManager: delete FilterIndex - 7
,09-01 11:15:31.757  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-01 11:15:31.757  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-01 11:15:31.757  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 11:15:31.757  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 11:15:31.757  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-01 11:15:31.757  3228  3309 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-01 11:15:31.757  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 11:15:31.767  3228  3368 D BtGatt.ScanManager: stopping BLe Batch,
09-01 11:15:31.767  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 11:15:31.767  3228  3309 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
,09-01 11:15:31.767  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 11:15:31.767  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-01 11:15:31.767  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 11:15:31.767  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-01 11:15:31.767  3228  3368 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-01 11:15:31.767  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:31.767  7058  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:15:31.767  7058  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:15:31.767  7058  7058 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 11:15:31.767  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:31.767  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 11:15:31.767  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:31.767  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34cf0132 removed from the list
09-01 11:15:31.767  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:31.767  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:31.767  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:31.767  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-01 11:15:31.767  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@315e053d removed from the list
09-01 11:15:31.767  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:15:31.767  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce7fe7e added. We now have 2 listener(s)
09-01 11:15:31.777  3228  3309 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-01 11:15:31.777  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:31.777  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-01 11:15:31.777  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:15:31.777  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:15:31.777  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:31.777  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c5efdf added. We now have 9 listener(s)
09-01 11:15:31.777  7058  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:15:31.777  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 11:15:31.787  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:15:31.787  7058  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:15:31.787  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:31.787  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:31.787  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:31.787  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:31.787  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:31.787  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:31.787  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:15:31.797  7058  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:15:31.797  7058  7244 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:15:31.797  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:15:31.797  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29759ef5 added. We now have 3 listener(s)
09-01 11:15:31.797  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:31.797  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-01 11:15:31.797  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:15:31.797  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:15:31.797  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:31.797  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2401848a added. We now have 10 listener(s)
09-01 11:15:31.797  7058  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:15:31.797  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 11:15:31.797  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 11:15:31.797  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 11:15:31.797  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 11:15:31.797  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 11:15:31.807  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 11:15:31.807  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-01 11:15:31.817  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-01 11:15:31.817  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-01 11:15:31.817  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-01 11:15:31.817  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 11:15:31.817  7058  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-01 11:15:31.827  3228  7789 D BtGatt.GattService: registerClient() - UUID=3ebf3511-3184-48e3-ae71-c088668e452a
,09-01 11:15:31.867  3228  3309 D BtGatt.GattService: onClientRegistered() - UUID=3ebf3511-3184-48e3-ae71-c088668e452a, clientIf=6
,09-01 11:15:31.867  7058  7066 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-01 11:15:31.867  3228  3246 D BtGatt.GattService: start scan with filters
,09-01 11:15:31.867  3228  3368 D BtGatt.ScanManager: handling starting scan
,09-01 11:15:31.867  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-01 11:15:31.867  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-01 11:15:31.867  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-01 11:15:31.877  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-01 11:15:31.877  3228  3309 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-01 11:15:31.877  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 11:15:31.877  3228  3368 D BtGatt.ScanManager: allow scan with filters
09-01 11:15:31.877  3228  3368 D BtGatt.ScanManager: client filter size is = 1available filters are = 13,
09-01 11:15:31.877  3228  3368 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
09-01 11:15:31.877  3228  3309 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-01 11:15:31.877  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 11:15:31.877  3228  3368 D BtGatt.ScanManager: Starting BLE batch scan
09-01 11:15:31.877  3228  3368 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-01 11:15:31.877  3228  3309 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-01 11:15:31.877  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:31.877  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 11:15:31.877  7058  7058 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 11:15:31.877  3228  3309 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
09-01 11:15:31.877  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 11:15:31.877  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-01 11:15:31.887  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-01 11:15:31.887  7058  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 11:15:31.887  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:31.887  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 11:15:31.887  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 11:15:31.887  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:31.887  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-01 11:15:31.887  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:15:31.887  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce7fe7e removed from the list
09-01 11:15:31.887  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 11:15:31.887  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c5efdf removed from the list
09-01 11:15:31.887  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:31.887  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 11:15:31.887  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-01 11:15:31.897  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-01 11:15:31.897  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:31.897  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 11:15:31.897  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 11:15:31.897  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:31.897  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 11:15:31.897  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c5efdf not in the list
09-01 11:15:31.897  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 11:15:31.897  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-01 11:15:31.897  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-01 11:15:31.897  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 11:15:31.897  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-01 11:15:31.897  3228  7789 D BtGatt.GattService: stopScan() - queue size =1,
,09-01 11:15:31.897  3228  3246 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-01 11:15:31.897  3228  3368 D BtGatt.ScanManager: filter size is 1
,09-01 11:15:31.897  3228  3368 D BtGatt.ScanManager: delete FilterIndex - 8
,09-01 11:15:31.897  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 11:15:31.897  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 11:15:31.897  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 11:15:31.897  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 11:15:31.897  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-01 11:15:31.897  3228  3309 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-01 11:15:31.897  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:31.907  3228  3368 D BtGatt.ScanManager: stopping BLe Batch
,09-01 11:15:31.907  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 11:15:31.907  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-01 11:15:31.907  7058  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 11:15:31.907  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 11:15:31.907  3228  3309 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-01 11:15:31.907  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 11:15:31.907  3228  3368 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-01 11:15:31.907  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:15:31.907  3228  3309 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-01 11:15:31.907  3228  3309 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 11:15:31.907  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:31.907  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:31.907  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:31.907  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2401848a removed from the list
09-01 11:15:31.907  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:31.907  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:31.907  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:31.907  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:15:31.907  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29759ef5 removed from the list
,09-01 11:15:31.907  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:15:31.907  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@227b5f56 added. We now have 2 listener(s)
09-01 11:15:31.907  7058  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 11:15:31.907  7058  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 11:15:31.907  7058  7058 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 11:15:31.907  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-01 11:15:31.907  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-01 11:15:31.907  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-01 11:15:31.917  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 11:15:31.917  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1817fbd7 added. We now have 9 listener(s)
09-01 11:15:31.917  7058  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 11:15:31.917  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 11:15:31.917  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 11:15:31.917  7058  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 11:15:31.917  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 11:15:31.917  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 11:15:31.917  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 11:15:31.917  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 11:15:31.917  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 11:15:31.917  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 11:15:31.917  7058  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 11:15:31.917  7058  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 11:15:31.917  7058  7244 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 11:15:31.917  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 11:15:31.917  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f3fb7ad added. We now have 3 listener(s)
,09-01 11:15:31.927  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:31.927  7058  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 11:15:31.927  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-01 11:15:31.927  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 11:15:31.927  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 11:15:31.927  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 11:15:31.927  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e61ae2 added. We now have 10 listener(s)
09-01 11:15:31.927  7058  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 11:15:31.927  7058  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 11:15:31.927  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 11:15:31.927  7058  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 11:15:31.927  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:31.927  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:31.927  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 11:15:31.927  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:15:31.927  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@227b5f56 removed from the list
09-01 11:15:31.927  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 11:15:31.927  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1817fbd7 removed from the list
09-01 11:15:31.927  7058  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-01 11:15:31.927  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:31.927  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:31.927  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:15:31.927  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 11:15:31.927  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 11:15:31.927  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 11:15:31.927  7058  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1817fbd7 not in the list
,09-01 11:15:31.927  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:31.927  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 11:15:31.927  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 11:15:31.927  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 11:15:31.927  7058  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 11:15:31.927  7058  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e61ae2 removed from the list
09-01 11:15:31.927  7058  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 11:15:31.927  7058  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 11:15:31.927  7058  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 11:15:31.927  7058  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 11:15:31.927  7058  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f3fb7ad removed from the list
,09-01 11:15:31.937  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-01 11:15:31.937  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-01 11:15:31.937  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-01 11:15:31.937  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-01 11:15:31.937  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-01 11:15:31.937  7058  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-01 11:15:31.947  7058  7910 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1450, name: My test thread name)
09-01 11:15:31.947  7058  7910 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1450, thread name: My test thread name)
09-01 11:15:31.947  7058  7910 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1450, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-01 11:15:31.957  7058  7911 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1452, name: My test thread name)
,09-01 11:15:31.957  7058  7911 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1452, thread name: My test thread name)
,09-01 11:15:31.957  7058  7911 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1452, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-01 11:15:31.957  1019  1132 E WifiNative-wlan0: do suspend true
,09-01 11:15:31.957  7058  7244 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-01 11:15:31.957  7058  7244 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-01 11:15:31.957  7058  7244 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-01 11:15:31.957  7058  7244 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-01 11:15:31.957  7058  7244 D com.test.thalitest.ThaliTestRunner: Total duration: 23238 ms
,09-01 11:15:31.957  7058  7244 I jxcore-log: *Native tests were executed*
09-01 11:15:31.957  7058  7244 I jxcore-log: 
09-01 11:15:31.957  7058  7244 I jxcore-log: Total number of executed tests:  80
09-01 11:15:31.957  7058  7244 I jxcore-log: 
,09-01 11:15:31.957  7058  7244 I jxcore-log: Number of passed tests:  80
09-01 11:15:31.957  7058  7244 I jxcore-log: 
09-01 11:15:31.957  7058  7244 I jxcore-log: Number of failed tests:  0
09-01 11:15:31.957  7058  7244 I jxcore-log: 
09-01 11:15:31.957  7058  7244 I jxcore-log: Number of ignored tests:  0
09-01 11:15:31.957  7058  7244 I jxcore-log: 
,09-01 11:15:31.957  7058  7244 I jxcore-log: Total duration:  23238
09-01 11:15:31.957  7058  7244 I jxcore-log: 
09-01 11:15:31.957  7058  7244 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-01 11:15:31.957  7058  7244 I jxcore-log: 
,09-01 11:15:31.967  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:15:31.967  7058  7244 I jxcore-log: 
09-01 11:15:31.967  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:15:31.967  7058  7244 I jxcore-log: 
09-01 11:15:31.967  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:15:31.967  7058  7244 I jxcore-log: 
09-01 11:15:31.967  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:15:31.967  7058  7244 I jxcore-log: 
09-01 11:15:31.967  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:15:31.967  7058  7244 I jxcore-log: 
09-01 11:15:31.967  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:15:31.967  7058  7244 I jxcore-log: 
09-01 11:15:31.977  7058  7058 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-01 11:15:31.977  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 11:15:31.977  7058  7244 I jxcore-log: 
,09-01 11:15:31.977  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:15:31.977  7058  7244 I jxcore-log: 
09-01 11:15:31.977  1019  1131 D WifiP2pService: InactiveState{ what=143375 }
09-01 11:15:31.977  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:15:31.977  7058  7244 I jxcore-log: 
09-01 11:15:31.977  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-01 11:15:31.977  7058  7244 I jxcore-log: 
09-01 11:15:31.987  1019  1131 D WifiP2pService: P2pEnabledState{ what=143375 }
09-01 11:15:31.977  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 11:15:31.977  7058  7244 I jxcore-log: 
09-01 11:15:31.977  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 11:15:31.977  7058  7244 I jxcore-log: 
09-01 11:15:31.977  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:15:31.977  7058  7244 I jxcore-log: 
09-01 11:15:31.977  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:15:31.977  7058  7244 I jxcore-log: 
09-01 11:15:31.977  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 11:15:31.977  7058  7244 I jxcore-log: 
09-01 11:15:31.977  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 11:15:31.977  7058  7244 I jxcore-log: 
09-01 11:15:31.977  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:15:31.977  7058  7244 I jxcore-log: 
09-01 11:15:31.977  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 11:15:31.977  7058  7244 I jxcore-log: 
09-01 11:15:31.987  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 11:15:31.987  7058  7244 I jxcore-log: 
09-01 11:15:31.987  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 11:15:31.987  7058  7244 I jxcore-log: 
,09-01 11:15:31.987  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 11:15:31.987  7058  7244 I jxcore-log: 
09-01 11:15:31.987  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 11:15:31.987  7058  7244 I jxcore-log: 
,09-01 11:15:31.987  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 11:15:31.987  7058  7244 I jxcore-log: 
,09-01 11:15:31.987  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 11:15:31.987  7058  7244 I jxcore-log: 
,09-01 11:15:31.987  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 11:15:31.987  7058  7244 I jxcore-log: 
09-01 11:15:31.987  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 11:15:31.987  7058  7244 I jxcore-log: 
,09-01 11:15:31.987  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 11:15:31.987  7058  7244 I jxcore-log: 
,09-01 11:15:31.987  1019  6811 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-01 11:15:31.987  1019  6811 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-01 11:15:31.987  1019  6811 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
09-01 11:15:31.987  1019  1132 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-01 11:15:31.987  1019  6811 D BatteryService: stay LED for charging
09-01 11:15:31.987  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-01 11:15:31.997  1019  1132 E WifiStateMachine: VerifyingLinkState enter
,09-01 11:15:31.997  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-01 11:15:31.997  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 11:15:31.997  1019  1019 I MotionRecognitionService: Plugged
09-01 11:15:31.997  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
09-01 11:15:31.997  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-01 11:15:31.997  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:31.997  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:31.997  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:31.997  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:31.997  1019  1134 E ConnectivityService: updateNetworkInfo()
,09-01 11:15:31.997  1019  1134 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,09-01 11:15:31.997  1019  1134 D ConnectivityService: Adding iface wlan0 to network 504
,09-01 11:15:32.007  1183  1183 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-01 11:15:32.007  1183  1183 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-01 11:15:32.007  1424  1424 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-01 11:15:32.007  1424  1424 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-01 11:15:32.017  1183  1183 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-01 11:15:32.017  1183  1183 D SViewCoverView: level :100 plugged : 2
,09-01 11:15:32.017  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-01 11:15:32.017  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-01 11:15:32.017  3228  3228 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-01 11:15:32.017  3228  7842 D HeadsetStateMachine: Disconnected process message: 10
,09-01 11:15:32.017  1019  1148 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,09-01 11:15:32.017  1019  1134 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
09-01 11:15:32.017  1019  1148 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-01 11:15:32.017  1019  1148 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-01 11:15:32.017  1019  1134 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,09-01 11:15:32.027  1019  1134 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
09-01 11:15:32.027  1019  1148 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-01 11:15:32.027  1019  1148 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-01 11:15:32.027  1019  1134 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-01 11:15:32.027  1019  1134 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
,09-01 11:15:32.027  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-01 11:15:32.037  1019  1134 D ConnectivityService: LTETest block dns file not exists
,09-01 11:15:32.037  1019  1317 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
09-01 11:15:32.037  1019  1317 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-01 11:15:32.037  1019  1317 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:32.037  1019  1134 V NetworkStats: updateIfacesLocked()
,09-01 11:15:32.037  1019  1317 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:32.037  1019  1134 V NetworkStats: performPollLocked(flags=0x1)
09-01 11:15:32.037  1019  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-01 11:15:32.037  1019  1134 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:32.037  1019  1134 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 11:15:32.037  1019  1134 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 11:15:32.047  1635  1635 I Hs20UtilService: Starting #22,
09-01 11:15:32.047  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-01 11:15:32.047  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 11:15:32.047  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 11:15:32.047  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:32.047  1019  1134 V NetworkStats: performPollLocked() took 11ms
09-01 11:15:32.047  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:32.047  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:32.047  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:32.047  1019  1134 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:32.047  1019  1134 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-01 11:15:32.047  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:32.047  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:32.047  1635  1673 I Hs20UtilService: Message received 5007
,09-01 11:15:32.057  4723  4723 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-01 11:15:32.057  4723  4723 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-01 11:15:32.067  1019  1132 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,09-01 11:15:32.077  1019  1134 E ConnectivityService: updateNetworkInfo(),
,09-01 11:15:32.077  1019  1134 E ConnectivityService: updateNetworkInfo()
09-01 11:15:32.077  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-01 11:15:32.077  1019  1134 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 11:15:32.077  1019  1134 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:32.077  1019  1134 V NetworkStats: updateIfacesLocked()
09-01 11:15:32.077  1019  1134 V NetworkStats: performPollLocked(flags=0x1)
09-01 11:15:32.077  1019  1134 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 11:15:32.077  1019  1134 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 11:15:32.077  1019  1134 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:32.077  1019  1134 V NetworkStats: performPollLocked() took 4ms
,09-01 11:15:32.087  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-01 11:15:32.087  1183  1183 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 11:15:32.087  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 11:15:32.087  1019  1344 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 11:15:32.087  1019  1132 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-01 11:15:32.087  1019  1344 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-01 11:15:32.087  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:32.087  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:32.087  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:32.087  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:32.087  1019  1132 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-01 11:15:32.087  1019  1344 W ActivityManager: userId = 0, bbcId = -10000,
09-01 11:15:32.087  1019  1344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:32.087  1019  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-01 11:15:32.087  1635  1635 I Hs20UtilService: Starting #23
09-01 11:15:32.087  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-01 11:15:32.087  1019  1019 I WifiTrafficPoller: mBoosterFLAG : 0
09-01 11:15:32.087  1019  1019 I WifiTrafficPoller: current booster mode : FullMode
,09-01 11:15:32.087  1635  1673 I Hs20UtilService: Message received 5007
,09-01 11:15:32.097  1183  1183 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 11:15:32.097  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-01 11:15:32.097  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:32.097  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:32.097  1019  1134 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-01 11:15:32.097  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:32.097  1019  1134 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-01 11:15:32.097  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:32.097  1019  7877 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:15:32.097  1019  7877 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-01 11:15:32.097  1019  7877 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-01 11:15:32.097  1019  7877 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,09-01 11:15:32.097  1019  7877 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 11:15:32.097  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:32.097  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 11:15:32.097  4723  4723 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-01 11:15:32.107   278  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-01 11:15:32.107  1019  1134 D ConnectivityService:    accepting network in place of null
09-01 11:15:32.107   278  1009 D Netd    : getNetworkForDns: using netid 504 for uid 1000
09-01 11:15:32.107  4723  4723 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-01 11:15:32.107  1467  1467 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-01 11:15:32.107  1467  1467 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 11:15:32.107  1019  1132 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-01 11:15:32.107  1019  1131 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-01 11:15:32.107  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-01 11:15:32.107  1019  1134 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-01 11:15:32.107  1019  1134 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-01 11:15:32.107  1019  1134 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-01 11:15:32.107  7058  7058 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-01 11:15:32.107  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-01 11:15:32.107  4723  4723 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-01 11:15:32.107  4723  4723 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-01 11:15:32.107  4723  4806 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 11:15:32.107  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-01 11:15:32.107  7058  7244 I jxcore-log: 
,09-01 11:15:32.117  1019  1134 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} },
09-01 11:15:32.117  1019  1134 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504],
09-01 11:15:32.117  1183  1685 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-01 11:15:32.127  1019  1019 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-01 11:15:32.127  1019  1135 D Tethering: MasterInitialState.processMessage what=3
,09-01 11:15:32.127  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit,
09-01 11:15:32.127  1019  1129 V NetworkStats: updateIfacesLocked()
09-01 11:15:32.127  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
09-01 11:15:32.127  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 11:15:32.127  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 11:15:32.127  1183  1183 D StatusBar.NetworkController: EthernetConnected: false
09-01 11:15:32.127  1183  1183 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-01 11:15:32.127  1183  1183 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-01 11:15:32.127  1183  1183 D StatusBar.NetworkController: updateDataNetType()
,09-01 11:15:32.127  1019  1129 V NetworkStats: performPollLocked() took 5ms
09-01 11:15:32.127  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:32.127  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 11:15:32.127  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:32.127  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:32.127  1019  1130 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-01 11:15:32.127  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit,
,09-01 11:15:32.137  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-01 11:15:32.137  1183  1183 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-01 11:15:32.137  1019  1545 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 11:15:32.137  1019  1545 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 11:15:32.137  1019  1545 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:32.137  1019  1545 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:32.137  1019  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 11:15:32.137  1183  1183 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-01 11:15:32.137  1183  1183 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 19 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,09-01 11:15:32.137  1183  1183 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-01 11:15:32.137  1183  1183 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,09-01 11:15:32.137  1183  1183 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 11:15:32.137  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-01 11:15:32.137  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:32.137  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:32.137  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-01 11:15:32.137  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:32.137  1635  1635 I Hs20UtilService: Starting #24
,09-01 11:15:32.137  1635  1673 I Hs20UtilService: Message received 5007
09-01 11:15:32.137  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 11:15:32.137  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:32.137  4723  4723 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-01 11:15:32.137  4723  4723 I NearbySettings: MountReceiver.onReceive - Keep current state,
,09-01 11:15:32.147  1019  1317 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-01 11:15:32.147  1019  1544 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-01 11:15:32.147  1019  1544 D SecContentProvider2: mCursor = null
,09-01 11:15:32.147  1019  1031 D SecContentProvider2: uri = 15 selection = getToastGravity
09-01 11:15:32.147  1019  1031 D SecContentProvider2: mCursor = null
,09-01 11:15:32.157  1019  1505 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
09-01 11:15:32.157  1019  1505 D SecContentProvider2: mCursor = null
,09-01 11:15:32.157  1019  1545 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-01 11:15:32.157  1019  1545 D SecContentProvider2: mCursor = null,
,09-01 11:15:32.157  1019  1490 D SecContentProvider2: uri = 15 selection = getToastEnabledState
09-01 11:15:32.157  1019  1490 D SecContentProvider2: mCursor = null
09-01 11:15:32.157  1019  1546 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
09-01 11:15:32.157  1019  1546 D SecContentProvider2: mCursor = null
,09-01 11:15:32.187   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,09-01 11:15:32.187  1019  1317 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1019
,09-01 11:15:32.197  1183  1183 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-01 11:15:32.237  1019  7877 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false,
,09-01 11:15:32.247  7914  7914 D AndroidRuntime: ,
09-01 11:15:32.247  7914  7914 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-01 11:15:32.247  7914  7914 D AndroidRuntime: CheckJNI is OFF
,09-01 11:15:32.247  7914  7914 D AndroidRuntime: readGMSProperty: start
09-01 11:15:32.247  7914  7914 D AndroidRuntime: readGMSProperty: already setted!!,
09-01 11:15:32.247  7914  7914 D AndroidRuntime: propertySet: couldn't set property (it is from app)
,09-01 11:15:32.247  7914  7914 D AndroidRuntime: readGMSProperty: could not set the property(default)!!,
,09-01 11:15:32.247  7914  7914 D AndroidRuntime: readGMSProperty: end
,09-01 11:15:32.247  7914  7914 D AndroidRuntime: addProductProperty: start
,09-01 11:15:32.267  1019  7877 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 01 Sep 2016 09:15:32 GMT], X-Android-Received-Millis=[1472721332274], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472721332253]},
09-01 11:15:32.267  1019  7877 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-01 11:15:32.267  1019  1134 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
,09-01 11:15:32.267  1019  7877 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-01 11:15:32.267  1019  1134 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504],
09-01 11:15:32.267  1183  1685 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-01 11:15:32.267  1019  1134 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-01 11:15:32.267  7058  7058 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-01 11:15:32.267  1019  1134 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-01 11:15:32.267  1019  1134 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-01 11:15:32.277  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-01 11:15:32.277  7058  7244 I jxcore-log: 
,09-01 11:15:32.277  1183  1183 D StatusBar.NetworkController: EthernetConnected: false
09-01 11:15:32.277  1183  1183 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-01 11:15:32.277  1183  1183 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
,09-01 11:15:32.277  1183  1183 D StatusBar.NetworkController: updateDataNetType()
,09-01 11:15:32.277  1183  1183 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-01 11:15:32.277  1183  1183 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-01 11:15:32.277  1183  1183 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-01 11:15:32.277  1183  1183 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 19 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-01 11:15:32.277  1183  1183 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-01 11:15:32.277  1183  1183 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
09-01 11:15:32.277  1183  1183 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 11:15:32.277  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700",
09-01 11:15:32.277  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:32.277  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 11:15:32.277  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-01 11:15:32.277  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 11:15:32.367  7914  7914 E AffinityControl: AffinityControl: registerfunction enter,
,09-01 11:15:32.387  7914  7914 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,09-01 11:15:32.407  7058  7058 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-01 11:15:32.407  7058  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-01 11:15:32.407  7058  7244 I jxcore-log: 
,09-01 11:15:32.417  1019  6683 D PackageManager: START PACKAGE DELETE: observer{168721514}
09-01 11:15:32.417  1019  6683 D PackageManager: pkg{<packageName>}
09-01 11:15:32.417  1019  6683 D PackageManager: user{0}
09-01 11:15:32.417  1019  6683 D PackageManager: caller{2000}
09-01 11:15:32.417  1019  6683 D PackageManager: flags{2}
,09-01 11:15:32.417  1019  6683 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-01 11:15:32.417  1019  6683 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true,
09-01 11:15:32.417  1019  6683 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,09-01 11:15:32.417  1019  6683 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
09-01 11:15:32.417  1019  6683 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-01 11:15:32.427  1019  1061 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
09-01 11:15:32.427  1019  1061 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-01 11:15:32.427  1019  1061 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-01 11:15:32.427  1019  1061 D ApplicationPolicy: getApplicationUninstallationEnabled
,09-01 11:15:32.427  1019  1061 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-01 11:15:32.427  1019  1061 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,09-01 11:15:32.457  1019  1046 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,09-01 11:15:32.457  1019  1046 I ActivityManager: Killing 7058:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-01 11:15:32.567  1019  1344 I WindowState: WIN DEATH: Window{381ac4b6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-01 11:15:32.577   258   450 I SurfaceFlinger: id=13 Removed NainActivit (6/9),
09-01 11:15:32.577  1019  1046 I ActivityManager:   Force finishing activity ActivityRecord{3504ae93 u0 com.test.thalitest/.MainActivity t163},
09-01 11:15:32.577   258  1041 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
09-01 11:15:32.577  1019  1053 I PowerManagerService: [PWL] Off : 75s ago
09-01 11:15:32.577  1019  1053 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-01 11:15:32.577  1019  1053 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-01 11:15:32.577  1019  1053 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1019, ws=null) (elapsedTime=23086)
,09-01 11:15:32.587  1019  1344 D InputDispatcher: Focus left window: 7058
,09-01 11:15:32.597  1019  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-01 11:15:32.597  1019  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-01 11:15:32.617  1019  1046 D InputDispatcher: Focused application released,
09-01 11:15:32.617  1019  1134 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:15:32.617  1019  1061 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,09-01 11:15:32.647  1019  1061 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-01 11:15:32.667  2820  2820 I art     : Explicit concurrent mark sweep GC freed 16591(990KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 791us total 36.284ms
,09-01 11:15:32.687  1986  1986 E SamsungIME: mOCRHelper is null
,09-01 11:15:32.707  1019  1103 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-01 11:15:32.727  1019  1490 W ActivityManager: Spurious death for ProcessRecord{278ff536 7058:com.test.thalitest/u0a170}, curProc for 7058: null
,09-01 11:15:32.737  2804  2804 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Sep 01 11:15:32 GMT+02:00 2016,
09-01 11:15:32.737  1458  1458 D PersonaManager: isKioskContainerExistOnDevice
,09-01 11:15:32.747  1458  1458 D RegisteredServicesCache: empty dynamic service
,09-01 11:15:32.767  1458  1458 D RegisteredComponentCache: Collect Tech packages for Knox
,09-01 11:15:32.777  1458  1458 D PersonaManager: isKioskContainerExistOnDevice
,09-01 11:15:32.777  1019  1129 V NetworkStats: removeUidsLocked() for UIDs [10170]
09-01 11:15:32.777  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 11:15:32.777  1019  1129 V NetworkStats: performPollLocked(flags=0x3)
,09-01 11:15:32.777  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 11:15:32.777  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 11:15:32.797  1019  1129 V NetworkStats: performPollLocked() took 15ms
09-01 11:15:32.797  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 11:15:32.797  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 11:15:32.797  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 11:15:32.827  1019  1019 I art     : Explicit concurrent mark sweep GC freed 75205(4MB) AllocSpace objects, 11(177KB) LOS objects, 33% free, 23MB/35MB, paused 4.970ms total 179.224ms
,09-01 11:15:32.827  1019  1031 I art     : WaitForGcToComplete blocked for 137.757ms for cause Explicit
,09-01 11:15:32.827   295   295 E SMD     : DCD OFF
,09-01 11:15:32.897  1019  1100 V AlarmManager: waitForAlarm result :4
,09-01 11:15:32.897  1019  1019 D RCPManagerService: PackageReceiver onReceive()
,09-01 11:15:32.907  1019  1019 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-01 11:15:32.907  1019  1019 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-01 11:15:32.907  1019  1019 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-01 11:15:32.907  1019  1019 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,09-01 11:15:32.917  1019  1019 I OTPFW   : ProvisionData::getAllEntries Enter
,09-01 11:15:32.927  1019  1019 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-01 11:15:32.977  1019  1031 I art     : Explicit concurrent mark sweep GC freed 12480(896KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 3.318ms total 153.096ms
,09-01 11:15:32.977  1019  1344 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-01 11:15:32.977  1019  1344 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-01 11:15:32.977  1019  1061 I art     : WaitForGcToComplete blocked for 255.513ms for cause Explicit
09-01 11:15:32.977  1696  1920 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-01 11:15:32.977  1019  1317 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-01 11:15:32.977  1019  1317 D SecContentProvider2: mCursor = null
,09-01 11:15:32.977  1019  1344 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:32.977  1019  1344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:32.977  1019  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-01 11:15:32.987  1019  1045 D EnterpriseDeviceManagerService: Package has changed for user 0
09-01 11:15:32.987  1019  1045 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,09-01 11:15:32.997  1019  1045 W TextServicesManagerService: no available spell checker services found
,09-01 11:15:33.027  2804  2804 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-01 11:15:33.027  1019  3288 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
,09-01 11:15:33.027  1019  3288 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-01 11:15:33.027  1019  3288 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-01 11:15:33.027  1019  3288 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:33.027  1019  3288 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.027  1019  3288 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:33.027  1019  3288 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.027  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 11:15:33.037  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 11:15:33.037  2804  2804 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-01 11:15:33.037  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-01 11:15:33.037  1019  1019 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-01 11:15:33.037  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,09-01 11:15:33.047  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED,
09-01 11:15:33.047  1019  1019 V EnterpriseBillingPolicy: uID is 10170
09-01 11:15:33.047  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
09-01 11:15:33.047  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-01 11:15:33.047  2804  2804 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-01 11:15:33.047  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-01 11:15:33.047  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-01 11:15:33.047  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
,09-01 11:15:33.047  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-01 11:15:33.047  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-01 11:15:33.047  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 11:15:33.047  7932  7932 E Zygote  : MountEmulatedStorage()
09-01 11:15:33.047  7932  7932 E Zygote  : v2
09-01 11:15:33.047  7932  7932 I libpersona: KNOX_SDCARD checking this for 10090
,09-01 11:15:33.047  7932  7932 I libpersona: KNOX_SDCARD not a persona
,09-01 11:15:33.047  1019  3288 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7932 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,09-01 11:15:33.057  7932  7932 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 11:15:33.057  7932  7932 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 11:15:33.057  7932  7932 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-01 11:15:33.057  1019  1046 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,09-01 11:15:33.057  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:33.057  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.057  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.057  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:33.067  2804  2804 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-01 11:15:33.077  7941  7941 E Zygote  : MountEmulatedStorage(),
,09-01 11:15:33.077  7941  7941 E Zygote  : v2
09-01 11:15:33.077  1019  1046 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7941 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
09-01 11:15:33.077  7941  7941 I libpersona: KNOX_SDCARD checking this for 10052
09-01 11:15:33.077  7941  7941 I libpersona: KNOX_SDCARD not a persona
09-01 11:15:33.077  7941  7941 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-01 11:15:33.087  7941  7941 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 11:15:33.087  7941  7941 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-01 11:15:33.087  1019  1046 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,09-01 11:15:33.097  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.097  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.097  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.097  1019  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:33.097  7932  7932 D TimaKeyStoreProvider: TimaSignature is unavailable
09-01 11:15:33.097  7932  7932 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:33.107  2804  7931 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-01 11:15:33.117  7962  7962 E Zygote  : MountEmulatedStorage()
,09-01 11:15:33.117  7962  7962 E Zygote  : v2
09-01 11:15:33.117  7962  7962 I libpersona: KNOX_SDCARD checking this for 10098
09-01 11:15:33.117  7962  7962 I libpersona: KNOX_SDCARD not a persona
09-01 11:15:33.117  7962  7962 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-01 11:15:33.117  7941  7941 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:33.117  7941  7941 D ActivityThread: Added TimaKeyStore provider
09-01 11:15:33.117  1019  1046 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7962 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-01 11:15:33.117  7962  7962 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 11:15:33.117  1019  1484 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
09-01 11:15:33.117  1019  1134 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
09-01 11:15:33.117  7962  7962 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-01 11:15:33.117  1019  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.117  1019  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.117  1019  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.117  1019  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.127  2804  7931 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
09-01 11:15:33.127  2804  7931 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
09-01 11:15:33.137  2804  7931 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-01 11:15:33.137  1019  1484 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7975 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-01 11:15:33.147  1019  1045 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75),
,09-01 11:15:33.147  7975  7975 E Zygote  : MountEmulatedStorage()
,09-01 11:15:33.147  7975  7975 E Zygote  : v2
09-01 11:15:33.147  7975  7975 I libpersona: KNOX_SDCARD checking this for 10032
09-01 11:15:33.147  7975  7975 I libpersona: KNOX_SDCARD not a persona
09-01 11:15:33.147  7975  7975 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 11:15:33.157  7975  7975 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 11:15:33.157  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 11:15:33.157  7975  7975 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-01 11:15:33.157  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 11:15:33.157  7962  7962 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:33.157  7962  7962 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:33.167  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-01 11:15:33.167  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-01 11:15:33.167  1019  1019 V EnterpriseBillingPolicy: uID is 10170
09-01 11:15:33.167  1019  3365 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-01 11:15:33.167  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
09-01 11:15:33.167  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-01 11:15:33.167  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-01 11:15:33.167  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-01 11:15:33.167  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package ,
09-01 11:15:33.167  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-01 11:15:33.167  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-01 11:15:33.177  1019  1061 W art     : Suspending all threads took: 5.519ms
,09-01 11:15:33.187  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,09-01 11:15:33.187  1019  1019 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,09-01 11:15:33.187  1019  1165 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,09-01 11:15:33.197  1019  1061 I art     : Explicit concurrent mark sweep GC freed 6143(298KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 13.612ms total 214.171ms
,09-01 11:15:33.197  7975  7975 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:33.197  7975  7975 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:33.217  7932  7932 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,09-01 11:15:33.217  7932  7932 D elm:15121: ELMEngine.ELMEngine( context ).
,09-01 11:15:33.217  7932  7932 D elm:15121: MDMBridge.setEnterpriseBridge()
,09-01 11:15:33.217  1019  1544 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
09-01 11:15:33.217  1019  1544 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-01 11:15:33.227  1019  1544 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:33.227  1019  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:33.227  1019  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-01 11:15:33.227  7932  7932 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-01 11:15:33.237  7932  7932 D elm:15121: ElmAgentService : onCreate()
,09-01 11:15:33.237  7932  7992 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,09-01 11:15:33.237  7932  7992 D elm:15121: MainReceiver.listeningToPackageRemoved()
,09-01 11:15:33.237  7932  7992 D elm:15121: MDMBridge.getInstance()
,09-01 11:15:33.237  7932  7992 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-01 11:15:33.237  2804  7931 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-01 11:15:33.237  1019  1032 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,09-01 11:15:33.237  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:33.247  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:33.247  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:33.247  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:33.257  1019  1045 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-01 11:15:33.257  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 11:15:33.257  1019  1045 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 11:15:33.257  7993  7993 E Zygote  : MountEmulatedStorage()
09-01 11:15:33.257  1019  1045 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-01 11:15:33.257  7993  7993 E Zygote  : v2
09-01 11:15:33.257  7993  7993 I libpersona: KNOX_SDCARD checking this for 1000
09-01 11:15:33.257  7993  7993 I libpersona: KNOX_SDCARD not a persona
09-01 11:15:33.267  7932  7992 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-01 11:15:33.267  7993  7993 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 11:15:33.267  1019  1032 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7993 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-01 11:15:33.267  7993  7993 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 11:15:33.267  7993  7993 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 11:15:33.277  2804  7931 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest,
09-01 11:15:33.277  2804  7931 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,09-01 11:15:33.287   324   324 I art     : Explicit concurrent mark sweep GC freed 8708(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 852us total 25.682ms,
,09-01 11:15:33.297  1019  1032 I ActivityManager: Killing 7422:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,09-01 11:15:33.297  7993  7993 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:33.297  7993  7993 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:33.307  7932  7932 D elm:15121: ElmAgentService : onDestroy().
,09-01 11:15:33.307   324   324 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 17.953ms
,09-01 11:15:33.317  1019  1082 I ActivityManager: Killing 7439:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,09-01 11:15:33.317  2804  2804 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-01 11:15:33.327  1019  1061 D PackageManager: delete codoeFile: 
,09-01 11:15:33.327  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-01 11:15:33.327   324   324 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 16.993ms
,09-01 11:15:33.327  1688  1688 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-01 11:15:33.327  1688  1688 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
09-01 11:15:33.327  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 11:15:33.337  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-01 11:15:33.337  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-01 11:15:33.337  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 11:15:33.347  1019  1061 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
,09-01 11:15:33.347  1019  1061 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,09-01 11:15:33.347  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-01 11:15:33.347  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-01 11:15:33.347  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-01 11:15:33.347  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-01 11:15:33.347  1019  1061 D PackageManager: result of delete: 1{168721514}
,09-01 11:15:33.347  1019  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 11:15:33.357  1019  1045 D UsbSettingsManager: clearDefaults: com.test.thalitest
,09-01 11:15:33.357  1019  1045 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-01 11:15:33.357  1019  1045 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-01 11:15:33.357  1019  1484 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
09-01 11:15:33.357  1019  1484 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,09-01 11:15:33.357  1019  1484 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:33.357  1019  1484 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 11:15:33.357  1019  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-01 11:15:33.367  7914  7914 D AndroidRuntime: Shutting down VM,
,09-01 11:15:33.377  7975  8011 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-01 11:15:33.377  7975  8011 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-01 11:15:33.387  1876  8010 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-01 11:15:33.387  1019  1490 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,09-01 11:15:33.387  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.387  1876  8010 D AccountUtils: Clearing selected account for com.test.thalitest
09-01 11:15:33.387  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.387  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.387  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:33.397  7975  8011 D SPPClientService: PushLog.txt file is not deleted.
09-01 11:15:33.397  7975  8011 D SPPClientService: PushLog.txt file is not deleted.
09-01 11:15:33.397  7975  8011 D SPPClientService: ============PushLog. stop!
,09-01 11:15:33.407  8015  8015 E Zygote  : MountEmulatedStorage(),
09-01 11:15:33.407  1019  1490 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8015 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-01 11:15:33.407  8015  8015 E Zygote  : v2
09-01 11:15:33.407  8015  8015 I libpersona: KNOX_SDCARD checking this for 1000
09-01 11:15:33.407  8015  8015 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-01 11:15:33.407  8015  8015 I libpersona: KNOX_SDCARD not a persona
,09-01 11:15:33.417  1019  1544 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 11:15:33.417  1019  1544 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:33.417  1019  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 11:15:33.417  1019  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 11:15:33.417  8015  8015 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 11:15:33.417  8015  8015 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 11:15:33.427  1019  1490 I ActivityManager: Killing 7454:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,09-01 11:15:33.427  1019  1505 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-01 11:15:33.427  1019  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-01 11:15:33.427  1019  1505 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:33.427  1019  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 11:15:33.427  1019  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
09-01 11:15:33.437  1019  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-01 11:15:33.437  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
,09-01 11:15:33.437  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:33.437  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 11:15:33.437  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 11:15:33.437  1019  1484 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-01 11:15:33.437  1019  1484 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-01 11:15:33.437  1019  1484 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:33.437  1019  1484 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 11:15:33.437  1019  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-01 11:15:33.447  1019  1317 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
09-01 11:15:33.447  1019  1317 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,09-01 11:15:33.447  8015  8015 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:33.447  8015  8015 D ActivityThread: Added TimaKeyStore provider
09-01 11:15:33.447  1019  1317 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:33.447  1019  1317 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:33.447  1019  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,09-01 11:15:33.467  7764  7764 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,09-01 11:15:33.467  1876  8010 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-01 11:15:33.467  1019  6683 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,09-01 11:15:33.467  1019  6683 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.467  1019  6683 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.467  1019  6683 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.467  1019  6683 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:33.477  1876  8030 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
09-01 11:15:33.477  1876  8030 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,09-01 11:15:33.487  8035  8035 E Zygote  : MountEmulatedStorage()
09-01 11:15:33.487  8035  8035 E Zygote  : v2
09-01 11:15:33.487  8035  8035 I libpersona: KNOX_SDCARD checking this for 1000
09-01 11:15:33.487  8035  8035 I libpersona: KNOX_SDCARD not a persona
,09-01 11:15:33.487  8035  8035 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 11:15:33.487  1019  6683 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=8035 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-01 11:15:33.487  8015  8015 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,09-01 11:15:33.487  1019  3288 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-01 11:15:33.487  8035  8035 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 11:15:33.487  1019  3288 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,09-01 11:15:33.487  8035  8035 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 11:15:33.497  1019  3288 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:33.497  1019  3288 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 11:15:33.497  1019  3288 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-01 11:15:33.497  1019  1490 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-01 11:15:33.497  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:33.497  1019  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 11:15:33.497  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 11:15:33.507  1019  6683 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,09-01 11:15:33.507  1876  8030 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
09-01 11:15:33.507  1019  6683 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.507  1876  8030 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,09-01 11:15:33.507  1019  6683 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.507  1019  6683 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.507  1019  6683 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:33.507  8035  8035 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:33.517  8035  8035 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:33.517  8051  8051 E Zygote  : MountEmulatedStorage()
09-01 11:15:33.517  8051  8051 I libpersona: KNOX_SDCARD checking this for 10039
,09-01 11:15:33.517  8051  8051 E Zygote  : v2
09-01 11:15:33.517  8051  8051 I libpersona: KNOX_SDCARD not a persona
09-01 11:15:33.527  1019  6683 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=8051 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,09-01 11:15:33.527  8051  8051 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-01 11:15:33.527  1019  6683 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 11:15:33.527  1019  6683 W ActivityManager: userId = 0, bbcId = -10000
,09-01 11:15:33.527  1019  6683 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 11:15:33.527  1019  6683 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 11:15:33.527  8051  8051 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 11:15:33.527  8051  8051 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 11:15:33.537  1019  1317 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
09-01 11:15:33.537  1019  1317 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,09-01 11:15:33.547  1019  1317 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:33.547  1019  1317 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 11:15:33.547  1019  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,09-01 11:15:33.547  1019  6683 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-01 11:15:33.547  1019  6683 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,09-01 11:15:33.547  1876  8030 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
09-01 11:15:33.547  1876  8030 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
09-01 11:15:33.547  1876  8030 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,09-01 11:15:33.557  8051  8051 D TimaKeyStoreProvider: TimaSignature is unavailable
09-01 11:15:33.557  1019  6683 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.557  1019  6683 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:33.557  1019  6683 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.557  1019  6683 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 11:15:33.557  1019  6683 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.557  1019  6683 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-01 11:15:33.557  1019  6683 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.557  8051  8051 D ActivityThread: Added TimaKeyStore provider
09-01 11:15:33.557  8035  8035 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-01 11:15:33.567  3228  3307 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-01 11:15:33.567  1876  8030 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
09-01 11:15:33.567  1876  8030 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,09-01 11:15:33.567  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.,
09-01 11:15:33.577  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
09-01 11:15:33.577  1876  8030 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,09-01 11:15:33.577  1876  8030 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
09-01 11:15:33.577  1876  8030 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0,
09-01 11:15:33.577  1876  8030 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
09-01 11:15:33.577  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false,
09-01 11:15:33.577  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
09-01 11:15:33.577  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,09-01 11:15:33.577  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false,
09-01 11:15:33.577  7914  7914 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-01 11:15:33.577  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,09-01 11:15:33.577  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
,09-01 11:15:33.577  8068  8068 E Zygote  : MountEmulatedStorage()
09-01 11:15:33.577  8068  8068 E Zygote  : v2
09-01 11:15:33.577  8068  8068 I libpersona: KNOX_SDCARD checking this for 10011
09-01 11:15:33.577  8068  8068 I libpersona: KNOX_SDCARD not a persona
,09-01 11:15:33.577  8068  8068 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-01 11:15:33.577  1019  6683 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=8068 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
09-01 11:15:33.587  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
09-01 11:15:33.587  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
09-01 11:15:33.587  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
09-01 11:15:33.587  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
09-01 11:15:33.587  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
09-01 11:15:33.587  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
09-01 11:15:33.587  8068  8068 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 11:15:33.587  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
09-01 11:15:33.587  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
09-01 11:15:33.587  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
09-01 11:15:33.587  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
09-01 11:15:33.587  8068  8068 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-01 11:15:33.587  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
09-01 11:15:33.587  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
09-01 11:15:33.587  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
09-01 11:15:33.587  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
09-01 11:15:33.587  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
09-01 11:15:33.587  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,09-01 11:15:33.587  1019  1490 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
09-01 11:15:33.597  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.597  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.597  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.597  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.597  7764  7764 D BluetoothAdapter: cancelDiscovery
,09-01 11:15:33.597  1019  1061 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-01 11:15:33.597  1019  1061 D PackageManager: userId{-1}
09-01 11:15:33.597  1019  1061 D PackageManager: andCode{true}
,09-01 11:15:33.617  1019  1490 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=8084 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-01 11:15:33.627  8068  8068 D TimaKeyStoreProvider: TimaSignature is unavailable
09-01 11:15:33.627  8084  8084 I libpersona: KNOX_SDCARD checking this for 1000
09-01 11:15:33.627  8084  8084 E Zygote  : MountEmulatedStorage()
09-01 11:15:33.627  8084  8084 I libpersona: KNOX_SDCARD not a persona
09-01 11:15:33.627  8084  8084 E Zygote  : v2
09-01 11:15:33.627  8068  8068 D ActivityThread: Added TimaKeyStore provider
09-01 11:15:33.627  8084  8084 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 11:15:33.627  8084  8084 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 11:15:33.627  8084  8084 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 11:15:33.637  3228  3393 D BluetoothAdapterProperties: mDiscovering is false
09-01 11:15:33.637  3228  3393 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
09-01 11:15:33.637  1876  1876 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-01 11:15:33.637  1876  1876 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-01 11:15:33.657  8084  8084 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:33.657  7764  7764 D BluetoothAdapter: cancelDiscovery = true
,09-01 11:15:33.657  1019  1061 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
09-01 11:15:33.657  8084  8084 D ActivityThread: Added TimaKeyStore provider
09-01 11:15:33.657  7764  7764 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,09-01 11:15:33.657  1019  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.657  1019  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.657  1019  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.657  1019  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:33.667  8051  8051 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-01 11:15:33.667  8051  8051 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 11:15:33.667  8051  8051 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-01 11:15:33.667  8051  8051 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-01 11:15:33.667  8051  8051 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-01 11:15:33.667  8051  8051 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-01 11:15:33.667  8051  8051 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-01 11:15:33.677  8068  8068 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-01 11:15:33.677  8068  8068 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-01 11:15:33.687  1019  1061 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8103 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a,
,09-01 11:15:33.687  8103  8103 E Zygote  : MountEmulatedStorage(),
09-01 11:15:33.697  8103  8103 E Zygote  : v2
09-01 11:15:33.697  8103  8103 I libpersona: KNOX_SDCARD checking this for 10003
09-01 11:15:33.697  8103  8103 I libpersona: KNOX_SDCARD not a persona
,09-01 11:15:33.697  8103  8103 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 11:15:33.697  8103  8103 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 11:15:33.697  8103  8103 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 11:15:33.707  1019  6811 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-01 11:15:33.707  1019  6683 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-01 11:15:33.707  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-01 11:15:33.707  7764  7764 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
09-01 11:15:33.707  7764  7764 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-01 11:15:33.707  7764  7764 E SQLiteLog: (3850) statement aborts at 17: [INSERT INTO dump_log(timestamp,message) VALUES (?,?)] disk I/O error
09-01 11:15:33.707  7764  7764 E SQLiteDatabase: Error inserting timestamp=1472721333664 message=Predictor: service stopped by removePlaceCategories()
09-01 11:15:33.707  7764  7764 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-01 11:15:33.707  7764  7764 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-01 11:15:33.707  7764  7764 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
09-01 11:15:33.707  7764  7764 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
09-01 11:15:33.707  7764  7764 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-01 11:15:33.707  7764  7764 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
,09-01 11:15:33.707  7764  7764 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
09-01 11:15:33.707  7764  7764 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
09-01 11:15:33.707  7764  7764 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
09-01 11:15:33.707  7764  7764 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739),
09-01 11:15:33.707  7764  7764 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-01 11:15:33.707  7764  7764 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-01 11:15:33.707  7764  7764 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 11:15:33.707  7764  7764 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:33.707  7764  7764 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:15:33.707  7764  7764 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 11:15:33.707  7764  7764 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194),
09-01 11:15:33.707  7764  7764 E UserAnalysis: It failed to insert to dump_log table
,09-01 11:15:33.717  1019  6683 W ActivityManager: userId = 0, bbcId = -10000
09-01 11:15:33.717  1019  6683 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 11:15:33.717  1019  6683 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 11:15:33.737  1019  1544 I ActivityManager: Killing 7471:com.sec.android.soagent/u0a31 (adj 15): empty #21
,09-01 11:15:33.737  8068  8068 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,09-01 11:15:33.737  8068  8068 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,09-01 11:15:33.747  8035  8035 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/history.db" with flag (131138) and mode_t (0) due to error (30)
,09-01 11:15:33.747  8035  8035 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/history.db'.
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:159)
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:66)
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 11:15:33.747  8035  8035 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-01 11:15:33.747  8035  8035 D AndroidRuntime: Shutting down VM
,09-01 11:15:33.747  8035  8035 E AndroidRuntime: FATAL EXCEPTION: main
09-01 11:15:33.747  8035  8035 E AndroidRuntime: Process: com.samsung.android.sm, PID: 8035
09-01 11:15:33.747  8035  8035 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.samsung.android.sm.ui.security.MonitorReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3132)
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181),
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	,at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 11:15:33.747  8035  8035 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method),
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:159)
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:66),
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
09-01 11:15:33.747  8035  8035 E AndroidRuntime: 	... 9 more
09-01 11:15:33.747  8068  8068 I MultiDex: VM with version 2.1.0 has multidex support,
09-01 11:15:33.747  8068  8068 I MultiDex: install
09-01 11:15:33.747  8068  8068 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-01 11:15:33.757  1876  1876 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-01 11:15:33.757  1876  1876 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-01 11:15:33.757  1019  1317 D LocationManagerService: getProviders()=[passive, gps]
09-01 11:15:33.757  1019  1032 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-01 11:15:33.767  8103  8103 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 11:15:33.767  8103  8103 D ActivityThread: Added TimaKeyStore provider
,09-01 11:15:33.767  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.767  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.767  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 11:15:33.767  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 11:15:33.787  8124  8124 E Zygote  : MountEmulatedStorage()
09-01 11:15:33.787  8124  8124 E Zygote  : v2
09-01 11:15:33.787  8124  8124 I libpersona: KNOX_SDCARD checking this for 1000
09-01 11:15:33.787  8124  8124 I libpersona: KNOX_SDCARD not a persona
,09-01 11:15:33.797  8124  8124 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-01 11:15:33.797  8124  8124 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 11:15:33.797  8124  8124 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 11:15:33.797  1019  1032 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8124 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-01 11:15:33.807  8051  8051 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)
,09-01 11:15:33.807  8051  8051 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.gallery3d/databases/picasa.db'.
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider$SyncContext.<init>(PicasaContentProvider.java:911)
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider.attachInfo(PicasaContentProvider.java:103)
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 11:15:33.807  8051  8051 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 11:15:33.807  1019  1484 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup

```
