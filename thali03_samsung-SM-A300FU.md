#### Test 797638305c870dd_thali03_samsung-SM-A300FU Logs


```
--------- beginning of system
08-30 16:00:15.579  1020  1492 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
08-30 16:00:15.579  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:15.579  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:15.579  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:15.579  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:15.599  1020  1492 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7008 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
--------- beginning of main
08-30 16:00:15.599  7008  7008 E Zygote  : MountEmulatedStorage()
08-30 16:00:15.599  7008  7008 I libpersona: KNOX_SDCARD checking this for 10148
08-30 16:00:15.599  7008  7008 E Zygote  : v2
08-30 16:00:15.599  7008  7008 I libpersona: KNOX_SDCARD not a persona
08-30 16:00:15.609  1020  1359 I ActivityManager: Killing 6577:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-30 16:00:15.609  7008  7008 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 16:00:15.609  7008  7008 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 16:00:15.609  7008  7008 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 16:00:15.639  7008  7008 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 16:00:15.639  7008  7008 D ActivityThread: Added TimaKeyStore provider
08-30 16:00:15.649  1020  1033 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-30 16:00:15.649  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:15.649  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 16:00:15.649  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
08-30 16:00:15.659  1020  1220 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 16:00:15.659  1020  1220 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-30 16:00:15.659  1020  1220 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:15.659  1020  1220 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 16:00:15.659  1020  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-30 16:00:15.679  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 16:00:15.699  1020  1493 D PowerManagerService: [api] handleWakeLockDeath : release WakeLock : PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10081, pid=6577, ws=null) (elapsedTime=3126)
08-30 16:00:15.699  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 16:00:15.699  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 16:00:15.709  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 16:00:15.709  6978  6978 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 172.989ms
08-30 16:00:15.709  1020  1045 W ProcessCpuTracker: Skipping unknown process pid 6577
08-30 16:00:15.739  1020  1494 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-30 16:00:15.739  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 16:00:15.739  7008  7008 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
08-30 16:00:15.749  1020  1494 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:15.749  1020  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 16:00:15.749  1020  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-30 16:00:15.749  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 16:00:15.749  1020  4405 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 16:00:15.749  1020  4405 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-30 16:00:15.749  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 16:00:15.749  1020  4405 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:15.749  1020  4405 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 16:00:15.749  1020  4405 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-30 16:00:15.749  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 16:00:15.749  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 16:00:15.759  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 16:00:15.759  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 16:00:15.769  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 16:00:15.789  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 16:00:15.799  1020  1507 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
08-30 16:00:15.799  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 16:00:15.799  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 16:00:15.799  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:15.799  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 16:00:15.799  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:15.799  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:15.799  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:15.799  6953  6953 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-30 16:00:15.819  7038  7038 E Zygote  : MountEmulatedStorage()
08-30 16:00:15.819  7038  7038 E Zygote  : v2
08-30 16:00:15.819  1020  1507 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=7038 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-30 16:00:15.819  7038  7038 I libpersona: KNOX_SDCARD checking this for 1000
08-30 16:00:15.819  7038  7038 I libpersona: KNOX_SDCARD not a persona
08-30 16:00:15.829  7038  7038 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 16:00:15.829  7038  7038 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 16:00:15.829  7038  7038 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 16:00:15.839  1020  1507 I ActivityManager: Killing 6592:com.sec.esdk.elm/u0a90 (adj 15): empty #21
08-30 16:00:15.859  7038  7038 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 16:00:15.869  7038  7038 D ActivityThread: Added TimaKeyStore provider
08-30 16:00:15.879  1020  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-30 16:00:15.879  1020  1492 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:15.879  1020  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 16:00:15.879  1020  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
08-30 16:00:15.889  7038  7038 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
08-30 16:00:15.899  6953  6953 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-30 16:00:15.899  7026  7026 D AndroidRuntime: 
08-30 16:00:15.899  7026  7026 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 16:00:15.909  7026  7026 D AndroidRuntime: CheckJNI is OFF
08-30 16:00:15.909  7026  7026 D AndroidRuntime: readGMSProperty: start
08-30 16:00:15.909  7026  7026 D AndroidRuntime: readGMSProperty: already setted!!
08-30 16:00:15.909  7026  7026 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 16:00:15.909  7026  7026 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 16:00:15.909  7026  7026 D AndroidRuntime: readGMSProperty: end
08-30 16:00:15.909  7026  7026 D AndroidRuntime: addProductProperty: start
08-30 16:00:15.909  6953  6953 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-30 16:00:15.949  6753  6839 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 697 ms] updated apps [took 697 ms] 
08-30 16:00:15.949  1020  1032 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
08-30 16:00:15.949  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:15.949  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:15.949  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:15.949  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:15.979  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 16:00:15.979  7062  7062 E Zygote  : MountEmulatedStorage()
08-30 16:00:15.979  7062  7062 E Zygote  : v2
08-30 16:00:15.979  7062  7062 I libpersona: KNOX_SDCARD checking this for 10152
08-30 16:00:15.979  7062  7062 I libpersona: KNOX_SDCARD not a persona
08-30 16:00:15.979  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 16:00:15.979  6953  6953 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-30 16:00:15.979  7062  7062 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 16:00:15.989  1020  1032 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7062 uid=10152 gids={50152, 9997} abi=armeabi-v7a
08-30 16:00:15.989  1020  1032 I ActivityManager: Killing 6344:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
08-30 16:00:15.999  7062  7062 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 16:00:15.999  1020  1139 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-30 16:00:15.999  7062  7062 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 16:00:15.999  1020  3781 I ActivityManager: Killing 6360:com.android.calendar/u0a131 (adj 15): empty #21
08-30 16:00:16.009  6978  6978 W art     : Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 302.670ms
08-30 16:00:16.029  7062  7062 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 16:00:16.029  7062  7062 D ActivityThread: Added TimaKeyStore provider
08-30 16:00:16.029  1020  1032 I ActivityManager: Killing 6619:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
08-30 16:00:16.039  6978  7077 D Mms/ArtClassLoader: init before art
08-30 16:00:16.069  6978  6978 D Mms/TelephonyPermission: start operation mode monitor
08-30 16:00:16.069  7026  7026 E AffinityControl: AffinityControl: registerfunction enter
08-30 16:00:16.079  7062  7062 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
08-30 16:00:16.079  7062  7062 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
08-30 16:00:16.079  6978  6978 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 16:00:16.079  7062  7062 I TapandpayWidget:Utils: Clear T&P info.
08-30 16:00:16.089  1948  6852 W art     : Verification of void com.google.android.gms.games.broker.GameAgent.addGameBadgeOps(com.google.android.gms.common.internal.ClientContext, com.google.android.gms.games.server.api.MarketInstance, java.lang.String, java.util.ArrayList, int) took 173.419ms
08-30 16:00:16.099  7026  7026 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 16:00:16.109  6978  6978 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-30 16:00:16.109  6978  6978 D Mms/TelephonyPermission: isDefault true
08-30 16:00:16.109  6978  6978 D Mms/MmsApp: onCreate() com.android.mms
08-30 16:00:16.109  1020  1494 E PersonaManagerService: inState():  stateMachine is null !!
08-30 16:00:16.109  1020  1494 I PersonaManagerService: PersonaId don't exist
08-30 16:00:16.109  1020  1494 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-30 16:00:16.119  7062  7062 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
08-30 16:00:16.119  1020  1494 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 16:00:16.139  1020  1494 W ActivityManager: mDVFSHelper.acquire()
08-30 16:00:16.139  1020  1494 D FocusedStackFrame: Set to : 0
08-30 16:00:16.149  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:16.149  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:16.149  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:16.149  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:16.149  1020  1050 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-30 16:00:16.149  1020  1050 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-30 16:00:16.159  1020  1494 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7084 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 16:00:16.159  1020  1494 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-30 16:00:16.159  1020  1494 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 16:00:16.169  1020  1494 D InputDispatcher: Focused application set to: xxxx
08-30 16:00:16.169  1020  1494 D InputDispatcher: Focus left window: 1495
08-30 16:00:16.169  7084  7084 E Zygote  : MountEmulatedStorage()
08-30 16:00:16.169  1020  4405 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
08-30 16:00:16.169  7026  7026 D AndroidRuntime: Shutting down VM
08-30 16:00:16.169  7084  7084 E Zygote  : v2
08-30 16:00:16.169  7084  7084 I libpersona: KNOX_SDCARD checking this for 10170
08-30 16:00:16.169  7084  7084 I libpersona: KNOX_SDCARD not a persona
08-30 16:00:16.169  1020  4405 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:16.169  1020  4405 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:16.169  1020  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-30 16:00:16.169  1020  4405 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:16.169  1020  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-30 16:00:16.169  1020  4405 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:16.169  7084  7084 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 16:00:16.169   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-30 16:00:16.179  7084  7084 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 16:00:16.179  7084  7084 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-30 16:00:16.199  1020  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 16:00:16.199  1020  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 16:00:16.209  7084  7084 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 16:00:16.209  7084  7084 D ActivityThread: Added TimaKeyStore provider
08-30 16:00:16.239  7099  7099 E Zygote  : MountEmulatedStorage()
08-30 16:00:16.239  7099  7099 I libpersona: KNOX_SDCARD checking this for 10009
08-30 16:00:16.239  7099  7099 E Zygote  : v2
08-30 16:00:16.239  7099  7099 I libpersona: KNOX_SDCARD not a persona
08-30 16:00:16.239  1020  4405 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7099 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-30 16:00:16.249  1020  4405 I ActivityManager: Killing 6643:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
08-30 16:00:16.249  7099  7099 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 16:00:16.249  7099  7099 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 16:00:16.259  1020  1507 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-30 16:00:16.259  1020  1020 V ActivityManager: Display changed displayId=0
08-30 16:00:16.269  1020  1050 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-30 16:00:16.279  1020  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-30 16:00:16.279  1020  1050 W DisplayManagerService: Failed to notify process 6643 that displays changed, assuming it died.
08-30 16:00:16.279  1020  1050 W DisplayManagerService: android.os.TransactionTooLargeException
08-30 16:00:16.279  1020  1050 W DisplayManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 16:00:16.279  1020  1050 W DisplayManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 16:00:16.279  1020  1050 W DisplayManagerService: 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
08-30 16:00:16.279  1020  1050 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1372)
08-30 16:00:16.279  1020  1050 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1170)
08-30 16:00:16.279  1020  1050 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:146)
08-30 16:00:16.279  1020  1050 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1305)
08-30 16:00:16.279  1020  1050 W DisplayManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:00:16.279  1020  1050 W DisplayManagerService: 	at android.os.Looper.loop(Looper.java:145)
08-30 16:00:16.279  1020  1050 W DisplayManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 16:00:16.279  1020  1050 W DisplayManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 16:00:16.279  7099  7099 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-30 16:00:16.279  1020  3784 I art     : Explicit concurrent mark sweep GC freed 145043(8MB) AllocSpace objects, 3(1847KB) LOS objects, 33% free, 23MB/34MB, paused 2.819ms total 218.438ms
08-30 16:00:16.319  7099  7099 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 16:00:16.319  7099  7099 D ActivityThread: Added TimaKeyStore provider
08-30 16:00:16.329  1020  1507 D PersonaManager: isKioskContainerExistOnDevice
08-30 16:00:16.329  6881  6946 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-30 16:00:16.329  6881  6946 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 16:00:16.329  6881  6946 I GAv4    :   adb logcat -s GAv4
08-30 16:00:16.339  6978  6978 D Mms/MmsApp: [start]    initCountryIso consume time = 847.278333
08-30 16:00:16.349  1020  1020 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-30 16:00:16.369   258  1115 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
08-30 16:00:16.369   258   446 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-30 16:00:16.369  1020  1438 D CountryDetector: The first listener is added
08-30 16:00:16.379  7026  7026 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-30 16:00:16.379  1495  1495 V ActivityThread: updateVisibility : ActivityRecord{377177a1 token=android.os.BinderProxy@124cfa3d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-30 16:00:16.379  1495  1495 D Launcher: onTrimMemory. Level: 20
,08-30 16:00:16.379  6978  6978 D Mms/MmsApp: [end]    initCountryIso consume time = 43.157865
08-30 16:00:16.379  6978  6978 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.112968
,08-30 16:00:16.389  6953  6953 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-30 16:00:16.389  1020  1465 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
08-30 16:00:16.389  1020  1465 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,08-30 16:00:16.399  1020  1465 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:16.399  1020  1465 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 16:00:16.399  1020  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,08-30 16:00:16.409  6881  6946 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 16:00:16.409  1020  1494 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-30 16:00:16.429  6978  6978 D Mms/MmsConfig: before partial update
,08-30 16:00:16.439  6953  6953 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-30 16:00:16.439  6953  7123 D Ads     : Skipping gmscore version check
,08-30 16:00:16.449  6881  6946 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-30 16:00:16.459  6978  6978 D Mms/MmsConfig: Load Resize quality : 80
,08-30 16:00:16.469  6978  6978 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,08-30 16:00:16.469  6978  6978 D EasySignUpManager_1.0.1: isAuth is false
08-30 16:00:16.469  6978  6978 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,08-30 16:00:16.479  1472  1996 D TP/MmsSmsProvider: query,matched:2117, calling pid = 6978
,08-30 16:00:16.479  1472  1996 D TP/MmsSmsProvider: match 2117:Elapsed time : 2.770 ms
,08-30 16:00:16.489  6881  7125 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-30 16:00:16.489  6881  6946 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
,08-30 16:00:16.499  6978  6978 D EasySignUpManager_1.0.1: isAuth is false
,08-30 16:00:16.499  6978  6978 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,08-30 16:00:16.499  6978  6978 E CscParser: mps_code.dat does not exist
,08-30 16:00:16.499  6978  6978 E CscParser: customer_path =/system/csc/customer.xml
,08-30 16:00:16.499  6978  6978 E CscParser: fileName + /system/csc/customer.xml
,08-30 16:00:16.509  1020  1493 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 16:00:16.519  1020  1493 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:16.519  1020  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 16:00:16.519  1020  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,08-30 16:00:16.519  6978  6978 E CscParser: mps_code.dat does not exist
08-30 16:00:16.519  6978  6978 E CscParser: customer_path =/system/csc/customer.xml
08-30 16:00:16.519  6978  6978 E CscParser: fileName + /system/csc/customer.xml
,08-30 16:00:16.529  6953  6953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 16:00:16.529  6978  6978 D CscParser: getInstance fileName =/system/csc/customer.xml
08-30 16:00:16.539  6978  6978 D Mms/MmsConfig:  enable multiwindow = false
,08-30 16:00:16.559  6978  6978 E Mms/MessageUtils: setCountryDetector : update country detector info 
,08-30 16:00:16.559  6978  6978 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-30 16:00:16.569   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb74797c8
08-30 16:00:16.569   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-30 16:00:16.569   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
08-30 16:00:16.569   272   349 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1220045512)
08-30 16:00:16.579  6978  6978 D Mms/MmsConfig: [end]    init() consume time = 192.688906
,08-30 16:00:16.579  6978  6978 D Mms/Contact: [start]    init() consume time = 1.180834
,08-30 16:00:16.579  7084  7084 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-30 16:00:16.599  1472  1489 D TP/MmsSmsProvider: query,matched:13, calling pid = 6978
,08-30 16:00:16.599  1472  1489 D TP/MmsSmsProvider: match 13:Elapsed time : 7.048 ms
,08-30 16:00:16.609  6978  6978 D Mms/Contact: [end]    init consume time = 33.837448
,08-30 16:00:16.609  7084  7084 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 7252-7255)
08-30 16:00:16.609  7084  7084 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-30 16:00:16.619  6978  7129 D Mms/DraftCache: [start]    rebuildCache consume time = 11.695468
,08-30 16:00:16.619   272   349 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
08-30 16:00:16.619   272   349 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-30 16:00:16.619   272   349 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1220045512) wakelock released: 1, error no: 0
08-30 16:00:16.619   272   349 I rmt_storage: 
,08-30 16:00:16.629   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb74797c8
,08-30 16:00:16.629  1472  1491 D TP/MmsSmsProvider: query,matched:12, calling pid = 6978
,08-30 16:00:16.629  6978  6978 D Mms/MethodReflector: getSubId is called
08-30 16:00:16.629  6978  6978 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,08-30 16:00:16.629  1472  1491 D TP/MmsSmsProvider: match 12:Elapsed time : 1.475 ms
,08-30 16:00:16.639  6978  7129 D Mms/DraftCache: [end]    rebuildCache consume time = 14.783021
,08-30 16:00:16.639  6978  6978 D Mms/MethodReflector: getTelephonyProperty is called
08-30 16:00:16.639  6978  6978 D Mms/DownloadManager: roaming -> false (slotId = 0)
,08-30 16:00:16.639  6978  6978 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-30 16:00:16.639  6978  6978 D Mms/DownloadManager: auto download without roaming -> true
08-30 16:00:16.639  6978  6978 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-30 16:00:16.639  6978  6978 D Mms/MethodReflector: getSubId is called
,08-30 16:00:16.639  6978  6978 D Mms/MethodReflector: getDefaultSmsSubId is called
08-30 16:00:16.639  6978  6978 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
08-30 16:00:16.639  6978  6978 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
08-30 16:00:16.639  6978  6978 D Mms/MethodReflector: getTelephonyProperty is called
08-30 16:00:16.639  6978  6978 D Mms/DownloadManager: roaming -> false (slotId = 1)
08-30 16:00:16.639  6978  6978 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-30 16:00:16.639  6978  6978 D Mms/DownloadManager: auto download without roaming -> true
08-30 16:00:16.639  6978  6978 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-30 16:00:16.639  6978  6978 D Mms/DownloadManager: auto download during roaming secondary -> false
08-30 16:00:16.639  6978  6978 D Mms/DownloadManager: mAutoDownload ------> true
,08-30 16:00:16.659  6881  6893 W art     : Suspending all threads took: 12.725ms
,08-30 16:00:16.689  6978  7077 D Mms/ArtClassLoader: init [DONE] art
,08-30 16:00:16.709  6978  6978 D ComposerPerformance: 1472565616716 ms / [DONE] Composer constructor,
,08-30 16:00:16.709  6978  6978 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,08-30 16:00:16.709  6978  6978 I Mms/ReservationManager: ReservationManager()
08-30 16:00:16.709  6978  6978 I Mms/ReservationManager: resetAfterConnected()
,08-30 16:00:16.709  1472  1491 D TP/MmsSmsProvider: query,matched:7, calling pid = 6978
,08-30 16:00:16.709  1472  1491 D TP/MmsSmsProvider: match 7:Elapsed time : 1.651 ms
08-30 16:00:16.709  6978  7134 D Mms/Conversation: [start]    init() consume time = 75.899115
08-30 16:00:16.719  1472  1489 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-30 16:00:16.719  6978  6978 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
08-30 16:00:16.719  1472  1489 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-30 16:00:16.719  1472  1489 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
08-30 16:00:16.719  1472  1489 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
08-30 16:00:16.719  1472  1489 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-30 16:00:16.719  1472  1489 D TP/MmsSmsProvider: need read changed broadcast:false
08-30 16:00:16.719  6978  7134 D Mms/Conversation: [end]    init consume time = 9.034739
08-30 16:00:16.719  6978  6978 D Mms/MmsApp: [end]    onCreate() consume time = 3.009167
08-30 16:00:16.729  6978  7134 D Mms/MessagingNotification: [start]    init() consume time = 7.190729
08-30 16:00:16.729  6978  7134 D Mms/MessagingNotification: [end]    init consume time = 2.625886
08-30 16:00:16.739  6978  7135 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 2.907291
08-30 16:00:16.739  1472  1491 D TP/MmsSmsProvider: query,matched:0, calling pid = 6978
08-30 16:00:16.739  1472  1491 V TP/MmsSmsProvider: getSimpleConversations entered.
08-30 16:00:16.739  1472  1491 D TP/MmsSmsProvider: match 0:Elapsed time : 1.099 ms
08-30 16:00:16.739  6978  6978 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
08-30 16:00:16.739  1472  1996 D TP/MmsSmsProvider: query,matched:400, calling pid = 6978
08-30 16:00:16.739  6978  6978 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
08-30 16:00:16.749  6978  6978 D Mms/MethodReflector: getSubId is called
08-30 16:00:16.749  6978  6978 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-30 16:00:16.749  1020  1494 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
08-30 16:00:16.749  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:16.749  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:16.749  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:16.749  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:16.749  6978  6978 D Mms/MethodReflector: getTelephonyProperty is called
08-30 16:00:16.749  6978  6978 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-30 16:00:16.749  6978  6978 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-30 16:00:16.749  6978  7136 D Mms/Synchronizer: [start]    doSync consume time = 11.249375
08-30 16:00:16.749  6978  6978 D Mms/DownloadManager: auto download without roaming -> true
08-30 16:00:16.749  6978  6978 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-30 16:00:16.749  6978  6978 D Mms/DownloadManager: mAutoDownload ------> true
08-30 16:00:16.759  7138  7138 E Zygote  : MountEmulatedStorage()
08-30 16:00:16.759  7138  7138 E Zygote  : v2
08-30 16:00:16.759  7138  7138 I libpersona: KNOX_SDCARD checking this for 10068
08-30 16:00:16.759  7138  7138 I libpersona: KNOX_SDCARD not a persona
08-30 16:00:16.759  7138  7138 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 16:00:16.759  1020  1494 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7138 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-30 16:00:16.769  7138  7138 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 16:00:16.769  7138  7138 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-30 16:00:16.779  6978  7135 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 26.444011
08-30 16:00:16.779  1472  1652 D TP/MmsSmsProvider: update, matched:300, calling pid = 6978
08-30 16:00:16.779  1472  1652 V TP/MmsSmsProvider: syncDBData start
08-30 16:00:16.779  1472  1652 V TP/MmsSmsProvider: syncDBData sms end
08-30 16:00:16.779  1472  1652 V TP/MmsSmsProvider: syncDBData mms end
08-30 16:00:16.779  1472  1652 V TP/MmsSmsProvider: syncDBData end
08-30 16:00:16.779  6978  7136 D Mms/Synchronizer: [end]    doSync consume time = 4.580781
08-30 16:00:16.789  7138  7138 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 16:00:16.789  7138  7138 D ActivityThread: Added TimaKeyStore provider
08-30 16:00:16.789   304   304 I art     : Explicit concurrent mark sweep GC freed 8692(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 26.368ms
08-30 16:00:16.809   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 17.789ms
08-30 16:00:16.809  7138  7138 D BadgeProvider: onCreate
08-30 16:00:16.809  7138  7138 D BadgeProvider: DatabaseHelper
08-30 16:00:16.819  6978  7134 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
08-30 16:00:16.829   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 641us total 16.556ms
08-30 16:00:16.829  1472  1489 D TP/SmsProvider: query,matched:26, calling pid = 6978
08-30 16:00:16.829  1020  1045 W ActivityManager: Activity pause timeout for ActivityRecord{37083f02 u0 com.test.thalitest/.MainActivity t163}
08-30 16:00:16.839  1472  1489 D TP/SmsProvider: match 26:Elapsed time : 6.336 ms
08-30 16:00:16.839  1020  1139 I ActivityManager: Killing 6660:com.qualcomm.timeservice/1000 (adj 15): empty #21
08-30 16:00:16.849  1472  1996 D TP/MmsSmsProvider: query,matched:6, calling pid = 6978
08-30 16:00:16.849  1472  1996 D TP/MmsSmsProvider: match 6:Elapsed time : 1.564 ms
08-30 16:00:16.859  6978  6978 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
08-30 16:00:16.859  1020  4405 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-30 16:00:16.859  1020  4405 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
08-30 16:00:16.859  1020  4405 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:16.859  1020  4405 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:16.859  1020  4405 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
08-30 16:00:16.859  1020  1492 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
08-30 16:00:16.869  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:16.869  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:16.869  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:16.869  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:16.869  7084  7084 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {23caa68e}
08-30 16:00:16.879  7154  7154 E Zygote  : MountEmulatedStorage()
08-30 16:00:16.879  7154  7154 E Zygote  : v2
08-30 16:00:16.879  7154  7154 I libpersona: KNOX_SDCARD checking this for 10042
08-30 16:00:16.879  7154  7154 I libpersona: KNOX_SDCARD not a persona
08-30 16:00:16.879  7154  7154 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 16:00:16.889  1020  1492 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7154 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
08-30 16:00:16.889  1020  1139 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
08-30 16:00:16.889  7154  7154 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 16:00:16.889  7084  7084 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-30 16:00:16.889  1020  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:16.889  1020  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:16.889  1020  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:16.889  1020  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:16.889  7154  7154 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
08-30 16:00:16.899  7084  7084 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 16:00:16.919  7167  7167 E Zygote  : MountEmulatedStorage()
08-30 16:00:16.919  7167  7167 E Zygote  : v2
08-30 16:00:16.919  7167  7167 I libpersona: KNOX_SDCARD checking this for 10023
08-30 16:00:16.919  7167  7167 I libpersona: KNOX_SDCARD not a persona
08-30 16:00:16.919  7167  7167 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 16:00:16.919  7167  7167 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 16:00:16.919  7167  7167 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 16:00:16.919  1020  1139 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7167 uid=10023 gids={50023, 9997} abi=armeabi-v7a
08-30 16:00:16.919  1020  1494 I ActivityManager: Killing 6610:com.android.providers.calendar/u0a37 (adj 15): empty #21
08-30 16:00:16.939  7154  7154 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 16:00:16.939  7154  7154 D ActivityThread: Added TimaKeyStore provider
08-30 16:00:16.949  6978  7184 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
08-30 16:00:16.949  6978  7184 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
08-30 16:00:16.949  1020  1359 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
08-30 16:00:16.949  1020  1359 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:16.949  1020  1359 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:16.949  1020  1359 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:16.949  1020  1359 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:16.969  1948  4427 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
08-30 16:00:16.969  7154  7154 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 16:00:16.969  7154  7154 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-30 16:00:16.969  7154  7154 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-30 16:00:16.969  7167  7167 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 16:00:16.969  7167  7167 D ActivityThread: Added TimaKeyStore provider
08-30 16:00:16.979  7188  7188 E Zygote  : MountEmulatedStorage()
08-30 16:00:16.979  7188  7188 I libpersona: KNOX_SDCARD checking this for 1000
08-30 16:00:16.979  7188  7188 E Zygote  : v2
08-30 16:00:16.979  7188  7188 I libpersona: KNOX_SDCARD not a persona
08-30 16:00:16.979  7188  7188 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 16:00:16.979  1020  1359 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7188 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-30 16:00:16.979  7188  7188 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 16:00:16.979  1020  1359 I ActivityManager: Killing 6429:com.android.defcontainer/u0a3 (adj 15): empty #21
08-30 16:00:16.979  7188  7188 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 16:00:16.989  1020  4405 I ActivityManager: Killing 6700:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
08-30 16:00:16.989  1020  4405 I ActivityManager: Killing 6686:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #22
08-30 16:00:17.009  7084  7084 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-30 16:00:17.019  7188  7188 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 16:00:17.019  7188  7188 D ActivityThread: Added TimaKeyStore provider
08-30 16:00:17.019  7084  7084 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 16:00:17.029  7084  7084 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 16:00:17.059  7167  7167 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
08-30 16:00:17.059  7188  7188 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
08-30 16:00:17.059  7188  7188 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
08-30 16:00:17.059  1020  1033 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
08-30 16:00:17.059  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
08-30 16:00:17.059  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:17.059  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:17.059  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
08-30 16:00:17.069  1948  4427 D Icing   : Loaded CLD2 Version V2.0 - 20141016
08-30 16:00:17.079  6978  7134 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
08-30 16:00:17.089  7188  7188 I FilterInstaller: FilterPackageService : ACTION_CHANGED
08-30 16:00:17.099  7167  7167 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
08-30 16:00:17.099  7167  7167 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-30 16:00:17.109  7167  7167 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
08-30 16:00:17.109  7167  7167 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-30 16:00:17.109  7154  7154 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-30 16:00:17.109  7167  7167 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-30 16:00:17.109  7167  7167 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
08-30 16:00:17.109  7167  7167 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
08-30 16:00:17.109  7167  7167 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
08-30 16:00:17.109  7188  7205 E FilterInstaller: installFilters
08-30 16:00:17.109  7167  7167 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
08-30 16:00:17.109  1020  1060 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
08-30 16:00:17.119  1020  1060 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-30 16:00:17.119  7167  7167 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
08-30 16:00:17.119  7167  7167 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
08-30 16:00:17.119  7167  7167 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
08-30 16:00:17.119  1020  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:17.119  1020  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:17.119  1020  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:17.119  1020  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:17.119  7167  7167 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
08-30 16:00:17.119  7188  7205 E FilterInstaller: There is no requred permission
08-30 16:00:17.129  6881  7176 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 16:00:17.129  6881  7176 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-30 16:00:17.129  7206  7206 E Zygote  : MountEmulatedStorage()
08-30 16:00:17.129  7206  7206 E Zygote  : v2
08-30 16:00:17.129  7206  7206 I libpersona: KNOX_SDCARD checking this for 10003
08-30 16:00:17.129  7206  7206 I libpersona: KNOX_SDCARD not a persona
08-30 16:00:17.129  7206  7206 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 16:00:17.139  1020  1060 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7206 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-30 16:00:17.139  1020  1032 I splitIntent: Queue : backgroundsplit_0 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
08-30 16:00:17.139  1020  1032 I ActivityManager: Killing 5132:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
08-30 16:00:17.139  7206  7206 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 16:00:17.139  7206  7206 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 16:00:17.149  1020  1045 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
08-30 16:00:17.149  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:17.149  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:17.149  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:17.149  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:17.149   288   288 E SMD     : DCD OFF
08-30 16:00:17.159  7221  7221 E Zygote  : MountEmulatedStorage()
08-30 16:00:17.159  7221  7221 I libpersona: KNOX_SDCARD checking this for 10130
08-30 16:00:17.159  7221  7221 E Zygote  : v2
08-30 16:00:17.159  7221  7221 I libpersona: KNOX_SDCARD not a persona
08-30 16:00:17.169  7221  7221 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 16:00:17.169  7221  7221 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 16:00:17.169  7221  7221 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
08-30 16:00:17.169  1020  1045 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7221 uid=10130 gids={50130, 9997} abi=armeabi-v7a
08-30 16:00:17.179  7206  7206 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 16:00:17.179  7206  7206 D ActivityThread: Added TimaKeyStore provider
08-30 16:00:17.189  7221  7221 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 16:00:17.189  1020  1492 I ActivityManager: Killing 6732:com.samsung.helphub/1000 (adj 15): empty #21
08-30 16:00:17.189  7221  7221 D ActivityThread: Added TimaKeyStore provider
08-30 16:00:17.199  6881  7176 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
08-30 16:00:17.209  7084  7084 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 16:00:17.209  7084  7084 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 16:00:17.209  7084  7084 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 16:00:17.209  7084  7084 I Adreno-EGL: Local Branch: 
08-30 16:00:17.209  7084  7084 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 16:00:17.209  7084  7084 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 16:00:17.209  7084  7084 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-30 16:00:17.209   284   284 E installd: system dir 0 : /system/app/
08-30 16:00:17.209   284   284 E installd: system dir 1 : /system/priv-app/
08-30 16:00:17.209   284   284 E installd: system dir 2 : /vendor/app/
08-30 16:00:17.209   284   284 E installd: system dir 3 : /oem/app/
08-30 16:00:17.229  1020  1060 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-30 16:00:17.229  1948  4427 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
08-30 16:00:17.239  7221  7221 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 16:00:17.239  7221  7221 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
08-30 16:00:17.249  6776  6819 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
08-30 16:00:17.259  1020  1359 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-30 16:00:17.259  1020  1359 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:17.259  1020  1359 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 16:00:17.259  1020  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-30 16:00:17.269  1020  1492 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
08-30 16:00:17.269  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:17.269  6776  6819 I AcmsKeyStoreHelper: Key Store exist
08-30 16:00:17.269  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:17.269  6776  6819 I AcmsKeyStoreHelper: Hence loading the keystore file
08-30 16:00:17.269  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:17.269  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:17.279  6881  7176 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-30 16:00:17.279  6881  7176 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d66f674: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-30 16:00:17.279  6881  7176 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-30 16:00:17.289  7242  7242 E Zygote  : MountEmulatedStorage()
08-30 16:00:17.289  7242  7242 E Zygote  : v2
08-30 16:00:17.289  7242  7242 I libpersona: KNOX_SDCARD checking this for 10131
08-30 16:00:17.289  7242  7242 I libpersona: KNOX_SDCARD not a persona
08-30 16:00:17.289  7242  7242 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 16:00:17.289  7242  7242 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 16:00:17.289  1020  1492 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7242 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-30 16:00:17.289  7242  7242 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 16:00:17.289  1020  1492 I ActivityManager: Killing 6716:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
08-30 16:00:17.309  7242  7242 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 16:00:17.309  7242  7242 D ActivityThread: Added TimaKeyStore provider
08-30 16:00:17.329  7242  7242 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 16:00:17.329  7242  7242 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 16:00:17.329  7242  7242 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 16:00:17.339  6776  6819 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
08-30 16:00:17.339  6776  6819 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-30 16:00:17.339  6776  6819 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-30 16:00:17.339  6776  6819 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-30 16:00:17.339  6776  6819 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-30 16:00:17.339  6776  6819 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
08-30 16:00:17.339  6776  6819 D AcmsCore: This is NOT a valid MirrorLink app
08-30 16:00:17.339  6776  6819 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-30 16:00:17.339  6776  6819 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-30 16:00:17.339  6776  6819 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-30 16:00:17.339  6776  6819 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
08-30 16:00:17.339  6776  6776 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-30 16:00:17.339  6776  6776 D AcmsService: Enter onDestroy
08-30 16:00:17.339  6776  6776 I AcmsService: cleanUp(): inside service clean up
08-30 16:00:17.339  6776  6776 D AcmsCore: AcmsCore: inside DeInit
08-30 16:00:17.339  6776  6776 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
08-30 16:00:17.339  6776  6776 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
08-30 16:00:17.339  6776  6776 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-30 16:00:17.339  6776  6776 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-30 16:00:17.339  6776  6776 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
08-30 16:00:17.339  6776  6776 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-30 16:00:17.339  6776  6776 D AcmsService: killing acms process
08-30 16:00:17.339  6776  6776 I Process : Sending signal. PID: 6776 SIG: 9
08-30 16:00:17.349  7084  7084 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 16:00:17.369  2546  2556 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
08-30 16:00:17.369  1020  3442 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-30 16:00:17.369  7084  7084 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-30 16:00:17.369  1020  3781 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-30 16:00:17.369  7084  7084 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-30 16:00:17.369  1020  3781 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
08-30 16:00:17.379  1020  3781 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:17.379  1020  3781 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:17.379  1020  3781 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
08-30 16:00:17.379  7084  7084 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-30 16:00:17.379  7084  7084 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-30 16:00:17.389  1020  1139 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-30 16:00:17.389  1020  1139 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
08-30 16:00:17.389  1020  1139 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:17.389  1020  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:17.389  1020  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
08-30 16:00:17.409  1020  1465 I ActivityManager: Killing 6766:com.sec.spp.push/u0a32 (adj 15): empty #21
,08-30 16:00:17.499  1020  3781 I ActivityManager: Process ACMS.Process (pid 6776)(adj 0) has died(57,753)
,08-30 16:00:17.509  7084  7084 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 16:00:17.519  7084  7084 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 16:00:17.529  7084  7084 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-30 16:00:17.529  7084  7084 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-30 16:00:17.539  7084  7084 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-30 16:00:17.549  7084  7084 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 16:00:17.549  7084  7084 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 16:00:17.589  7084  7279 D OpenGLRenderer: Render dirty regions requested: true
,08-30 16:00:17.589  1020  1493 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-30 16:00:17.589  1020  1493 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-30 16:00:17.589  1020  1493 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-30 16:00:17.589  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-30 16:00:17.589  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
,08-30 16:00:17.599  7084  7084 V ActivityThread: updateVisibility : ActivityRecord{1fd52d69 token=android.os.BinderProxy@3f9f3433 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-30 16:00:17.599  7084  7259 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-30 16:00:17.609  7084  7084 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,08-30 16:00:17.609  7084  7084 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-30 16:00:17.619   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-30 16:00:17.629  1020  1507 D InputDispatcher: Focus entered window: 7084
,08-30 16:00:17.629  7084  7084 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-30 16:00:17.629  1020  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 16:00:17.629  1020  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 16:00:17.629  7084  7279 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 16:00:17.639  7084  7279 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-30 16:00:17.639  7084  7279 D OpenGLRenderer: Enabling debug mode 0
,08-30 16:00:17.659  1020  1494 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-30 16:00:17.659  1181  1181 D PanelView: There is/are notification(s) 
,08-30 16:00:17.659  1020  7285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 16:00:17.669  1915  1915 I SamsungIME: getCurrentCandidateView
,08-30 16:00:17.679  1020  1050 I ActivityManager: Displayed Component not be shown by security: +1s345ms (total +1s531ms)
,08-30 16:00:17.679  1020  1050 W ActivityManager: mDVFSHelper.release()
08-30 16:00:17.679  1020  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{37083f02 u0 com.test.thalitest/.MainActivity t163} time:98323
,08-30 16:00:17.679  7084  7084 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-30 16:00:17.679  7084  7084 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3f9f3433 time:98328
,08-30 16:00:17.689   258  1115 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-30 16:00:17.689   258   448 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-30 16:00:17.839  1915  1915 D SamsungIME: Dismiss ExpandCandiate
,08-30 16:00:17.839  7084  7084 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7084
,08-30 16:00:17.989  1915  1915 I SamsungIME: getDebugLevel  : 0x4f4c
,08-30 16:00:18.019  7084  7084 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 16:00:18.049  1915  1915 I SamsungIME: getDebugLevel  : 0x4f4c
,08-30 16:00:18.059  1915  1915 I SamsungIME: KeybaordView init() : load resources
,08-30 16:00:18.089  1915  1915 I SamsungIME: getCurrentKeyboard
,08-30 16:00:18.089  1915  1915 I SamsungIME: getTextKeyboard
,08-30 16:00:18.109  1915  1915 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-30 16:00:18.109  7084  7287 D jxcore_app_log: JniHelper::setJavaVM(0xb81f32b0), pthread_self() = -1200092512
,08-30 16:00:18.119  7084  7287 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 16:00:18.119  7084  7287 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 16:00:18.119  7084  7287 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 16:00:18.119  7084  7287 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 16:00:18.119  7084  7287 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 16:00:18.119  7084  7287 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11ea75b4 added. We now have 1 listener(s)
,08-30 16:00:18.129  7084  7287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,08-30 16:00:18.129  7084  7287 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-30 16:00:18.129  7084  7287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 16:00:18.129  7084  7287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 16:00:18.129  7084  7287 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 16:00:18.129  7084  7287 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 16:00:18.129  7084  7287 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 16:00:18.129  7084  7287 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-30 16:00:18.129  7084  7287 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 16:00:18.129  7084  7287 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 16:00:18.129  7084  7287 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 16:00:18.129  7084  7287 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 16:00:18.129  7084  7287 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 16:00:18.129  7084  7287 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 16:00:18.129  7084  7287 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 16:00:18.129  7084  7287 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 16:00:18.129  7084  7287 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 16:00:18.129  7084  7287 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 16:00:18.129  7084  7287 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@391d9023 added. We now have 1 listener(s)
,08-30 16:00:18.129  7084  7287 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:00:18.139  7084  7287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 16:00:18.139  7084  7287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 16:00:18.139  7084  7287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 16:00:18.139  7084  7287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 16:00:18.139  7084  7287 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 16:00:18.139  7084  7287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:00:18.149  7084  7287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
08-30 16:00:18.149  7084  7287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-30 16:00:18.149  7084  7287 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:00:18.149  7084  7287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:18.149  7084  7287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:18.149  7084  7287 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:18.149  7084  7287 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:18.149  7084  7287 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:00:18.149  7084  7287 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:00:18.149  7084  7287 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:00:18.149  7084  7287 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 16:00:18.149  7084  7287 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:00:18.159  7084  7287 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 16:00:18.159  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:00:18.159  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:18.199  7084  7084 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 16:00:18.719  7084  7295 W jxcore-log: Initializing JXcore engine,
08-30 16:00:18.719  7084  7295 W jxcore-log: JXcore engine is ready
08-30 16:00:18.729  6978  6978 I Mms/MmsApp:  start initViewCache mms
08-30 16:00:18.729  6978  6978 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1945.865937
08-30 16:00:18.729  6978  6978 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-30 16:00:18.789  2057  2057 E audit   : type=1400 msg=audit(1472565618.789:205): avc:  denied  { ioctl } for  pid=7295 comm="Thread-1341" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 16:00:18.789  2057  2057 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-30 16:00:18.789  2057  2057 E audit   : type=1300 msg=audit(1472565618.789:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9f59f8f8 items=0 ppid=304 ppcomm=main pid=7295 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1341" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-30 16:00:18.789  2057  2057 E audit   : type=1320 msg=audit(1472565618.789:205): 
,08-30 16:00:18.799  7084  7295 W jxcore-log: Starting JXcore engine
,08-30 16:00:18.839  6978  6978 D AbsListView: Get MotionRecognitionManager
,08-30 16:00:18.839  1020  1032 D MotionRecognitionService:  ssp status : false,
,08-30 16:00:18.839  6978  6978 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 116.602656
,08-30 16:00:18.919  7084  7295 W jxcore-log: Platform android
08-30 16:00:18.919  7084  7295 W jxcore-log: 
08-30 16:00:18.919  7084  7295 W jxcore-log: Process ARCH arm
08-30 16:00:18.919  7084  7295 W jxcore-log: 
,08-30 16:00:18.929  6978  6978 D Mms/BubbleViewCache: fillCache bubble = 1
,08-30 16:00:19.129  7084  7295 I jxcore-log: JXcore Cordova bridge is ready!,
08-30 16:00:19.129  7084  7295 I jxcore-log: 
08-30 16:00:19.129  7084  7295 W jxcore-log: JXcore engine is started
,08-30 16:00:19.129  7084  7287 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 16:00:19.139  7084  7084 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 16:00:20.149   288   288 E SMD     : DCD OFF
,08-30 16:00:20.189  1948  6836 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 16:00:20.189  1948  6836 I qtaguid : Tagging socket 96 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1948, getuid(): 10011
,08-30 16:00:20.219  1948  6836 I qtaguid : Tagging socket 104 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1948, getuid(): 10011
,08-30 16:00:20.379  1948  6836 I qtaguid : Untagging socket 96
,08-30 16:00:20.379  1948  1948 I ConfigFetchService: fetch service done; releasing wakelock
,08-30 16:00:20.379  1948  1948 I ConfigFetchService: stopping self
,08-30 16:00:20.389  1020  1493 I ActivityManager: Killing 6753:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-30 16:00:20.749  1020  1045 W ProcessCpuTracker: Skipping unknown process pid 7297,
08-30 16:00:20.749  1020  1045 W ProcessCpuTracker: Skipping unknown process pid 7298
,08-30 16:00:20.769  1020  3422 D SSRM:n  : SIOP:: AP = 410
,08-30 16:00:22.369  1020  3442 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 16:00:23.159   288   288 E SMD     : DCD OFF,
,08-30 16:00:25.319  1020  1465 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 16:00:25.319  1020  1465 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4236, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-30 16:00:25.329  1020  1465 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-30 16:00:25.329  1020  1465 D BatteryService: stay LED for charging
,08-30 16:00:25.329  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 16:00:25.329  1020  1020 I MotionRecognitionService: Plugged
,08-30 16:00:25.329  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 16:00:25.329  1181  1181 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-30 16:00:25.329  1181  1181 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 16:00:25.339  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-30 16:00:25.339  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,08-30 16:00:25.349  3280  3280 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 16:00:25.349  3280  3421 D HeadsetStateMachine: Disconnected process message: 10
,08-30 16:00:25.359  1181  1181 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-30 16:00:25.359  1181  1181 D SViewCoverView: level :99 plugged : 2
,08-30 16:00:25.359  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,08-30 16:00:25.369  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,08-30 16:00:25.369  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,08-30 16:00:25.389  1684  1684 I ConfigService: onDestroy
,08-30 16:00:26.159   288   288 E SMD     : DCD OFF
08-30 16:00:26.159  1020  1060 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-30 16:00:27.189  1020  1311 E Watchdog: !@Sync 3
,08-30 16:00:27.239  1020  1060 D PackageManager: [MSG] MCS_UNBIND
,08-30 16:00:27.239  1020  3784 I ActivityManager: Killing 6820:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,08-30 16:00:28.169   318   318 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-30 16:00:28.169   318   318 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-30 16:00:29.159   288   288 E SMD     : DCD OFF
,08-30 16:00:30.709  1020  1052 I PowerManagerService: [PWL] Off : 50s ago
,08-30 16:00:30.789  1020  3422 D SSRM:n  : SIOP:: AP = 390
,08-30 16:00:30.989  1020  1098 V AlarmManager: waitForAlarm result :4
08-30 16:00:30.989  1020  1098 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,08-30 16:00:31.219  6953  7053 D Finsky  : [1309] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,08-30 16:00:31.219  6953  6953 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-30 16:00:31.309  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 16:00:31.309  7084  7295 I jxcore-log: 
,08-30 16:00:31.309  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 16:00:31.309  7084  7295 I jxcore-log: 
,08-30 16:00:31.319  7084  7295 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:00:31.319  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:31.319  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:31.319  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:31.319  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:31.319  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:00:31.319  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:00:31.319  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:00:31.319  7084  7295 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:00:31.319  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 16:00:31.319  7084  7295 I jxcore-log: 
,08-30 16:00:31.329  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 16:00:31.329  7084  7295 I jxcore-log: 
,08-30 16:00:31.989  7084  7295 D executeNativeTests: Running unit tests
,08-30 16:00:32.079  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:00:32.079  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29567784 added. We now have 2 listener(s)
,08-30 16:00:32.079  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-30 16:00:32.079  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:00:32.079  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 16:00:32.079  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:00:32.079  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d added. We now have 2 listener(s)
08-30 16:00:32.079  7084  7295 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:00:32.079  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 16:00:32.089  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:00:32.089  7084  7295 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:00:32.089  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:32.089  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:32.089  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:32.089  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:32.089  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:00:32.089  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:00:32.089  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:00:32.099  7084  7295 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:00:32.099  7084  7295 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 16:00:32.099  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:32.099  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:32.099  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 16:00:32.109  7084  7295 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 16:00:32.109  7084  7295 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 16:00:32.109  7084  7295 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-30 16:00:32.109  7084  7295 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-30 16:00:32.109  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-30 16:00:32.109  7084  7295 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 16:00:32.109  7084  7295 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 16:00:32.109  7084  7295 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:00:32.109  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:00:32.109  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:32.109  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:32.109  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.109  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:00:32.109  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:00:32.109  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29567784 removed from the list
08-30 16:00:32.109  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:00:32.109  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d removed from the list
08-30 16:00:32.109  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:32.109  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.109  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:00:32.109  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:32.109  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:32.109  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:32.109  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.109  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
,08-30 16:00:32.109  7084  7295 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-30 16:00:32.119  7084  7295 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:32.119  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:32.119  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:32.119  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:00:32.119  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.119  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.119  7084  7295 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29567784 not in the list
08-30 16:00:32.119  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:00:32.119  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:32.119  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:00:32.119  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.119  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.119  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.119  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-30 16:00:32.119  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:32.119  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.119  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
,08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 16:00:32.119  7084  7295 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:00:32.119  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:32.119  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:32.119  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:32.119  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.119  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:32.119  7084  7295 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29567784 not in the list
08-30 16:00:32.119  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.119  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
,08-30 16:00:32.119  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:32.119  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.119  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.119  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.119  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.119  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:00:32.119  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:32.119  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.119  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.119  7084  7295 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 16:00:32.129  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:00:32.129  7084  7295 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:00:32.129  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:32.129  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:32.129  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:32.129  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:32.129  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:00:32.129  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:00:32.129  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:00:32.129  7084  7295 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:00:32.129  7084  7295 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:00:32.129  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:00:32.129  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:00:32.129  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 16:00:32.129  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:00:32.129  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 16:00:32.139  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:32.139  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:32.139  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 16:00:32.149  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 16:00:32.149  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 16:00:32.149  7084  7295 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-30 16:00:32.159  7084  7295 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-30 16:00:32.159  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 16:00:32.159  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 16:00:32.159  7084  7295 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 16:00:32.159   288   288 E SMD     : DCD OFF,
,08-30 16:00:32.159  3280  3417 D BtGatt.GattService: registerClient() - UUID=ce81a4d0-e827-4cc0-844a-1f4e02735964
,08-30 16:00:32.209  3280  3358 D BtGatt.GattService: onClientRegistered() - UUID=ce81a4d0-e827-4cc0-844a-1f4e02735964, clientIf=6
,08-30 16:00:32.209  7084  7097 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 16:00:32.209  3280  3290 D BtGatt.GattService: start scan with filters
,08-30 16:00:32.219  3280  3420 D BtGatt.ScanManager: handling starting scan
,08-30 16:00:32.219  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 16:00:32.219  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 16:00:32.219  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 16:00:32.219  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 16:00:32.219  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:00:32.219  3280  3420 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
,08-30 16:00:32.229  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 16:00:32.229  7084  7084 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:00:32.229  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 16:00:32.229  3280  3358 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-30 16:00:32.229  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 16:00:32.229  3280  3420 D BtGatt.ScanManager: allow scan with filters
08-30 16:00:32.229  3280  3420 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-30 16:00:32.239  3280  3420 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-30 16:00:32.239  7084  7295 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 16:00:32.239  3280  3358 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-30 16:00:32.239  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 16:00:32.239  7084  7295 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:32.239  3280  3420 D BtGatt.ScanManager: Starting BLE batch scan
08-30 16:00:32.239  7084  7295 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 16:00:32.249  3280  3420 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 16:00:32.249  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:32.249  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 16:00:32.249  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.249  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:00:32.249  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 16:00:32.249  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 16:00:32.249  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 16:00:32.249  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 16:00:32.249  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 16:00:32.249  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 16:00:32.249  3280  3443 D BtGatt.GattService: stopScan() - queue size =1
,08-30 16:00:32.249  3280  3417 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 16:00:32.249  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:00:32.249  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 16:00:32.249  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 16:00:32.249  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 16:00:32.249  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 16:00:32.259  3280  3358 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-30 16:00:32.259  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 16:00:32.259  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:00:32.259  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 16:00:32.259  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 16:00:32.259  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 16:00:32.269  3280  3358 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-30 16:00:32.269  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 16:00:32.269  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:00:32.269  3280  3420 D BtGatt.ScanManager: filter size is 1
,08-30 16:00:32.269  3280  3420 D BtGatt.ScanManager: delete FilterIndex - 3
,08-30 16:00:32.269  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:32.269  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.269  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:00:32.269  7084  7295 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29567784 not in the list
08-30 16:00:32.269  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.269  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.269  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:32.269  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:32.269  7084  7295 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 16:00:32.269  7084  7084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:00:32.269  7084  7084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:00:32.269  7084  7084 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:00:32.279  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-30 16:00:32.279  3280  3358 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-30 16:00:32.279  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 16:00:32.279  3280  3420 D BtGatt.ScanManager: stopping BLe Batch
,08-30 16:00:32.279  7084  7295 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:00:32.279  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:32.279  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:32.279  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:32.279  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:32.279  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:00:32.279  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:00:32.279  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:00:32.289  3280  3358 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-30 16:00:32.289  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 16:00:32.289  3280  3420 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 16:00:32.289  7084  7295 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:00:32.289  7084  7295 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:00:32.289  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:00:32.289  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:00:32.289  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 16:00:32.289  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:00:32.289  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 16:00:32.289  3280  3358 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-30 16:00:32.289  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 16:00:32.289  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:32.299  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:32.299  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 16:00:32.309  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 16:00:32.309  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 16:00:32.309  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 16:00:32.309  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 16:00:32.309  7084  7295 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 16:00:32.319  3280  3417 D BtGatt.GattService: registerClient() - UUID=fdd5b074-d1a5-44b7-b677-a6ca4db25279
,08-30 16:00:32.359  3280  3358 D BtGatt.GattService: onClientRegistered() - UUID=fdd5b074-d1a5-44b7-b677-a6ca4db25279, clientIf=6
,08-30 16:00:32.359  7084  7097 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 16:00:32.359  3280  3290 D BtGatt.GattService: start scan with filters
,08-30 16:00:32.359  3280  3420 D BtGatt.ScanManager: handling starting scan
,08-30 16:00:32.359  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 16:00:32.359  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 16:00:32.359  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 16:00:32.369  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 16:00:32.369  3280  3358 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-30 16:00:32.369  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 16:00:32.369  3280  3420 D BtGatt.ScanManager: allow scan with filters
,08-30 16:00:32.369  3280  3420 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-30 16:00:32.369  3280  3420 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-30 16:00:32.369  3280  3358 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-30 16:00:32.369  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 16:00:32.379  3280  3420 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 16:00:32.379  3280  3420 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 16:00:32.379  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 16:00:32.379  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 16:00:32.379  7084  7084 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:00:32.379  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 16:00:32.379  3280  3358 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-30 16:00:32.379  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 16:00:32.389  7084  7295 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 16:00:32.389  3280  3358 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-30 16:00:32.389  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 16:00:32.389  7084  7295 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:00:32.399  7084  7295 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 16:00:32.399  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:32.399  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 16:00:32.399  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.399  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:00:32.399  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 16:00:32.399  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 16:00:32.399  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 16:00:32.399  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 16:00:32.399  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 16:00:32.399  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 16:00:32.399  3280  3443 D BtGatt.GattService: stopScan() - queue size =1
,08-30 16:00:32.399  3280  3420 D BtGatt.ScanManager: filter size is 1
,08-30 16:00:32.399  3280  3420 D BtGatt.ScanManager: delete FilterIndex - 4
,08-30 16:00:32.399  3280  3417 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 16:00:32.399  3280  3358 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-30 16:00:32.399  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 16:00:32.399  3280  3420 D BtGatt.ScanManager: stopping BLe Batch
08-30 16:00:32.399  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:00:32.399  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 16:00:32.399  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 16:00:32.399  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 16:00:32.399  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 16:00:32.399  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:00:32.399  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 16:00:32.409  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 16:00:32.409  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 16:00:32.409  3280  3358 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-30 16:00:32.409  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-30 16:00:32.409  3280  3420 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-30 16:00:32.409  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:00:32.409  7084  7084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 16:00:32.409  7084  7084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:00:32.409  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:32.409  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.409  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:00:32.409  7084  7295 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29567784 not in the list
08-30 16:00:32.409  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.409  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.409  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:32.409  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.409  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.409  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:32.409  7084  7084 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:00:32.409  3280  3358 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-30 16:00:32.409  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 16:00:32.409  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:32.409  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:32.409  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.409  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.409  7084  7295 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 16:00:32.419  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-30 16:00:32.419  7084  7295 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:00:32.419  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:32.419  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:32.419  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:32.419  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:32.419  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:00:32.419  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:00:32.419  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:00:32.419  7084  7295 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:00:32.419  7084  7295 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 16:00:32.419  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:00:32.419  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:00:32.419  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 16:00:32.419  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:00:32.419  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 16:00:32.429  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:32.429  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 16:00:32.429  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:32.439  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 16:00:32.439  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 16:00:32.439  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 16:00:32.439  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 16:00:32.439  7084  7295 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 16:00:32.439  3280  3293 D BtGatt.GattService: registerClient() - UUID=78b93296-a754-48e4-8d0e-4d34e603f8ec
,08-30 16:00:32.489  3280  3358 D BtGatt.GattService: onClientRegistered() - UUID=78b93296-a754-48e4-8d0e-4d34e603f8ec, clientIf=6
,08-30 16:00:32.489  7084  7097 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 16:00:32.489  3280  3443 D BtGatt.GattService: start scan with filters
,08-30 16:00:32.489  3280  3420 D BtGatt.ScanManager: handling starting scan
,08-30 16:00:32.489  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 16:00:32.489  3280  3358 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-30 16:00:32.489  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 16:00:32.489  3280  3420 D BtGatt.ScanManager: allow scan with filters
,08-30 16:00:32.489  3280  3420 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-30 16:00:32.489  3280  3420 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-30 16:00:32.489  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 16:00:32.499  3280  3358 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
08-30 16:00:32.499  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 16:00:32.499  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 16:00:32.499  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
08-30 16:00:32.499  3280  3420 D BtGatt.ScanManager: Starting BLE batch scan
08-30 16:00:32.499  3280  3420 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 16:00:32.499  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:00:32.499  7084  7084 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:00:32.499  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 16:00:32.509  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 16:00:32.509  3280  3358 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-30 16:00:32.509  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 16:00:32.509  7084  7295 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 16:00:32.509  7084  7295 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:00:32.519  7084  7295 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 16:00:32.519  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:32.519  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 16:00:32.519  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.519  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:00:32.519  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 16:00:32.519  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 16:00:32.519  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 16:00:32.519  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 16:00:32.519  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 16:00:32.519  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 16:00:32.519  3280  3358 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-30 16:00:32.519  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 16:00:32.519  3280  3293 D BtGatt.GattService: stopScan() - queue size =1
,08-30 16:00:32.519  3280  3420 D BtGatt.ScanManager: filter size is 1
08-30 16:00:32.519  3280  3420 D BtGatt.ScanManager: delete FilterIndex - 5
,08-30 16:00:32.519  3280  3443 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 16:00:32.529  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:00:32.529  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 16:00:32.529  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 16:00:32.529  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 16:00:32.529  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 16:00:32.529  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:00:32.529  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 16:00:32.529  3280  3358 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-30 16:00:32.529  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 16:00:32.529  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 16:00:32.529  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 16:00:32.529  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:00:32.529  3280  3420 D BtGatt.ScanManager: stopping BLe Batch
,08-30 16:00:32.529  7084  7084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 16:00:32.539  7084  7084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 16:00:32.539  7084  7084 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:00:32.539  7084  7295 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:00:32.539  7084  7295 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 16:00:32.539  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:32.539  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 16:00:32.539  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:00:32.539  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:00:32.539  3280  3358 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-30 16:00:32.539  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 16:00:32.539  3280  3420 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 16:00:32.539  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,08-30 16:00:32.539  7084  7295 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29567784 not in the list
08-30 16:00:32.539  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.539  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
,08-30 16:00:32.539  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:32.539  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:32.549  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.549  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:32.549  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:00:32.549  3280  3358 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-30 16:00:32.549  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:32.549  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:00:32.549  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.549  7084  7295 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-30 16:00:32.549  7084  7295 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:32.549  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 16:00:32.549  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:00:32.549  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:32.549  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:32.549  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.549  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.549  7084  7295 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29567784 not in the list
,08-30 16:00:32.549  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.549  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.549  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:32.549  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:00:32.549  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.549  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.549  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:32.549  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:32.549  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 16:00:32.549  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.549  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.549  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-30 16:00:32.549  7084  7295 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:32.549  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:00:32.549  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:32.549  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:00:32.549  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.549  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:32.549  7084  7295 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29567784 not in the list
,08-30 16:00:32.549  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.549  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list,
08-30 16:00:32.549  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:32.549  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:00:32.549  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.549  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:00:32.549  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.559  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:32.559  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:32.559  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:00:32.559  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.559  7084  7295 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 16:00:32.559  7084  7295 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:32.559  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:32.559  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 16:00:32.559  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:32.559  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.559  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.559  7084  7295 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29567784 not in the list
08-30 16:00:32.559  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:00:32.559  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.559  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:32.559  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:00:32.559  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-30 16:00:32.559  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.559  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-30 16:00:32.559  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:32.559  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:32.559  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:00:32.559  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list,
08-30 16:00:32.559  7084  7295 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 16:00:32.559  7084  7295 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:32.559  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:00:32.559  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 16:00:32.559  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:32.559  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:00:32.559  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.559  7084  7295 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29567784 not in the list
08-30 16:00:32.559  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:00:32.559  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.559  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:32.559  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.559  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:32.559  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.559  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.559  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:32.559  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:32.559  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:00:32.559  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.559  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 16:00:32.559  7084  7295 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 16:00:32.559  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 16:00:32.559  7084  7295 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 16:00:32.559  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 16:00:32.559  7084  7295 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 16:00:32.559  7084  7295 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:32.559  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:32.559  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:32.559  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:00:32.559  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.559  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.559  7084  7295 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29567784 not in the list
08-30 16:00:32.559  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.559  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.559  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 16:00:32.559  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.559  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.559  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.559  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.569  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:00:32.569  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:32.569  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.569  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.569  7084  7295 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:00:32.569  7084  7295 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 16:00:32.569  7084  7295 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:00:32.569  7084  7295 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 16:00:32.569  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 16:00:32.569  7084  7295 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 16:00:32.569  7084  7295 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 16:00:32.569  7084  7295 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 16:00:32.569  7084  7295 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:00:32.569  7084  7295 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 16:00:32.569  7084  7295 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 16:00:32.569  7084  7295 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:00:32.569  7084  7295 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 16:00:32.569  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 16:00:32.579  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-30 16:00:32.579  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 16:00:32.579  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 16:00:32.579  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 16:00:32.579  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 16:00:32.579  7084  7295 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 16:00:32.579  7084  7295 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:00:32.579  7084  7295 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 16:00:32.579  7084  7295 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:32.579  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:32.579  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:32.579  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:32.579  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.579  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.579  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 16:00:32.579  7084  7306 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1405)
08-30 16:00:32.579  7084  7295 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29567784 not in the list
08-30 16:00:32.579  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.579  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.579  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:32.579  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.579  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.579  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.579  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.579  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:32.579  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:32.579  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.579  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.579  7084  7307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1405
08-30 16:00:32.589  7084  7295 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 16:00:32.589  7084  7295 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:32.589  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:32.589  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:32.589  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:32.589  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.589  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.589  7084  7295 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29567784 not in the list
08-30 16:00:32.589  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.589  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.589  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:32.589  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.589  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.589  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.589  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.589  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:32.589  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:32.589  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.589  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.589  7084  7295 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 16:00:32.589  7084  7295 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:32.589  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:32.589  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:32.589  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:32.589  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.589  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.589  7084  7295 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29567784 not in the list
08-30 16:00:32.589  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.589  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.589  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:32.589  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.589  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.589  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.589  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.589  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:32.589  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:32.589  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.589  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.589  7084  7295 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 16:00:32.589  7084  7295 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 16:00:32.589  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 16:00:32.589  7084  7295 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 16:00:32.589  7084  7295 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 16:00:32.589  7084  7295 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 16:00:32.589  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 16:00:32.589  7084  7295 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 16:00:32.589  7084  7295 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 16:00:32.589  7084  7295 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 16:00:32.589  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 16:00:32.589  7084  7295 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 16:00:32.589  7084  7295 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:32.589  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:32.589  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:32.589  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:32.589  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.589  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.589  7084  7295 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29567784 not in the list
08-30 16:00:32.589  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.589  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.589  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:32.589  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.589  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.589  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.589  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.589  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:32.589  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:32.589  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.589  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.589  7084  7306 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-30 16:00:32.589  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:32.589  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.589  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.589  7084  7295 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29567784 not in the list
08-30 16:00:32.589  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.589  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.589  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:32.589  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.589  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.589  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.589  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.589  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:32.589  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.589  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.589  7084  7295 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29567784 not in the list
08-30 16:00:32.589  7084  7295 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:32.589  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:32.589  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:32.589  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:32.589  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.589  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.589  7084  7295 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29567784 not in the list
08-30 16:00:32.589  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.599  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.599  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:32.599  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.599  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.599  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.599  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.599  7084  7306 D BluetoothSocket: connect(): myUserId = 0
08-30 16:00:32.599  7084  7306 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:00:32.599  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:32.599  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:32.599  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.599  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.599  7084  7295 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 16:00:32.599  3280  3443 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:00:32.599  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:00:32.599  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 16:00:32.599  7084  7295 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 16:00:32.599  7084  7295 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 16:00:32.599  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 16:00:32.599  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 16:00:32.599  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:32.599  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 16:00:32.599  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 16:00:32.599  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 16:00:32.599  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.599  7084  7295 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 16:00:32.599  7084  7295 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29567784 not in the list
08-30 16:00:32.599  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.599  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 16:00:32.599  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 16:00:32.599  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 16:00:32.599  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.599  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.599  7084  7084 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 16:00:32.599  7084  7084 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 16:00:32.599  7084  7306 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
08-30 16:00:32.599  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:00:32.599  7084  7308 D BluetoothSocket: bindListen(): myUserId = 0
08-30 16:00:32.599  7084  7308 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:00:32.599  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.599  7084  7295 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:32.599  7084  7084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:00:32.599  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:32.599  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:32.599  7084  7084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:00:32.599  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:32.599  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.599  7084  7084 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:00:32.599  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.599  7084  7295 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29567784 not in the list
08-30 16:00:32.599  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.609  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.609  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:32.609  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.609  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.609  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.609  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.609  7084  7308 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[107]}
08-30 16:00:32.609  7084  7308 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 16:00:32.609  7084  7308 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 16:00:32.609  7084  7308 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@eab7687
08-30 16:00:32.609  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:32.609  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:32.609  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.609  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.609  7084  7308 D BluetoothSocket: channel: 6
08-30 16:00:32.609  7084  7308 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3088c9b4, channel: 6, state: LISTENING
08-30 16:00:32.609  7084  7308 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3088c9b4, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@eab7687, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@ceae9ddmSocket: android.net.LocalSocket@11351952 impl:android.net.LocalSocketImpl@28bef423 fd:FileDescriptor[107]
08-30 16:00:32.609  7084  7308 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@11351952 impl:android.net.LocalSocketImpl@28bef423 fd:FileDescriptor[107]
08-30 16:00:32.609  7084  7308 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 16:00:32.609  7084  7295 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 16:00:32.609  7084  7308 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 16:00:32.609  7084  7308 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 16:00:32.609  7084  7295 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 16:00:32.609  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 16:00:32.609  7084  7295 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 16:00:32.609  7084  7295 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:32.609  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:32.609  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:32.609  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:32.609  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.609  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.609  7084  7295 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29567784 not in the list
,08-30 16:00:32.609  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.609  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.609  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:32.609  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.609  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.609  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.609  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.609  7084  7084 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 16:00:32.609  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:32.609  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:32.609  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.609  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.609  7084  7295 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:32.609  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:32.609  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:32.609  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:32.609  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.609  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.609  7084  7295 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29567784 not in the list
08-30 16:00:32.609  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.609  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.609  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:32.609  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.609  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.609  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.609  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.619  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:32.619  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:32.619  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.619  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.619  7084  7295 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:32.619  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:32.619  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:32.619  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:32.619  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.619  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.619  7084  7295 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29567784 not in the list
08-30 16:00:32.619  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.619  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.619  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:32.619  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.619  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.619  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:32.619  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:32.619  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:32.619  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:32.619  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:32.619  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26534b6d not in the list
08-30 16:00:32.619  7084  7295 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 16:00:32.619  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 16:00:32.619  7084  7295 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 16:00:32.619  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 16:00:32.619  7084  7295 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 16:00:32.619  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 16:00:32.619  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 16:00:32.619  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 16:00:32.619  7084  7295 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 16:00:32.619  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 16:00:32.619  7084  7295 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 16:00:32.619  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 16:00:32.619  7084  7295 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 16:00:32.619  7084  7295 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 16:00:32.619  7084  7295 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 16:00:32.619  7084  7295 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 16:00:32.619  7084  7295 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 16:00:32.619  7084  7295 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 16:00:32.619  7084  7295 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 16:00:32.619  7084  7295 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 16:00:32.619  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:00:32.619  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3dc2cd20 added. We now have 2 listener(s)
08-30 16:00:32.619  7084  7295 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:00:32.619  7084  7295 D BluetoothAdapter: enable()
08-30 16:00:32.629  7084  7295 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 16:00:32.629  1020  1494 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-30 16:00:32.629  1020  1494 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 16:00:32.629  1020  1494 D SecContentProvider2: mCursor = null
08-30 16:00:32.629  1020  1494 D WifiService: setWifiEnabled: true pid=7084, uid=10170
08-30 16:00:32.629  1020  1494 W ActivityManager: Permission Denial: getCurrentUser() from pid=7084, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-30 16:00:32.629  1020  1494 W WifiService: Failed getting userId using ActivityManagerNative
08-30 16:00:32.629  1020  1494 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7084, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-30 16:00:32.629  1020  1494 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-30 16:00:32.629  1020  1494 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-30 16:00:32.629  1020  1494 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-30 16:00:32.629  1020  1494 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-30 16:00:32.629  1020  1494 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-30 16:00:32.629  1020  1494 D SettingsProvider: name = wifi_on
08-30 16:00:32.639  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:00:32.639  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2d3146d9 added. We now have 3 listener(s)
08-30 16:00:32.639  7084  7295 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:00:32.639  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:00:32.639  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2667789e added. We now have 4 listener(s)
08-30 16:00:32.639  7084  7295 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:00:32.639  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:00:32.639  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@902af7f added. We now have 5 listener(s)
08-30 16:00:32.639  7084  7295 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:00:32.639  1020  1359 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-30 16:00:32.639  1020  1359 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 16:00:32.639  1020  1359 D SecContentProvider2: mCursor = null
08-30 16:00:32.649  1020  1359 D WifiService: setWifiEnabled: false pid=7084, uid=10170
08-30 16:00:32.649  1020  1359 D SettingsProvider: name = wifi_on
08-30 16:00:32.649  7084  7295 D BluetoothAdapter: disable()
,08-30 16:00:32.649  1020  1139 D SettingsProvider: name = bluetooth_on,
08-30 16:00:32.649  1020  1129 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 16:00:32.649  1383  1383 I wpa_supplicant: reset timer : RESET_TIMER 0
08-30 16:00:32.649  1383  1383 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-30 16:00:32.659  1383  1383 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-30 16:00:32.659  1383  1383 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-30 16:00:32.659  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:00:32.659  3280  3354 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-30 16:00:32.659  3280  3354 D BluetoothAdapterProperties: Setting state to 13
08-30 16:00:32.659  3280  3354 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 16:00:32.659  3280  3354 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 16:00:32.659  3280  3354 D BluetoothAdapterService: updateAdapterState state is 13
08-30 16:00:32.659  1020  3781 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 16:00:32.659  1020  3781 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 16:00:32.659  1020  3781 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:32.659  1020  3781 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-30 16:00:32.659  1020  3781 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:32.669  1383  1383 I wpa_supplicant: Scan aborted because the firmware maybe busy.
,08-30 16:00:32.669  1383  1383 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
08-30 16:00:32.669  1383  1383 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
08-30 16:00:32.669  3280  3280 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-30 16:00:32.669  3280  3280 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2019449, channel: 19, state: LISTENING
08-30 16:00:32.669  3280  3280 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2019449, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@171dc976, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@f50914emSocket: android.net.LocalSocket@1e7d26f impl:android.net.LocalSocketImpl@22ac9b7c fd:FileDescriptor[82]
08-30 16:00:32.669  3280  3280 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1e7d26f impl:android.net.LocalSocketImpl@22ac9b7c fd:FileDescriptor[82]
,08-30 16:00:32.669  1020  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:00:32.669  4748  4748 D BluetoothPbap: Proxy object disconnected
,08-30 16:00:32.669  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 16:00:32.669  4748  4748 D PbapServerProfile: Bluetooth service disconnected
08-30 16:00:32.669  1020  1020 I InputMethodManagerService: [BT Setting State] State =13
,08-30 16:00:32.669  3280  3354 D BluetoothAdapterService: Autoconnection is available 
08-30 16:00:32.669  3280  3354 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-30 16:00:32.669  3280  3354 D BluetoothAdapterService: terminating service from this receiver
08-30 16:00:32.679  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:00:32.679  7084  7295 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:00:32.679  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:32.679  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:32.679  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:32.679  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:00:32.679  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:00:32.679  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:00:32.679  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:00:32.679  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:00:32.679  7084  7295 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:00:32.679  7084  7295 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 16:00:32.679  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:00:32.679  1181  1181 D BluetoothTile:  onBluetoothStateChange:,
,08-30 16:00:32.689  1181  1181 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 16:00:32.689  1181  1181 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:00:32.689  1181  1181 D BluetoothTile:  getBluetoothState : 13
,08-30 16:00:32.689  1915  1915 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 16:00:32.689  1181  1781 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 16:00:32.689  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:32.689  3280  3280 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3ea8745a, channel: 5, state: LISTENING
,08-30 16:00:32.689  3280  3280 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3ea8745a, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d6d7411, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@18c9268bmSocket: android.net.LocalSocket@31e5f368 impl:android.net.LocalSocketImpl@39828381 fd:FileDescriptor[80]
08-30 16:00:32.689  3280  3280 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@31e5f368 impl:android.net.LocalSocketImpl@39828381 fd:FileDescriptor[80]
,08-30 16:00:32.699  1020  1492 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 16:00:32.699  1020  1139 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-30 16:00:32.699  1020  1129 E WifiNative-wlan0: do suspend true
,08-30 16:00:32.699  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-30 16:00:32.699  4748  4748 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:00:32.699  1181  1781 D BluetoothTile:  handleUpdatestate:false name:null
08-30 16:00:32.699  3280  3280 I BtOppRfcommListener: stopping Accept Thread
,08-30 16:00:32.699  3280  3280 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@37697c26, channel: 12, state: LISTENING
08-30 16:00:32.699  3280  3280 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@37697c26, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@f72a50, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2721a067mSocket: android.net.LocalSocket@1edade14 impl:android.net.LocalSocketImpl@2a52d6bd fd:FileDescriptor[85]
08-30 16:00:32.699  3280  3280 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1edade14 impl:android.net.LocalSocketImpl@2a52d6bd fd:FileDescriptor[85]
,08-30 16:00:32.699  3280  5301 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 16:00:32.699  3280  5301 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-30 16:00:32.699  1020  1220 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-30 16:00:32.709  1181  1781 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-30 16:00:32.709  1020  1220 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:32.709  1020  1220 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 16:00:32.709  1020  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:32.709  7084  7084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:00:32.709  3280  3354 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 16:00:32.709  3280  3354 D BluetoothAdapterProperties: mDiscovering is false
,08-30 16:00:32.709  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:32.709  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:32.709  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:32.709  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:32.709  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:00:32.709  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:00:32.709  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:00:32.709  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:00:32.709  1020  1492 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-30 16:00:32.709  4748  4748 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 16:00:32.709  7084  7084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:00:32.709  7084  7084 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:00:32.709  3280  3354 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-30 16:00:32.709  1020  1493 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-30 16:00:32.709  1020  1493 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 16:00:32.719  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:32.719  1020  1493 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:32.719  1020  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 16:00:32.719  1020  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 16:00:32.729  3280  3358 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-30 16:00:32.729  3280  3358 D BluetoothAdapterProperties: Scan Mode:20
,08-30 16:00:32.729  3280  3354 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-30 16:00:32.729  3280  3354 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-30 16:00:32.729  3280  3354 E bt-btif : cmd socket is not created
08-30 16:00:32.729  3280  3361 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
08-30 16:00:32.729  3280  3354 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 16:00:32.729  7084  7306 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2fe67795, channel: -1, state: INIT
08-30 16:00:32.729  7084  7306 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2fe67795, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2fce80aa, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@339cc49bmSocket: android.net.LocalSocket@28892038 impl:android.net.LocalSocketImpl@2d83f811 fd:FileDescriptor[106]
08-30 16:00:32.729  7084  7306 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@28892038 impl:android.net.LocalSocketImpl@2d83f811 fd:FileDescriptor[106]
08-30 16:00:32.729  7084  7306 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1405)
,08-30 16:00:32.729  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:32.739  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:32.739  1684  1684 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:00:32.739  3280  3280 V BluetoothOppManager: cleanUp...
,08-30 16:00:32.739  4748  4748 D DockEventReceiver: finishStartingService: stopping service
,08-30 16:00:32.739  3280  3361 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
,08-30 16:00:32.739  3280  3361 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
08-30 16:00:32.739  3280  3361 W bt-btif : invalid rfc slot id: 4
,08-30 16:00:32.749  4748  4748 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 16:00:32.749  1181  1181 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:00:32.749  1181  1181 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
08-30 16:00:32.749  3280  3361 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 16:00:32.749  3280  3361 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:00:32.749  3280  3361 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 16:00:32.749  3280  3361 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 16:00:32.749  3280  3361 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:00:32.749  3280  3361 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-30 16:00:32.749  1020  1033 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
08-30 16:00:32.749  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:32.749  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:32.749  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:32.749  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:32.759  1020  1128 D WifiP2pService: InactiveState{ what=143375 }
08-30 16:00:32.759  1020  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 16:00:32.769  7314  7314 E Zygote  : MountEmulatedStorage()
08-30 16:00:32.769  1020  1033 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7314 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-30 16:00:32.769  7314  7314 E Zygote  : v2
08-30 16:00:32.769  7314  7314 I libpersona: KNOX_SDCARD checking this for 10055
08-30 16:00:32.769  7314  7314 I libpersona: KNOX_SDCARD not a persona
,08-30 16:00:32.769  7314  7314 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 16:00:32.779   278   963 D CommandListener: Clearing all IP addresses on wlan0,
08-30 16:00:32.779  7314  7314 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 16:00:32.779  7314  7314 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 16:00:32.779  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 16:00:32.779  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-30 16:00:32.779  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:32.779  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:32.779  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:32.779  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:32.779  1684  2531 V NativeCrypto: Read error: ssl=0xb872a2a8: I/O error during system call, Connection timed out
08-30 16:00:32.779  1684  2531 V NativeCrypto: SSL shutdown failed: ssl=0xb872a2a8: I/O error during system call, Broken pipe
,08-30 16:00:32.789  1020  1131 E ConnectivityService: updateNetworkInfo(),
,08-30 16:00:32.789  1020  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 16:00:32.789  1020  1131 E ConnectivityService: updateNetworkInfo()
08-30 16:00:32.789  1020  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
08-30 16:00:32.789  1020  1129 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 16:00:32.789  1020  1128 D WifiP2pService: InactiveState{ what=131204 }
08-30 16:00:32.789  1020  1128 D WifiP2pService: P2pEnabledState{ what=131204 }
08-30 16:00:32.789  1020  1128 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-30 16:00:32.789  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-30 16:00:32.789  1020  4405 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
08-30 16:00:32.789  1020  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:00:32.789  1020  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:00:32.789  1020  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-30 16:00:32.789  1020  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:00:32.789  1020  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-30 16:00:32.789  1020  1748 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 16:00:32.789  1020  1748 I qtaguid : Tagging socket 349 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1020, getuid(): 1000
,08-30 16:00:32.799  1020  1748 I qtaguid : Untagging socket 349
,08-30 16:00:32.799  1020  1748 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 16:00:32.799  1020  1020 D WifiScanningService: SCAN_AVAILABLE : 1
,08-30 16:00:32.809  1020  1154 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 16:00:32.809  1020  1020 D RttService: SCAN_AVAILABLE : 1
08-30 16:00:32.809  1020  1155 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 16:00:32.809  1020  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:00:32.809  1020  1050 D WifiDisplayAdapter: onP2pDisconnected
,08-30 16:00:32.809  1020  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-30 16:00:32.809  7314  7314 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 16:00:32.809  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-30 16:00:32.809  1020  1020 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-30 16:00:32.819  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
,08-30 16:00:32.819  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 16:00:32.819  1020  1128 D WifiP2pService: P2pDisablingState
08-30 16:00:32.819  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:32.819  1020  1128 D WifiP2pService: P2pDisablingState{ what=147458 }
08-30 16:00:32.819  7314  7314 D ActivityThread: Added TimaKeyStore provider
08-30 16:00:32.819  1020  1128 D WifiP2pService: p2p socket connection lost
08-30 16:00:32.819  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:32.819  1020  1128 D WifiP2pService: P2pDisabledState
08-30 16:00:32.819  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:32.819  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:32.819  1020  1129 E WifiNative-wlan0: do suspend true
,08-30 16:00:32.819  1020  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-30 16:00:32.829  1020  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-30 16:00:32.829  1020  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-30 16:00:32.829  1020  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-30 16:00:32.829  1020  1050 D WifiDisplayController: disconnect
08-30 16:00:32.829  1020  1050 D WifiDisplayController: updateConnection
08-30 16:00:32.829  1020  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-30 16:00:32.829  1020  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 16:00:32.829  1020  1050 D WifiDisplayAdapter: onP2pDisconnected
08-30 16:00:32.829  1020  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-30 16:00:32.829  1020  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
08-30 16:00:32.829  1020  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 16:00:32.829  1181  1181 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-30 16:00:32.839  1020  1032 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-30 16:00:32.839  1181  1181 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-30 16:00:32.849  1020  1128 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-30 16:00:32.849  1020  1128 D WifiP2pService: DefaultState{ what=143375 }
,08-30 16:00:32.849  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-30 16:00:32.859  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 16:00:32.859  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-30 16:00:32.879  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:32.879  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:32.879  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:32.879  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:32.879  7314  7314 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-30 16:00:32.889   278   959 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
08-30 16:00:32.889   278   959 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-30 16:00:32.889   278   963 D CommandListener: Clearing all IP addresses on wlan0
08-30 16:00:32.889  1020  1131 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-30 16:00:32.889  1020  1131 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:32.889  1020  1131 V NetworkStats: updateIfacesLocked()
08-30 16:00:32.889  1020  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 16:00:32.889  1020  1131 V NetworkStats: performPollLocked(flags=0x1)
08-30 16:00:32.889  1020  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-30 16:00:32.889  1020  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-30 16:00:32.889  1020  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 16:00:32.889  1020  1131 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-30 16:00:32.889  1020  1131 V NetworkStats: performPollLocked() took 4ms
08-30 16:00:32.889  1383  1383 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED,
08-30 16:00:32.889  1020  1131 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-30 16:00:32.899  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling,
08-30 16:00:32.899  1020  1049 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-30 16:00:32.899  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:32.899  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:32.909  1020  1131 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 16:00:32.909  1020  1128 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-30 16:00:32.909  1181  1769 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 16:00:32.909  1020  1131 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-30 16:00:32.909  1020  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:00:32.909  1020  1131 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-30 16:00:32.909  1020  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-30 16:00:32.909  1472  1472 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-30 16:00:32.909  1472  1472 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 16:00:32.909  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 16:00:32.909  1020  1129 D SecContentProvider2: mCursor = null
,08-30 16:00:32.919  7314  7314 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-30 16:00:32.919  7314  7314 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() ,
08-30 16:00:32.919  7314  7314 D UserAnalysis: Create SecureDbHelper
08-30 16:00:32.919  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-30 16:00:32.919  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 16:00:32.919  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 16:00:32.919  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:32.919  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:32.919  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:32.919  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:32.919  1020  1129 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-30 16:00:32.929  4748  4748 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 16:00:32.929  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-30 16:00:32.929  1181  1181 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 16:00:32.929  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 16:00:32.929  1181  1781 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-30 16:00:32.929  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 16:00:32.929  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:32.929  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:32.929  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:32.929  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:32.929  1181  1181 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 16:00:32.929  1181  1181 D HotspotTile: onReceive : 0, 0
08-30 16:00:32.929  1181  1181 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-30 16:00:32.929  1020  1131 D ConnectivityService: nai.networkMonitor.doQuit()
08-30 16:00:32.929  1020  1131 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-30 16:00:32.929  1020  1131 E ConnectivityService: updateNetworkInfo()
08-30 16:00:32.929  1020  1131 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 16:00:32.929  1020  1131 E ConnectivityService: updateNetworkInfo()
08-30 16:00:32.929  7314  7314 D IntelligenceServiceApplication: onCreate()
,08-30 16:00:32.929  1020  1020 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-30 16:00:32.929  1020  1134 D Tethering: MasterInitialState.processMessage what=3
08-30 16:00:32.929  1020  1049 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-30 16:00:32.929  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:32.929  1020  1126 V NetworkStats: updateIfacesLocked()
08-30 16:00:32.929  1020  1126 V NetworkStats: performPollLocked(flags=0x1)
08-30 16:00:32.939  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 16:00:32.939  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 16:00:32.939  7084  7084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:00:32.939  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:32.939  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:32.939  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:32.939  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:00:32.939  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:00:32.939  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:32.939  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:32.939  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:00:32.939  7084  7084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:00:32.939  7084  7084 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:00:32.939  3280  3354 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 16:00:32.939  1020  1126 V NetworkStats: performPollLocked() took 5ms
08-30 16:00:32.939  3280  3354 D BtConfig.SecureMode: isSecureModeOn:false
08-30 16:00:32.939  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:32.939  3280  3354 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-30 16:00:32.939  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-30 16:00:32.939  3280  3354 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-30 16:00:32.939  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-30 16:00:32.939  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 16:00:32.939  7084  7084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:00:32.939  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:32.939  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:32.939  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:32.939  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:00:32.939  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:00:32.939  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:32.939  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:32.939  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:00:32.939  7084  7084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:00:32.939  7084  7084 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:00:32.939  1020  3784 I ActivityManager: Killing 6230:com.samsung.android.sm/1000 (adj 15): empty #21
08-30 16:00:32.939  3280  3354 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-30 16:00:32.939  1181  1181 D StatusBar.NetworkController: EthernetConnected: false
08-30 16:00:32.939  1181  1181 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-30 16:00:32.939  1181  1181 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-30 16:00:32.939  1181  1181 D StatusBar.NetworkController: updateDataNetType()
,08-30 16:00:32.939  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:32.939  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:32.939  1020  1127 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-30 16:00:32.939  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:32.939  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:32.939  7314  7314 D IntelligenceServiceApplication: no applications having user consent for prediction
08-30 16:00:32.949  1020  1493 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 16:00:32.949  1020  1493 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-30 16:00:32.949  1020  1493 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:32.949  1020  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:32.949  1020  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 16:00:32.949  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-30 16:00:32.949  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-30 16:00:32.949  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-30 16:00:32.949  1181  1181 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-30 16:00:32.949  3280  3354 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-30 16:00:32.949  3280  3280 D HeadsetService: Received stop request...Stopping profile...
,08-30 16:00:32.949  1181  1181 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-30 16:00:32.949  1181  1181 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 19 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-30 16:00:32.949  1181  1181 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-30 16:00:32.949  1181  1181 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-30 16:00:32.949  1020  1493 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-30 16:00:32.949  1020  1032 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-30 16:00:32.949  7314  7314 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-30 16:00:32.949  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:32.949  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:32.949  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:32.949  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:32.949  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-30 16:00:32.949  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 16:00:32.949  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 16:00:32.959  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:32.959  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:32.959  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:32.959  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:32.959  7314  7314 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.,
,08-30 16:00:32.969  1383  1383 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 16:00:32.969  7336  7336 E Zygote  : MountEmulatedStorage(),
08-30 16:00:32.969  7336  7336 E Zygote  : v2
08-30 16:00:32.969  7336  7336 I libpersona: KNOX_SDCARD checking this for 10105
08-30 16:00:32.969  7336  7336 I libpersona: KNOX_SDCARD not a persona
,08-30 16:00:32.969  1020  1032 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7336 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-30 16:00:32.969  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
,08-30 16:00:32.979  1020  1359 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-30 16:00:32.979  1020  1359 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:32.979  1020  1359 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-30 16:00:32.979  1020  1359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:32.979  1020  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:32.979  1020  1020 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 16:00:32.979  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-30 16:00:32.979  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 16:00:32.979  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:32.979  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:32.979  4748  4748 D HeadsetProfile: Bluetooth service disconnected
08-30 16:00:32.979  3280  3354 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-30 16:00:32.979  7336  7336 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 16:00:32.979  1020  1465 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 16:00:32.979  1020  1465 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 16:00:32.979  1020  1465 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:32.979  1020  1465 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:32.979  1020  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:32.979  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-30 16:00:32.979  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-30 16:00:32.979  3280  3354 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-30 16:00:32.979  1020  1493 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 16:00:32.979  7336  7336 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 16:00:32.979  1020  1493 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-30 16:00:32.989  1020  1493 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:32.989  1020  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:32.989  1020  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 16:00:32.989  7336  7336 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 16:00:32.989  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-30 16:00:32.989  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-30 16:00:32.989  3280  3354 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-30 16:00:32.989  1020  1507 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 16:00:32.989  1020  1507 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:32.989  1020  1507 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-30 16:00:32.989  1020  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:32.989  1020  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 16:00:32.989  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-30 16:00:32.989  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-30 16:00:32.989  3280  3354 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-30 16:00:32.999  1020  1033 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 16:00:32.999  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 16:00:32.999  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:32.999  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:32.999  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 16:00:32.999  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-30 16:00:32.999  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 16:00:32.999  3280  3354 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-30 16:00:32.999  1020  3784 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 16:00:32.999  1020  3784 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 16:00:32.999  1020  3784 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:32.999  1020  3784 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:32.999  1020  3784 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:32.999  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-30 16:00:32.999  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 16:00:32.999  3280  3354 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-30 16:00:32.999  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-30 16:00:32.999  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 16:00:32.999  3280  3354 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-30 16:00:32.999  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-30 16:00:32.999  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 16:00:32.999  3280  3354 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-30 16:00:32.999  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-30 16:00:32.999  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-30 16:00:33.009  3280  3354 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-30 16:00:33.009  3280  3354 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 16:00:33.009  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-30 16:00:33.009  3280  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 16:00:33.009  3280  3280 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-30 16:00:33.009  3280  3280 D A2dpService: Received stop request...Stopping profile...
08-30 16:00:33.009  3280  3424 D A2dpStateMachine: Exit Disconnected: -1
,08-30 16:00:33.009  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
,08-30 16:00:33.009  1020  1020 D BluetoothA2dp: Proxy object disconnected
,08-30 16:00:33.009  1020  1020 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-30 16:00:33.009  4748  4748 D BluetoothA2dp: Proxy object disconnected
08-30 16:00:33.009  4748  4748 D A2dpProfile: Bluetooth service disconnected
,08-30 16:00:33.019  3280  3280 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 16:00:33.019  3280  3280 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-30 16:00:33.019  3280  3280 D HidService: Received stop request...Stopping profile...
08-30 16:00:33.019  3280  3280 D HidService: Stopping Bluetooth HidService
08-30 16:00:33.019  3280  3280 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 16:00:33.019  3280  3280 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-30 16:00:33.019  3280  3280 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 16:00:33.019  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
,08-30 16:00:33.019  4748  4748 D BluetoothInputDevice: Proxy object disconnected
08-30 16:00:33.019  4748  4748 D HidProfile: Bluetooth service disconnected
,08-30 16:00:33.019  3280  3280 D HealthService: Received stop request...Stopping profile...
08-30 16:00:33.019  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
08-30 16:00:33.019  7336  7336 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 16:00:33.019  7336  7336 D ActivityThread: Added TimaKeyStore provider
,08-30 16:00:33.029  1383  1383 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-30 16:00:33.029  3280  3280 D PanService: Received stop request...Stopping profile...
08-30 16:00:33.029  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
08-30 16:00:33.029  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 16:00:33.029  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
08-30 16:00:33.029  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 16:00:33.029  1020  1020 D BluetoothPan: BluetoothPAN Proxy object disconnected,
08-30 16:00:33.029  4748  4748 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 16:00:33.029  4748  4748 D PanProfile: Bluetooth service disconnected
08-30 16:00:33.029  3280  3280 D BluetoothMapService: Received stop request...Stopping profile...
,08-30 16:00:33.039  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
,08-30 16:00:33.039  3280  3280 D SapService: Received stop request...Stopping profile...
08-30 16:00:33.039  3280  3280 D SapService: Stopping Bluetooth SapService
08-30 16:00:33.039  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
,08-30 16:00:33.039  4748  4748 D BluetoothMap: Proxy object disconnected
08-30 16:00:33.039  4748  4748 D MapProfile: Bluetooth service disconnected
,08-30 16:00:33.039  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-30 16:00:33.039  3280  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 16:00:33.049  3280  3280 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-30 16:00:33.049  3280  3426 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 16:00:33.049  3280  3280 I GKI_LINUX: GKI_exit_task 2 done
08-30 16:00:33.049  3280  3280 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-30 16:00:33.049  3280  3280 D BluetoothA2dp: Proxy object disconnected
08-30 16:00:33.049  3280  3280 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-30 16:00:33.049  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-30 16:00:33.049  3280  3280 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-30 16:00:33.049  3280  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 16:00:33.049  3280  3280 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-30 16:00:33.049  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-30 16:00:33.049  3280  3280 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-30 16:00:33.049  3280  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 16:00:33.049  3280  3280 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 16:00:33.049  3280  3280 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 16:00:33.049  3280  3280 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 16:00:33.049  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-30 16:00:33.049  3280  3280 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-30 16:00:33.049  3280  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 16:00:33.049  3280  3280 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 16:00:33.049  3280  3280 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 16:00:33.049  3280  3280 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-30 16:00:33.049  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-30 16:00:33.049  3280  3280 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-30 16:00:33.049  3280  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 16:00:33.049  3280  3280 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-30 16:00:33.049  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true,
08-30 16:00:33.049  3280  3280 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-30 16:00:33.049  3280  3280 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-30 16:00:33.049  3280  3280 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-30 16:00:33.049  4748  4748 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-30 16:00:33.049  4748  4748 D SapProfile: Bluetooth service disconnected
,08-30 16:00:33.049  3280  3354 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-30 16:00:33.049  3280  3354 D BluetoothAdapterProperties: Setting state to 10
08-30 16:00:33.049  3280  3354 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 16:00:33.049  3280  3354 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 16:00:33.049  3280  3354 D BluetoothAdapterService: updateAdapterState state is 10
,08-30 16:00:33.049  1383  1383 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-30 16:00:33.049  1383  1383 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-30 16:00:33.049  1383  1383 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,08-30 16:00:33.049  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 16:00:33.049  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 16:00:33.049  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
08-30 16:00:33.049  1383  1383 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-30 16:00:33.049  1383  1383 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
08-30 16:00:33.059  1020  1134 D Tethering: InitialState.processMessage what=4
,08-30 16:00:33.059  3280  3354 D BluetoothAdapterService: Autoconnection is available 
08-30 16:00:33.059  3280  3354 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-30 16:00:33.059  3280  3354 I BluetoothAdapterState: Entering OffState
,08-30 16:00:33.059  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 16:00:33.059  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
08-30 16:00:33.059  1020  1134 E Tethering: No numeric data
08-30 16:00:33.059  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 16:00:33.059  1020  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 16:00:33.059  1020  1134 D Tethering: clearTetheredNotification()
,08-30 16:00:33.059  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 16:00:33.059  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
08-30 16:00:33.059  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 16:00:33.059  1020  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-30 16:00:33.069  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:33.069  1181  1181 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 16:00:33.069  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 16:00:33.069  1181  1181 D HotspotTile: updateTetherState():false, false
08-30 16:00:33.069  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
08-30 16:00:33.069  7084  7098 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 16:00:33.069  7084  7098 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 16:00:33.069  7084  7098 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-30 16:00:33.069  7084  7098 D BluetoothLeAdvertiser: Exit stop advertising
08-30 16:00:33.069  7084  7098 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-30 16:00:33.069  7084  7098 D BluetoothLeScanner: Exiting stopAllScan
08-30 16:00:33.069  1020  1126 V NetworkStats: performPollLocked() took 5ms
08-30 16:00:33.069  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:33.069  1455  1482 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 16:00:33.069  1455  1482 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 16:00:33.069  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:33.069  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:33.069  1750  1997 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 16:00:33.069  1750  1997 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 16:00:33.079  4748  4762 D BluetoothMap: onBluetoothStateChange: up=false
,08-30 16:00:33.079  3280  3443 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 16:00:33.079  4748  4769 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 16:00:33.089  4748  4762 D BluetoothPbap: onBluetoothStateChange: up=false
,08-30 16:00:33.089  1181  1991 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 16:00:33.089  1181  1991 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 16:00:33.089  1441  7342 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 16:00:33.089  1441  7342 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 16:00:33.089  1684  1699 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 16:00:33.089  1684  1699 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 16:00:33.089  3280  3293 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 16:00:33.089  3280  3293 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 16:00:33.089  4748  4769 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-30 16:00:33.099  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-30 16:00:33.099  1472  1491 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 16:00:33.099  1472  1491 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 16:00:33.099  1020  1049 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 16:00:33.099  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 16:00:33.099  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 16:00:33.099  4748  4762 D Bluetoothsap: onBluetoothStateChange: up=false
08-30 16:00:33.099  4748  4762 D Bluetoothsap: Unbinding service...
08-30 16:00:33.099  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 16:00:33.099  1020  1049 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 16:00:33.109  7084  7084 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,08-30 16:00:33.109  1020  1049 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 16:00:33.109  4748  4769 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 16:00:33.109  4748  4769 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 16:00:33.109  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 16:00:33.109  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 16:00:33.109  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 16:00:33.109  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-30 16:00:33.109  1020  1020 I InputMethodManagerService: [BT Setting State] State =10
08-30 16:00:33.109  1020  1020 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-30 16:00:33.109  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 16:00:33.109  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 16:00:33.109  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 16:00:33.109  1181  1181 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 16:00:33.109  1181  1181 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:00:33.109  1181  1181 D BluetoothTile:  getBluetoothState : 10
,08-30 16:00:33.119  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-30 16:00:33.119  1915  1915 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 16:00:33.119  4748  4748 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:00:33.119  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 16:00:33.119  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 16:00:33.119  1020  1507 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-30 16:00:33.119  7084  7084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:00:33.119  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:33.119  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:33.119  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:33.119  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:00:33.119  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:00:33.119  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:33.119  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:33.119  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:00:33.119  1020  3784 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 16:00:33.129  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 16:00:33.129  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:00:33.129  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 16:00:33.129  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 16:00:33.129  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 16:00:33.129  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 16:00:33.129  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 16:00:33.129  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 16:00:33.129  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 16:00:33.129  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 16:00:33.129  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 16:00:33.129  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 16:00:33.139  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 16:00:33.139  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 16:00:33.139  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 16:00:33.139  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 16:00:33.139  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 16:00:33.139  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 16:00:33.139  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 16:00:33.159   257   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-30 16:00:33.159   257   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 16:00:33.159  7336  7372 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-30 16:00:33.169   257   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-30 16:00:33.169   257   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 16:00:33.169  7336  7372 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-30 16:00:33.179   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 16:00:33.179  1383  1383 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 16:00:33.239  1383  1383 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-30 16:00:33.239  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 16:00:33.239  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-30 16:00:33.239  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 16:00:33.309  7336  7336 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-30 16:00:33.309  7336  7336 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 16:00:33.309  7336  7336 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 16:00:33.309  7336  7336 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.q.e.b(PG:170)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08,-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 16:00:33.309  7336  7336 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.q.k.d(PG:583)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.q.e.b(PG:170)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 16:00:33.309  7336  7336 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 16:00:33.309  7336  7336 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 16:00:33.309  7336  7336 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 16:00:33.309  7336  7336 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 16:00:33.319  1020  1507 I ActivityManager: Killing 6842:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
08-30 16:00:33.319  1020  3784 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 16:00:33.319  1020  3784 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 16:00:33.329  1020  3784 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:33.329  1020  3784 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:33.329  1020  3784 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 16:00:33.329  4748  4748 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 16:00:33.329  1632  1632 I Hs20UtilService: Starting #8
08-30 16:00:33.329  1632  1654 I Hs20UtilService: Message received 5007
08-30 16:00:33.339  1020  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-30 16:00:33.339  1020  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-30 16:00:33.349  4748  4748 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 16:00:33.349  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 16:00:33.349  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 16:00:33.349  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 16:00:33.349  4748  4748 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 16:00:33.349  4748  4840 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-30 16:00:33.349  1750  2213 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:00:33.349  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-30 16:00:33.349  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 16:00:33.359  4748  4748 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-30 16:00:33.359  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 16:00:33.359  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:33.359  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:33.359  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:33.359  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:33.359  1181  1181 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 16:00:33.359  1181  1181 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-30 16:00:33.359  1181  1181 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 16:00:33.359  1181  1181 D HotspotTile: onReceive : 1, 0
08-30 16:00:33.359  1181  1781 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-30 16:00:33.359  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:00:33.359  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:00:33.369  4748  4748 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 16:00:33.369  4748  4748 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 16:00:33.369  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-30 16:00:33.369  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 16:00:33.369  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 16:00:33.369  4748  4748 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 16:00:33.369  4748  4840 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-30 16:00:33.379  1020  3784 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-30 16:00:33.379  1020  3784 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:33.379  1020  3784 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:33.379  1020  3784 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:33.379  1020  3784 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:33.379  7336  7376 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 16:00:33.389  7383  7383 E Zygote  : MountEmulatedStorage()
08-30 16:00:33.389  7383  7383 I libpersona: KNOX_SDCARD checking this for 10064
08-30 16:00:33.389  7383  7383 E Zygote  : v2
08-30 16:00:33.389  7383  7383 I libpersona: KNOX_SDCARD not a persona
,08-30 16:00:33.389  7383  7383 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 16:00:33.389  1020  3784 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7383 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 16:00:33.399  7383  7383 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 16:00:33.399  7383  7383 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 16:00:33.409  1020  1438 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 16:00:33.409  1020  1438 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:33.409  1020  1438 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 16:00:33.409  1020  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-30 16:00:33.419  7383  7383 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 16:00:33.419  7383  7383 D ActivityThread: Added TimaKeyStore provider
,08-30 16:00:33.429  1020  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:00:33.439  1020  1020 I ApplicationPolicy: updateDataUsageMap
,08-30 16:00:33.439  7383  7383 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-30 16:00:33.439  1020  1044 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:00:33.449  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:33.449  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:33.459  7383  7383 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 16:00:33.459  7383  7383 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-30 16:00:33.499  7383  7383 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 16:00:33.499  1020  1359 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-30 16:00:33.499  1020  1359 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:33.499  1020  1359 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:33.499  1020  1359 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:33.499  1020  1359 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:33.509  7400  7400 E Zygote  : MountEmulatedStorage()
08-30 16:00:33.509  7400  7400 I libpersona: KNOX_SDCARD checking this for 10065
08-30 16:00:33.509  7400  7400 E Zygote  : v2
08-30 16:00:33.509  7400  7400 I libpersona: KNOX_SDCARD not a persona
08-30 16:00:33.509  7400  7400 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 16:00:33.509  1020  1359 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7400 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 16:00:33.509  1020  1359 I ActivityManager: Killing 6881:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-30 16:00:33.519  7400  7400 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 16:00:33.519  7400  7400 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 16:00:33.539  7400  7400 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 16:00:33.539  7400  7400 D ActivityThread: Added TimaKeyStore provider
,08-30 16:00:33.559  7400  7400 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 16:00:33.559  1020  4405 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:33.559  1020  4405 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 16:00:33.559  1020  4405 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
08-30 16:00:33.559  1020  4405 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-30 16:00:33.559  1020  4405 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:33.559  1020  4405 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:33.559  1020  4405 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:33.559  1020  4405 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:33.579  7415  7415 E Zygote  : MountEmulatedStorage(),
08-30 16:00:33.579  7415  7415 E Zygote  : v2
08-30 16:00:33.579  7415  7415 I libpersona: KNOX_SDCARD checking this for 10102,
08-30 16:00:33.579  7415  7415 I libpersona: KNOX_SDCARD not a persona
,08-30 16:00:33.579  7415  7415 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-30 16:00:33.579  1020  4405 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7415 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-30 16:00:33.579  1020  4405 I ActivityManager: Killing 6860:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,08-30 16:00:33.579  7415  7415 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 16:00:33.579  7415  7415 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 16:00:33.599  7415  7415 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 16:00:33.599  7415  7415 D ActivityThread: Added TimaKeyStore provider
,08-30 16:00:33.609   304   304 I art     : Explicit concurrent mark sweep GC freed 8686(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 30.340ms
,08-30 16:00:33.619  7415  7415 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 16:00:33.619   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 573us total 16.445ms
,08-30 16:00:33.639   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 580us total 16.560ms
,08-30 16:00:33.829  7415  7435 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-30 16:00:33.829  7415  7435 I Babel_SMS: MmsConfig.loadMmsSettings
08-30 16:00:33.829  7415  7435 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-30 16:00:33.829  7415  7435 I Babel_SMS: MmsConfig.loadFromDatabase
,08-30 16:00:33.839  7415  7435 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-30 16:00:33.839  7415  7435 I Babel_SMS: MmsConfig.loadFromResources
,08-30 16:00:33.849  7415  7435 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-30 16:00:33.849  7415  7435 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-30 16:00:33.869  1020  1493 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-30 16:00:33.869  1020  1493 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-30 16:00:33.869  1020  1493 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:33.869  1020  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 16:00:33.869  1020  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-30 16:00:33.889  7415  7415 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 16:00:33.889  7415  7415 I Babel_Crash: startup - clean
,08-30 16:00:33.919  1020  4405 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 16:00:33.919  1020  4405 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 16:00:33.919  1020  4405 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:33.919  1020  4405 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:33.919  1020  4405 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 16:00:33.929  1632  1632 I Hs20UtilService: Starting #9
,08-30 16:00:33.929  1632  1654 I Hs20UtilService: Message received 5007
,08-30 16:00:33.929  4748  4748 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 16:00:33.929  4748  4748 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 16:00:33.929  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 16:00:33.929  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 16:00:33.929  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-30 16:00:33.929  4748  4748 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 16:00:33.929  4748  4840 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 16:00:33.939  7415  7415 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 16:00:33.939  1020  1359 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 16:00:33.939  1020  1359 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 16:00:33.939  1020  1359 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:33.939  1020  1359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:33.939  7415  7415 W AudioCapabilities: Unsupported mime audio/evrc
,08-30 16:00:33.939  1020  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 16:00:33.949  1632  1632 I Hs20UtilService: Starting #10
,08-30 16:00:33.949  7415  7415 W AudioCapabilities: Unsupported mime audio/qcelp
,08-30 16:00:33.949  1020  1220 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-30 16:00:33.949  1020  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:33.949  1020  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:33.949  1020  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:33.949  1020  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:33.949  1632  1654 I Hs20UtilService: Message received 5011
,08-30 16:00:33.959  7415  7415 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-30 16:00:33.959  7415  7415 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-30 16:00:33.959  7438  7438 E Zygote  : MountEmulatedStorage()
,08-30 16:00:33.959  7438  7438 E Zygote  : v2
08-30 16:00:33.959  7438  7438 I libpersona: KNOX_SDCARD checking this for 1000
08-30 16:00:33.959  7438  7438 I libpersona: KNOX_SDCARD not a persona
,08-30 16:00:33.959  7438  7438 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-30 16:00:33.959  1020  1047 D Tethering: interfaceRemoved wlan0
08-30 16:00:33.959  1020  1047 E Tethering: attempting to remove unknown iface (wlan0), ignoring,
,08-30 16:00:33.959  7438  7438 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 16:00:33.969  7438  7438 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 16:00:33.969  7415  7415 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-30 16:00:33.969  7415  7415 W AudioCapabilities: Unsupported mime audio/x-ima
08-30 16:00:33.969  7415  7415 W AudioCapabilities: Unsupported mime audio/qcelp
,08-30 16:00:33.969  1020  1220 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7438 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-30 16:00:33.969  7415  7415 W AudioCapabilities: Unsupported mime audio/evrc
,08-30 16:00:33.979  7415  7415 W VideoCapabilities: Unsupported mime video/wvc1
,08-30 16:00:33.989  7415  7415 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-30 16:00:33.989  7438  7438 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 16:00:33.989  7438  7438 D ActivityThread: Added TimaKeyStore provider
,08-30 16:00:33.999  7415  7415 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-30 16:00:33.999  7415  7415 W VideoCapabilities: Unsupported mime video/wvc1
,08-30 16:00:33.999  7415  7415 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-30 16:00:34.009  7415  7415 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-30 16:00:34.009  7415  7415 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-30 16:00:34.009  7415  7415 W VideoCapabilities: Unsupported mime video/mp43
,08-30 16:00:34.009  7415  7415 W VideoCapabilities: Unsupported mime video/sorenson
,08-30 16:00:34.019  7415  7415 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-30 16:00:34.019  7438  7438 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 16:00:34.029  7438  7438 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-30 16:00:34.029  7438  7438 D SecurityLogAgent: StateMachine : Current State = 1
,08-30 16:00:34.029  7438  7438 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 16:00:34.029  1020  1139 I ActivityManager: Killing 6906:com.sec.pcw.device/1000 (adj 15): empty #21
,08-30 16:00:34.039  1020  1493 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:34.039  1020  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:34.039  1020  1047 D Tethering: interfaceRemoved p2p0
08-30 16:00:34.039  1020  1047 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-30 16:00:34.039  1020  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 16:00:34.039  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:34.039  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 16:00:34.039  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 16:00:34.049  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:34.049  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 16:00:34.049  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 16:00:34.049  7415  7415 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-30 16:00:34.049  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:34.049  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:34.049  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 16:00:34.059  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:34.059  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 16:00:34.059  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 16:00:34.059  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:34.059  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 16:00:34.059  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 16:00:34.069  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:34.069  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:34.069  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 16:00:34.069  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:34.069  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:34.069  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 16:00:34.069  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:34.069  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:34.069  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 16:00:34.079  7415  7415 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 16:00:34.079  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:34.079  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:34.079  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 16:00:34.079  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:34.079  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:34.079  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 16:00:34.079  7415  7415 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 16:00:34.079  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:34.079  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:34.079  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 16:00:34.079  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:34.079  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:34.079  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 16:00:34.089  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:34.089  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:34.089  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 16:00:34.089  7415  7415 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 16:00:34.089  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:34.089  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:34.089  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 16:00:34.089  7415  7415 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 16:00:34.099  4748  4748 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 16:00:34.099  1020  1220 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-30 16:00:34.099  1020  1220 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 16:00:34.099  1020  1220 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:34.099  1020  1220 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 16:00:34.099  1020  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 16:00:34.099  1020  4405 I ActivityManager: Killing 6802:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-30 16:00:34.099  7415  7415 I vclib   : onServiceConnected
,08-30 16:00:34.109  1684  1684 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:00:34.109  4748  4748 D DockEventReceiver: finishStartingService: stopping service
,08-30 16:00:34.109  4748  4748 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 16:00:34.119  1181  1181 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:00:34.119  1181  1181 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-30 16:00:34.129  1020  1507 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 16:00:34.129  1020  1507 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 16:00:34.129  1020  1507 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:34.129  1020  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:34.129  1020  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 16:00:34.139  1632  1632 I Hs20UtilService: Starting #11
,08-30 16:00:34.139  1632  1654 I Hs20UtilService: Message received 5011
,08-30 16:00:34.139  7438  7438 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-30 16:00:34.139  7438  7438 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 16:00:34.139  7438  7438 D SecurityLogAgent: StateMachine : Current State = 1
08-30 16:00:34.139  7438  7438 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 16:00:34.139  1020  1220 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-30 16:00:34.149  1020  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:34.149  1020  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:34.149  1020  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:34.149  1020  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:34.159  7456  7456 E Zygote  : MountEmulatedStorage()
08-30 16:00:34.159  1020  1220 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7456 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-30 16:00:34.159  7456  7456 E Zygote  : v2
08-30 16:00:34.159  7456  7456 I libpersona: KNOX_SDCARD checking this for 1000
08-30 16:00:34.159  7456  7456 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 16:00:34.159  7456  7456 I libpersona: KNOX_SDCARD not a persona
,08-30 16:00:34.159  7456  7456 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 16:00:34.169  7456  7456 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 16:00:34.179   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 16:00:34.179  7456  7456 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-30 16:00:34.179  7456  7456 D ActivityThread: Added TimaKeyStore provider
,08-30 16:00:34.199  7456  7456 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-30 16:00:34.199  7456  7456 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-30 16:00:34.199  7456  7456 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-30 16:00:34.209  7456  7456 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-30 16:00:34.209  7456  7456 I PCWCLIENTTRACE_PushUtil: sales region : global
08-30 16:00:34.209  7456  7456 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-30 16:00:34.209  7456  7456 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:00:34.219  1020  1220 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
08-30 16:00:34.219  1020  1220 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-30 16:00:34.219  1020  1220 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-30 16:00:34.219  1020  1220 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-30 16:00:34.219  1020  1220 I ActivityManager: Killing 7008:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,08-30 16:00:34.219  7456  7471 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-30 16:00:34.229  1020  1020 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-30 16:00:34.229  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:34.229  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:34.229  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:34.229  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:34.239  7473  7473 E Zygote  : MountEmulatedStorage()
08-30 16:00:34.239  7473  7473 E Zygote  : v2
08-30 16:00:34.239  7473  7473 I libpersona: KNOX_SDCARD checking this for 10001
08-30 16:00:34.239  7473  7473 I libpersona: KNOX_SDCARD not a persona
,08-30 16:00:34.239  7473  7473 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 16:00:34.249  1020  1020 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7473 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 16:00:34.249  7473  7473 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 16:00:34.249  7473  7473 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-30 16:00:34.269  7473  7473 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 16:00:34.269  7473  7473 D ActivityThread: Added TimaKeyStore provider
,08-30 16:00:34.349  1020  1033 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-30 16:00:34.349  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:34.349  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:34.349  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:34.349  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:34.369  7491  7491 E Zygote  : MountEmulatedStorage(),
08-30 16:00:34.369  7491  7491 E Zygote  : v2
08-30 16:00:34.369  7491  7491 I libpersona: KNOX_SDCARD checking this for 1000
08-30 16:00:34.369  7491  7491 I libpersona: KNOX_SDCARD not a persona
,08-30 16:00:34.369  7491  7491 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 16:00:34.369  1020  1033 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7491 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-30 16:00:34.369  1020  1033 I ActivityManager: Killing 7038:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,08-30 16:00:34.379  7491  7491 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 16:00:34.379  7491  7491 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 16:00:34.399  7491  7491 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 16:00:34.399  7491  7491 D ActivityThread: Added TimaKeyStore provider
,08-30 16:00:34.439  7491  7491 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-30 16:00:34.559  7491  7491 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-30 16:00:34.569  7491  7491 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-30 16:00:34.569  7491  7491 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:00:34.569  7491  7491 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-30 16:00:34.569  7491  7491 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-30 16:00:34.569  7491  7491 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-30 16:00:34.569  1020  1438 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-30 16:00:34.569  1020  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:34.569  1020  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:34.569  1020  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:34.569  1020  1438 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:34.589  7506  7506 E Zygote  : MountEmulatedStorage(),
08-30 16:00:34.589  7506  7506 E Zygote  : v2
08-30 16:00:34.589  7506  7506 I libpersona: KNOX_SDCARD checking this for 10008,
08-30 16:00:34.589  7506  7506 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 16:00:34.589  7506  7506 I libpersona: KNOX_SDCARD not a persona
,08-30 16:00:34.589  1020  1438 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7506 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-30 16:00:34.589  7506  7506 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 16:00:34.589  1020  1438 I ActivityManager: Killing 7062:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-30 16:00:34.589  7506  7506 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-30 16:00:34.599  7506  7506 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 16:00:34.599  7506  7506 D ActivityThread: Added TimaKeyStore provider
,08-30 16:00:34.669  1020  1139 I ActivityManager: Killing 7099:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-30 16:00:34.669  1020  1032 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-30 16:00:34.669  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-30 16:00:34.669  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:34.669  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 16:00:34.669  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-30 16:00:34.689  1948  1948 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 16:00:34.689  1948  2803 I iu.UploadsManager: num queued entries: 0
,08-30 16:00:34.689  1948  2803 I iu.UploadsManager: num updated entries: 0
,08-30 16:00:34.689  1948  2803 I iu.SyncManager: NEXT; no task
,08-30 16:00:34.689  1020  1438 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 16:00:34.689  1020  1438 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,08-30 16:00:34.699  1020  1438 W ActivityManager: userId = 0, bbcId = -10000,
08-30 16:00:34.699  1020  1438 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 16:00:34.699  1020  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,08-30 16:00:34.699  1948  1948 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 16:00:34.699  1948  1948 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,08-30 16:00:34.709  1020  1098 V AlarmManager: waitForAlarm result :4
,08-30 16:00:34.709  2808  2808 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 30 16:00:34 GMT+02:00 2016
,08-30 16:00:34.709  1020  1220 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-30 16:00:34.709  1020  1220 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-30 16:00:34.709  1020  1220 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:34.709  1020  1220 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:34.709  1020  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-30 16:00:34.719  2808  2808 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-30 16:00:34.719  1020  3781 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-30 16:00:34.729  1020  3781 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:34.729  1020  3781 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:34.729  1020  3781 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:34.729  1020  3781 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:34.729  2808  2808 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-30 16:00:34.729  2808  2808 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-30 16:00:34.739  1020  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
08-30 16:00:34.739  2808  2808 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-30 16:00:34.739  2808  7522 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-30 16:00:34.739  2808  7522 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-30 16:00:34.739  7523  7523 E Zygote  : MountEmulatedStorage()
08-30 16:00:34.739  7523  7523 I libpersona: KNOX_SDCARD checking this for 10031
08-30 16:00:34.739  7523  7523 E Zygote  : v2
08-30 16:00:34.739  7523  7523 I libpersona: KNOX_SDCARD not a persona
08-30 16:00:34.739  7523  7523 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 16:00:34.739  1020  3781 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7523 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
08-30 16:00:34.749  2808  7522 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-30 16:00:34.749  7523  7523 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 16:00:34.749  7523  7523 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 16:00:34.749  2808  7522 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-30 16:00:34.749  2808  2808 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-30 16:00:34.759  7523  7523 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 16:00:34.769  7523  7523 D ActivityThread: Added TimaKeyStore provider
,08-30 16:00:34.799  7523  7523 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-30 16:00:34.799  1020  1438 I ActivityManager: Killing 7138:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-30 16:00:34.809  1020  3784 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-30 16:00:34.809  1020  3784 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:34.809  1020  3784 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:34.809  1020  3784 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:34.809  1020  3784 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:34.819  2744  7538 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-30 16:00:34.829  7539  7539 E Zygote  : MountEmulatedStorage()
08-30 16:00:34.829  7539  7539 E Zygote  : v2
08-30 16:00:34.829  7539  7539 I libpersona: KNOX_SDCARD checking this for 10032
,08-30 16:00:34.829  7539  7539 I libpersona: KNOX_SDCARD not a persona
,08-30 16:00:34.829  7539  7539 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 16:00:34.829  7539  7539 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 16:00:34.829  2744  7538 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
08-30 16:00:34.829  1020  3784 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7539 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 16:00:34.829  2744  7538 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
08-30 16:00:34.829  2744  7538 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
08-30 16:00:34.829  2744  7538 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-30 16:00:34.839  7539  7539 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,08-30 16:00:34.859  7539  7539 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 16:00:34.859  7539  7539 D ActivityThread: Added TimaKeyStore provider
,08-30 16:00:34.899  7539  7554 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-30 16:00:34.899  7539  7554 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-30 16:00:34.909  7539  7554 D SPPClientService: PushLog.txt file is not deleted.
,08-30 16:00:34.909  7539  7539 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
08-30 16:00:34.909  7539  7554 D SPPClientService: PushLog.txt file is not deleted.
,08-30 16:00:34.909  7539  7554 D SPPClientService: ============PushLog. stop!
,08-30 16:00:34.909  1020  4405 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-30 16:00:34.909  1020  4405 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:34.909  1020  4405 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:34.909  1020  4405 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:34.909  1020  4405 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:34.929  7556  7556 E Zygote  : MountEmulatedStorage()
,08-30 16:00:34.929  7556  7556 E Zygote  : v2
08-30 16:00:34.929  7556  7556 I libpersona: KNOX_SDCARD checking this for 10036
08-30 16:00:34.929  7556  7556 I libpersona: KNOX_SDCARD not a persona
,08-30 16:00:34.929  1020  4405 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7556 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 16:00:34.929  7556  7556 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-30 16:00:34.929  1020  4405 I ActivityManager: Killing 6978:com.android.mms/u0a41 (adj 15): empty #21
08-30 16:00:34.929  1020  3781 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-30 16:00:34.929  1020  3781 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-30 16:00:34.929  1020  3781 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:34.929  1020  3781 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-30 16:00:34.929  1020  3781 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
08-30 16:00:34.929  7556  7556 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 16:00:34.929  7556  7556 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-30 16:00:34.949  7556  7556 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 16:00:34.949  7556  7556 D ActivityThread: Added TimaKeyStore provider
,08-30 16:00:34.959  7539  7564 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-30 16:00:34.999  7556  7556 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@1a3776b6
,08-30 16:00:35.009  7556  7556 I SA      : [SSP] onCreated
,08-30 16:00:35.019  7556  7556 I SA      : [TPM] There is no property file
,08-30 16:00:35.019  7556  7556 I SA      : [SCU] isHaveSA() - false,
,08-30 16:00:35.029  1020  1220 D CountryDetector: No listener is left
,08-30 16:00:35.029  7556  7556 I SA      : [TPM] getModelProperty : null
,08-30 16:00:35.029  7556  7556 I SA      : [TPM] getCSCProperty : null
,08-30 16:00:35.029  7556  7556 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-30 16:00:35.029  7556  7556 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-30 16:00:35.029  7556  7556 I SA      : [DM] TFT FEATURE: false
,08-30 16:00:35.029  7556  7556 I SA      : [DM] init START
,08-30 16:00:35.039  7556  7556 I SA      : [DM] This device is not a Vodafone
,08-30 16:00:35.039  7556  7556 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-30 16:00:35.039  7556  7556 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-30 16:00:35.039  7556  7556 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-30 16:00:35.039  7556  7556 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-30 16:00:35.039  7556  7556 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-30 16:00:35.039  7556  7556 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-30 16:00:35.039  7556  7556 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-30 16:00:35.039  7556  7556 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 16:00:35.049  7556  7556 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-30 16:00:35.049  7556  7556 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-30 16:00:35.049  7556  7556 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-30 16:00:35.049  7556  7556 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-30 16:00:35.049  7556  7556 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-30 16:00:35.049  7556  7556 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-30 16:00:35.049  7556  7556 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-30 16:00:35.049  7556  7556 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-30 16:00:35.049  7556  7556 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,08-30 16:00:35.049  7556  7556 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-30 16:00:35.049  7556  7556 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-30 16:00:35.049  7556  7556 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-30 16:00:35.049  7556  7556 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-30 16:00:35.049  7556  7556 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-30 16:00:35.049  7556  7556 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-30 16:00:35.049  7556  7556 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-30 16:00:35.049  7556  7556 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-30 16:00:35.049  7556  7556 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-30 16:00:35.049  7556  7556 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,08-30 16:00:35.049  7556  7556 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-30 16:00:35.059  7556  7556 I SA      : [SCU] isHaveSA() - false
08-30 16:00:35.059  7556  7556 I SA      : support phone number id : false
08-30 16:00:35.059  7556  7556 I SA      : [DM] Supports Ref Jpn : true
,08-30 16:00:35.059  7556  7556 I SA      : [DM] init END
,08-30 16:00:35.059  7556  7556 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-30 16:00:35.059  7556  7556 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-30 16:00:35.059  7556  7556 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-30 16:00:35.069  7556  7556 I SA      : [SLFUCHKMGR] constructor called
,08-30 16:00:35.079  7556  7556 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-30 16:00:35.079  7556  7556 I SA      : [OR] == isSIMCardReady false ==
,08-30 16:00:35.079  7556  7556 I SA      : [SCU] == networkStateCheck == false
,08-30 16:00:35.079  7556  7556 I SA      : [OR] onReceive END
,08-30 16:00:35.079  1020  1507 I ActivityManager: Killing 7154:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,08-30 16:00:35.089  1233  1233 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:00:35.089  1799  1799 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-30 16:00:35.099  2546  2556 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,08-30 16:00:35.099  1799  1799 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-30 16:00:35.099  1799  1799 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,08-30 16:00:35.099  1799  1799 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-30 16:00:35.099  1799  1799 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-30 16:00:35.109  1799  1799 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-30 16:00:35.109  1799  1799 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-30 16:00:35.109  1020  1465 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-30 16:00:35.109  1020  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:35.109  1020  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:35.109  1020  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:35.109  1020  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:35.129  1020  1465 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7578 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 16:00:35.129  7578  7578 E Zygote  : MountEmulatedStorage()
08-30 16:00:35.129  7578  7578 I libpersona: KNOX_SDCARD checking this for 10077,
08-30 16:00:35.129  7578  7578 E Zygote  : v2
08-30 16:00:35.129  7578  7578 I libpersona: KNOX_SDCARD not a persona,
08-30 16:00:35.129  7578  7578 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 16:00:35.129  7578  7578 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 16:00:35.129  7578  7578 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-30 16:00:35.139  7578  7578 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 16:00:35.139  7578  7578 D ActivityThread: Added TimaKeyStore provider
,08-30 16:00:35.159   288   288 E SMD     : DCD OFF
,08-30 16:00:35.179   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 16:00:35.349  1020  1359 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-30 16:00:35.349  1020  1359 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-30 16:00:35.349  1020  1359 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:35.349  1020  1359 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 16:00:35.349  1020  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-30 16:00:35.349  1020  1492 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-30 16:00:35.359  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:35.359  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:35.359  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:35.359  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:35.369  7596  7596 E Zygote  : MountEmulatedStorage()
08-30 16:00:35.369  7596  7596 E Zygote  : v2
08-30 16:00:35.369  7596  7596 I libpersona: KNOX_SDCARD checking this for 10110
08-30 16:00:35.369  7596  7596 I libpersona: KNOX_SDCARD not a persona
,08-30 16:00:35.369  7596  7596 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 16:00:35.369  1020  1492 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7596 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 16:00:35.379  1020  3784 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-30 16:00:35.379  1020  3784 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
08-30 16:00:35.379  1020  3784 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:35.379  1020  3784 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 16:00:35.379  1020  3784 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-30 16:00:35.379  7596  7596 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 16:00:35.379  7596  7596 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-30 16:00:35.379  1020  4405 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 16:00:35.379  1020  4405 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4227, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-30 16:00:35.379  7415  7595 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
08-30 16:00:35.379  1020  4405 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-30 16:00:35.379  1020  4405 D BatteryService: stay LED for charging
08-30 16:00:35.379  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 16:00:35.379  1020  1020 I MotionRecognitionService: Plugged
,08-30 16:00:35.379  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 16:00:35.389  1181  1181 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-30 16:00:35.389  1181  1181 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 16:00:35.389  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-30 16:00:35.389  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,08-30 16:00:35.389  1181  1181 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-30 16:00:35.389  1181  1181 D SViewCoverView: level :99 plugged : 2
,08-30 16:00:35.399  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
08-30 16:00:35.399  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,08-30 16:00:35.399  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,08-30 16:00:35.399  7596  7596 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 16:00:35.399  1020  1139 I ActivityManager: Killing 7167:com.wsomacp/u0a23 (adj 15): empty #21
08-30 16:00:35.399  7596  7596 D ActivityThread: Added TimaKeyStore provider
,08-30 16:00:35.539  1020  3784 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-30 16:00:35.649  7596  7596 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-30 16:00:35.649  7596  7596 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 16:00:35.649  7596  7596 I GAv4    :   adb logcat -s GAv4
,08-30 16:00:35.669  7596  7596 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 16:00:35.669  1020  3784 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-30 16:00:35.679   257   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-30 16:00:35.679   257   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 16:00:35.689  7596  7614 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-30 16:00:35.689  1020  3781 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-30 16:00:35.689  1020  3781 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 16:00:35.689  1020  3781 D SecContentProvider2: mCursor = null
,08-30 16:00:35.689  1020  3781 D WifiService: setWifiEnabled: true pid=7084, uid=10170
,08-30 16:00:35.689  1020  3781 W ActivityManager: Permission Denial: getCurrentUser() from pid=7084, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-30 16:00:35.689  1020  3781 W WifiService: Failed getting userId using ActivityManagerNative
08-30 16:00:35.689  1020  3781 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7084, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-30 16:00:35.689  1020  3781 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-30 16:00:35.689  1020  3781 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-30 16:00:35.689  1020  3781 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-30 16:00:35.689  1020  3781 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-30 16:00:35.689  1020  3781 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 16:00:35.689  1020  3781 D SettingsProvider: name = wifi_on
,08-30 16:00:35.699  1020  1129 E WifiHW  : ##################### set firmware type 0 #####################
,08-30 16:00:35.709   257   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-30 16:00:35.709   257   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 16:00:35.709  7596  7614 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
08-30 16:00:35.709  7596  7596 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-30 16:00:35.719  7596  7619 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-30 16:00:35.719   257   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-30 16:00:35.719   257   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 16:00:35.719  7596  7620 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-30 16:00:35.719   257   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-30 16:00:35.719   257   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 16:00:35.729  7596  7620 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-30 16:00:35.989  1020  1033 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 16:00:35.989  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:35.999  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 16:00:35.999  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-30 16:00:36.029  7596  7596 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-30 16:00:36.049  7596  7596 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 6694-6696)
08-30 16:00:36.049  7596  7596 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-30 16:00:36.069  7596  7596 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2019449}
,08-30 16:00:36.069  7596  7596 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-30 16:00:36.069  7596  7596 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 16:00:36.089  7596  7596 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-30 16:00:36.089  7596  7596 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 16:00:36.099  7596  7596 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 16:00:36.099  1020  1047 D Tethering: interfaceAdded wlan0
,08-30 16:00:36.109  1020  1134 E Tethering: No numeric data
,08-30 16:00:36.109  1020  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 16:00:36.109  1020  1134 D Tethering: clearTetheredNotification()
,08-30 16:00:36.109  1181  1181 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-30 16:00:36.109  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:36.109  1020  1126 V NetworkStats: performPollLocked(flags=0x1)
08-30 16:00:36.109  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 16:00:36.109  1181  1181 D HotspotTile: updateTetherState():false, false
08-30 16:00:36.109  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 16:00:36.119  1020  1126 V NetworkStats: performPollLocked() took 3ms
08-30 16:00:36.119  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:36.119  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 16:00:36.119  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-30 16:00:36.119  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 16:00:36.119  1020  1134 D Tethering: InitialState.processMessage what=4
,08-30 16:00:36.119  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:36.119  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:36.119  1020  1134 E Tethering: No numeric data
,08-30 16:00:36.119  1020  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 16:00:36.119  1020  1134 D Tethering: clearTetheredNotification()
,08-30 16:00:36.119  1020  1126 V NetworkStats: performPollLocked(flags=0x1)
08-30 16:00:36.119  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:36.119  1181  1181 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 16:00:36.119  1181  1181 D HotspotTile: updateTetherState():false, false
,08-30 16:00:36.119  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 16:00:36.119  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 16:00:36.119  1020  1047 D Tethering: interfaceAdded p2p0
,08-30 16:00:36.129  1020  1047 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-30 16:00:36.129  1020  1126 V NetworkStats: performPollLocked() took 5ms
,08-30 16:00:36.129  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:36.129  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false
,08-30 16:00:36.129  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-30 16:00:36.129  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 16:00:36.129   278   963 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-30 16:00:36.129  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:36.129  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:36.129   278   963 D SoftapController: Softap fwReload - Ok
,08-30 16:00:36.129   278   963 D CommandListener: Setting iface cfg
08-30 16:00:36.129   278   963 D CommandListener: Trying to bring down wlan0
,08-30 16:00:36.139   278   963 D CommandListener: Clearing all IP addresses on wlan0
,08-30 16:00:36.139  7596  7596 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 16:00:36.139  7596  7596 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 16:00:36.139  7596  7596 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 16:00:36.139  7596  7596 I Adreno-EGL: Local Branch: 
08-30 16:00:36.139  7596  7596 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 16:00:36.139  7596  7596 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 16:00:36.139  7596  7596 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 16:00:36.139  1020  1129 E WifiHW  : supplicant_name : p2p_supplicant
,08-30 16:00:36.139  1020  1129 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-30 16:00:36.139  1020  1129 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": Permission denied
,08-30 16:00:36.149  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-30 16:00:36.159  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 16:00:36.159  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 16:00:36.159  1181  1181 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 16:00:36.159  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:36.159  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:36.159  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:36.159  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:36.159  1181  1181 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 16:00:36.159  1181  1781 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-30 16:00:36.159  1181  1181 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-30 16:00:36.159  4748  4748 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 16:00:36.159  1181  1181 D HotspotTile: onReceive : 2, 0
,08-30 16:00:36.169  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:36.179  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:36.179   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 16:00:36.199  7648  7648 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-30 16:00:36.199  7648  7648 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-30 16:00:36.199  7648  7648 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-30 16:00:36.209  7596  7656 W cr.media: Requires BLUETOOTH permission
,08-30 16:00:36.209  7596  7596 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 16:00:36.229  7596  7596 I NSApplication: Starting up...
,08-30 16:00:36.229  1020  1492 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-30 16:00:36.229  7648  7648 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-30 16:00:36.229  1020  1494 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-30 16:00:36.229   378   378 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7648
08-30 16:00:36.229   378   378 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-30 16:00:36.229  7648  7648 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-30 16:00:36.229  7648  7648 I wpa_supplicant: ssSupport state is = 1
08-30 16:00:36.229  7648  7648 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-30 16:00:36.229  7648  7648 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-30 16:00:36.229   378   378 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7648
08-30 16:00:36.229   378   378 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-30 16:00:36.239  1020  1465 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-30 16:00:36.239  1020  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:36.239  1020  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:36.239  1020  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:36.239  1020  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:36.249  1020  1465 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7662 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-30 16:00:36.249  7662  7662 E Zygote  : MountEmulatedStorage()
08-30 16:00:36.249  7662  7662 E Zygote  : v2
,08-30 16:00:36.249  7662  7662 I libpersona: KNOX_SDCARD checking this for 10117
08-30 16:00:36.249  7662  7662 I libpersona: KNOX_SDCARD not a persona
,08-30 16:00:36.259  7662  7662 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 16:00:36.259  1020  1465 I ActivityManager: Killing 7188:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
08-30 16:00:36.259  7662  7662 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 16:00:36.259  7662  7662 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 16:00:36.279   304   304 I art     : Explicit concurrent mark sweep GC freed 8709(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 774us total 25.169ms
,08-30 16:00:36.289  7662  7662 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 16:00:36.289  7662  7662 D ActivityThread: Added TimaKeyStore provider,
,08-30 16:00:36.299   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 17.327ms
,08-30 16:00:36.309  7662  7662 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 16:00:36.309   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 596us total 16.586ms
,08-30 16:00:36.439   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,08-30 16:00:36.439  7648  7648 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-30 16:00:36.489  7648  7648 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-30 16:00:36.489  7648  7648 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-30 16:00:36.499  7648  7648 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-30 16:00:36.499   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7648
08-30 16:00:36.499   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-30 16:00:36.499  7648  7648 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running,
08-30 16:00:36.499  7648  7648 I wpa_supplicant: ssSupport state is = 1
08-30 16:00:36.499  7648  7648 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 16:00:36.499  7648  7648 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-30 16:00:36.499  7648  7648 E wpa_supplicant: SIM READ ERROR
08-30 16:00:36.499  7648  7648 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 16:00:36.499  7648  7648 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 16:00:36.499  7648  7648 E wpa_supplicant: SIM READ ERROR
,08-30 16:00:36.499  7648  7648 I wpa_supplicant: Blacklist: Clear (all) 
08-30 16:00:36.509  7648  7648 I wpa_supplicant: wpa_default_ap_write_once
08-30 16:00:36.509  7648  7648 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-30 16:00:36.509  7648  7648 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 16:00:36.509  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 16:00:36.509  7648  7648 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-30 16:00:36.509  7648  7648 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 16:00:36.509  7648  7648 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 16:00:36.509  7648  7648 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 16:00:36.509  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 16:00:36.509  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-30 16:00:36.569  7648  7648 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-30 16:00:36.649  1020  1465 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-30 16:00:36.649  1020  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:36.649  1020  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:36.649  1020  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:36.649  1020  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:36.669  7684  7684 E Zygote  : MountEmulatedStorage(),
,08-30 16:00:36.669  7684  7684 E Zygote  : v2
08-30 16:00:36.669  7684  7684 I libpersona: KNOX_SDCARD checking this for 10121
08-30 16:00:36.669  7684  7684 I libpersona: KNOX_SDCARD not a persona
,08-30 16:00:36.669  7684  7684 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 16:00:36.669  1020  1465 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7684 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-30 16:00:36.669  1020  1465 I ActivityManager: Killing 7221:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-30 16:00:36.669  7684  7684 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 16:00:36.679  7684  7684 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 16:00:36.689  7684  7684 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 16:00:36.699  7684  7684 D ActivityThread: Added TimaKeyStore provider
,08-30 16:00:36.709  7684  7684 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 16:00:36.709  7684  7684 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-30 16:00:36.709  7684  7684 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 16:00:36.719  7684  7684 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:00:36.729  7684  7684 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-30 16:00:36.729  7684  7684 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
08-30 16:00:36.729  1020  1507 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-30 16:00:36.729  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:36.729  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:36.729  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:36.729  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:36.749  7648  7648 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-30 16:00:36.749  7648  7648 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage,
,08-30 16:00:36.759  7701  7701 E Zygote  : MountEmulatedStorage(),
,08-30 16:00:36.759  7701  7701 E Zygote  : v2
,08-30 16:00:36.759  7701  7701 I libpersona: KNOX_SDCARD checking this for 10141
08-30 16:00:36.759  7701  7701 I libpersona: KNOX_SDCARD not a persona
,08-30 16:00:36.759  7701  7701 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 16:00:36.759  7701  7701 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 16:00:36.759  7701  7701 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 16:00:36.769  1020  1507 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7701 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
08-30 16:00:36.769  1020  1507 I ActivityManager: Killing 7242:com.android.calendar/u0a131 (adj 15): empty #21
,08-30 16:00:36.779  7648  7648 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
08-30 16:00:36.779   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7648
08-30 16:00:36.779   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-30 16:00:36.779  7648  7648 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-30 16:00:36.779  7648  7648 I wpa_supplicant: ssSupport state is = 1
,08-30 16:00:36.779  7648  7648 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-30 16:00:36.779  7648  7648 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-30 16:00:36.789  7701  7701 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-30 16:00:36.789  7701  7701 D ActivityThread: Added TimaKeyStore provider
,08-30 16:00:36.799  7648  7648 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-30 16:00:36.799   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7648
08-30 16:00:36.799   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-30 16:00:36.799  7648  7648 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-30 16:00:36.799  7648  7648 I wpa_supplicant: ssSupport state is = 1
08-30 16:00:36.799  7648  7648 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 16:00:36.799  7648  7648 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 16:00:36.799  7648  7648 E wpa_supplicant: SIM READ ERROR
08-30 16:00:36.799  7648  7648 I wpa_supplicant: wpa_default_ap_write_once
08-30 16:00:36.799  7648  7648 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-30 16:00:36.799  7648  7648 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 16:00:36.799  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 16:00:36.799  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 16:00:36.799  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-30 16:00:36.799  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false
,08-30 16:00:36.799  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-30 16:00:36.799  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 16:00:36.809  7701  7701 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-30 16:00:36.809  7701  7701 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 16:00:36.809  7701  7701 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 16:00:36.809  7701  7701 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-30 16:00:36.849  1020  3784 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 16:00:36.869  1020  1032 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 16:00:36.889  1020  1492 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 16:00:36.899  1020  1438 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 16:00:36.909  7648  7648 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-30 16:00:36.909  7648  7648 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-30 16:00:36.929  1020  3781 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-30 16:00:36.939  1020  3781 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-30 16:00:36.939  1020  3781 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:36.939  1020  3781 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:36.939  1020  3781 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:36.949  7725  7725 E Zygote  : MountEmulatedStorage()
,08-30 16:00:36.949  7725  7725 E Zygote  : v2
,08-30 16:00:36.949  7725  7725 I libpersona: KNOX_SDCARD checking this for 10068,
08-30 16:00:36.949  1020  3781 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7725 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-30 16:00:36.949  7725  7725 I libpersona: KNOX_SDCARD not a persona
,08-30 16:00:36.959  7725  7725 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-30 16:00:36.959  1020  1492 D RCPManagerService: exchangeData() failure , invalid userId,
,08-30 16:00:36.959  7725  7725 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 16:00:36.959  7725  7725 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-30 16:00:36.959  1020  1438 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 16:00:36.969  7648  7648 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-30 16:00:36.969  7648  7648 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-30 16:00:36.969  7648  7648 I wpa_supplicant: Skip scan - bUseNetwork false
,08-30 16:00:36.979  7725  7725 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 16:00:36.989  7725  7725 D ActivityThread: Added TimaKeyStore provider
,08-30 16:00:36.989  1020  1494 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 16:00:36.989  1020  1493 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-30 16:00:36.989  1020  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:36.989  1020  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:36.989  1020  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:36.989  1020  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:37.009  7741  7741 E Zygote  : MountEmulatedStorage(),
08-30 16:00:37.009  7741  7741 E Zygote  : v2
08-30 16:00:37.009  7741  7741 I libpersona: KNOX_SDCARD checking this for 10009
08-30 16:00:37.009  7741  7741 I libpersona: KNOX_SDCARD not a persona
08-30 16:00:37.009  7741  7741 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 16:00:37.009  7741  7741 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 16:00:37.009  7741  7741 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
08-30 16:00:37.009  1020  1493 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7741 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-30 16:00:37.009  1020  1493 I ActivityManager: Killing 6953:com.android.vending/u0a26 (adj 15): empty #21,
08-30 16:00:37.009  1020  1493 I ActivityManager: Killing 7206:com.android.defcontainer/u0a3 (adj 15): empty #22
,08-30 16:00:37.029  7725  7725 D BadgeProvider: onCreate
,08-30 16:00:37.029  7725  7725 D BadgeProvider: DatabaseHelper
,08-30 16:00:37.039  7741  7741 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 16:00:37.039  7741  7741 D ActivityThread: Added TimaKeyStore provider
,08-30 16:00:37.119  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false
,08-30 16:00:37.119  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-30 16:00:37.119  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 16:00:37.149  1020  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-30 16:00:37.149  1020  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-30 16:00:37.149  7648  7648 I wpa_supplicant: HOTSPOT20_ENABLE called
08-30 16:00:37.149  7648  7648 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 16:00:37.149  7648  7648 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 16:00:37.149  7648  7648 E wpa_supplicant: SIM READ ERROR
08-30 16:00:37.149  7648  7648 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 16:00:37.179   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 16:00:37.179  7648  7648 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-30 16:00:37.189  7648  7648 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-30 16:00:37.189  1020  1129 D WifiConfigStore: Loading config and enabling all networks 
,08-30 16:00:37.189  1020  1494 I art     : Explicit concurrent mark sweep GC freed 68096(3MB) AllocSpace objects, 12(240KB) LOS objects, 33% free, 23MB/34MB, paused 2.466ms total 162.055ms
,08-30 16:00:37.199  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-30 16:00:37.199  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 16:00:37.199  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 16:00:37.199  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:37.199  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:37.199  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:37.199  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:37.199  1181  1181 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 16:00:37.199  1181  1181 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-30 16:00:37.199  1181  1181 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 16:00:37.199  1181  1181 D HotspotTile: onReceive : 3, 0
,08-30 16:00:37.199  1181  1781 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-30 16:00:37.199  4748  4748 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 16:00:37.209  1020  1129 E WifiConfigStore: Not a HS20
,08-30 16:00:37.219  1020  1129 D WifiNative-wlan0: callSECApiInt - ID [65]
08-30 16:00:37.219  7084  7084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:00:37.219  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:37.219  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:37.219  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:37.219  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:37.219  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:00:37.219  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:37.219  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:37.219  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:00:37.219  1020  1129 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-30 16:00:37.219  7648  7648 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-30 16:00:37.219  7648  7648 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-30 16:00:37.219  7648  7648 I wpa_supplicant: reset timer : RESET_TIMER 0
08-30 16:00:37.219  7648  7648 I wpa_supplicant: P2P: Current p2p state = IDLE
08-30 16:00:37.219  7648  7648 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-30 16:00:37.219  7648  7648 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-30 16:00:37.219  7648  7648 I wpa_supplicant: First Scan Start
,08-30 16:00:37.219  7648  7648 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-30 16:00:37.219  7084  7084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:00:37.219  7084  7084 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:00:37.219  1020  1129 D WifiNative-wlan0: Setting external_sim to 1
,08-30 16:00:37.219  1020  1129 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 16:00:37.219  1020  1129 I WifiNative-HAL: startHal
08-30 16:00:37.219  1020  1129 E wifi    : getStaticLongField sWifiHalHandle 0x9f12888c
08-30 16:00:37.219  1020  1129 I WifiNative-HAL: Could not start hal
,08-30 16:00:37.229  7415  7415 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 16:00:37.229  1020  1129 E WifiNative-wlan0: do suspend true,
08-30 16:00:37.229  1020  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-30 16:00:37.229  1020  1128 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-30 16:00:37.229   278   963 D CommandListener: Setting iface cfg
08-30 16:00:37.229   278   963 D CommandListener: Trying to bring up p2p0
08-30 16:00:37.229  1020  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-30 16:00:37.229  1020  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-30 16:00:37.229  1020  1129 E WifiNative-wlan0: invaild command id : 215
08-30 16:00:37.229  7084  7084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:00:37.229  1020  1128 D WifiP2pService: P2pEnablingState
08-30 16:00:37.229  1020  1128 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 16:00:37.229  1020  1128 D WifiP2pService: P2pEnablingState{ what=147457 }
08-30 16:00:37.229  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:37.229  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:37.229  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:37.229  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:37.229  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:00:37.229  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:37.229  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:37.229  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:00:37.229  1020  1128 D WifiP2pService: P2p socket connection successful
,08-30 16:00:37.229  7084  7084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:00:37.229  7084  7084 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:00:37.239  7648  7648 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-30 16:00:37.239  1020  1128 D WifiP2pService: P2pEnabledState
08-30 16:00:37.239  7648  7648 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 16:00:37.239  1020  1020 D WifiScanningService: SCAN_AVAILABLE : 3
,08-30 16:00:37.239  5939  5939 D FactoryTest: Not factory mode
08-30 16:00:37.239  5939  5939 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-30 16:00:37.239  5939  5939 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-30 16:00:37.239  5939  5939 D MTPRx   : still no open session command from host, so toast
,08-30 16:00:37.239  1020  1020 D RttService: SCAN_AVAILABLE : 3
08-30 16:00:37.239  7725  7735 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-30 16:00:37.239  1020  1154 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:00:37.239  1020  1154 I WifiNative-HAL: startHal
08-30 16:00:37.239  1020  1154 E wifi    : getStaticLongField sWifiHalHandle 0x9dfea9bc
08-30 16:00:37.239  1020  1154 I WifiNative-HAL: Could not start hal
,08-30 16:00:37.239  1020  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-30 16:00:37.239  1020  1155 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 16:00:37.239  1020  1154 E WifiScanningService: could not start HAL
,08-30 16:00:37.249  1020  1131 E ConnectivityService: updateNetworkInfo()
08-30 16:00:37.249  7648  7648 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-30 16:00:37.249  1020  1129 E WifiStateMachine: Failed to set frequency band 0
,08-30 16:00:37.249  5939  5939 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-30 16:00:37.249  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 16:00:37.249  1020  1129 D SecContentProvider2: mCursor = null
,08-30 16:00:37.249  5939  5939 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-30 16:00:37.249  1020  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-30 16:00:37.249  1020  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 16:00:37.249  1020  1050 D WifiDisplayController: disconnect
08-30 16:00:37.249  1020  1050 D WifiDisplayController: updateConnection
08-30 16:00:37.249  1020  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-30 16:00:37.249  5939  5939 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:117895
,08-30 16:00:37.249  1020  1020 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-30 16:00:37.249  1020  1493 E PersonaManagerService: inState():  stateMachine is null !!
,08-30 16:00:37.249  1020  1493 I PersonaManagerService: PersonaId don't exist
08-30 16:00:37.249  1020  1493 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-30 16:00:37.249  1020  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 16:00:37.259  1181  1181 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-30 16:00:37.259  1020  1128 D WifiNative-p2p0: p2pGetDeviceAddress
08-30 16:00:37.259  1020  1494 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-30 16:00:37.259  1020  1128 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-30 16:00:37.259  1181  1181 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-30 16:00:37.259  1020  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:00:37.259  1020  1050 D WifiDisplayAdapter: onP2pDisconnected
08-30 16:00:37.259  1020  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 16:00:37.259  1020  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-30 16:00:37.259  1020  1493 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-30 16:00:37.259  1020  1493 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:37.259  1020  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:37.259  1020  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-30 16:00:37.269  1020  1493 W ActivityManager: mDVFSHelper.acquire()
,08-30 16:00:37.289  1020  1493 D PersonaManager: isKioskContainerExistOnDevice
,08-30 16:00:37.299  1020  1493 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-30 16:00:37.299  1020  1493 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-30 16:00:37.299  1020  1493 D InputDispatcher: Focused application set to: xxxx
08-30 16:00:37.299  1020  1493 D InputDispatcher: Focus left window: 7084
,08-30 16:00:37.299  5939  5939 E MTPRx   : started activity for popup
,08-30 16:00:37.299  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 16:00:37.299  1020  1129 D SecContentProvider2: mCursor = null
,08-30 16:00:37.299  1020  3781 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-30 16:00:37.299  1020  3781 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-30 16:00:37.299  1020  1128 D WifiP2pService: DeviceAddress: 0a:75:42
,08-30 16:00:37.309  1020  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 16:00:37.309  1020  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 16:00:37.309  1020  1050 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-30 16:00:37.309  1020  1050 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-30 16:00:37.309  1020  1050 D WifiDisplayController:  primary type: 10-0050F204-5
08-30 16:00:37.309  1020  1050 D WifiDisplayController:  secondary type: null
08-30 16:00:37.309  1020  1050 D WifiDisplayController:  wps: 0
08-30 16:00:37.309  1020  1050 D WifiDisplayController:  grpcapab: 0
08-30 16:00:37.309  1020  1050 D WifiDisplayController:  devcapab: 0
08-30 16:00:37.309  1020  1050 D WifiDisplayController:  status: 3
08-30 16:00:37.309  1020  1050 D WifiDisplayController:  wfdInfo: null
08-30 16:00:37.309  1020  1050 D WifiDisplayController:  groupownerAddress: null
08-30 16:00:37.309  1020  1050 D WifiDisplayController:  GOdeviceName: null
08-30 16:00:37.309  1020  1050 D WifiDisplayController:  interfaceAddress: 
08-30 16:00:37.309  1020  1050 D WifiDisplayController:  SConnectInfo : null
,08-30 16:00:37.319  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0,
,08-30 16:00:37.319  7725  7735 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-30 16:00:37.319  7725  7735 D BadgeProvider: sendNotify, [notify] : null
08-30 16:00:37.319  7725  7735 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-30 16:00:37.319  7725  7735 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-30 16:00:37.319  7725  7735 D BadgeProvider: update, [UpdateCount] : 1
,08-30 16:00:37.319  1495  1495 D Launcher.Model: reloadBadges entered.
,08-30 16:00:37.319  1020  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-30 16:00:37.329  1020  1128 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-30 16:00:37.329  1020  1128 D WifiP2pService: InactiveState,
08-30 16:00:37.329  1020  1128 D WifiP2pService: InactiveState{ what=143376 }
08-30 16:00:37.329  1020  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 16:00:37.329  7648  7648 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-30 16:00:37.329  1020  1128 D WifiP2pService: InactiveState{ what=143376 }
,08-30 16:00:37.329  1020  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 16:00:37.339  5939  5939 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-30 16:00:37.339  5939  5939 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-30 16:00:37.339  5939  5939 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-30 16:00:37.339  5939  5939 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 16:00:37.339  5939  5939 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 16:00:37.339  5939  5939 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 16:00:37.339  1020  1494 I ActivityManager: Killing 7383:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-30 16:00:37.349   278   959 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 16:00:37.349   278   959 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-30 16:00:37.349  1020  4405 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 16:00:37.349  1020  4405 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 16:00:37.349  1020  4405 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:37.349  1020  4405 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:37.349  1020  4405 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 16:00:37.349  1632  1632 I Hs20UtilService: Starting #12
,08-30 16:00:37.349  1632  1654 I Hs20UtilService: Message received 5011
,08-30 16:00:37.359  7438  7438 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 16:00:37.359  7438  7438 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-30 16:00:37.359  7438  7438 D SecurityLogAgent: StateMachine : Current State = 1
,08-30 16:00:37.359  7438  7438 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 16:00:37.369  1020  1438 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 16:00:37.369  1020  1438 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 16:00:37.379  1020  1438 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:37.379  1020  1438 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:37.379  1020  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 16:00:37.379  1632  1632 I Hs20UtilService: Starting #13
,08-30 16:00:37.379  1632  1654 I Hs20UtilService: Message received 5011
,08-30 16:00:37.379  5939  5939 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
08-30 16:00:37.379  1020  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-30 16:00:37.379  1020  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-30 16:00:37.379  1020  1129 E WifiNative-wlan0: invaild command id : 215
,08-30 16:00:37.379  7438  7438 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 16:00:37.379  7438  7438 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 16:00:37.379  7438  7438 D SecurityLogAgent: StateMachine : Current State = 1
08-30 16:00:37.379  7438  7438 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 16:00:37.389  1020  1032 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-30 16:00:37.389  1020  1032 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 16:00:37.389  1020  1032 D InputDispatcher: Focused application set to: xxxx
,08-30 16:00:37.389  1020  1032 D InputDispatcher: Focus entered window: 7084
,08-30 16:00:37.389  1020  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-30 16:00:37.389  1020  1494 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-30 16:00:37.399  1020  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 16:00:37.399  1020  1494 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@32ee2cde attribute=null, token = android.os.BinderProxy@3876a8f8
,08-30 16:00:37.409  4748  4748 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-30 16:00:37.409  4748  4748 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 16:00:37.409  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 16:00:37.409  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 16:00:37.409  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 16:00:37.409  4748  4748 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 16:00:37.409  4748  4840 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 16:00:37.409  1020  1465 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-30 16:00:37.419  1020  1465 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.samsung.android.app.FileShareClient/com.samsung.android.app.FileShareClient.ClientBroadcastReceiver}
08-30 16:00:37.419  1020  1465 W BroadcastQueue: android.os.TransactionTooLargeException
08-30 16:00:37.419  1020  1465 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 16:00:37.419  1020  1465 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 16:00:37.419  1020  1465 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-30 16:00:37.419  1020  1465 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-30 16:00:37.419  1020  1465 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-30 16:00:37.419  1020  1465 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-30 16:00:37.419  1020  1465 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-30 16:00:37.419  1020  1465 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-30 16:00:37.419  1020  1465 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
08-30 16:00:37.419  1020  1465 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-30 16:00:37.419  1020  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:37.419  1020  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:37.419  1020  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:37.419  1020  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-30 16:00:37.439  7768  7768 E Zygote  : MountEmulatedStorage(),
08-30 16:00:37.439  7768  7768 I libpersona: KNOX_SDCARD checking this for 10064
08-30 16:00:37.439  7768  7768 E Zygote  : v2
,08-30 16:00:37.439  7768  7768 I libpersona: KNOX_SDCARD not a persona
08-30 16:00:37.449  7768  7768 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 16:00:37.449  7768  7768 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 16:00:37.449  1020  1465 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7768 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 16:00:37.449  7768  7768 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 16:00:37.459  5939  5939 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-30 16:00:37.459  1020  1044 W libprocessgroup: failed to open /acct/uid_10064/pid_7383/cgroup.procs: No such file or directory
,08-30 16:00:37.469  5939  5939 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-30 16:00:37.469  5939  5939 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-30 16:00:37.469  7768  7768 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 16:00:37.479  7768  7768 D ActivityThread: Added TimaKeyStore provider
,08-30 16:00:37.489  7768  7768 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-30 16:00:37.489  7084  7084 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-30 16:00:37.489  7084  7084 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
08-30 16:00:37.489  7084  7084 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-30 16:00:37.489  7084  7084 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-30 16:00:37.489  1020  1494 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false,
08-30 16:00:37.489  1020  1494 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-30 16:00:37.489  1020  1494 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-30 16:00:37.489  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-30 16:00:37.489  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
,08-30 16:00:37.499  7768  7768 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 16:00:37.499  7768  7768 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-30 16:00:37.509  7084  7084 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 16:00:37.509  7084  7084 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-30 16:00:37.519  7084  7084 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3868519f Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@4ebfd76, 16908290=android.view.AbsSavedState$1@4ebfd76}, android:focusedViewId=100}]}]
08-30 16:00:37.519  7084  7084 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-30 16:00:37.519  7084  7084 V ActivityThread: updateVisibility : ActivityRecord{1fd52d69 token=android.os.BinderProxy@3f9f3433 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-30 16:00:37.519  7084  7084 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 16:00:37.519  7084  7084 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-30 16:00:37.519  7084  7084 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3f9f3433 time:118167
,08-30 16:00:37.529  1020  1493 D PersonaManager: isKioskContainerExistOnDevice
,08-30 16:00:37.529  7768  7768 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 16:00:37.539  7400  7400 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 16:00:37.549  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:37.549  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 16:00:37.549  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-30 16:00:37.549  1020  1220 I ActivityManager: Killing 7314:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-30 16:00:38.159   288   288 E SMD     : DCD OFF
,08-30 16:00:38.179   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-30 16:00:38.439  7648  7648 I wpa_supplicant: nl80211: Received scan results (20 BSSes),
08-30 16:00:38.439  7648  7648 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-30 16:00:38.439  7648  7648 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-30 16:00:38.439  7648  7648 I wpa_supplicant: Trying to associate with  'G700'
,08-30 16:00:38.439  7648  7648 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-30 16:00:38.439  7648  7648 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-30 16:00:38.439  1020  7757 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
,08-30 16:00:38.459  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 16:00:38.459  1020  1129 D SecContentProvider2: mCursor = null
,08-30 16:00:38.559  7648  7648 E wpa_supplicant: Cmd 35605 not handled
,08-30 16:00:38.559  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 16:00:38.559  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
08-30 16:00:38.559  7648  7648 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-30 16:00:38.559  7648  7648 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-30 16:00:38.559  7648  7648 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-30 16:00:38.559  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 16:00:38.559  7648  7648 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-30 16:00:38.559  7648  7648 I wpa_supplicant: Associated with F4.99.3E
08-30 16:00:38.559  7648  7648 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-30 16:00:38.559  7648  7648 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-30 16:00:38.559  7648  7648 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-30 16:00:38.559  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 16:00:38.559  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
08-30 16:00:38.559  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 16:00:38.559  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 16:00:38.559  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
08-30 16:00:38.559  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 16:00:38.559  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, true
08-30 16:00:38.559  1020  1047 D Tethering: interfaceStatusChanged wlan0, true
,08-30 16:00:38.559  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-30 16:00:38.559  1020  1134 E Tethering: No numeric data
08-30 16:00:38.559  1020  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 16:00:38.559  1020  1134 D Tethering: clearTetheredNotification()
,08-30 16:00:38.559  1020  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-30 16:00:38.559  1181  1181 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-30 16:00:38.559  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:38.559  1181  1181 D HotspotTile: updateTetherState():false, false
,08-30 16:00:38.569  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 16:00:38.569  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-30 16:00:38.569  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 16:00:38.569  1020  1129 D SecContentProvider2: mCursor = null
,08-30 16:00:38.569  1020  1126 V NetworkStats: performPollLocked() took 4ms
08-30 16:00:38.569  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:38.569  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:38.569  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:38.569  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 16:00:38.569  1020  1129 D SecContentProvider2: mCursor = null
,08-30 16:00:38.569  7648  7648 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-30 16:00:38.569  7648  7648 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-30 16:00:38.569  7648  7648 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-30 16:00:38.569  7648  7648 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-30 16:00:38.569  7648  7648 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 16:00:38.569  7648  7648 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-30 16:00:38.569  7648  7648 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-30 16:00:38.569  7648  7648 I wpa_supplicant: Blacklist: Clear (temp) 
08-30 16:00:38.569  7648  7648 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-30 16:00:38.579  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, true
08-30 16:00:38.579  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-30 16:00:38.579  1020  1047 D Tethering: interfaceStatusChanged wlan0, true
,08-30 16:00:38.579  1020  1129 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-30 16:00:38.579  1020  1129 E WifiConfigStore: setLastSelectedConfiguration -1
,08-30 16:00:38.579  1020  1129 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-30 16:00:38.579  1020  1131 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-30 16:00:38.579  1020  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-30 16:00:38.579  1020  1131 E ConnectivityService: updateNetworkInfo()
,08-30 16:00:38.589  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-30 16:00:38.589  1020  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:00:38.589  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 16:00:38.589  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 16:00:38.589  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:38.589  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:38.589  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:38.589  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:38.589  1020  1139 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
,08-30 16:00:38.589  1020  1139 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
,08-30 16:00:38.589  1020  1139 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:38.589  1020  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:38.589  1020  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 16:00:38.589  1632  1632 I Hs20UtilService: Starting #14
,08-30 16:00:38.599  1020  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:00:38.599  1632  1654 I Hs20UtilService: Message received 5007
,08-30 16:00:38.599  4748  4748 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 16:00:38.599  4748  4748 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 16:00:38.599  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 16:00:38.599  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 16:00:38.599  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 16:00:38.599  4748  4748 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 16:00:38.599  4748  4840 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 16:00:38.609   278   963 D CommandListener: Setting iface cfg,
,08-30 16:00:38.609  1020  1129 E WifiStateMachine: Start Dhcp Watchdog 2
,08-30 16:00:38.609  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 16:00:38.609  1020  1129 D SecContentProvider2: mCursor = null
,08-30 16:00:38.619  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-30 16:00:38.619  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 16:00:38.619  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-30 16:00:38.619  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:38.629  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:38.629  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:38.629  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:38.629  1020  1129 E WifiNative-wlan0: do suspend false
,08-30 16:00:38.629  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 16:00:38.629  1020  1128 D WifiP2pService: InactiveState{ what=143375 }
,08-30 16:00:38.629  1020  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
08-30 16:00:38.629  1020  1129 D SecContentProvider2: mCursor = null
,08-30 16:00:38.699  1020  1033 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-30 16:00:38.699  1020  1033 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-30 16:00:38.699  1020  1033 D SecContentProvider2: mCursor = null
,08-30 16:00:38.699  1020  1033 D WifiService: setWifiEnabled: false pid=7084, uid=10170
,08-30 16:00:38.699  1020  1033 D SettingsProvider: name = wifi_on
,08-30 16:00:38.709  1020  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:00:38.719  1020  1129 E WifiNative-wlan0: do suspend true
,08-30 16:00:38.739  1020  1128 D WifiP2pService: InactiveState{ what=143375 }
,08-30 16:00:38.739  1020  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 16:00:38.739  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-30 16:00:38.739  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 16:00:38.739  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 16:00:38.739  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:38.739  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:38.739  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:38.749  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:38.749   278   963 D CommandListener: Clearing all IP addresses on wlan0
,08-30 16:00:38.749  1020  1131 E ConnectivityService: updateNetworkInfo(),
08-30 16:00:38.749  1020  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-30 16:00:38.749  1020  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,08-30 16:00:38.749   278   963 E Netd    : no such netId 503
,08-30 16:00:38.749  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-30 16:00:38.759  1020  1131 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
08-30 16:00:38.759  1020  1131 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,08-30 16:00:38.759  1020  1131 V NetworkStats: updateIfacesLocked()
08-30 16:00:38.759  1020  1131 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:38.759  1020  1131 V NetworkStats: performPollLocked(flags=0x1)
,08-30 16:00:38.759  1020  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 16:00:38.759  1020  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 16:00:38.759  1020  1128 D WifiP2pService: InactiveState{ what=131204 }
08-30 16:00:38.759  1020  1128 D WifiP2pService: P2pEnabledState{ what=131204 }
08-30 16:00:38.759  1020  1129 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 16:00:38.759  1020  1020 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 16:00:38.759  1020  1131 V NetworkStats: performPollLocked() took 4ms
08-30 16:00:38.759  1020  1131 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:38.759  1020  1154 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 16:00:38.769  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-30 16:00:38.769  1020  1493 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 16:00:38.769  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 16:00:38.769  1020  1493 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 16:00:38.769  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 16:00:38.769  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:38.769  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:38.769  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:38.769  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:38.769  1020  1020 D RttService: SCAN_AVAILABLE : 1
08-30 16:00:38.769  1020  1155 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:00:38.769  1020  1131 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-30 16:00:38.769  1020  1493 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:38.769  1020  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:38.769  1020  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 16:00:38.769  1020  1131 D ConnectivityService: nai.networkMonitor.doQuit()
08-30 16:00:38.769  1020  1131 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-30 16:00:38.769  1020  1131 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-30 16:00:38.769  1020  1128 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-30 16:00:38.769  1632  1632 I Hs20UtilService: Starting #15
,08-30 16:00:38.769  1020  1131 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 16:00:38.769  1632  1654 I Hs20UtilService: Message received 5007
08-30 16:00:38.769  1020  1131 E ConnectivityService: updateNetworkInfo()
08-30 16:00:38.769  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:38.769  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:38.769  1020  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 16:00:38.769  1020  1050 D WifiDisplayAdapter: onP2pDisconnected
08-30 16:00:38.769  1020  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 16:00:38.769  1020  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-30 16:00:38.769  4748  4748 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 16:00:38.779  4748  4748 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 16:00:38.779  1020  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-30 16:00:38.779  1020  1020 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-30 16:00:38.779  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 16:00:38.779  1020  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-30 16:00:38.779  1020  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-30 16:00:38.779  1020  1050 D WifiDisplayController: disconnect
08-30 16:00:38.779  1020  1050 D WifiDisplayController: updateConnection
08-30 16:00:38.779  1020  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-30 16:00:38.779  1020  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-30 16:00:38.779  1020  1131 E ConnectivityService: updateNetworkInfo()
08-30 16:00:38.779  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - P2P: FAILED
08-30 16:00:38.779  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-30 16:00:38.779  4748  4748 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 16:00:38.779  1181  1181 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED,
08-30 16:00:38.779  1020  1465 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
08-30 16:00:38.779  1020  1128 D WifiP2pService: P2pDisablingState
08-30 16:00:38.779  1181  1181 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-30 16:00:38.779  1020  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-30 16:00:38.779  1020  1050 D WifiDisplayAdapter: onP2pDisconnected
08-30 16:00:38.779  1020  1129 E WifiNative-wlan0: do suspend true
08-30 16:00:38.779  1020  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-30 16:00:38.779  4748  4840 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-30 16:00:38.779  1020  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
08-30 16:00:38.779  1020  1128 D WifiP2pService: P2pDisablingState{ what=147458 }
08-30 16:00:38.779  1020  1128 D WifiP2pService: p2p socket connection lost
08-30 16:00:38.779  1020  1128 D WifiP2pService: P2pDisabledState
,08-30 16:00:38.789  4748  4748 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-30 16:00:38.789  4748  4748 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 16:00:38.789  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 16:00:38.789  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 16:00:38.789  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 16:00:38.789  4748  4748 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 16:00:38.789  4748  4840 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 16:00:38.799  7768  7768 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 16:00:38.799  7768  7768 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-30 16:00:38.799  7768  7768 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 16:00:38.799  7400  7400 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 16:00:38.809  1020  1128 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-30 16:00:38.809  1020  1128 D WifiP2pService: DefaultState{ what=143375 }
,08-30 16:00:38.809  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-30 16:00:38.809  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 16:00:38.809  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-30 16:00:38.809  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:38.819   278   963 D CommandListener: Clearing all IP addresses on wlan0
,08-30 16:00:38.819  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:38.819  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:38.819  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:38.819  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-30 16:00:38.829  7648  7648 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-30 16:00:38.829  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-30 16:00:38.829  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 16:00:38.829  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
08-30 16:00:38.829  1020  4405 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 16:00:38.829  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:38.829  1020  4405 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 16:00:38.829  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:38.829  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:38.829  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:38.829  1020  4405 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:38.829  1020  4405 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:38.829  1020  4405 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 16:00:38.839  1632  1632 I Hs20UtilService: Starting #16
,08-30 16:00:38.839  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 16:00:38.839  1020  1129 D SecContentProvider2: mCursor = null
,08-30 16:00:38.839  1632  1654 I Hs20UtilService: Message received 5007
,08-30 16:00:38.839  4748  4748 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 16:00:38.849  7786  7786 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-30 16:00:38.849  7084  7084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:00:38.849  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:38.849  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:38.849  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:38.849  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:00:38.849  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:00:38.849  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:38.849  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:38.849  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:00:38.849  7786  7786 I dhcpcd  : version 5.5.6 starting
,08-30 16:00:38.849  7084  7084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:00:38.849  7084  7084 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:00:38.849  7786  7786 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-30 16:00:38.859  4748  4748 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 16:00:38.859  4748  4748 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 16:00:38.869  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 16:00:38.869  7084  7084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-30 16:00:38.869  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:38.869  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:38.869  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:38.869  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:00:38.869  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:00:38.869  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:38.869  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:38.869  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:00:38.869  7084  7084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:00:38.869  7084  7084 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:00:38.869  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-30 16:00:38.869  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 16:00:38.869  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 16:00:38.869  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:38.869  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:38.869  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:38.879  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:38.879  1181  1181 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 16:00:38.879  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 16:00:38.879  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 16:00:38.879  4748  4748 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 16:00:38.879  4748  4840 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 16:00:38.879  1181  1181 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-30 16:00:38.879  1181  1181 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 16:00:38.879  1181  1781 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-30 16:00:38.879  1181  1181 D HotspotTile: onReceive : 0, 0
,08-30 16:00:38.889  1181  1211 I art     : Background sticky concurrent mark sweep GC freed 1057(108KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 23MB/24MB, paused 7.255ms total 17.835ms,
,08-30 16:00:38.899  1020  1493 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 16:00:38.899  1020  1493 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 16:00:38.899  1020  1493 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:38.899  1020  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 16:00:38.899  1020  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 16:00:38.899  1632  1632 I Hs20UtilService: Starting #17
,08-30 16:00:38.909  1632  1654 I Hs20UtilService: Message received 5011
,08-30 16:00:38.909  7786  7786 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-30 16:00:38.909  7786  7786 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-30 16:00:38.909  7786  7786 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-30 16:00:38.909  7786  7786 I dhcpcd  : bssid match
08-30 16:00:38.909  7786  7786 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
08-30 16:00:38.909  7438  7438 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 16:00:38.909  7438  7438 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found ,
08-30 16:00:38.909  7438  7438 D SecurityLogAgent: StateMachine : Current State = 1
08-30 16:00:38.909  7438  7438 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 16:00:39.039  7786  7786 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-30 16:00:39.069  7648  7648 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 16:00:39.129  7786  7786 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,08-30 16:00:39.179  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false,
08-30 16:00:39.179  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 16:00:39.179  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-30 16:00:39.179  7648  7648 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-30 16:00:39.199  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false,
08-30 16:00:39.199  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
08-30 16:00:39.209  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 16:00:39.209  1020  1134 D Tethering: InitialState.processMessage what=4
,08-30 16:00:39.209  7648  7648 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-30 16:00:39.209  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 16:00:39.209  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
08-30 16:00:39.209  7648  7648 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-30 16:00:39.209  7648  7648 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-30 16:00:39.209  7648  7648 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-30 16:00:39.209  7648  7648 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-30 16:00:39.209  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 16:00:39.209  1020  1134 E Tethering: No numeric data
,08-30 16:00:39.209  1020  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 16:00:39.209  1020  1134 D Tethering: clearTetheredNotification()
08-30 16:00:39.209  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 16:00:39.209  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
08-30 16:00:39.209  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 16:00:39.209  1020  1126 V NetworkStats: performPollLocked(flags=0x1)
08-30 16:00:39.209  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:39.209  1181  1181 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 16:00:39.209  1181  1181 D HotspotTile: updateTetherState():false, false
08-30 16:00:39.209  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 16:00:39.209  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 16:00:39.219  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
08-30 16:00:39.219  1020  1126 V NetworkStats: performPollLocked() took 4ms
,08-30 16:00:39.219  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit,
08-30 16:00:39.219  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:39.419  7648  7648 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 16:00:39.489  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
,08-30 16:00:39.489  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
08-30 16:00:39.489  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,08-30 16:00:39.489  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
,08-30 16:00:39.489  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-30 16:00:39.489  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 16:00:39.489  7648  7648 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-30 16:00:39.599  1020  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-30 16:00:39.599  1020  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-30 16:00:39.599  7415  7415 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 16:00:39.619  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-30 16:00:39.619  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 16:00:39.619  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:39.619  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-30 16:00:39.619  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:39.619  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:39.619  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:39.619  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:39.619  1181  1181 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 16:00:39.619  1181  1181 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-30 16:00:39.629  4748  4748 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 16:00:39.629  1181  1181 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 16:00:39.629  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:39.629  1181  1781 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-30 16:00:39.629  1181  1181 D HotspotTile: onReceive : 1, 0
,08-30 16:00:39.629  1750  2213 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 16:00:39.639  1020  1493 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 16:00:39.639  1020  1493 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 16:00:39.639  1020  1493 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:39.639  1020  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:39.639  1020  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 16:00:39.639  1632  1632 I Hs20UtilService: Starting #18
,08-30 16:00:39.639  1632  1654 I Hs20UtilService: Message received 5011
,08-30 16:00:39.649  7438  7438 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 16:00:39.649  7438  7438 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 16:00:39.649  7438  7438 D SecurityLogAgent: StateMachine : Current State = 1
08-30 16:00:39.649  7438  7438 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 16:00:40.269  1020  1045 W ActivityManager: mDVFSHelper.release()
,08-30 16:00:40.409   278   957 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-30 16:00:40.419  1020  1047 D Tethering: interfaceRemoved wlan0
08-30 16:00:40.419  1020  1047 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-30 16:00:40.629  1020  1047 D Tethering: interfaceRemoved p2p0
,08-30 16:00:40.629  1020  1047 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-30 16:00:40.809  1020  3422 D SSRM:n  : SIOP:: AP = 380,
,08-30 16:00:41.159   288   288 E SMD     : DCD OFF,
,08-30 16:00:41.179  1020  1098 V AlarmManager: waitForAlarm result :4,
,08-30 16:00:41.199   278   959 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 16:00:41.199   278   959 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-30 16:00:41.209  1020  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:41.209  1020  1045 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 16:00:41.209  1020  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-30 16:00:41.489  1020  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1,
,08-30 16:00:41.709  7084  7295 D BluetoothAdapter: enable()
,08-30 16:00:41.709  1020  1492 W ActivityManager: Permission Denial: getCurrentUser() from pid=7084, uid=10170 requires android.permission.INTERACT_ACROSS_USERS,
,08-30 16:00:41.719  1020  1492 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-30 16:00:41.719  1020  1492 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7084, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-30 16:00:41.719  1020  1492 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-30 16:00:41.719  1020  1492 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-30 16:00:41.719  1020  1492 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-30 16:00:41.719  1020  1492 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-30 16:00:41.719  1020  1492 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 16:00:41.719  1020  1492 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 16:00:41.719  1020  1492 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 16:00:41.719  1020  1492 D SettingsProvider: name = bluetooth_on
,08-30 16:00:41.729  1020  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-30 16:00:41.729  1020  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 16:00:41.739  1020  1049 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-30 16:00:41.739  3280  3354 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-30 16:00:41.739  3280  3354 D BluetoothAdapterProperties: Setting state to 11
08-30 16:00:41.739  3280  3354 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-30 16:00:41.739  3280  3354 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 16:00:41.739  3280  3354 D BluetoothAdapterService: updateAdapterState state is 11
,08-30 16:00:41.739  3280  3354 D BluetoothAdapterService: Autoconnection is available 
,08-30 16:00:41.739  3280  3354 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-30 16:00:41.739  3280  3354 D BtConfig.SecureMode: isSecureModeOn:false
,08-30 16:00:41.739  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-30 16:00:41.749  3280  3354 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,08-30 16:00:41.749  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 16:00:41.749  3280  3354 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
,08-30 16:00:41.749  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-30 16:00:41.749  3280  3354 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-30 16:00:41.749  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 16:00:41.749  3280  3354 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-30 16:00:41.749  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 16:00:41.749  3280  3354 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-30 16:00:41.749  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-30 16:00:41.749  3280  3354 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-30 16:00:41.749  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 16:00:41.749  3280  3354 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-30 16:00:41.749  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 16:00:41.749  3280  3354 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-30 16:00:41.749  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 16:00:41.749  3280  3354 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 16:00:41.749  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 16:00:41.749  3280  3354 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-30 16:00:41.749  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 16:00:41.749  3280  3354 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-30 16:00:41.749  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 16:00:41.749  3280  3354 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-30 16:00:41.749  3280  3354 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-30 16:00:41.749  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-30 16:00:41.749  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 16:00:41.749  3280  3354 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-30 16:00:41.749  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:00:41.749  1020  1020 I InputMethodManagerService: [BT Setting State] State =11
,08-30 16:00:41.759  1181  1181 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-30 16:00:41.759  1181  1181 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:00:41.759  1181  1181 D BluetoothTile:  getBluetoothState : 11
,08-30 16:00:41.769  1181  1781 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 16:00:41.769  1181  1781 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-30 16:00:41.769  1915  1915 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 16:00:41.769  4748  4748 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:00:41.769  1020  1220 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 16:00:41.779  1020  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 16:00:41.779  1020  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-30 16:00:41.779  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:41.779  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:41.779  1020  1465 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 16:00:41.779  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 16:00:41.789  1020  1494 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:41.789  1020  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:41.789  1020  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:41.789  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-30 16:00:41.789  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-30 16:00:41.789  3280  3354 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-30 16:00:41.789  1684  1684 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 16:00:41.789  1020  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 16:00:41.789  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-30 16:00:41.789  3280  3280 D HeadsetService: Received start request. Starting profile...
,08-30 16:00:41.789  3280  3280 D HeadsetService: start()
08-30 16:00:41.789  3280  3280 D HeadsetStateMachine: make
,08-30 16:00:41.789  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:41.789  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:41.789  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:41.799  3280  3280 E HeadsetStateMachine: # of Max HF connection is 2
,08-30 16:00:41.799  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-30 16:00:41.799  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 16:00:41.799  3280  3354 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-30 16:00:41.799  1020  4405 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 16:00:41.799  1020  4405 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 16:00:41.799  1020  4405 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:41.799  1020  4405 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:41.799  1020  4405 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 16:00:41.799  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService,
08-30 16:00:41.799  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 16:00:41.799  3280  3354 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-30 16:00:41.809  1020  3781 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 16:00:41.809  1020  3781 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-30 16:00:41.809  1020  3781 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:41.809  1020  3781 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:41.809  1020  3781 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:41.809  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 16:00:41.809  4748  4748 D BluetoothNotiBroadcastReceiver: onReceive
08-30 16:00:41.809  1020  4405 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-30 16:00:41.809  1020  4405 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-30 16:00:41.809  1020  4405 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:41.809  1020  4405 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:41.809  1020  4405 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-30 16:00:41.809  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-30 16:00:41.809  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-30 16:00:41.809  3280  3354 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-30 16:00:41.819  1020  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 16:00:41.819  1020  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 16:00:41.819  1020  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:41.819  1020  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:41.819  1020  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:41.819  1020  1507 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-30 16:00:41.819  1020  1507 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-30 16:00:41.819  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-30 16:00:41.819  1020  1507 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:41.819  1020  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:41.819  1020  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-30 16:00:41.819  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 16:00:41.819  3280  3354 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-30 16:00:41.819  3280  3280 I bluedroid: get_profile_interface handsfree
,08-30 16:00:41.829  1020  1465 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 16:00:41.829  1020  1465 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 16:00:41.829  1020  1465 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:41.829  1020  1465 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:41.829  1020  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:41.829  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,08-30 16:00:41.829  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 16:00:41.829  3280  3354 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-30 16:00:41.829  1020  1465 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 16:00:41.829  1020  1465 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 16:00:41.829  1020  1465 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:41.829  1020  1465 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:41.829  1020  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:41.839  1181  1181 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:00:41.839  1181  1181 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-30 16:00:41.839  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-30 16:00:41.839  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 16:00:41.839  3280  3354 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-30 16:00:41.839  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-30 16:00:41.839  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 16:00:41.839  3280  3354 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-30 16:00:41.839  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-30 16:00:41.839  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 16:00:41.839  3280  3354 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-30 16:00:41.839  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-30 16:00:41.839  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 16:00:41.839  3280  3354 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-30 16:00:41.839  3280  3354 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-30 16:00:41.839  1020  1139 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-30 16:00:41.839  1020  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:41.839  1020  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:41.839  1020  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:41.839  1020  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:41.859  7820  7820 E Zygote  : MountEmulatedStorage()
08-30 16:00:41.859  7820  7820 E Zygote  : v2
08-30 16:00:41.859  7820  7820 I libpersona: KNOX_SDCARD checking this for 10055
08-30 16:00:41.859  7820  7820 I libpersona: KNOX_SDCARD not a persona
,08-30 16:00:41.859  7820  7820 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 16:00:41.859  7820  7820 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 16:00:41.859  1020  1139 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7820 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-30 16:00:41.859  3280  3280 E DualScoManager: Dual Sco Manager already instantiated
,08-30 16:00:41.859  3280  3280 I DualScoManager: Set HeadsetServiceHelper
08-30 16:00:41.859  7820  7820 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 16:00:41.859  3280  3280 D BluetoothAtMessage: createCMTIContentObservers
,08-30 16:00:41.859  1020  1493 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-30 16:00:41.859  1020  1493 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 16:00:41.859  1020  1493 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 16:00:41.859  1020  1493 D SettingsProvider: selectionArgs: false
08-30 16:00:41.859  1020  1493 D SettingsProvider: selectionArgs: 1002
08-30 16:00:41.859  1020  1493 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 16:00:41.859  1020  1493 D SettingsProvider: ret = -1
,08-30 16:00:41.869  3280  7819 D HeadsetStateMachine: Enter Disconnected: -2
08-30 16:00:41.869  3280  3280 D HeadsetService: mStartError = false
,08-30 16:00:41.869  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
,08-30 16:00:41.869  3280  3280 D A2dpService: Received start request. Starting profile...
08-30 16:00:41.869  3280  3280 D A2dpService: start()
08-30 16:00:41.869  3280  3280 I bluedroid: get_profile_interface avrcp
08-30 16:00:41.869  3280  7819 D HeadsetStateMachine: Clear mHeadsetBrsf
08-30 16:00:41.869  3280  7819 D HeadsetStateMachine: map size, before remove : 0
08-30 16:00:41.869  3280  7819 D HeadsetStateMachine: map size, after remove: 0
,08-30 16:00:41.869  3280  3280 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 16:00:41.869  3280  3280 D Avrcp   : Initialize Media Controller
08-30 16:00:41.869  3280  3280 D Avrcp   : Get the Context Package Name: com.android.bluetooth
08-30 16:00:41.869  3280  3280 E Avrcp   : getActiveSessions
08-30 16:00:41.869  3280  3280 D Avrcp   : pick active media Controller
08-30 16:00:41.869  3280  3280 D Avrcp   : Get the active Media Controller 
,08-30 16:00:41.879  3280  3280 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-30 16:00:41.879  7820  7820 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 16:00:41.879  7820  7820 D ActivityThread: Added TimaKeyStore provider
08-30 16:00:41.879  3280  3280 D A2dpStateMachine: make
08-30 16:00:41.879  3280  7829 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-30 16:00:41.889  3280  3280 I bluedroid: get_profile_interface a2dp
,08-30 16:00:41.889  3280  7837 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 16:00:41.889  3280  3280 E bt-btif : warning : media task started media_task_refcnt 1 
,08-30 16:00:41.889  3280  3280 D A2dpService: mStartError = false
08-30 16:00:41.889  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
08-30 16:00:41.889  3280  3280 D HidService: Received start request. Starting profile...
08-30 16:00:41.889  3280  3280 D HidService: start()
08-30 16:00:41.889  3280  3280 I bluedroid: get_profile_interface hidhost
08-30 16:00:41.889  3280  3280 D HidService: setHidService(): set to: null
08-30 16:00:41.889  3280  3280 D HidService: mStartError = false
08-30 16:00:41.889  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
08-30 16:00:41.889  3280  3280 D HeadsetStateMachine: Try to query the phonestate on bind
,08-30 16:00:41.889  3280  7836 D A2dpStateMachine: Enter Disconnected: -2
,08-30 16:00:41.889  1441  1454 I Telecom : BluetoothPhoneService: queryPhoneState
,08-30 16:00:41.889  1441  1441 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-30 16:00:41.889  1441  1441 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-30 16:00:41.889  1441  1454 I Telecom : BluetoothPhoneService: Result of Message : true
,08-30 16:00:41.899  3280  3280 D HealthService: Received start request. Starting profile...
08-30 16:00:41.899  3280  3280 D HealthService: start()
,08-30 16:00:41.899  3280  3280 I bluedroid: get_profile_interface health
,08-30 16:00:41.899  3280  3280 D HealthService: mStartError = false
08-30 16:00:41.899  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
,08-30 16:00:41.899  3280  3280 D HeadsetStateMachine: Proxy object connected
,08-30 16:00:41.899  3280  3280 D PanService: Received start request. Starting profile...
08-30 16:00:41.899  3280  3280 D PanService: start()
08-30 16:00:41.899  3280  3280 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 16:00:41.899  3280  3280 I bluedroid: get_profile_interface pan
08-30 16:00:41.899  3280  3280 D PanService: mStartError = false
08-30 16:00:41.899  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
08-30 16:00:41.899  3280  3280 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-30 16:00:41.899  3280  7819 D HeadsetStateMachine: Disconnected process message: 11
08-30 16:00:41.899  3280  3280 D BluetoothMapService: Received start request. Starting profile...
08-30 16:00:41.899  3280  3280 D BluetoothMapService: start()
,08-30 16:00:41.899  3280  3280 D BluetoothMapService: mStartError = false
08-30 16:00:41.899  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
,08-30 16:00:41.899  3280  3280 D SapService: Received start request. Starting profile...
08-30 16:00:41.899  3280  3280 D SapService: start()
08-30 16:00:41.899  3280  3280 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-30 16:00:41.899  3280  3280 I bluedroid: get_profile_interface sap
08-30 16:00:41.899  3280  3280 D SapService: mStartError = false
08-30 16:00:41.899  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
08-30 16:00:41.909  3280  3280 D HeadsetPhoneState: sendDeviceDataStateChanged
08-30 16:00:41.909  3280  3280 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-30 16:00:41.909  3280  3280 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-30 16:00:41.909  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-30 16:00:41.909  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-30 16:00:41.909  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-30 16:00:41.909  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-30 16:00:41.909  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-30 16:00:41.909  3280  7819 D HeadsetStateMachine: Disconnected process message: 18
08-30 16:00:41.909  3280  7819 D HeadsetStateMachine: Disconnected process message: 10
08-30 16:00:41.909  3280  7819 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 16:00:41.909  3280  7819 D HeadsetStateMachine: Disconnected process message: 11
,08-30 16:00:41.909  3280  7829 D BluetoothMediaBrowser: no now playing list
08-30 16:00:41.909  3280  7829 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-30 16:00:41.919  7820  7820 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-30 16:00:41.919  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-30 16:00:41.919  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-30 16:00:41.929  3280  3354 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-30 16:00:41.929  3280  3354 I bluedroid: enable
,08-30 16:00:41.929  3280  3358 E bt-btif : Calling BTA_HhEnable
,08-30 16:00:41.929  3280  3358 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-30 16:00:41.929  3280  3358 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-30 16:00:41.939  3280  3358 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
08-30 16:00:41.939  3280  3358 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
,08-30 16:00:41.939  3280  3358 E BluetoothServiceJni: populateRssiValuesNative
08-30 16:00:41.939  3280  3358 I bluedroid: getModelRssiValues
08-30 16:00:41.939  3280  3358 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-30 16:00:41.939  3280  3358 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-30 16:00:41.939  1020  1020 D SettingsProvider: name = bluetooth_name
,08-30 16:00:41.939  3280  3358 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-30 16:00:41.939  3280  3358 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-30 16:00:41.939  3280  3358 D BluetoothAdapterProperties: Scan Mode:20
08-30 16:00:41.939  3280  3358 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 16:00:41.939  3280  3358 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-30 16:00:41.939  3280  3358 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-30 16:00:41.939  3280  3358 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-30 16:00:41.939  3280  3358 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-30 16:00:41.939  3280  3358 E bt-btif : JVenable fails
,08-30 16:00:41.939  3280  3358 D bte_conf: Device ID record 1 : primary
,08-30 16:00:41.939  3280  3358 D bte_conf:   vendorId            = 0075
08-30 16:00:41.939  3280  3358 D bte_conf:   vendorIdSource      = 0001
08-30 16:00:41.939  3280  3358 D bte_conf:   product             = 0100
,08-30 16:00:41.939  3280  3358 D bte_conf:   version             = 0200
08-30 16:00:41.949  3280  3358 D bte_conf:   clientExecutableURL = 
08-30 16:00:41.949  3280  3358 D bte_conf:   serviceDescription  = 
08-30 16:00:41.949  3280  3358 D bte_conf:   documentationURL    = 
08-30 16:00:41.949  3280  3358 D bte_conf: bte_load_did_conf no section named DID2.
08-30 16:00:41.949  3280  3358 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-30 16:00:41.949  3280  3358 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 16:00:41.949  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:41.949  3280  3354 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 16:00:41.949  3280  3354 D BluetoothAdapterProperties: ScanMode =  20
08-30 16:00:41.949  3280  3354 D BluetoothAdapterProperties: State =  11
,08-30 16:00:41.949  1020  1465 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-30 16:00:41.949  3280  3354 D BluetoothAdapterProperties: Setting state to 12
08-30 16:00:41.949  3280  3354 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 16:00:41.949  3280  3358 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-30 16:00:41.949  3280  3358 D BluetoothAdapterProperties: Scan Mode:21
08-30 16:00:41.949  3280  3358 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 16:00:41.949  1020  1493 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-30 16:00:41.949  1020  1493 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 16:00:41.949  1020  1493 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 16:00:41.949  1020  1493 D SettingsProvider: selectionArgs: false
,08-30 16:00:41.949  1020  1493 D SettingsProvider: selectionArgs: 1002
08-30 16:00:41.949  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:41.949  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:41.949  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:41.949  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:00:41.949  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:41.949  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:41.949  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:41.949  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:00:41.949  1020  1493 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 16:00:41.949  1020  1493 D SettingsProvider: ret = -1
,08-30 16:00:41.949  3280  3354 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-30 16:00:41.949  3280  3354 D BluetoothAdapterService: updateAdapterState state is 12
,08-30 16:00:41.959  1020  1438 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 16:00:41.959  1020  1438 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 16:00:41.959  1020  1438 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:41.959  1020  1438 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:41.959  1020  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:41.959  4748  4769 D BluetoothPan: Binding service...
,08-30 16:00:41.959  7820  7820 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-30 16:00:41.959  7820  7820 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-30 16:00:41.959  7820  7820 D UserAnalysis: Create SecureDbHelper
,08-30 16:00:41.959  3280  3354 D BluetoothAdapterService: Autoconnection is available 
08-30 16:00:41.959  1020  4405 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 16:00:41.959  3280  3354 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-30 16:00:41.959  1020  4405 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-30 16:00:41.959  3280  3354 D BluetoothAdapterService: starting service from this receiver
08-30 16:00:41.959  7084  7084 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:00:41.969  1020  4405 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:41.969  1020  4405 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:41.969  1020  4405 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:41.969  3280  3354 I BluetoothAdapterState: Entering On State from state = 11
,08-30 16:00:41.969  3280  3280 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-30 16:00:41.969  3280  3280 I BluetoothPbapService: Handler(): got msg=1
,08-30 16:00:41.969  1020  1438 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-30 16:00:41.969  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan,
08-30 16:00:41.969  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 16:00:41.979  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:41.979  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:41.979  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:41.979  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:41.979  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:41.979  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:41.979  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:00:41.979  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:41.979  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:41.979  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:41.979  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:00:41.979  3280  7842 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-30 16:00:41.979  7820  7820 D IntelligenceServiceApplication: onCreate()
,08-30 16:00:41.979  4748  7759 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 16:00:41.979  1020  1359 I ActivityManager: Killing 7336:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-30 16:00:41.979  7084  7084 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:00:41.989  3280  7842 D BluetoothSocket: bindListen(): myUserId = 0
08-30 16:00:41.989  3280  7842 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:00:41.989  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:41.989  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 16:00:41.989  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 16:00:41.989  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:41.989  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:41.989  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:41.989  4748  7759 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 16:00:41.989  7820  7820 D IntelligenceServiceApplication: no applications having user consent for prediction
08-30 16:00:41.989  7084  7097 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 16:00:41.989  7084  7097 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 16:00:41.989  3280  7842 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-30 16:00:41.989  3280  7842 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 16:00:41.989  3280  7842 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 16:00:41.989  3280  7842 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c22f36a
08-30 16:00:41.989  3280  7842 D BluetoothSocket: channel: 19
08-30 16:00:41.989  3280  7842 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-30 16:00:41.989  4748  4748 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 16:00:41.989  4748  4748 D PanProfile: Bluetooth service connected
08-30 16:00:41.989  1455  1482 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 16:00:41.989  1455  1482 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 16:00:41.989  1020  1049 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-30 16:00:41.989  1020  1507 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-30 16:00:41.989  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 16:00:41.999  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-30 16:00:41.999  1020  1049 E BluetoothHeadset: BluetoothHeadset service is binded
08-30 16:00:41.999  1750  1764 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 16:00:41.999  1750  1764 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 16:00:41.999  4748  4748 D HeadsetProfile: Bluetooth service connected
,08-30 16:00:41.999  1441  7342 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 16:00:41.999  1020  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 16:00:41.999  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 16:00:41.999  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:41.999  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:41.999  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-30 16:00:41.999  7820  7820 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-30 16:00:41.999  1441  7342 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 16:00:41.999  4748  4762 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 16:00:41.999  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-30 16:00:42.009  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 16:00:42.009  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:42.009  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:42.009  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-30 16:00:42.009  1020  1049 D BluetoothPan: Binding service...
,08-30 16:00:42.009  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-30 16:00:42.009  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 16:00:42.009  1020  1020 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 16:00:42.009  3280  3293 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 16:00:42.009  4748  4748 D BluetoothMap: Proxy object connected
08-30 16:00:42.009  4748  4748 D MapProfile: Bluetooth service connected
08-30 16:00:42.009  4748  4748 D BluetoothMap: getConnectedDevices()
,08-30 16:00:42.009  3280  3293 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 16:00:42.009  1020  1049 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 16:00:42.009  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 16:00:42.009  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:42.009  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:42.009  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:42.009  3280  3280 D BluetoothA2dp: Proxy object connected
08-30 16:00:42.009  3280  3280 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-30 16:00:42.009  4748  4769 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 16:00:42.009  4748  4769 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-30 16:00:42.009  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 16:00:42.009  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 16:00:42.019  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:42.019  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:42.019  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-30 16:00:42.019  4748  4748 D BluetoothA2dp: Proxy object connected
08-30 16:00:42.019  4748  4748 D A2dpProfile: Bluetooth service connected
08-30 16:00:42.019  4748  7759 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 16:00:42.019  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-30 16:00:42.019  7820  7820 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
08-30 16:00:42.019  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 16:00:42.019  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:42.019  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:42.019  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:42.019  1181  3353 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 16:00:42.019  1181  3353 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 16:00:42.019  1441  1454 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 16:00:42.019  1441  1454 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 16:00:42.019  1020  1049 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-30 16:00:42.019  4748  4748 D BluetoothPbap: Proxy object connected
08-30 16:00:42.019  4748  4748 D PbapServerProfile: Bluetooth service connected
,08-30 16:00:42.029  1020  1049 E BluetoothManagerService: Unable to call onBluetoothStateChange() on callback #14
08-30 16:00:42.029  1020  1049 E BluetoothManagerService: android.os.TransactionTooLargeException
08-30 16:00:42.029  1020  1049 E BluetoothManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 16:00:42.029  1020  1049 E BluetoothManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 16:00:42.029  1020  1049 E BluetoothManagerService: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub$Proxy.onBluetoothStateChange(IBluetoothStateChangeCallback.java:84)
08-30 16:00:42.029  1020  1049 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:1053)
08-30 16:00:42.029  1020  1049 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2007)
08-30 16:00:42.029  1020  1049 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
08-30 16:00:42.029  1020  1049 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1576)
08-30 16:00:42.029  1020  1049 E BluetoothManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:00:42.029  1020  1049 E BluetoothManagerService: 	at android.os.Looper.loop(Looper.java:145)
08-30 16:00:42.029  1020  1049 E BluetoothManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 16:00:42.029  1020  1049 E BluetoothManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-30 16:00:42.029  1684  2204 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 16:00:42.029  1684  2204 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 16:00:42.029  3280  3293 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 16:00:42.029  3280  3293 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 16:00:42.029  4748  7759 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 16:00:42.029  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-30 16:00:42.029  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 16:00:42.029  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:42.039  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 16:00:42.039  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:42.039  1472  1652 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 16:00:42.039  1472  1652 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 16:00:42.039  1020  1049 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 16:00:42.039  1020  1049 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 16:00:42.039  4748  4748 D BluetoothInputDevice: Proxy object connected
08-30 16:00:42.039  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 16:00:42.039  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-30 16:00:42.039  4748  4748 D HidProfile: Bluetooth service connected
08-30 16:00:42.039  1020  1020 D BluetoothA2dp: Proxy object connected
,08-30 16:00:42.039  1472  1996 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 16:00:42.039  1020  1049 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 16:00:42.039  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 16:00:42.039  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:42.039  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 16:00:42.039  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:42.039  1472  1996 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 16:00:42.049  4748  4762 D Bluetoothsap: onBluetoothStateChange: up=true
08-30 16:00:42.049  4748  4762 D Bluetoothsap: Binding service...
,08-30 16:00:42.049  4748  4762 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-30 16:00:42.049  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-30 16:00:42.049  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 16:00:42.049  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:42.049  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:42.049  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:42.049  4748  4762 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-30 16:00:42.049  1441  7342 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 16:00:42.049  4748  4748 D Bluetoothsap: BluetoothSAP Proxy object connected
08-30 16:00:42.049  4748  4748 D SapProfile: Bluetooth service connected
08-30 16:00:42.049  4748  4748 D Bluetoothsap: getConnectedDevices()
08-30 16:00:42.049  1020  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 16:00:42.049  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 16:00:42.059  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:42.059  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:42.059  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:42.059  1441  7342 E BluetoothHeadset: BluetoothHeadset service is binded,
,08-30 16:00:42.059  1441  1454 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 16:00:42.059  1020  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 16:00:42.059  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 16:00:42.059  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:42.059  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:42.059  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:42.059  1441  1454 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 16:00:42.059  1020  1049 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 16:00:42.059  1020  1049 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 16:00:42.059  4748  4769 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 16:00:42.059  4748  4769 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 16:00:42.059  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-30 16:00:42.059  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-30 16:00:42.059  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
08-30 16:00:42.059  1020  1020 I InputMethodManagerService: [BT Setting State] State =12
08-30 16:00:42.059  1020  1020 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-30 16:00:42.069  1181  1181 D BluetoothTile:  onBluetoothStateChange:
,08-30 16:00:42.069  1181  1181 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-30 16:00:42.069  1441  1441 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@11ea75b4, true
,08-30 16:00:42.069  1181  1181 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:00:42.069  1181  1181 D BluetoothTile:  getBluetoothState : 12
,08-30 16:00:42.069  1441  1441 D BluetoothHeadset: registerMessageListener
,08-30 16:00:42.069  1181  1781 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 16:00:42.079  1181  1781 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 16:00:42.079  1915  1915 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 16:00:42.079  4748  4748 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:00:42.079  1181  1781 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 16:00:42.089  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:42.089  3280  3417 D HeadsetService: registerMessageListener
,08-30 16:00:42.089  1020  1465 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 16:00:42.089  1020  1492 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-30 16:00:42.089  3280  3417 D HeadsetService: registerMessageListener
,08-30 16:00:42.089  3280  7819 D HeadsetStateMachine: Disconnected process message: 70
,08-30 16:00:42.089  1441  1441 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-30 16:00:42.089  1441  1441 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-30 16:00:42.099  3280  7819 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@f08205b
,08-30 16:00:42.099  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 16:00:42.099  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:00:42.099  4748  4748 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-30 16:00:42.099  4748  4748 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
,08-30 16:00:42.099  4748  4748 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-30 16:00:42.099  1441  1441 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-30 16:00:42.099  1441  1441 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-30 16:00:42.099  4748  4748 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-30 16:00:42.099  1441  1441 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-30 16:00:42.099  3280  7819 D HeadsetStateMachine: Disconnected process message: 9
,08-30 16:00:42.099  3280  7819 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-30 16:00:42.099  3280  7844 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-30 16:00:42.109   283   283 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-30 16:00:42.109   283   283 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-30 16:00:42.109   283   283 V voice   : voice_set_parameters: exit with code(-2)
08-30 16:00:42.109   283   283 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
,08-30 16:00:42.109   283   283 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-30 16:00:42.109   283   283 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-30 16:00:42.109   283   283 V audio_hw_primary: adev_set_parameters: exit
08-30 16:00:42.109  3280  7844 D BluetoothSocket: bindListen(): myUserId = 0
08-30 16:00:42.109  3280  7819 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
08-30 16:00:42.109  3280  7844 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 16:00:42.109  3280  7844 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-30 16:00:42.109  3280  7844 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 16:00:42.109  3280  7844 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 16:00:42.109  3280  7844 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1b3b0f8
,08-30 16:00:42.109  3280  7844 D BluetoothSocket: channel: 5
,08-30 16:00:42.109  4748  4748 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 16:00:42.109  1020  1220 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-30 16:00:42.109  1020  1220 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 16:00:42.109  1020  1220 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:42.109  1020  1220 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:42.109  1020  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 16:00:42.119  4748  4748 D DockEventReceiver: finishStartingService: stopping service
,08-30 16:00:42.119  1684  1684 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:00:42.119  4748  4748 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 16:00:42.129  1181  1181 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:00:42.129  1181  1181 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-30 16:00:42.139  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
,08-30 16:00:42.139  3280  3280 D BtConfig.SecureMode: isSecureModeOn:false
,08-30 16:00:42.139  1020  3784 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 16:00:42.139  1020  3784 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-30 16:00:42.139  1020  3784 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:42.139  1020  3784 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:42.139  1020  3784 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:42.149  1020  1359 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-30 16:00:42.149  1020  1359 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:42.149  1020  1359 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:42.149  1020  1359 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:42.149  1020  1359 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:42.159  7847  7847 E Zygote  : MountEmulatedStorage()
08-30 16:00:42.159  7847  7847 I libpersona: KNOX_SDCARD checking this for 10105
08-30 16:00:42.159  7847  7847 E Zygote  : v2
08-30 16:00:42.159  1020  1359 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7847 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-30 16:00:42.159  7847  7847 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 16:00:42.159  7847  7847 I libpersona: KNOX_SDCARD not a persona
,08-30 16:00:42.159  1020  1438 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-30 16:00:42.169  7847  7847 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 16:00:42.169  7847  7847 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 16:00:42.169  3280  7855 D BluetoothSocket: bindListen(): myUserId = 0
08-30 16:00:42.169  3280  7855 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 16:00:42.169  3280  7855 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
08-30 16:00:42.169  3280  7855 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 16:00:42.169  3280  7855 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 16:00:42.169  3280  7855 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@deee4a4
,08-30 16:00:42.169  3280  7855 D BluetoothSocket: channel: 12
08-30 16:00:42.169  3280  7855 I BtOppRfcommListener: Accept thread started.
,08-30 16:00:42.189  7847  7847 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 16:00:42.189  7847  7847 D ActivityThread: Added TimaKeyStore provider
,08-30 16:00:42.309   257   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-30 16:00:42.309   257   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 16:00:42.319  7847  7868 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-30 16:00:42.329   257   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-30 16:00:42.329   257   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 16:00:42.329  7847  7868 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-30 16:00:42.369  1020  3442 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 16:00:42.479  7847  7847 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-30 16:00:42.479  7847  7847 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-30 16:00:42.479  7847  7847 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-30 16:00:42.479  7847  7847 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.q.e.b(PG:170)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 16:00:42.479  7847  7847 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177,)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.q.k.d(PG:583)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.q.e.b(PG:170)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 16:00:42.479  7847  7847 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.m,ap.m.q.a(PG:8698)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 16:00:42.479  7847  7847 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 16:00:42.479  7847  7847 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 16:00:42.479  7847  7847 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 16:00:42.479  1020  1507 I ActivityManager: Killing 7456:com.sec.pcw.device/1000 (adj 15): empty #21
,08-30 16:00:42.549  7847  7878 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 16:00:42.569  1020  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 16:00:42.569  1020  1492 W ActivityManager: userId = 0, bbcId = -10000,
,08-30 16:00:42.569  1020  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 16:00:42.569  1020  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-30 16:00:43.179   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 16:00:44.169   288   288 E SMD     : DCD OFF
,08-30 16:00:44.189   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 16:00:44.739  7084  7295 D BluetoothAdapter: disable(),
,08-30 16:00:44.739  1020  3781 D SettingsProvider: name = bluetooth_on
,08-30 16:00:44.749  3280  3354 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF,
08-30 16:00:44.749  1020  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 16:00:44.749  3280  3354 D BluetoothAdapterProperties: Setting state to 13
08-30 16:00:44.749  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-30 16:00:44.749  3280  3354 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 16:00:44.749  3280  3354 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 16:00:44.749  3280  3354 D BluetoothAdapterService: updateAdapterState state is 13
,08-30 16:00:44.749  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:44.749  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:44.749  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 16:00:44.749  3280  3354 D BluetoothAdapterService: Autoconnection is available 
08-30 16:00:44.749  3280  3354 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-30 16:00:44.749  3280  3354 D BluetoothAdapterService: terminating service from this receiver,
08-30 16:00:44.749  3280  3280 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-30 16:00:44.749  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 16:00:44.749  1020  1020 I InputMethodManagerService: [BT Setting State] State =13
,08-30 16:00:44.749  3280  3280 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3339820d, channel: 19, state: LISTENING
08-30 16:00:44.749  3280  3280 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3339820d, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c22f36a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@382a85c2mSocket: android.net.LocalSocket@14e83fd3 impl:android.net.LocalSocketImpl@1a87a710 fd:FileDescriptor[80]
08-30 16:00:44.749  3280  3280 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@14e83fd3 impl:android.net.LocalSocketImpl@1a87a710 fd:FileDescriptor[80]
,08-30 16:00:44.759  1181  1181 D BluetoothTile:  onBluetoothStateChange:
,08-30 16:00:44.759  1181  1181 D BluetoothTile:  onBluetoothPairedDevicesChanged:,
08-30 16:00:44.759  1181  1181 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:00:44.759  1181  1181 D BluetoothTile:  getBluetoothState : 13
,08-30 16:00:44.759  1181  1781 D BluetoothTile:  handleUpdatestate:false name:null
08-30 16:00:44.759  1181  1781 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 16:00:44.759  1915  1915 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
08-30 16:00:44.759  1181  1781 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-30 16:00:44.769  1020  1033 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 16:00:44.769  1020  4405 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 16:00:44.769  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ),
,08-30 16:00:44.769  4748  4748 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:00:44.779  7084  7084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:00:44.779  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:44.779  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:44.779  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:44.779  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:00:44.779  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:00:44.779  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:44.779  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:44.779  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:00:44.779  7084  7084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:00:44.779  7084  7084 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:00:44.779  1020  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-30 16:00:44.779  1020  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:44.779  1020  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:44.779  1020  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:44.779  3280  3354 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 16:00:44.779  4748  4748 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 16:00:44.779  3280  3354 D BluetoothAdapterProperties: mDiscovering is false
,08-30 16:00:44.789  7084  7084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:00:44.789  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:44.789  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:44.789  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:44.789  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:00:44.789  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:00:44.789  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:44.789  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:44.789  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:00:44.789  1020  3784 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-30 16:00:44.789  1020  4405 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-30 16:00:44.789  1020  4405 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 16:00:44.789  3280  3354 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-30 16:00:44.789  1020  4405 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:44.789  1020  4405 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:44.789  1020  4405 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 16:00:44.789  4748  4748 D BluetoothPbap: Proxy object disconnected
,08-30 16:00:44.789  4748  4748 D PbapServerProfile: Bluetooth service disconnected
,08-30 16:00:44.799  7084  7084 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:00:44.799  3280  3358 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-30 16:00:44.799  3280  3358 D BluetoothAdapterProperties: Scan Mode:20
,08-30 16:00:44.799  7084  7084 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:00:44.799  1684  1684 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:00:44.799  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:44.809  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:44.809  3280  3354 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 16:00:44.809  3280  3354 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-30 16:00:44.809  3280  3354 E bt-btif : cmd socket is not created
,08-30 16:00:44.809  4748  4748 D DockEventReceiver: finishStartingService: stopping service
08-30 16:00:44.809  3280  3354 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 16:00:44.809  3280  3361 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-30 16:00:44.809  3280  7855 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-30 16:00:44.819  3280  3280 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@27093209, channel: 5, state: LISTENING
08-30 16:00:44.819  3280  3280 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@27093209, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1b3b0f8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@281f3c0emSocket: android.net.LocalSocket@1a6d062f impl:android.net.LocalSocketImpl@2fa8243c fd:FileDescriptor[82]
08-30 16:00:44.819  3280  3280 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1a6d062f impl:android.net.LocalSocketImpl@2fa8243c fd:FileDescriptor[82]
,08-30 16:00:44.819  3280  3280 I BtOppRfcommListener: stopping Accept Thread
08-30 16:00:44.819  3280  3280 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@809e5c5, channel: 12, state: LISTENING
08-30 16:00:44.819  3280  3280 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@809e5c5, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@deee4a4, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2b970b1amSocket: android.net.LocalSocket@4cdd64b impl:android.net.LocalSocketImpl@bf14828 fd:FileDescriptor[86]
08-30 16:00:44.819  3280  3280 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@4cdd64b impl:android.net.LocalSocketImpl@bf14828 fd:FileDescriptor[86]
08-30 16:00:44.819  3280  7855 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-30 16:00:44.819  3280  3361 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 16:00:44.819  3280  3361 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:00:44.819  3280  3361 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 16:00:44.819  3280  3361 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 16:00:44.819  3280  3361 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:00:44.819  3280  3361 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-30 16:00:44.819  4748  4748 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 16:00:44.829  3280  3280 V BluetoothOppManager: cleanUp...
,08-30 16:00:44.829  1181  1181 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:00:44.829  1181  1181 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-30 16:00:45.019  3280  3354 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-30 16:00:45.019  3280  3354 D BtConfig.SecureMode: isSecureModeOn:false
,08-30 16:00:45.019  3280  3354 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-30 16:00:45.019  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-30 16:00:45.019  3280  3354 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
,08-30 16:00:45.019  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,08-30 16:00:45.019  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-30 16:00:45.019  3280  3354 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService,
,08-30 16:00:45.019  1020  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
,08-30 16:00:45.019  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-30 16:00:45.019  1020  1032 W ActivityManager: userId = 0, bbcId = -10000,
,08-30 16:00:45.019  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:45.019  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,08-30 16:00:45.019  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-30 16:00:45.019  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-30 16:00:45.019  3280  3354 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-30 16:00:45.029  1020  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 16:00:45.029  1020  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-30 16:00:45.029  3280  3280 D HeadsetService: Received stop request...Stopping profile...
08-30 16:00:45.029  1020  1492 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:45.029  1020  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:45.029  1020  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:45.029  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-30 16:00:45.029  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
08-30 16:00:45.029  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 16:00:45.029  3280  3354 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-30 16:00:45.029  1020  1438 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 16:00:45.029  1020  1438 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 16:00:45.029  1020  1020 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 16:00:45.029  1020  1438 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:45.029  1020  1438 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:45.029  1020  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:45.029  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-30 16:00:45.029  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 16:00:45.029  3280  3354 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-30 16:00:45.029  1020  1033 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 16:00:45.029  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-30 16:00:45.029  4748  4748 D HeadsetProfile: Bluetooth service disconnected
,08-30 16:00:45.039  3280  3280 D A2dpService: Received stop request...Stopping profile...
,08-30 16:00:45.039  3280  7836 D A2dpStateMachine: Exit Disconnected: -1
08-30 16:00:45.039  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:45.039  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 16:00:45.039  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:45.039  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,08-30 16:00:45.039  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-30 16:00:45.039  3280  3354 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-30 16:00:45.039  1020  4405 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 16:00:45.039  1020  4405 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 16:00:45.039  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
,08-30 16:00:45.039  1020  4405 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:45.039  1020  4405 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:45.039  1020  4405 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:45.039  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-30 16:00:45.039  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 16:00:45.039  3280  3354 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-30 16:00:45.039  1020  1020 D BluetoothA2dp: Proxy object disconnected
08-30 16:00:45.039  1020  1020 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 16:00:45.039  1020  1359 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 16:00:45.039  1020  1359 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 16:00:45.049  4748  4748 D BluetoothA2dp: Proxy object disconnected
08-30 16:00:45.049  4748  4748 D A2dpProfile: Bluetooth service disconnected
08-30 16:00:45.049  1020  1359 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:45.049  1020  1359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:45.049  1020  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:45.049  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,08-30 16:00:45.049  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-30 16:00:45.049  3280  3354 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-30 16:00:45.049  1020  3781 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 16:00:45.049  1020  3781 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 16:00:45.049  1020  3781 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:45.049  1020  3781 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:45.049  1020  3781 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:45.049  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 16:00:45.049  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 16:00:45.049  3280  3354 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-30 16:00:45.049  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-30 16:00:45.049  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-30 16:00:45.049  3280  3354 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-30 16:00:45.049  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
,08-30 16:00:45.049  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 16:00:45.049  3280  3354 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,08-30 16:00:45.049  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-30 16:00:45.059  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-30 16:00:45.059  3280  3354 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-30 16:00:45.059  3280  3354 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-30 16:00:45.059  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-30 16:00:45.059  3280  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 16:00:45.059  3280  3280 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-30 16:00:45.059  3280  3280 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-30 16:00:45.059  3280  3280 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-30 16:00:45.059  3280  3280 D HidService: Received stop request...Stopping profile...
,08-30 16:00:45.059  3280  3280 D HidService: Stopping Bluetooth HidService
08-30 16:00:45.059  3280  3280 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-30 16:00:45.059  3280  3280 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-30 16:00:45.059  3280  3280 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-30 16:00:45.059  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
,08-30 16:00:45.069  3280  3280 D HealthService: Received stop request...Stopping profile...
08-30 16:00:45.069  4748  4748 D BluetoothInputDevice: Proxy object disconnected
08-30 16:00:45.069  4748  4748 D HidProfile: Bluetooth service disconnected
08-30 16:00:45.069  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
,08-30 16:00:45.069  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-30 16:00:45.069  3280  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-30 16:00:45.069  3280  3280 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-30 16:00:45.069  3280  3280 D PanService: Received stop request...Stopping profile...
,08-30 16:00:45.069  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
,08-30 16:00:45.069  1020  1020 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-30 16:00:45.069  3280  3280 D BluetoothA2dp: Proxy object disconnected
,08-30 16:00:45.069  3280  3280 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-30 16:00:45.069  3280  7837 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 16:00:45.069  3280  3280 I GKI_LINUX: GKI_exit_task 2 done
08-30 16:00:45.069  3280  3280 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-30 16:00:45.069  4748  4748 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 16:00:45.069  4748  4748 D PanProfile: Bluetooth service disconnected
,08-30 16:00:45.079  3280  3280 D BluetoothMapService: Received stop request...Stopping profile...
,08-30 16:00:45.079  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
,08-30 16:00:45.079  3280  3280 D SapService: Received stop request...Stopping profile...
,08-30 16:00:45.079  3280  3280 D SapService: Stopping Bluetooth SapService
08-30 16:00:45.079  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
,08-30 16:00:45.079  4748  4748 D BluetoothMap: Proxy object disconnected
08-30 16:00:45.079  4748  4748 D MapProfile: Bluetooth service disconnected
,08-30 16:00:45.079  4748  4748 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-30 16:00:45.079  4748  4748 D SapProfile: Bluetooth service disconnected
,08-30 16:00:45.079  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,08-30 16:00:45.079  3280  3280 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-30 16:00:45.079  3280  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 16:00:45.079  3280  3280 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-30 16:00:45.089  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
,08-30 16:00:45.089  3280  3280 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-30 16:00:45.089  3280  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-30 16:00:45.089  3280  3280 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 16:00:45.089  3280  3280 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-30 16:00:45.089  3280  3280 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-30 16:00:45.089  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
,08-30 16:00:45.089  3280  3280 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-30 16:00:45.089  3280  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 16:00:45.089  3280  3280 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-30 16:00:45.089  3280  3280 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 16:00:45.089  3280  3280 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-30 16:00:45.089  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true,
08-30 16:00:45.089  3280  3280 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-30 16:00:45.089  3280  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 16:00:45.089  3280  3280 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-30 16:00:45.089  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-30 16:00:45.089  3280  3280 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-30 16:00:45.089  3280  3280 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-30 16:00:45.089  3280  3280 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-30 16:00:45.089  3280  3354 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-30 16:00:45.089  3280  3354 D BluetoothAdapterProperties: Setting state to 10
08-30 16:00:45.089  3280  3354 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-30 16:00:45.089  3280  3354 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 16:00:45.099  3280  3354 D BluetoothAdapterService: updateAdapterState state is 10
,08-30 16:00:45.099  3280  3354 D BluetoothAdapterService: Autoconnection is available 
08-30 16:00:45.099  3280  3354 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-30 16:00:45.099  3280  3354 I BluetoothAdapterState: Entering OffState
,08-30 16:00:45.099  7084  7097 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 16:00:45.099  7084  7097 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 16:00:45.099  7084  7097 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-30 16:00:45.099  7084  7097 D BluetoothLeAdvertiser: Exit stop advertising
08-30 16:00:45.099  7084  7097 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-30 16:00:45.099  7084  7097 D BluetoothLeScanner: Exiting stopAllScan
,08-30 16:00:45.099  1455  1486 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 16:00:45.099  1455  1486 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 16:00:45.099  1750  1761 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 16:00:45.099  1750  1761 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 16:00:45.099  4748  7759 D BluetoothMap: onBluetoothStateChange: up=false
,08-30 16:00:45.099  3280  3293 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 16:00:45.109  4748  4762 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 16:00:45.109  4748  4769 D BluetoothPbap: onBluetoothStateChange: up=false
,08-30 16:00:45.109  1181  1191 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 16:00:45.109  1181  1191 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 16:00:45.109  1441  1467 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 16:00:45.109  1441  1467 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 16:00:45.109  1684  2204 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 16:00:45.109  1684  2204 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 16:00:45.109  3280  3290 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 16:00:45.109  3280  3290 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 16:00:45.109  7847  7862 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 16:00:45.109  7847  7862 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 16:00:45.109  4748  7759 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-30 16:00:45.109  1472  1491 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 16:00:45.109  1472  1491 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 16:00:45.119  1020  1049 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 16:00:45.119  4748  4762 D Bluetoothsap: onBluetoothStateChange: up=false
,08-30 16:00:45.119  4748  4762 D Bluetoothsap: Unbinding service...
,08-30 16:00:45.119  1020  1049 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 16:00:45.119  1020  1049 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 16:00:45.119  4748  4769 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 16:00:45.119  4748  4769 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 16:00:45.119  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:00:45.119  1020  1020 I InputMethodManagerService: [BT Setting State] State =10
08-30 16:00:45.119  1020  1020 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-30 16:00:45.129  1181  1181 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 16:00:45.129  1181  1181 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:00:45.129  1181  1181 D BluetoothTile:  getBluetoothState : 10
,08-30 16:00:45.129  1020  1032 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 16:00:45.129  1915  1915 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 16:00:45.129  1020  1139 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 16:00:45.129  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 16:00:45.139  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:45.139  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:00:45.139  4748  4748 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:00:45.139  4748  4748 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 16:00:45.139  1020  1494 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-30 16:00:45.139  1020  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 16:00:45.139  1020  1494 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:45.139  1020  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:45.139  1020  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 16:00:45.149  4748  4748 D DockEventReceiver: finishStartingService: stopping service
,08-30 16:00:45.149  1684  1684 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:00:45.149  4748  4748 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 16:00:45.159  1181  1181 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:00:45.159  1181  1181 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-30 16:00:45.179   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 16:00:45.429  1020  1033 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 16:00:45.429  1020  1033 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4240, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
08-30 16:00:45.429  1020  1033 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
08-30 16:00:45.439  1181  1181 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-30 16:00:45.429  1020  1033 D BatteryService: stay LED for charging
08-30 16:00:45.439  1181  1181 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 16:00:45.429  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 16:00:45.439  1020  1020 I MotionRecognitionService: Plugged
08-30 16:00:45.439  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
08-30 16:00:45.439  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-30 16:00:45.439  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,08-30 16:00:45.469  1181  1181 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-30 16:00:45.469  1181  1181 D SViewCoverView: level :99 plugged : 2
,08-30 16:00:45.469  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2,
,08-30 16:00:45.469  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,08-30 16:00:45.469  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,08-30 16:00:46.189   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 16:00:47.169   288   288 E SMD     : DCD OFF,
,08-30 16:00:47.189   318   318 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 16:00:47.749  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 16:00:47.749  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:48.189   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-30 16:00:48.849  1020  1098 V AlarmManager: waitForAlarm result :4
,08-30 16:00:48.849   278   959 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,08-30 16:00:48.849   278   959 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-30 16:00:48.869  1020  1045 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:48.869  1020  1045 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 16:00:48.869  1020  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-30 16:00:50.169   288   288 E SMD     : DCD OFF,
,08-30 16:00:50.749  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-30 16:00:50.749  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ef90f77 added. We now have 6 listener(s)
,08-30 16:00:50.749  7084  7295 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:00:50.749  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:00:50.749  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1fcc07e4 added. We now have 7 listener(s),
08-30 16:00:50.749  7084  7295 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:00:50.749  7084  7295 I System.out: IsBluetoothEnabled
,08-30 16:00:50.749  7084  7295 D BluetoothAdapter: disable(),
08-30 16:00:50.759  1020  1033 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-30 16:00:50.759  7084  7295 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:50.759  7084  7295 D BluetoothAdapter: enable()
,08-30 16:00:50.769  1020  1493 W ActivityManager: Permission Denial: getCurrentUser() from pid=7084, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-30 16:00:50.769  1020  1493 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-30 16:00:50.769  1020  1493 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7084, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-30 16:00:50.769  1020  1493 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-30 16:00:50.769  1020  1493 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-30 16:00:50.769  1020  1493 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-30 16:00:50.769  1020  1493 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-30 16:00:50.769  1020  1493 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 16:00:50.769  1020  1493 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 16:00:50.769  1020  1493 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 16:00:50.779  1020  1493 D SettingsProvider: name = bluetooth_on
,08-30 16:00:50.789  1020  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-30 16:00:50.789  1020  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 16:00:50.799  1020  1049 D SecContentProvider: uri = 3 selection = isBluetoothEnabled,
08-30 16:00:50.799  3280  3354 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-30 16:00:50.799  3280  3354 D BluetoothAdapterProperties: Setting state to 11
08-30 16:00:50.799  1020  4405 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 16:00:50.799  3280  3354 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 16:00:50.799  1020  4405 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-30 16:00:50.799  3280  3354 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 16:00:50.799  3280  3354 D BluetoothAdapterService: updateAdapterState state is 11
08-30 16:00:50.799  3280  3354 D BluetoothAdapterService: Autoconnection is available 
,08-30 16:00:50.799  3280  3354 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-30 16:00:50.799  3280  3354 D BtConfig.SecureMode: isSecureModeOn:false
08-30 16:00:50.799  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-30 16:00:50.799  3280  3354 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-30 16:00:50.799  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 16:00:50.799  3280  3354 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-30 16:00:50.799  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-30 16:00:50.799  3280  3354 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-30 16:00:50.799  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 16:00:50.799  3280  3354 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-30 16:00:50.799  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 16:00:50.799  3280  3354 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-30 16:00:50.799  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-30 16:00:50.799  3280  3354 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-30 16:00:50.799  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 16:00:50.799  3280  3354 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-30 16:00:50.799  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 16:00:50.799  3280  3354 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-30 16:00:50.799  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 16:00:50.799  3280  3354 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 16:00:50.799  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 16:00:50.799  3280  3354 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,08-30 16:00:50.799  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 16:00:50.799  3280  3354 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-30 16:00:50.799  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 16:00:50.799  3280  3354 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-30 16:00:50.799  3280  3354 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-30 16:00:50.799  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-30 16:00:50.799  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 16:00:50.799  3280  3354 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-30 16:00:50.799  1020  4405 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:50.799  1020  4405 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:50.799  1020  4405 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 16:00:50.799  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-30 16:00:50.799  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-30 16:00:50.799  3280  3354 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-30 16:00:50.799  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 16:00:50.799  1020  1020 I InputMethodManagerService: [BT Setting State] State =11
,08-30 16:00:50.809  3280  3280 D HeadsetService: Received start request. Starting profile...
,08-30 16:00:50.809  3280  3280 D HeadsetService: start()
08-30 16:00:50.809  3280  3280 D HeadsetStateMachine: make
,08-30 16:00:50.809  3280  3280 E HeadsetStateMachine: # of Max HF connection is 2
,08-30 16:00:50.819  1181  1181 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-30 16:00:50.819  1181  1181 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:00:50.819  1181  1181 D BluetoothTile:  getBluetoothState : 11
,08-30 16:00:50.819  1915  1915 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 16:00:50.829  4748  4748 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:00:50.829  1181  1781 D BluetoothTile:  handleUpdatestate:false name:null
08-30 16:00:50.829  1181  1781 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-30 16:00:50.829  1020  3422 D SSRM:n  : SIOP:: AP = 340
,08-30 16:00:50.829  1020  1220 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 16:00:50.829  1020  1493 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 16:00:50.839  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 16:00:50.839  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:50.839  1020  1507 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-30 16:00:50.839  1020  1507 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 16:00:50.839  1020  1507 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:50.839  1020  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 16:00:50.839  1020  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:50.839  1020  1494 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-30 16:00:50.839  1020  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-30 16:00:50.839  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,08-30 16:00:50.839  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 16:00:50.839  3280  3354 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-30 16:00:50.849  1020  1494 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:50.849  1020  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:50.849  1020  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-30 16:00:50.849  1020  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 16:00:50.849  1020  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 16:00:50.849  1020  1492 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:50.849  1020  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:50.849  1020  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:50.849  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,08-30 16:00:50.849  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 16:00:50.849  3280  3354 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-30 16:00:50.849  1684  1684 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 16:00:50.849  1020  1438 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-30 16:00:50.849  1020  1438 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-30 16:00:50.859  1020  1438 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:50.859  1020  1438 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:50.859  1020  1438 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-30 16:00:50.859  1020  1359 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 16:00:50.859  1020  1359 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-30 16:00:50.859  3280  3280 I bluedroid: get_profile_interface handsfree
,08-30 16:00:50.859  1020  1359 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:50.859  1020  1359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:50.859  1020  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:50.859  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,08-30 16:00:50.859  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-30 16:00:50.859  3280  3354 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-30 16:00:50.869  1020  1220 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 16:00:50.869  1020  1220 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 16:00:50.869  1020  1220 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:50.869  1020  1220 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:50.869  1020  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:50.869  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,08-30 16:00:50.869  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 16:00:50.869  3280  3354 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-30 16:00:50.869  1020  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 16:00:50.869  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 16:00:50.879  3280  3280 E DualScoManager: Dual Sco Manager already instantiated
08-30 16:00:50.879  3280  3280 I DualScoManager: Set HeadsetServiceHelper
08-30 16:00:50.879  4748  4748 D BluetoothNotiBroadcastReceiver: onReceive
08-30 16:00:50.879  3280  3280 D BluetoothAtMessage: createCMTIContentObservers
,08-30 16:00:50.879  1020  1507 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-30 16:00:50.879  1020  1507 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 16:00:50.879  1020  1507 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 16:00:50.879  1020  1507 D SettingsProvider: selectionArgs: false
08-30 16:00:50.879  1020  1507 D SettingsProvider: selectionArgs: 1002
08-30 16:00:50.879  1020  1507 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 16:00:50.879  1020  1507 D SettingsProvider: ret = -1
08-30 16:00:50.879  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:50.879  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:50.879  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:50.879  3280  7895 D HeadsetStateMachine: Enter Disconnected: -2
08-30 16:00:50.879  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-30 16:00:50.879  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-30 16:00:50.879  3280  3354 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-30 16:00:50.879  3280  3280 D HeadsetService: mStartError = false
,08-30 16:00:50.879  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
,08-30 16:00:50.879  3280  3280 D A2dpService: Received start request. Starting profile...
,08-30 16:00:50.879  1020  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 16:00:50.879  3280  3280 D A2dpService: start(),
08-30 16:00:50.879  1020  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-30 16:00:50.879  3280  3280 I bluedroid: get_profile_interface avrcp
08-30 16:00:50.879  1020  1494 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:50.879  1020  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:50.879  1020  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 16:00:50.889  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-30 16:00:50.889  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 16:00:50.889  3280  3354 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-30 16:00:50.889  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-30 16:00:50.889  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 16:00:50.889  3280  3354 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-30 16:00:50.889  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-30 16:00:50.889  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService,
08-30 16:00:50.889  3280  3354 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-30 16:00:50.889  3280  3354 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-30 16:00:50.889  3280  3354 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 16:00:50.889  3280  3354 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-30 16:00:50.889  3280  3354 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 16:00:50.889  3280  7895 D HeadsetStateMachine: Clear mHeadsetBrsf
08-30 16:00:50.889  3280  7895 D HeadsetStateMachine: map size, before remove : 0
08-30 16:00:50.889  3280  7895 D HeadsetStateMachine: map size, after remove: 0
,08-30 16:00:50.889  1181  1181 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:00:50.889  1181  1181 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
08-30 16:00:50.889  3280  3280 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 16:00:50.889  3280  3280 D Avrcp   : Initialize Media Controller
08-30 16:00:50.889  3280  3280 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-30 16:00:50.889  3280  3280 E Avrcp   : getActiveSessions
08-30 16:00:50.889  3280  3280 D Avrcp   : pick active media Controller
08-30 16:00:50.889  3280  3280 D Avrcp   : Get the active Media Controller 
,08-30 16:00:50.899  3280  3280 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-30 16:00:50.899  3280  7896 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-30 16:00:50.899  3280  3280 D A2dpStateMachine: make
,08-30 16:00:50.909  3280  7896 D BluetoothMediaBrowser: no now playing list,
08-30 16:00:50.909  3280  7896 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-30 16:00:50.909  3280  3280 I bluedroid: get_profile_interface a2dp
08-30 16:00:50.909  3280  7898 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-30 16:00:50.909  3280  3280 E bt-btif : warning : media task started media_task_refcnt 1 
08-30 16:00:50.909  3280  3280 D A2dpService: mStartError = false
,08-30 16:00:50.909  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
08-30 16:00:50.909  3280  3280 D HeadsetStateMachine: Try to query the phonestate on bind
08-30 16:00:50.909  3280  7897 D A2dpStateMachine: Enter Disconnected: -2,
08-30 16:00:50.909  1441  7342 I Telecom : BluetoothPhoneService: queryPhoneState
08-30 16:00:50.909  1441  1441 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-30 16:00:50.909  1441  1441 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-30 16:00:50.909  1441  7342 I Telecom : BluetoothPhoneService: Result of Message : true
,08-30 16:00:50.909  3280  3280 D HidService: Received start request. Starting profile...
08-30 16:00:50.909  3280  3280 D HidService: start()
08-30 16:00:50.909  3280  3280 I bluedroid: get_profile_interface hidhost
08-30 16:00:50.909  3280  3280 D HidService: setHidService(): set to: null
08-30 16:00:50.909  3280  3280 D HidService: mStartError = false
08-30 16:00:50.909  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
08-30 16:00:50.909  3280  3280 D HeadsetStateMachine: Proxy object connected
08-30 16:00:50.909  3280  3280 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-30 16:00:50.909  3280  7895 D HeadsetStateMachine: Disconnected process message: 11
,08-30 16:00:50.909  3280  3280 D HealthService: Received start request. Starting profile...
08-30 16:00:50.909  3280  3280 D HealthService: start()
,08-30 16:00:50.919  3280  3280 I bluedroid: get_profile_interface health
08-30 16:00:50.919  3280  3280 D HealthService: mStartError = false
08-30 16:00:50.919  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
,08-30 16:00:50.919  3280  3280 D PanService: Received start request. Starting profile...
08-30 16:00:50.919  3280  3280 D PanService: start()
08-30 16:00:50.919  3280  3280 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 16:00:50.919  3280  3280 I bluedroid: get_profile_interface pan
08-30 16:00:50.919  3280  3280 D PanService: mStartError = false
08-30 16:00:50.919  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
08-30 16:00:50.919  3280  3280 D HeadsetPhoneState: sendDeviceDataStateChanged
08-30 16:00:50.919  3280  3280 D HeadsetPhoneState: Signal level : previous=0 curr=4
,08-30 16:00:50.919  3280  7895 D HeadsetStateMachine: Disconnected process message: 18
,08-30 16:00:50.919  3280  3280 D BluetoothMapService: Received start request. Starting profile...
08-30 16:00:50.919  3280  3280 D BluetoothMapService: start()
,08-30 16:00:50.919  3280  3280 D BluetoothMapService: mStartError = false
08-30 16:00:50.919  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
08-30 16:00:50.919  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-30 16:00:50.919  3280  3280 D SapService: Received start request. Starting profile...
08-30 16:00:50.919  3280  3280 D SapService: start()
08-30 16:00:50.919  3280  3280 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-30 16:00:50.919  3280  3280 I bluedroid: get_profile_interface sap
08-30 16:00:50.919  3280  3280 D SapService: mStartError = false
08-30 16:00:50.919  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
08-30 16:00:50.919  3280  3280 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 16:00:50.919  3280  7895 D HeadsetStateMachine: Disconnected process message: 10
08-30 16:00:50.919  3280  7895 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 16:00:50.919  3280  7895 D HeadsetStateMachine: Disconnected process message: 11
,08-30 16:00:50.919  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-30 16:00:50.919  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-30 16:00:50.919  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-30 16:00:50.919  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-30 16:00:50.939  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-30 16:00:50.939  3280  3280 E BluetoothAdapterService(49133193): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-30 16:00:50.939  3280  3354 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-30 16:00:50.939  3280  3354 I bluedroid: enable
,08-30 16:00:50.949  3280  3358 E bt-btif : Calling BTA_HhEnable
,08-30 16:00:50.949  3280  3358 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-30 16:00:50.949  3280  3358 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-30 16:00:50.949  3280  3358 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
08-30 16:00:50.949  3280  3358 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-30 16:00:50.949  3280  3358 E BluetoothServiceJni: populateRssiValuesNative
08-30 16:00:50.949  3280  3358 I bluedroid: getModelRssiValues
08-30 16:00:50.949  3280  3358 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-30 16:00:50.949  3280  3358 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-30 16:00:50.949  3280  3358 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-30 16:00:50.949  1020  1020 D SettingsProvider: name = bluetooth_name
,08-30 16:00:50.959  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:50.959  3280  3358 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-30 16:00:50.959  3280  3358 D BluetoothAdapterProperties: Scan Mode:20
08-30 16:00:50.959  3280  3358 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 16:00:50.959  3280  3358 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
,08-30 16:00:50.959  3280  3358 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-30 16:00:50.959  3280  3358 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-30 16:00:50.959  3280  3358 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-30 16:00:50.959  3280  3358 E bt-btif : JVenable fails
,08-30 16:00:50.969  3280  3358 D bte_conf: Device ID record 1 : primary
,08-30 16:00:50.969  3280  3358 D bte_conf:   vendorId            = 0075
08-30 16:00:50.969  3280  3358 D bte_conf:   vendorIdSource      = 0001
,08-30 16:00:50.969  3280  3358 D bte_conf:   product             = 0100
,08-30 16:00:50.969  3280  3358 D bte_conf:   version             = 0200
08-30 16:00:50.969  3280  3358 D bte_conf:   clientExecutableURL = 
,08-30 16:00:50.969  3280  3358 D bte_conf:   serviceDescription  = 
08-30 16:00:50.969  3280  3358 D bte_conf:   documentationURL    = 
,08-30 16:00:50.969  3280  3358 D bte_conf: bte_load_did_conf no section named DID2.
,08-30 16:00:50.969  3280  3354 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-30 16:00:50.969  3280  3354 D BluetoothAdapterProperties: ScanMode =  20
,08-30 16:00:50.969  3280  3354 D BluetoothAdapterProperties: State =  11
08-30 16:00:50.969  3280  3358 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-30 16:00:50.969  3280  3358 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 16:00:50.969  1020  1493 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-30 16:00:50.969  3280  3354 D BluetoothAdapterProperties: Setting state to 12
,08-30 16:00:50.969  3280  3354 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 16:00:50.979  3280  3358 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-30 16:00:50.979  3280  3358 D BluetoothAdapterProperties: Scan Mode:21
08-30 16:00:50.979  3280  3358 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 16:00:50.979  1020  4405 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-30 16:00:50.979  1020  4405 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 16:00:50.979  1020  4405 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 16:00:50.979  1020  4405 D SettingsProvider: selectionArgs: false
08-30 16:00:50.979  1020  4405 D SettingsProvider: selectionArgs: 1002
08-30 16:00:50.979  1020  4405 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 16:00:50.979  1020  4405 D SettingsProvider: ret = -1
,08-30 16:00:50.979  3280  3354 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 16:00:50.979  3280  3354 D BluetoothAdapterService: updateAdapterState state is 12
,08-30 16:00:50.979  1020  1507 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 16:00:50.979  1020  1507 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 16:00:50.979  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:50.979  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:50.979  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:50.979  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:00:50.979  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:50.979  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:50.979  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:50.979  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:00:50.989  1020  1507 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:50.989  1020  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:50.989  1020  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:50.989  7084  7084 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:00:50.989  3280  3354 D BluetoothAdapterService: Autoconnection is available 
08-30 16:00:50.989  3280  3354 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-30 16:00:50.989  3280  3354 D BluetoothAdapterService: starting service from this receiver
08-30 16:00:50.989  4748  4762 D BluetoothPan: Binding service...
,08-30 16:00:50.989  1020  1220 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 16:00:50.989  1020  1220 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-30 16:00:50.989  1020  1220 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:50.989  1020  1220 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:50.989  1020  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:50.999  3280  3280 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-30 16:00:50.999  3280  3280 I BluetoothPbapService: Handler(): got msg=1
,08-30 16:00:50.999  3280  3354 I BluetoothAdapterState: Entering On State from state = 11
,08-30 16:00:51.139  1020  1049 I art     : Explicit concurrent mark sweep GC freed 66063(3MB) AllocSpace objects, 10(161KB) LOS objects, 33% free, 22MB/34MB, paused 2.335ms total 143.150ms
08-30 16:00:51.139  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-30 16:00:51.139  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 16:00:51.139  1020  4405 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-30 16:00:51.139  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:51.139  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:51.139  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:51.149  4748  4769 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 16:00:51.149  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 16:00:51.149  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 16:00:51.149  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:51.149  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:51.149  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:51.149  4748  4769 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 16:00:51.149  7084  7098 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 16:00:51.149  7084  7098 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 16:00:51.149  1455  1486 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 16:00:51.149  1455  1486 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 16:00:51.149  1020  1049 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-30 16:00:51.149  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 16:00:51.149  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 16:00:51.149  1020  1049 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 16:00:51.149  3280  7904 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-30 16:00:51.149  1750  1761 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 16:00:51.149  1750  1761 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 16:00:51.159  1441  1467 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 16:00:51.159  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:51.159  1020  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 16:00:51.159  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:51.159  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 16:00:51.159  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-30 16:00:51.159  1441  1467 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 16:00:51.159  4748  4762 D BluetoothMap: onBluetoothStateChange: up=true,
08-30 16:00:51.159  4748  4748 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 16:00:51.159  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-30 16:00:51.159  4748  4748 D PanProfile: Bluetooth service connected
08-30 16:00:51.159  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 16:00:51.159  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:51.159  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:51.159  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:51.169  3280  7904 D BluetoothSocket: bindListen(): myUserId = 0
08-30 16:00:51.169  1020  1049 D BluetoothPan: Binding service...
08-30 16:00:51.169  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-30 16:00:51.169  3280  7904 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 16:00:51.169  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-30 16:00:51.169  3280  3290 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 16:00:51.169  3280  3290 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 16:00:51.169  1020  1049 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 16:00:51.169  3280  7904 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-30 16:00:51.169  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 16:00:51.169  3280  7904 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 16:00:51.169  3280  7904 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 16:00:51.169  3280  7904 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@5c5e59
08-30 16:00:51.169  1020  1020 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 16:00:51.169  4748  4748 D HeadsetProfile: Bluetooth service connected
08-30 16:00:51.169  3280  7904 D BluetoothSocket: channel: 19
08-30 16:00:51.169  3280  7904 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-30 16:00:51.169  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:51.169  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:51.169  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:51.169  4748  4769 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 16:00:51.169  3280  3280 D BluetoothA2dp: Proxy object connected
08-30 16:00:51.169  3280  3280 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-30 16:00:51.169  4748  4748 D BluetoothMap: Proxy object connected
08-30 16:00:51.169  4748  4748 D MapProfile: Bluetooth service connected
08-30 16:00:51.169  4748  4748 D BluetoothMap: getConnectedDevices()
08-30 16:00:51.169  4748  4769 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 16:00:51.169  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 16:00:51.169  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 16:00:51.169  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:51.169  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 16:00:51.169  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:51.179  4748  7759 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 16:00:51.179  4748  4748 D BluetoothA2dp: Proxy object connected
08-30 16:00:51.179  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-30 16:00:51.179  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 16:00:51.179  4748  4748 D A2dpProfile: Bluetooth service connected
08-30 16:00:51.179  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:51.179  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:51.179  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:51.179  1181  1991 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 16:00:51.179  1181  1991 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 16:00:51.179  1441  7342 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 16:00:51.179  1441  7342 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 16:00:51.179  1684  1708 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 16:00:51.179  1684  1708 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 16:00:51.179  3280  7311 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 16:00:51.179  3280  7311 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 16:00:51.179  7847  7864 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 16:00:51.179  7847  7864 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 16:00:51.179  4748  4748 D BluetoothPbap: Proxy object connected
08-30 16:00:51.179  4748  7759 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 16:00:51.179  4748  4748 D PbapServerProfile: Bluetooth service connected
,08-30 16:00:51.189  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-30 16:00:51.189  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 16:00:51.189  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:51.189  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 16:00:51.189  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:51.189  1472  7761 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 16:00:51.189  1472  7761 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 16:00:51.189  4748  4748 D BluetoothInputDevice: Proxy object connected
08-30 16:00:51.189  1020  1049 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 16:00:51.189  1020  1049 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-30 16:00:51.189  4748  4748 D HidProfile: Bluetooth service connected
08-30 16:00:51.189  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 16:00:51.189  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-30 16:00:51.189  1020  1020 D BluetoothA2dp: Proxy object connected
,08-30 16:00:51.189  1472  1652 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 16:00:51.189  1020  1049 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 16:00:51.189  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 16:00:51.189  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:51.189  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:51.189  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:51.189  1472  1652 E BluetoothHeadset: BluetoothHeadset service is binded
08-30 16:00:51.189  4748  4762 D Bluetoothsap: onBluetoothStateChange: up=true
,08-30 16:00:51.189  4748  4762 D Bluetoothsap: Binding service...
,08-30 16:00:51.189  4748  4762 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-30 16:00:51.189  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-30 16:00:51.189  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-30 16:00:51.199  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:51.199  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:51.199  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:51.199  4748  4762 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-30 16:00:51.199  1441  1467 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 16:00:51.199  1020  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 16:00:51.199  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 16:00:51.199  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:51.199  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:51.199  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:51.199  1441  1467 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 16:00:51.199  4748  4748 D Bluetoothsap: BluetoothSAP Proxy object connected
08-30 16:00:51.199  4748  4748 D SapProfile: Bluetooth service connected
08-30 16:00:51.199  4748  4748 D Bluetoothsap: getConnectedDevices()
,08-30 16:00:51.199  1441  7342 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 16:00:51.199  1020  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 16:00:51.199  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 16:00:51.199  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:51.199  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:51.199  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:51.209  1441  7342 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 16:00:51.209  1020  1049 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 16:00:51.209  1020  1049 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 16:00:51.209  4748  4769 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 16:00:51.209  4748  4769 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 16:00:51.209  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-30 16:00:51.209  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-30 16:00:51.209  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 16:00:51.209  1020  1020 I InputMethodManagerService: [BT Setting State] State =12
08-30 16:00:51.209  1020  1020 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-30 16:00:51.209  1441  1441 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@de925dd, true
,08-30 16:00:51.209  1441  1441 D BluetoothHeadset: registerMessageListener
,08-30 16:00:51.219  1181  1181 D BluetoothTile:  onBluetoothStateChange:
,08-30 16:00:51.219  1181  1181 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-30 16:00:51.219  1181  1781 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 16:00:51.219  1181  1781 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 16:00:51.219  1181  1181 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:00:51.219  1181  1181 D BluetoothTile:  getBluetoothState : 12
,08-30 16:00:51.219  1181  1781 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 16:00:51.229  4748  4748 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:00:51.229  1915  1915 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 16:00:51.229  1020  1359 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 16:00:51.229  1020  1507 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-30 16:00:51.229  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:51.229  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 16:00:51.229  3280  3443 D HeadsetService: registerMessageListener
,08-30 16:00:51.239  3280  3443 D HeadsetService: registerMessageListener
,08-30 16:00:51.239  4748  4748 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-30 16:00:51.239  1441  1441 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-30 16:00:51.239  1441  1441 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-30 16:00:51.239  3280  7895 D HeadsetStateMachine: Disconnected process message: 70
08-30 16:00:51.239  3280  7895 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1de97a1e
,08-30 16:00:51.239  4748  4748 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-30 16:00:51.239  4748  4748 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-30 16:00:51.239  4748  4748 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-30 16:00:51.239  1441  1441 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-30 16:00:51.239  3280  7905 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-30 16:00:51.239  1441  1441 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-30 16:00:51.239  1441  1441 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-30 16:00:51.239  3280  7895 D HeadsetStateMachine: Disconnected process message: 9
,08-30 16:00:51.239  3280  7895 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-30 16:00:51.249  3280  7905 D BluetoothSocket: bindListen(): myUserId = 0
08-30 16:00:51.249  3280  7905 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 16:00:51.249  3280  7905 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-30 16:00:51.249  3280  7905 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 16:00:51.249  3280  7905 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 16:00:51.249  3280  7905 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@30d252ff
,08-30 16:00:51.249  4748  4748 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 16:00:51.249  3280  7905 D BluetoothSocket: channel: 5
,08-30 16:00:51.249  1020  1494 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-30 16:00:51.249  1020  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 16:00:51.249   283   712 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-30 16:00:51.249   283   712 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-30 16:00:51.249   283   712 V voice   : voice_set_parameters: exit with code(-2)
08-30 16:00:51.249  1020  1494 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:51.249   283   712 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-30 16:00:51.249  1020  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:51.249  1020  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 16:00:51.249   283   712 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-30 16:00:51.249   283   712 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
,08-30 16:00:51.249   283   712 V audio_hw_primary: adev_set_parameters: exit
,08-30 16:00:51.249  3280  7895 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-30 16:00:51.259  1684  1684 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:00:51.259  4748  4748 D DockEventReceiver: finishStartingService: stopping service
,08-30 16:00:51.259  4748  4748 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 16:00:51.269  1181  1181 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED,
08-30 16:00:51.269  1181  1181 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-30 16:00:51.269  3280  3280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2edb689
,08-30 16:00:51.269  3280  3280 D BtConfig.SecureMode: isSecureModeOn:false
,08-30 16:00:51.279  1020  1465 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 16:00:51.279  1020  1465 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-30 16:00:51.279  1020  1465 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:51.279  1020  1465 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:51.279  1020  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 16:00:51.289  1020  1032 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-30 16:00:51.299  3280  7910 D BluetoothSocket: bindListen(): myUserId = 0
08-30 16:00:51.299  3280  7910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 16:00:51.299  3280  7910 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
08-30 16:00:51.299  3280  7910 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 16:00:51.299  3280  7910 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 16:00:51.299  3280  7910 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f83201b
,08-30 16:00:51.299  3280  7910 D BluetoothSocket: channel: 12
08-30 16:00:51.299  3280  7910 I BtOppRfcommListener: Accept thread started.
,08-30 16:00:51.799  7084  7295 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:51.799  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:51.799  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:51.799  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:00:51.799  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:51.799  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:51.799  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:51.799  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:00:51.799  7084  7295 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:00:51.799  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:00:51.799  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@329f044d added. We now have 8 listener(s)
,08-30 16:00:51.799  7084  7295 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:00:51.809  1020  1220 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-30 16:00:51.809  1020  1220 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-30 16:00:51.809  1020  1220 D SecContentProvider2: mCursor = null
,08-30 16:00:51.809  1020  1220 D WifiService: setWifiEnabled: false pid=7084, uid=10170
,08-30 16:00:51.809  1020  1220 D SettingsProvider: name = wifi_on
,08-30 16:00:51.819  7084  7295 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:51.819  1020  1465 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-30 16:00:51.819  1020  1465 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-30 16:00:51.819  1020  1465 D SecContentProvider2: mCursor = null
,08-30 16:00:51.819  1020  1465 D WifiService: setWifiEnabled: true pid=7084, uid=10170
,08-30 16:00:51.819  1020  1465 W ActivityManager: Permission Denial: getCurrentUser() from pid=7084, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-30 16:00:51.819  1020  1465 W WifiService: Failed getting userId using ActivityManagerNative
08-30 16:00:51.819  1020  1465 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7084, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-30 16:00:51.819  1020  1465 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-30 16:00:51.819  1020  1465 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-30 16:00:51.819  1020  1465 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-30 16:00:51.819  1020  1465 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-30 16:00:51.819  1020  1465 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 16:00:51.819  1020  1465 D SettingsProvider: name = wifi_on
,08-30 16:00:51.829  1020  1129 E WifiHW  : ##################### set firmware type 0 #####################
,08-30 16:00:52.169  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
,08-30 16:00:52.169  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-30 16:00:52.169  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 16:00:52.169  1020  1047 D Tethering: interfaceAdded wlan0
,08-30 16:00:52.169  1020  1134 E Tethering: No numeric data
,08-30 16:00:52.179  1020  1126 V NetworkStats: performPollLocked(flags=0x1)
08-30 16:00:52.179  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:52.179  1181  1181 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-30 16:00:52.179  1181  1181 D HotspotTile: updateTetherState():false, false
,08-30 16:00:52.179  1020  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 16:00:52.179  1020  1134 D Tethering: clearTetheredNotification()
,08-30 16:00:52.179  1020  1047 D Tethering: interfaceAdded p2p0
,08-30 16:00:52.179  1020  1047 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-30 16:00:52.189  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-30 16:00:52.189  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 16:00:52.189  1020  1126 V NetworkStats: performPollLocked() took 13ms
,08-30 16:00:52.189  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:52.189  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 16:00:52.189  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-30 16:00:52.199  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:52.199  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 16:00:52.199  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:52.199   278   963 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-30 16:00:52.199   278   963 D SoftapController: Softap fwReload - Ok
,08-30 16:00:52.199   278   963 D CommandListener: Setting iface cfg
08-30 16:00:52.199   278   963 D CommandListener: Trying to bring down wlan0
,08-30 16:00:52.199   278   963 D CommandListener: Clearing all IP addresses on wlan0,
,08-30 16:00:52.209  1020  1129 E WifiHW  : supplicant_name : p2p_supplicant,
,08-30 16:00:52.219  1020  1129 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,08-30 16:00:52.229  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-30 16:00:52.229  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 16:00:52.229  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 16:00:52.229  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:52.229  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:52.229  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:52.229  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:52.229  1181  1181 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 16:00:52.229  1181  1181 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-30 16:00:52.239  1181  1781 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
08-30 16:00:52.239  1181  1181 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-30 16:00:52.239  1181  1181 D HotspotTile: onReceive : 2, 0
,08-30 16:00:52.239  4748  4748 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 16:00:52.249  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:52.249  1020  1507 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 16:00:52.249  1020  1507 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 16:00:52.249  1020  1507 W ActivityManager: userId = 0, bbcId = -10000
,08-30 16:00:52.249  1020  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 16:00:52.249  1020  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 16:00:52.259  1632  1632 I Hs20UtilService: Starting #19
,08-30 16:00:52.259  1632  1654 I Hs20UtilService: Message received 5011
,08-30 16:00:52.259  7438  7438 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 16:00:52.259  7921  7921 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-30 16:00:52.259  7921  7921 I wpa_supplicant: Successfully initialized wpa_supplicant
08-30 16:00:52.259  7438  7438 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-30 16:00:52.259  7921  7921 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-30 16:00:52.259  7438  7438 D SecurityLogAgent: StateMachine : Current State = 1
08-30 16:00:52.259  7438  7438 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 16:00:52.279  7921  7921 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-30 16:00:52.279   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7921
08-30 16:00:52.279   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-30 16:00:52.279  7921  7921 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-30 16:00:52.279  7921  7921 I wpa_supplicant: ssSupport state is = 1
08-30 16:00:52.279  7921  7921 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,08-30 16:00:52.279  7921  7921 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-30 16:00:52.279   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7921
08-30 16:00:52.279   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-30 16:00:52.429   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-30 16:00:52.429  7921  7921 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-30 16:00:52.479  7921  7921 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-30 16:00:52.479  7921  7921 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-30 16:00:52.479  7921  7921 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-30 16:00:52.489   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7921
08-30 16:00:52.489   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-30 16:00:52.489  7921  7921 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-30 16:00:52.489  7921  7921 I wpa_supplicant: ssSupport state is = 1
08-30 16:00:52.489  7921  7921 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 16:00:52.489  7921  7921 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-30 16:00:52.489  7921  7921 E wpa_supplicant: SIM READ ERROR
08-30 16:00:52.489  7921  7921 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 16:00:52.489  7921  7921 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 16:00:52.489  7921  7921 E wpa_supplicant: SIM READ ERROR
08-30 16:00:52.489  7921  7921 I wpa_supplicant: Blacklist: Clear (all) 
08-30 16:00:52.489  7921  7921 I wpa_supplicant: wpa_default_ap_write_once,
08-30 16:00:52.489  7921  7921 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-30 16:00:52.489  7921  7921 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 16:00:52.489  7921  7921 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-30 16:00:52.489  7921  7921 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 16:00:52.489  7921  7921 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-30 16:00:52.489  7921  7921 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-30 16:00:52.489  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 16:00:52.489  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 16:00:52.489  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
08-30 16:00:52.489  1020  1134 D Tethering: InitialState.processMessage what=4
,08-30 16:00:52.489  1020  1134 E Tethering: No numeric data,
08-30 16:00:52.499  1020  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 16:00:52.499  1020  1134 D Tethering: clearTetheredNotification(),
08-30 16:00:52.499  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-30 16:00:52.499  1020  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-30 16:00:52.499  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 16:00:52.499  1181  1181 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-30 16:00:52.499  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 16:00:52.499  1181  1181 D HotspotTile: updateTetherState():false, false
08-30 16:00:52.499  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:52.499  1020  1126 V NetworkStats: performPollLocked() took 6ms
,08-30 16:00:52.509  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:52.509  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:52.549  7921  7921 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-30 16:00:52.759  7921  7921 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
08-30 16:00:52.759  7921  7921 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-30 16:00:52.769  7921  7921 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-30 16:00:52.769   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7921
08-30 16:00:52.769   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-30 16:00:52.769  7921  7921 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-30 16:00:52.769  7921  7921 I wpa_supplicant: ssSupport state is = 1,
08-30 16:00:52.779  7921  7921 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-30 16:00:52.779  7921  7921 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-30 16:00:52.789  7921  7921 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-30 16:00:52.789   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7921,
08-30 16:00:52.789   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-30 16:00:52.789  7921  7921 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-30 16:00:52.789  7921  7921 I wpa_supplicant: ssSupport state is = 1
,08-30 16:00:52.789  7921  7921 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 16:00:52.789  7921  7921 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 16:00:52.789  7921  7921 E wpa_supplicant: SIM READ ERROR
08-30 16:00:52.789  7921  7921 I wpa_supplicant: wpa_default_ap_write_once,
,08-30 16:00:52.789  7921  7921 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-30 16:00:52.789  7921  7921 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 16:00:52.799  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false,
08-30 16:00:52.799  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 16:00:52.799  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-30 16:00:52.799  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false,
08-30 16:00:52.799  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 16:00:52.799  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-30 16:00:52.839  7921  7921 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-30 16:00:52.839  7921  7921 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-30 16:00:52.949  7921  7921 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-30 16:00:52.949  7921  7921 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-30 16:00:52.949  7921  7921 I wpa_supplicant: Skip scan - bUseNetwork false
,08-30 16:00:52.959  1020  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,08-30 16:00:52.959  1020  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21],
08-30 16:00:52.959  7921  7921 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-30 16:00:52.959  7921  7921 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-30 16:00:52.959  7921  7921 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 16:00:52.969  7921  7921 E wpa_supplicant: SIM READ ERROR,
08-30 16:00:52.969  7921  7921 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 16:00:52.989  7921  7921 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-30 16:00:52.999  7921  7921 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-30 16:00:53.009  1020  1129 D WifiConfigStore: Loading config and enabling all networks 
,08-30 16:00:53.009  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-30 16:00:53.009  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 16:00:53.009  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 16:00:53.009  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:53.009  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:53.009  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:53.009  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:53.009  1181  1181 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 16:00:53.009  1181  1181 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-30 16:00:53.009  1181  1181 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 16:00:53.009  1181  1781 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-30 16:00:53.009  4748  4748 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-30 16:00:53.009  1181  1181 D HotspotTile: onReceive : 3, 0
,08-30 16:00:53.019  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:53.019  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:53.019  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:53.019  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:53.019  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:53.019  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:53.019  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:53.019  7084  7084 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:00:53.019  7084  7084 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:00:53.019  1020  1033 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 16:00:53.019  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 16:00:53.019  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:53.019  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:53.019  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 16:00:53.019  1020  1129 E WifiConfigStore: Not a HS20
,08-30 16:00:53.019  1632  1632 I Hs20UtilService: Starting #20
,08-30 16:00:53.029  1632  1654 I Hs20UtilService: Message received 5011
08-30 16:00:53.029  1020  1129 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-30 16:00:53.029  7438  7438 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 16:00:53.029  7438  7438 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-30 16:00:53.029  1020  1129 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,08-30 16:00:53.029  7921  7921 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-30 16:00:53.029  7921  7921 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-30 16:00:53.029  7921  7921 I wpa_supplicant: reset timer : RESET_TIMER 0
08-30 16:00:53.029  7921  7921 I wpa_supplicant: P2P: Current p2p state = IDLE
08-30 16:00:53.029  7921  7921 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-30 16:00:53.029  7921  7921 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-30 16:00:53.029  7921  7921 I wpa_supplicant: First Scan Start
08-30 16:00:53.029  7921  7921 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-30 16:00:53.029  1020  1129 D WifiNative-wlan0: Setting external_sim to 1
,08-30 16:00:53.029  1020  1129 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 16:00:53.029  1020  1129 I WifiNative-HAL: startHal
08-30 16:00:53.029  1020  1129 E wifi    : getStaticLongField sWifiHalHandle 0x9f12888c
08-30 16:00:53.029  1020  1129 I WifiNative-HAL: Could not start hal
,08-30 16:00:53.029  7415  7415 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 16:00:53.029  7438  7438 D SecurityLogAgent: StateMachine : Current State = 1
,08-30 16:00:53.039  7438  7438 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 16:00:53.039  1020  1129 E WifiNative-wlan0: do suspend true
,08-30 16:00:53.039  1020  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-30 16:00:53.039  1020  1020 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 16:00:53.039  1020  1128 D WifiP2pService: P2pDisabledState{ what=131203 },
08-30 16:00:53.039  1020  1154 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:00:53.039  1020  1128 D WifiP2pService: P2pEnablingState
08-30 16:00:53.039  1020  1154 I WifiNative-HAL: startHal
08-30 16:00:53.039  1020  1128 D WifiP2pService: P2pEnablingState{ what=147457 }
08-30 16:00:53.039  1020  1154 E wifi    : getStaticLongField sWifiHalHandle 0x9dfea9bc
08-30 16:00:53.039  1020  1128 D WifiP2pService: P2p socket connection successful
08-30 16:00:53.039  1020  1154 I WifiNative-HAL: Could not start hal
,08-30 16:00:53.039  1020  1128 D WifiP2pService: P2pEnabledState
08-30 16:00:53.039  1020  1154 E WifiScanningService: could not start HAL
08-30 16:00:53.039   278   963 D CommandListener: Setting iface cfg
08-30 16:00:53.039   278   963 D CommandListener: Trying to bring up p2p0
08-30 16:00:53.039  1020  1020 D RttService: SCAN_AVAILABLE : 3
08-30 16:00:53.039  1020  1128 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 16:00:53.039  1020  1155 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:00:53.039  1020  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-30 16:00:53.039  1020  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-30 16:00:53.039  1020  1129 E WifiNative-wlan0: invaild command id : 215
08-30 16:00:53.039  1020  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-30 16:00:53.039  1020  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-30 16:00:53.039  1020  1129 E WifiNative-wlan0: invaild command id : 215
08-30 16:00:53.039  7921  7921 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 16:00:53.039  7921  7921 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 16:00:53.049  7921  7921 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-30 16:00:53.049  1020  1129 E WifiStateMachine: Failed to set frequency band 0
,08-30 16:00:53.049  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 16:00:53.049  1020  1129 D SecContentProvider2: mCursor = null
,08-30 16:00:53.049  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 16:00:53.049  1020  1129 D SecContentProvider2: mCursor = null
,08-30 16:00:53.049  1020  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-30 16:00:53.049  1020  1131 E ConnectivityService: updateNetworkInfo()
,08-30 16:00:53.049  1020  1020 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-30 16:00:53.049  1020  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-30 16:00:53.049  1020  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 16:00:53.049  1020  1050 D WifiDisplayController: disconnect
08-30 16:00:53.049  1020  1050 D WifiDisplayController: updateConnection
08-30 16:00:53.049  1020  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 16:00:53.049  1020  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 16:00:53.059  1181  1181 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-30 16:00:53.059  1020  4405 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 16:00:53.059  1181  1181 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-30 16:00:53.059  1020  1128 D WifiNative-p2p0: p2pGetDeviceAddress
,08-30 16:00:53.059  1020  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 16:00:53.059  1020  1050 D WifiDisplayAdapter: onP2pDisconnected
08-30 16:00:53.059  1020  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 16:00:53.059  1020  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-30 16:00:53.059  1020  1128 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-30 16:00:53.059  4748  4748 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE,
08-30 16:00:53.059  4748  4748 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 16:00:53.059  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 16:00:53.059  1020  1128 D WifiP2pService: DeviceAddress: 0a:75:42,
,08-30 16:00:53.069  1020  1050 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-30 16:00:53.069  1020  1050 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-30 16:00:53.069  1020  1050 D WifiDisplayController:  primary type: 10-0050F204-5
08-30 16:00:53.069  1020  1050 D WifiDisplayController:  secondary type: null
08-30 16:00:53.069  1020  1050 D WifiDisplayController:  wps: 0
08-30 16:00:53.069  1020  1050 D WifiDisplayController:  grpcapab: 0
08-30 16:00:53.069  1020  1050 D WifiDisplayController:  devcapab: 0
08-30 16:00:53.069  1020  1050 D WifiDisplayController:  status: 3
08-30 16:00:53.069  1020  1050 D WifiDisplayController:  wfdInfo: null
08-30 16:00:53.069  1020  1050 D WifiDisplayController:  groupownerAddress: null
08-30 16:00:53.069  1020  1050 D WifiDisplayController:  GOdeviceName: null
08-30 16:00:53.069  1020  1050 D WifiDisplayController:  interfaceAddress: 
08-30 16:00:53.069  1020  1050 D WifiDisplayController:  SConnectInfo : null
08-30 16:00:53.069  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 16:00:53.069  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 16:00:53.069  4748  4748 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 16:00:53.069  4748  4840 V NearbySettings: MountReceiver.mPrefHandler - 7002,
,08-30 16:00:53.069  7768  7768 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 16:00:53.069  7768  7768 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-30 16:00:53.069  7768  7768 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 16:00:53.069  7400  7400 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 16:00:53.089  1020  1128 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-30 16:00:53.089  1020  1128 D WifiP2pService: InactiveState
,08-30 16:00:53.089  1020  1128 D WifiP2pService: InactiveState{ what=143376 }
,08-30 16:00:53.089  1020  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 16:00:53.089  7921  7921 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-30 16:00:53.089  1020  1128 D WifiP2pService: InactiveState{ what=143376 }
,08-30 16:00:53.089  1020  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 16:00:53.159  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false
,08-30 16:00:53.159  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-30 16:00:53.159  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 16:00:53.169   288   288 E SMD     : DCD OFF,
,08-30 16:00:53.859  7084  7295 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:53.859  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:53.859  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:53.859  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:53.859  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:53.859  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:53.859  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:53.859  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:00:53.859  7084  7295 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:00:53.869  7084  7295 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-30 16:00:53.869  7084  7295 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-30 16:00:53.869  7084  7295 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3868519f Bundle[{}]
,08-30 16:00:53.869  7084  7295 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 16:00:53.869  7084  7295 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 16:00:53.869  7084  7295 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-30 16:00:53.869  7084  7295 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-30 16:00:53.869  7084  7295 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-30 16:00:53.879  7084  7295 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 16:00:53.879  7084  7295 I System.out: Running OutgoingSocketThread
,08-30 16:00:53.879  7084  7930 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1435)
,08-30 16:00:53.889  7084  7930 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 52689
,08-30 16:00:53.889  7084  7930 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 16:00:54.229  7921  7921 I wpa_supplicant: nl80211: Received scan results (22 BSSes),
08-30 16:00:54.229  7921  7921 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-30 16:00:54.229  7921  7921 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-30 16:00:54.229  7921  7921 I wpa_supplicant: Trying to associate with  'G700'
,08-30 16:00:54.229  7921  7921 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
08-30 16:00:54.229  7921  7921 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
08-30 16:00:54.239  1020  7927 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-30 16:00:54.249  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 16:00:54.249  1020  1129 D SecContentProvider2: mCursor = null
,08-30 16:00:54.409  7921  7921 E wpa_supplicant: Cmd 35605 not handled
,08-30 16:00:54.409  7921  7921 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-30 16:00:54.409  7921  7921 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-30 16:00:54.409  7921  7921 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-30 16:00:54.409  7921  7921 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-30 16:00:54.409  7921  7921 I wpa_supplicant: Associated with F4.99.3E
08-30 16:00:54.409  7921  7921 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-30 16:00:54.409  7921  7921 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-30 16:00:54.409  7921  7921 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-30 16:00:54.409  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
,08-30 16:00:54.409  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-30 16:00:54.419  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 16:00:54.419  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
,08-30 16:00:54.419  1020  1047 D Tethering: interfaceStatusChanged wlan0, false,
08-30 16:00:54.419  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false,
08-30 16:00:54.419  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,08-30 16:00:54.419  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-30 16:00:54.419  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,08-30 16:00:54.419  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, true
,08-30 16:00:54.419  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-30 16:00:54.419  1020  1047 D Tethering: interfaceStatusChanged wlan0, true
08-30 16:00:54.429  1020  1126 V NetworkStats: performPollLocked(flags=0x1)
08-30 16:00:54.419  1020  1134 E Tethering: No numeric data
08-30 16:00:54.429  1181  1181 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 16:00:54.419  7921  7921 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-30 16:00:54.429  1181  1181 D HotspotTile: updateTetherState():false, false
08-30 16:00:54.419  7921  7921 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-30 16:00:54.429  7921  7921 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-30 16:00:54.429  7921  7921 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-30 16:00:54.429  1020  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 16:00:54.429  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 16:00:54.439  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-30 16:00:54.429  1020  1129 D SecContentProvider2: mCursor = null
08-30 16:00:54.429  1020  1134 D Tethering: clearTetheredNotification()
08-30 16:00:54.429  7921  7921 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 16:00:54.429  7921  7921 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-30 16:00:54.429  7921  7921 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-30 16:00:54.429  7921  7921 I wpa_supplicant: Blacklist: Clear (temp) 
08-30 16:00:54.429  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:54.429  7921  7921 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-30 16:00:54.429  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 16:00:54.429  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 16:00:54.429  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, true
08-30 16:00:54.439  1020  1047 D Tethering: interfaceStatusChanged wlan0, true
08-30 16:00:54.439  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 16:00:54.439  1020  1129 D SecContentProvider2: mCursor = null
,08-30 16:00:54.439  1020  1126 V NetworkStats: performPollLocked() took 11ms
,08-30 16:00:54.439  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:54.439  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:54.439  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:54.449  1020  1129 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-30 16:00:54.449  1020  1129 E WifiConfigStore: setLastSelectedConfiguration -1
,08-30 16:00:54.459  1020  1129 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-30 16:00:54.459  1020  1131 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-30 16:00:54.459  1020  1131 E ConnectivityService: updateNetworkInfo()
08-30 16:00:54.459  1020  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 16:00:54.459  1020  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:00:54.459  1020  3781 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-30 16:00:54.469  1020  3781 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 16:00:54.469  1020  3781 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:54.469  1020  3781 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:54.469  1020  3781 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 16:00:54.469  1632  1632 I Hs20UtilService: Starting #21
,08-30 16:00:54.469  1632  1654 I Hs20UtilService: Message received 5007,
08-30 16:00:54.469  4748  4748 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 16:00:54.479  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-30 16:00:54.479  4748  4748 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null,
08-30 16:00:54.479  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 16:00:54.479  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 16:00:54.479  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:54.479  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:54.479  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:54.479  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:54.489  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-30 16:00:54.489  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 16:00:54.489  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-30 16:00:54.489  4748  4748 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 16:00:54.489  1020  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:00:54.489  4748  4840 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 16:00:54.499   278   963 D CommandListener: Setting iface cfg
,08-30 16:00:54.499  1020  1129 E WifiStateMachine: Start Dhcp Watchdog 3
,08-30 16:00:54.499  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 16:00:54.499  1020  1129 D SecContentProvider2: mCursor = null
,08-30 16:00:54.519  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-30 16:00:54.519  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 16:00:54.519  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 16:00:54.519  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:54.519  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:54.519  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:54.519  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:54.519  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 16:00:54.519  1020  1129 D SecContentProvider2: mCursor = null
08-30 16:00:54.529  1020  1129 E WifiNative-wlan0: do suspend false
08-30 16:00:54.529  1020  1128 D WifiP2pService: InactiveState{ what=143375 }
08-30 16:00:54.529  1020  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 16:00:54.739  7933  7933 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-30 16:00:54.749  7933  7933 I dhcpcd  : version 5.5.6 starting
,08-30 16:00:54.749  7933  7933 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-30 16:00:54.809  7933  7933 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-30 16:00:54.809  7933  7933 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-30 16:00:54.809  7933  7933 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-30 16:00:54.809  7933  7933 I dhcpcd  : bssid match
08-30 16:00:54.809  7933  7933 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-30 16:00:54.879  7933  7933 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-30 16:00:54.879  7084  7295 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1436)
08-30 16:00:54.879  7084  7295 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1436)
,08-30 16:00:54.889  7084  7295 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1441)
08-30 16:00:54.889  7084  7295 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-30 16:00:54.889  7084  7295 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1442)
08-30 16:00:54.889  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:00:54.889  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21927b02 added. We now have 2 listener(s)
,08-30 16:00:54.889  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-30 16:00:54.899  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:00:54.899  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:00:54.899  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:00:54.899  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12652c13 added. We now have 9 listener(s)
08-30 16:00:54.899  7084  7295 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:00:54.899  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 16:00:54.899  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:00:54.909  7084  7295 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:00:54.909  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:54.909  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:54.909  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:54.909  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:54.909  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:54.909  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:54.909  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:00:54.909  7084  7295 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:00:54.909  7084  7295 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 16:00:54.909  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:54.909  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:54.909  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 16:00:54.919  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e49849 added. We now have 3 listener(s)
,08-30 16:00:54.919  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-30 16:00:54.919  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 16:00:54.919  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 16:00:54.919  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:00:54.919  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a31454e added. We now have 10 listener(s)
,08-30 16:00:54.919  7084  7295 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:00:54.919  7084  7295 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:00:54.919  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:00:54.919  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:54.919  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:54.919  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:54.919  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:00:54.919  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:00:54.919  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21927b02 removed from the list
08-30 16:00:54.919  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:54.919  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12652c13 removed from the list
08-30 16:00:54.919  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:54.919  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:54.929  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:54.929  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:54.929  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:54.929  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:54.929  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:54.929  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12652c13 not in the list
08-30 16:00:54.929  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:54.929  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:54.929  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:54.929  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:54.929  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-30 16:00:54.929  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a31454e removed from the list
08-30 16:00:54.929  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:54.929  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-30 16:00:54.929  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:54.929  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:00:54.929  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e49849 removed from the list
08-30 16:00:54.929  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:00:54.929  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@326c766f added. We now have 2 listener(s)
08-30 16:00:54.929  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-30 16:00:54.929  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:00:54.929  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:00:54.929  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:00:54.929  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1e6f7c added. We now have 9 listener(s)
,08-30 16:00:54.929  7084  7295 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:00:54.929  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 16:00:54.939  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-30 16:00:54.939  7084  7295 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:00:54.939  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
08-30 16:00:54.939  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:54.939  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:54.939  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:54.939  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:54.939  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:54.939  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:00:54.939  7084  7295 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:00:54.939  7084  7295 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:00:54.939  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:00:54.939  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e0685a added. We now have 3 listener(s)
,08-30 16:00:54.949  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-30 16:00:54.949  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:54.949  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-30 16:00:54.949  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-30 16:00:54.949  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:00:54.949  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:00:54.949  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36f40a8b added. We now have 10 listener(s)
08-30 16:00:54.949  7084  7295 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:00:54.949  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 16:00:54.949  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:00:54.949  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 16:00:54.949  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:00:54.949  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 16:00:54.949  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 16:00:54.959  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 16:00:54.959  7933  7933 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
08-30 16:00:54.959  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 16:00:54.959  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 16:00:54.959  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 16:00:54.959  7084  7295 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 16:00:54.969  3280  7311 D BtGatt.GattService: registerClient() - UUID=5bf55db1-984e-4b7a-8dc2-1e16738503eb
,08-30 16:00:55.009  3280  3358 D BtGatt.GattService: onClientRegistered() - UUID=5bf55db1-984e-4b7a-8dc2-1e16738503eb, clientIf=6
,08-30 16:00:55.009  7084  7097 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-30 16:00:55.009  3280  3417 D BtGatt.GattService: start scan with filters
,08-30 16:00:55.009  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 16:00:55.009  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 16:00:55.009  3280  3420 D BtGatt.ScanManager: handling starting scan
08-30 16:00:55.009  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 16:00:55.009  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 16:00:55.019  3280  3358 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-30 16:00:55.019  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 16:00:55.019  3280  3420 D BtGatt.ScanManager: allow scan with filters
08-30 16:00:55.019  3280  3420 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-30 16:00:55.019  3280  3420 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
08-30 16:00:55.019  3280  3358 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-30 16:00:55.019  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 16:00:55.019  3280  3420 D BtGatt.ScanManager: Starting BLE batch scan
08-30 16:00:55.019  3280  3420 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 16:00:55.019  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 16:00:55.019  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 16:00:55.019  7084  7084 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 16:00:55.019  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 16:00:55.029  3280  3358 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-30 16:00:55.029  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 16:00:55.029  7084  7295 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 16:00:55.029  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:55.029  3280  3358 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-30 16:00:55.029  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 16:00:55.029  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 16:00:55.029  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:00:55.029  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:00:55.029  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts,
,08-30 16:00:55.029  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 16:00:55.029  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 16:00:55.029  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 16:00:55.039  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 16:00:55.039  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 16:00:55.039  3280  3293 D BtGatt.GattService: stopScan() - queue size =1,
,08-30 16:00:55.039  3280  7311 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 16:00:55.039  3280  3420 D BtGatt.ScanManager: filter size is 1
08-30 16:00:55.039  3280  3420 D BtGatt.ScanManager: delete FilterIndex - 6
08-30 16:00:55.039  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:00:55.039  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 16:00:55.039  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
08-30 16:00:55.039  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 16:00:55.039  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 16:00:55.039  3280  3358 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-30 16:00:55.039  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 16:00:55.039  3280  3420 D BtGatt.ScanManager: stopping BLe Batch
08-30 16:00:55.039  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:00:55.049  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 16:00:55.049  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 16:00:55.049  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 16:00:55.049  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:00:55.049  3280  3358 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
08-30 16:00:55.049  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 16:00:55.049  3280  3420 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 16:00:55.049  7084  7084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:00:55.049  7084  7084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:00:55.049  7084  7084 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:00:55.049  3280  3358 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-30 16:00:55.049  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 16:00:55.059  7084  7295 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-30 16:00:55.059  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:00:55.059  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:55.059  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:55.059  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:55.059  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:00:55.059  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:00:55.059  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@326c766f removed from the list
08-30 16:00:55.059  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:00:55.059  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1e6f7c removed from the list
08-30 16:00:55.059  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:55.059  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:55.059  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:55.059  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:55.069  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:55.069  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 16:00:55.069  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:55.069  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1e6f7c not in the list
08-30 16:00:55.069  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:55.069  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:55.069  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:55.069  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:55.069  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:55.069  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36f40a8b removed from the list
08-30 16:00:55.069  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:55.069  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:55.069  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:55.069  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:00:55.069  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e0685a removed from the list
08-30 16:00:55.069  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:00:55.069  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@716c467 added. We now have 2 listener(s)
,08-30 16:00:55.069  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-30 16:00:55.069  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:00:55.069  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-30 16:00:55.069  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:00:55.069  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3333214 added. We now have 9 listener(s)
08-30 16:00:55.069  7084  7295 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:00:55.069  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 16:00:55.079  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:00:55.079  7084  7295 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:00:55.079  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:55.079  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:55.079  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:55.079  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:55.079  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:55.079  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:55.079  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:00:55.079  7084  7295 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:00:55.079  7084  7295 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:00:55.079  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:00:55.079  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a3a8b2 added. We now have 3 listener(s)
,08-30 16:00:55.089  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:55.089  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-30 16:00:55.089  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:00:55.089  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:00:55.089  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:00:55.089  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36c14003 added. We now have 10 listener(s)
,08-30 16:00:55.089  7084  7295 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:00:55.089  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:00:55.089  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:00:55.089  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:00:55.089  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 16:00:55.089  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:00:55.089  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 16:00:55.089  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:00:55.089  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 16:00:55.099  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 16:00:55.099  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,08-30 16:00:55.109  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 16:00:55.109  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 16:00:55.109  7084  7295 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 16:00:55.109  3280  3417 D BtGatt.GattService: registerClient() - UUID=0140e3bf-ee18-488d-b596-99b4221a5058
,08-30 16:00:55.149  3280  3358 D BtGatt.GattService: onClientRegistered() - UUID=0140e3bf-ee18-488d-b596-99b4221a5058, clientIf=6,
08-30 16:00:55.159  7084  7098 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-30 16:00:55.159  3280  3290 D BtGatt.GattService: start scan with filters
08-30 16:00:55.159  3280  3420 D BtGatt.ScanManager: handling starting scan
08-30 16:00:55.159  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 16:00:55.159  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 16:00:55.159  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 16:00:55.159  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 16:00:55.159  3280  3358 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-30 16:00:55.159  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 16:00:55.159  3280  3420 D BtGatt.ScanManager: allow scan with filters,
08-30 16:00:55.159  3280  3420 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-30 16:00:55.159  3280  3420 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
08-30 16:00:55.159  3280  3358 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-30 16:00:55.159  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-30 16:00:55.159  3280  3420 D BtGatt.ScanManager: Starting BLE batch scan
08-30 16:00:55.159  3280  3420 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 16:00:55.159  3280  3358 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-30 16:00:55.159  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,08-30 16:00:55.169  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:00:55.169  7084  7084 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 16:00:55.169  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 16:00:55.169  3280  3358 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-30 16:00:55.169  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 16:00:55.169  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 16:00:55.179  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 16:00:55.179  7084  7295 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-30 16:00:55.179  7084  7295 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:55.179  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:55.179  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:55.179  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:55.179  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:55.179  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:00:55.179  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:00:55.179  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@716c467 removed from the list
08-30 16:00:55.179  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:55.179  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3333214 removed from the list
08-30 16:00:55.179  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:55.179  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:00:55.179  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:55.179  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 16:00:55.179  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:55.179  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:00:55.179  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:00:55.179  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:55.179  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:55.179  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3333214 not in the list
08-30 16:00:55.179  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 16:00:55.179  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 16:00:55.179  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 16:00:55.179  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 16:00:55.179  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 16:00:55.179  3280  7311 D BtGatt.GattService: stopScan() - queue size =1
,08-30 16:00:55.179  3280  3420 D BtGatt.ScanManager: filter size is 1
,08-30 16:00:55.179  3280  3420 D BtGatt.ScanManager: delete FilterIndex - 7
,08-30 16:00:55.179  3280  3417 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 16:00:55.179  3280  3358 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-30 16:00:55.179  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 16:00:55.179  3280  3420 D BtGatt.ScanManager: stopping BLe Batch
,08-30 16:00:55.189  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:00:55.189  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 16:00:55.189  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 16:00:55.189  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 16:00:55.189  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 16:00:55.189  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:00:55.189  3280  3358 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-30 16:00:55.189  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 16:00:55.189  3280  3420 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 16:00:55.189  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 16:00:55.189  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 16:00:55.189  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 16:00:55.189  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:55.189  3280  3358 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-30 16:00:55.189  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 16:00:55.189  7084  7084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:00:55.189  7084  7084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:00:55.189  7084  7084 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:00:55.189  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:55.189  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:55.189  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:55.189  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36c14003 removed from the list
08-30 16:00:55.189  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:55.189  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:55.189  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:55.189  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:00:55.189  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a3a8b2 removed from the list
,08-30 16:00:55.189  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:00:55.189  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220dd95f added. We now have 2 listener(s)
,08-30 16:00:55.189  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-30 16:00:55.189  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:00:55.189  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:00:55.189  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:00:55.189  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@369aafac added. We now have 9 listener(s)
08-30 16:00:55.189  7084  7295 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:00:55.189  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 16:00:55.199  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:00:55.199  7084  7295 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:00:55.199  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:55.199  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:55.199  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:55.199  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:55.199  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:55.199  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:55.199  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:00:55.199  7084  7295 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:00:55.199  7084  7295 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 16:00:55.199  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:55.199  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:00:55.199  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d39c0a added. We now have 3 listener(s)
,08-30 16:00:55.209  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:55.209  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-30 16:00:55.209  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:00:55.209  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 16:00:55.209  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:00:55.209  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2260ac7b added. We now have 10 listener(s)
08-30 16:00:55.209  7084  7295 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:00:55.209  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:00:55.209  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:00:55.209  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 16:00:55.209  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:00:55.209  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
,08-30 16:00:55.209  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 16:00:55.219  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 16:00:55.219  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 16:00:55.219  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 16:00:55.219  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 16:00:55.219  7084  7295 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 16:00:55.219  3280  3290 D BtGatt.GattService: registerClient() - UUID=c55e20f5-23e8-4c7d-a540-8107b5803e1c
,08-30 16:00:55.259  3280  3358 D BtGatt.GattService: onClientRegistered() - UUID=c55e20f5-23e8-4c7d-a540-8107b5803e1c, clientIf=6
,08-30 16:00:55.259  7084  7097 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 16:00:55.259  3280  3443 D BtGatt.GattService: start scan with filters
,08-30 16:00:55.269  3280  3420 D BtGatt.ScanManager: handling starting scan
,08-30 16:00:55.269  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 16:00:55.269  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 16:00:55.269  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 16:00:55.269  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 16:00:55.269  3280  3358 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-30 16:00:55.269  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 16:00:55.269  3280  3420 D BtGatt.ScanManager: allow scan with filters,
08-30 16:00:55.269  3280  3420 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-30 16:00:55.269  3280  3420 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
08-30 16:00:55.269  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 16:00:55.269  3280  3358 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-30 16:00:55.269  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 16:00:55.269  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 16:00:55.269  7084  7084 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 16:00:55.269  3280  3420 D BtGatt.ScanManager: Starting BLE batch scan
08-30 16:00:55.269  3280  3420 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 16:00:55.279  3280  3358 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-30 16:00:55.279  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 16:00:55.279  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 16:00:55.279  3280  3358 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-30 16:00:55.279  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 16:00:55.289  7084  7295 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:00:55.289  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:00:55.289  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 16:00:55.289  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:00:55.289  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:00:55.289  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 16:00:55.299  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:00:55.299  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220dd95f removed from the list
08-30 16:00:55.299  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:55.299  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@369aafac removed from the list
08-30 16:00:55.299  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:55.299  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:00:55.299  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:55.299  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 16:00:55.299  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:55.299  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:00:55.299  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:55.299  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:55.299  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:55.299  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@369aafac not in the list
08-30 16:00:55.299  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 16:00:55.299  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 16:00:55.299  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 16:00:55.299  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 16:00:55.299  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 16:00:55.299  3280  3293 D BtGatt.GattService: stopScan() - queue size =1
,08-30 16:00:55.299  3280  3420 D BtGatt.ScanManager: filter size is 1
,08-30 16:00:55.299  3280  3420 D BtGatt.ScanManager: delete FilterIndex - 8
,08-30 16:00:55.299  3280  3358 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-30 16:00:55.299  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 16:00:55.299  3280  3420 D BtGatt.ScanManager: stopping BLe Batch
,08-30 16:00:55.299  3280  3417 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 16:00:55.309  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-30 16:00:55.309  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 16:00:55.309  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 16:00:55.309  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 16:00:55.309  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 16:00:55.309  3280  3358 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-30 16:00:55.309  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 16:00:55.309  3280  3420 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
,08-30 16:00:55.309  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:00:55.309  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 16:00:55.309  7084  7295 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 16:00:55.309  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 16:00:55.309  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:55.309  3280  3358 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-30 16:00:55.309  3280  3358 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 16:00:55.319  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:55.319  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:55.319  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:55.319  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2260ac7b removed from the list
08-30 16:00:55.319  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:55.319  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:55.319  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:55.319  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:00:55.319  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d39c0a removed from the list
,08-30 16:00:55.319  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:00:55.319  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39439557 added. We now have 2 listener(s)
,08-30 16:00:55.319  7084  7084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:00:55.319  7084  7084 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:00:55.319  7084  7084 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:00:55.319  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-30 16:00:55.319  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 16:00:55.319  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 16:00:55.319  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:00:55.319  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11914844 added. We now have 9 listener(s)
,08-30 16:00:55.319  7084  7295 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:00:55.329  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 16:00:55.329  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:00:55.329  7084  7295 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:00:55.329  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:55.329  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:55.329  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:55.329  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:55.329  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:55.329  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:55.329  7084  7295 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:00:55.339  1020  1129 E WifiNative-wlan0: do suspend true
,08-30 16:00:55.339  7084  7295 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:00:55.339  7084  7295 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 16:00:55.339  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 16:00:55.339  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f3a262 added. We now have 3 listener(s)
,08-30 16:00:55.339  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:55.339  7084  7084 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:55.349  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-30 16:00:55.349  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 16:00:55.349  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 16:00:55.349  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:00:55.349  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d022ff3 added. We now have 10 listener(s)
,08-30 16:00:55.349  7084  7295 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:00:55.349  7084  7295 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:00:55.349  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:00:55.349  7084  7295 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 16:00:55.349  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:55.349  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:00:55.349  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:00:55.349  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 16:00:55.349  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39439557 removed from the list
08-30 16:00:55.349  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:00:55.349  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11914844 removed from the list
08-30 16:00:55.349  7084  7295 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 16:00:55.349  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:55.359  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:55.359  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:55.359  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:00:55.359  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:55.359  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:55.359  7084  7295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11914844 not in the list
08-30 16:00:55.359  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:55.359  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:55.359  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 16:00:55.359  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:55.359  7084  7295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:00:55.359  7084  7295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d022ff3 removed from the list
,08-30 16:00:55.359  7084  7295 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:00:55.359  7084  7295 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:55.359  7084  7295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:55.359  7084  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:00:55.359  7084  7295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30f3a262 removed from the list
,08-30 16:00:55.359  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything,
08-30 16:00:55.359  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 16:00:55.359  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-30 16:00:55.359  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:00:55.359  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-30 16:00:55.359  7084  7295 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:00:55.369  1020  1128 D WifiP2pService: InactiveState{ what=143375 },
08-30 16:00:55.369  1020  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
08-30 16:00:55.369  1020  1129 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 16:00:55.369  1020  1129 E WifiStateMachine: VerifyingLinkState enter
,08-30 16:00:55.369  7084  7964 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1449, name: My test thread name)
,08-30 16:00:55.369  7084  7964 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1449, thread name: My test thread name)
,08-30 16:00:55.369  7084  7964 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1449, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-30 16:00:55.369  1020  1131 E ConnectivityService: updateNetworkInfo()
,08-30 16:00:55.379  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-30 16:00:55.379  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 16:00:55.379  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 16:00:55.379  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:55.379  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:55.379  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:55.379  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:55.379  1020  1131 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-30 16:00:55.379  1020  1131 D ConnectivityService: Adding iface wlan0 to network 504
,08-30 16:00:55.379  7084  7965 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1451, name: My test thread name)
,08-30 16:00:55.379  7084  7965 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1451, thread name: My test thread name)
08-30 16:00:55.379  7084  7965 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1451, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-30 16:00:55.379  1020  1148 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
08-30 16:00:55.379  1020  1148 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-30 16:00:55.379  1020  1148 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-30 16:00:55.379  1020  1148 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-30 16:00:55.379  1020  1148 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-30 16:00:55.389  7084  7295 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-30 16:00:55.389  7084  7295 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-30 16:00:55.389  7084  7295 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-30 16:00:55.389  7084  7295 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-30 16:00:55.389  7084  7295 D com.test.thalitest.ThaliTestRunner: Total duration: 23311 ms
,08-30 16:00:55.389  7084  7295 I jxcore-log: *Native tests were executed*,
08-30 16:00:55.389  7084  7295 I jxcore-log: 
08-30 16:00:55.389  7084  7295 I jxcore-log: Total number of executed tests:  80
08-30 16:00:55.389  7084  7295 I jxcore-log: 
08-30 16:00:55.389  7084  7295 I jxcore-log: Number of passed tests:  80
08-30 16:00:55.389  7084  7295 I jxcore-log: 
08-30 16:00:55.389  7084  7295 I jxcore-log: Number of failed tests:  0
08-30 16:00:55.389  7084  7295 I jxcore-log: 
08-30 16:00:55.389  7084  7295 I jxcore-log: Number of ignored tests:  0
08-30 16:00:55.389  7084  7295 I jxcore-log: 
,08-30 16:00:55.389  7084  7295 I jxcore-log: Total duration:  23311,
,08-30 16:00:55.389  7084  7295 I jxcore-log: 
08-30 16:00:55.389  7084  7295 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 16:00:55.389  7084  7295 I jxcore-log: 
,08-30 16:00:55.389  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:00:55.389  7084  7295 I jxcore-log: 
08-30 16:00:55.389  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:00:55.389  7084  7295 I jxcore-log: 
08-30 16:00:55.399  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:00:55.399  7084  7295 I jxcore-log: 
08-30 16:00:55.399  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:00:55.399  7084  7295 I jxcore-log: 
08-30 16:00:55.399  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:00:55.399  7084  7295 I jxcore-log: 
08-30 16:00:55.399  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:00:55.399  7084  7295 I jxcore-log: 
08-30 16:00:55.399  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:00:55.399  7084  7295 I jxcore-log: 
08-30 16:00:55.409  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:00:55.409  7084  7295 I jxcore-log: 
08-30 16:00:55.409  1020  3784 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 16:00:55.409  1020  3784 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 16:00:55.409  1020  3784 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:55.409  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:00:55.409  7084  7295 I jxcore-log: 
08-30 16:00:55.409  1020  3784 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 16:00:55.409  1020  3784 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 16:00:55.409  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 16:00:55.409  7084  7295 I jxcore-log: 
08-30 16:00:55.409  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 16:00:55.409  7084  7295 I jxcore-log: 
08-30 16:00:55.409  1020  1129 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-30 16:00:55.409  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 16:00:55.409  7084  7295 I jxcore-log: 
08-30 16:00:55.409  1020  1131 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
08-30 16:00:55.409  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:00:55.409  7084  7295 I jxcore-log: 
08-30 16:00:55.409  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:00:55.409  7084  7295 I jxcore-log: 
08-30 16:00:55.409  1632  1632 I Hs20UtilService: Starting #22
08-30 16:00:55.409  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-30 16:00:55.409  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 16:00:55.409  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 16:00:55.409  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 16:00:55.409  7084  7295 I jxcore-log: 
08-30 16:00:55.409  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:55.409  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:55.409  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:55.409  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:55.409  1632  1654 I Hs20UtilService: Message received 5007
08-30 16:00:55.409  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 16:00:55.409  7084  7295 I jxcore-log: 
,08-30 16:00:55.419  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:00:55.419  7084  7295 I jxcore-log: 
08-30 16:00:55.419  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:00:55.419  7084  7295 I jxcore-log: 
08-30 16:00:55.419  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 16:00:55.419  7084  7295 I jxcore-log: 
08-30 16:00:55.419  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 16:00:55.419  7084  7295 I jxcore-log: 
08-30 16:00:55.419  1020  1131 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-30 16:00:55.419  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 16:00:55.419  7084  7295 I jxcore-log: 
08-30 16:00:55.419  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 16:00:55.419  7084  7295 I jxcore-log: 
08-30 16:00:55.419  4748  4748 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 16:00:55.419  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 16:00:55.419  7084  7295 I jxcore-log: 
08-30 16:00:55.419  1020  1131 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
08-30 16:00:55.419  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 16:00:55.419  7084  7295 I jxcore-log: 
08-30 16:00:55.419  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 16:00:55.419  7084  7295 I jxcore-log: 
08-30 16:00:55.419  1020  1131 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 16:00:55.419  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 16:00:55.419  7084  7295 I jxcore-log: 
08-30 16:00:55.419  1020  1131 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-30 16:00:55.419  1020  1131 D ConnectivityService: LTETest block dns file not exists
08-30 16:00:55.419  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 16:00:55.419  7084  7295 I jxcore-log: 
08-30 16:00:55.419  7084  7084 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 16:00:55.429  1020  1131 V NetworkStats: updateIfacesLocked()
08-30 16:00:55.429  1020  1131 V NetworkStats: performPollLocked(flags=0x1)
,08-30 16:00:55.429  1020  1131 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:55.429  1020  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 16:00:55.429  1020  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 16:00:55.439  4748  4748 I NearbySettings: MountReceiver.onReceive - Keep current state
08-30 16:00:55.439  1020  1131 V NetworkStats: performPollLocked() took 5ms
08-30 16:00:55.439  1020  1131 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:55.439  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-30 16:00:55.449  1020  1131 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-30 16:00:55.449  1020  1131 E ConnectivityService: updateNetworkInfo()
08-30 16:00:55.449  1020  1131 E ConnectivityService: updateNetworkInfo()
08-30 16:00:55.449  1020  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-30 16:00:55.449  1020  1131 V NetworkStats: updateIfacesLocked()
08-30 16:00:55.449  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-30 16:00:55.449  1020  1020 I WifiTrafficPoller: mBoosterFLAG : 0
08-30 16:00:55.449  1020  1020 I WifiTrafficPoller: current booster mode : FullMode
08-30 16:00:55.449  1020  1131 V NetworkStats: performPollLocked(flags=0x1)
08-30 16:00:55.449  1020  1131 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:55.449  1020  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 16:00:55.449  1020  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 16:00:55.449  1020  1129 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 16:00:55.449  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-30 16:00:55.449  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 16:00:55.449  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 16:00:55.449  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:55.449  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:55.449  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:55.449  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:55.449  1020  1129 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 16:00:55.459  1020  1131 V NetworkStats: performPollLocked() took 4ms
08-30 16:00:55.459  1020  1131 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:55.459  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:55.459  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:55.459  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 16:00:55.459  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-30 16:00:55.459  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:55.459  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:55.459  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:55.459  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:55.459  1020  7931 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:00:55.459  1020  1131 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-30 16:00:55.459  1020  7931 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-30 16:00:55.459  1020  1131 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-30 16:00:55.459  1020  7931 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 16:00:55.459  1020  7931 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-30 16:00:55.469  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:55.469  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:55.469  1020  7931 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 16:00:55.469  1020  1131 D ConnectivityService:    accepting network in place of null
08-30 16:00:55.469  1020  1129 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,08-30 16:00:55.469   278   959 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 16:00:55.469   278   959 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-30 16:00:55.469  1472  1472 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-30 16:00:55.469  1472  1472 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 16:00:55.469  1020  1131 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 16:00:55.469  1020  1131 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-30 16:00:55.469  1020  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-30 16:00:55.479  1020  1128 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-30 16:00:55.479  1020  1131 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-30 16:00:55.479  1020  1020 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-30 16:00:55.479  1020  1134 D Tethering: MasterInitialState.processMessage what=3
08-30 16:00:55.479  1020  1131 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-30 16:00:55.479  1020  3781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 16:00:55.479  1020  3781 D BatteryService: level:99, scale:100, status:2, health:2, present:true, voltage: 4258, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-30 16:00:55.479  1020  3781 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-30 16:00:55.479  1020  3781 D BatteryService: stay LED for charging
,08-30 16:00:55.489  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:55.489  1020  1126 V NetworkStats: updateIfacesLocked()
08-30 16:00:55.489  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 16:00:55.489  1020  1126 V NetworkStats: performPollLocked(flags=0x1)
08-30 16:00:55.489  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 16:00:55.489  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-30 16:00:55.489  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:55.489  1020  1126 V NetworkStats: performPollLocked() took 3ms
,08-30 16:00:55.499  1020  1049 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-30 16:00:55.499  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:55.499  1020  1127 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-30 16:00:55.499  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:55.499  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:55.499  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:55.499  1181  1181 D StatusBar.NetworkController: EthernetConnected: false
08-30 16:00:55.499  1181  1181 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-30 16:00:55.499  1181  1181 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-30 16:00:55.499  1181  1181 D StatusBar.NetworkController: updateDataNetType()
,08-30 16:00:55.499  1181  1769 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-30 16:00:55.499  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-30 16:00:55.499  1181  1181 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-30 16:00:55.509  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:55.509  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 16:00:55.509  1181  1181 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-30 16:00:55.509  1181  1181 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 19 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-30 16:00:55.509  1181  1181 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-30 16:00:55.509  1181  1181 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-30 16:00:55.509  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 16:00:55.509  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-30 16:00:55.509  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:55.509  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:55.509  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:55.509  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:55.509  1020  1020 I MotionRecognitionService: Plugged
08-30 16:00:55.509  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 16:00:55.509  1181  1181 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-30 16:00:55.509  1426  1426 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-30 16:00:55.509  1181  1181 D KeyguardUpdateMonitor: handleBatteryUpdate
08-30 16:00:55.509  1426  1426 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 99
,08-30 16:00:55.509  1181  1181 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-30 16:00:55.509  1181  1181 D SViewCoverView: level :99 plugged : 2
,08-30 16:00:55.519  1020  1492 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 16:00:55.519  1020  1492 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 16:00:55.519  3280  3280 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-30 16:00:55.519  3280  7895 D HeadsetStateMachine: Disconnected process message: 10
,08-30 16:00:55.519  1020  1492 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:55.519  1020  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:55.519  1020  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 16:00:55.519  1632  1632 I Hs20UtilService: Starting #23
08-30 16:00:55.529  1632  1654 I Hs20UtilService: Message received 5007
,08-30 16:00:55.529  4748  4748 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 16:00:55.529  4748  4748 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 16:00:55.529  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,08-30 16:00:55.529  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 16:00:55.529  4748  4748 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-30 16:00:55.529  4748  4748 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-30 16:00:55.529  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
08-30 16:00:55.529  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
08-30 16:00:55.529  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:99 status:2 health:2
,08-30 16:00:55.549  1020  1033 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 16:00:55.549  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 16:00:55.549  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
08-30 16:00:55.549  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 16:00:55.549  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 16:00:55.549  1632  1632 I Hs20UtilService: Starting #24
08-30 16:00:55.549  1632  1654 I Hs20UtilService: Message received 5007
,08-30 16:00:55.549  7084  7084 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-30 16:00:55.549  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 16:00:55.549  7084  7295 I jxcore-log: 
,08-30 16:00:55.549  4748  4748 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 16:00:55.549  4748  4748 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-30 16:00:55.559  1020  1507 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-30 16:00:55.569  1020  1494 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-30 16:00:55.569  1020  1494 D SecContentProvider2: mCursor = null
,08-30 16:00:55.569  1020  7931 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false,
,08-30 16:00:55.579  1020  3781 D SecContentProvider2: uri = 15 selection = getToastGravity
08-30 16:00:55.579  1020  3781 D SecContentProvider2: mCursor = null
,08-30 16:00:55.579  1020  1139 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-30 16:00:55.579  1020  1139 D SecContentProvider2: mCursor = null
,08-30 16:00:55.579  1020  1033 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-30 16:00:55.579  1020  1033 D SecContentProvider2: mCursor = null
,08-30 16:00:55.589  1020  4405 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-30 16:00:55.589  1020  4405 D SecContentProvider2: mCursor = null
08-30 16:00:55.589  1020  1465 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-30 16:00:55.589  1020  1465 D SecContentProvider2: mCursor = null
,08-30 16:00:55.609   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-30 16:00:55.629  1020  7931 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 14:00:55 GMT], X-Android-Received-Millis=[1472565655635], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472565655606]}
,08-30 16:00:55.629  1020  7931 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,08-30 16:00:55.629  1020  7931 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-30 16:00:55.629  1020  1131 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-30 16:00:55.629  1020  1131 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,08-30 16:00:55.629  1020  1131 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-30 16:00:55.629  1020  1131 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-30 16:00:55.629  1020  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 16:00:55.629  1181  1769 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-30 16:00:55.629  1020  1494 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1020
,08-30 16:00:55.639  1181  1181 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-30 16:00:55.639  1181  1181 D StatusBar.NetworkController: EthernetConnected: false
,08-30 16:00:55.639  1181  1181 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,08-30 16:00:55.639  1181  1181 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
,08-30 16:00:55.649  1181  1181 D StatusBar.NetworkController: updateDataNetType()
,08-30 16:00:55.649  1181  1181 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-30 16:00:55.649  1181  1181 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-30 16:00:55.649  1181  1181 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-30 16:00:55.649  1181  1181 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 19 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-30 16:00:55.649  1181  1181 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-30 16:00:55.649  1181  1181 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-30 16:00:55.649  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 16:00:55.649  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-30 16:00:55.649  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:55.649  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:55.649  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 16:00:55.649  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 16:00:55.669  7969  7969 D AndroidRuntime: 
08-30 16:00:55.669  7969  7969 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-30 16:00:55.669  7969  7969 D AndroidRuntime: CheckJNI is OFF
,08-30 16:00:55.669  7969  7969 D AndroidRuntime: readGMSProperty: start
08-30 16:00:55.669  7969  7969 D AndroidRuntime: readGMSProperty: already setted!!,
08-30 16:00:55.669  7969  7969 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 16:00:55.669  7969  7969 D AndroidRuntime: readGMSProperty: could not set the property(default)!!,
08-30 16:00:55.669  7969  7969 D AndroidRuntime: readGMSProperty: end
08-30 16:00:55.669  7969  7969 D AndroidRuntime: addProductProperty: start
,08-30 16:00:55.689  7084  7084 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-30 16:00:55.689  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 16:00:55.689  7084  7295 I jxcore-log: ,
,08-30 16:00:55.719  1020  1052 I PowerManagerService: [PWL] Off : 75s ago,
08-30 16:00:55.719  1020  1052 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,08-30 16:00:55.719  1020  1052 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-30 16:00:55.719  1020  1052 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1020, ws=null) (elapsedTime=22785)
08-30 16:00:55.719  1020  1052 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=3280, ws=null) (elapsedTime=699),
,08-30 16:00:55.789  7969  7969 E AffinityControl: AffinityControl: registerfunction enter,
,08-30 16:00:55.819  7084  7084 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-30 16:00:55.819  7084  7295 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 16:00:55.819  7084  7295 I jxcore-log: 
,08-30 16:00:55.829  7969  7969 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-30 16:00:55.849  1020  1493 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-30 16:00:55.849  1020  1493 D PackageManager: START PACKAGE DELETE: observer{982880213}
08-30 16:00:55.849  1020  1493 D PackageManager: pkg{<packageName>}
,08-30 16:00:55.849  1020  1493 D PackageManager: user{0}
08-30 16:00:55.849  1020  1493 D PackageManager: caller{2000}
08-30 16:00:55.849  1020  1493 D PackageManager: flags{2}
08-30 16:00:55.849  1020  1493 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true,
08-30 16:00:55.849  1020  1493 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-30 16:00:55.849  1020  1493 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-30 16:00:55.849  1020  1493 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-30 16:00:55.859  1020  1060 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
08-30 16:00:55.859  1020  1060 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-30 16:00:55.859  1020  1060 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1,
08-30 16:00:55.859  1020  1060 D ApplicationPolicy: getApplicationUninstallationEnabled
08-30 16:00:55.859  1020  1060 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true,
,08-30 16:00:55.859  1020  1060 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,08-30 16:00:55.869  1020  1045 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,08-30 16:00:55.869  1020  1045 I ActivityManager: Killing 7084:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-30 16:00:55.959  1020  3784 I WindowState: WIN DEATH: Window{19d1b1d1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 16:00:55.959   258   446 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-30 16:00:55.959   258   446 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-30 16:00:55.979  1020  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:00:55.979  1020  3784 D InputDispatcher: Focus left window: 7084
,08-30 16:00:55.979  1020  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-30 16:00:55.979  1020  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 16:00:56.009  1020  1045 I ActivityManager:   Force finishing activity ActivityRecord{37083f02 u0 com.test.thalitest/.MainActivity t163}
,08-30 16:00:56.029  1020  1045 D InputDispatcher: Focused application released
,08-30 16:00:56.029  1020  1438 W ActivityManager: Spurious death for ProcessRecord{173f53ea 7084:com.test.thalitest/u0a170}, curProc for 7084: null
,08-30 16:00:56.049  1020  1045 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-30 16:00:56.049  1020  1044 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:00:56.049  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:56.049  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:56.049  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:56.049  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:56.069  7984  7984 E Zygote  : MountEmulatedStorage()
,08-30 16:00:56.069  7984  7984 I libpersona: KNOX_SDCARD checking this for 1000
08-30 16:00:56.069  7984  7984 E Zygote  : v2
08-30 16:00:56.069  7984  7984 I libpersona: KNOX_SDCARD not a persona
08-30 16:00:56.069  7984  7984 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 16:00:56.069  1020  1045 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7984 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-30 16:00:56.069  1020  1060 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-30 16:00:56.079  7984  7984 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 16:00:56.079  7984  7984 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 16:00:56.089  1020  1060 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-30 16:00:56.119  2824  2824 I art     : Explicit concurrent mark sweep GC freed 16596(991KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 791us total 34.580ms
,08-30 16:00:56.149  7984  7984 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 16:00:56.159  1750  2030 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 16:00:56.159  7984  7984 D ActivityThread: Added TimaKeyStore provider
,08-30 16:00:56.159  1915  1915 E SamsungIME: mOCRHelper is null
,08-30 16:00:56.169  1020  1101 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 16:00:56.169   288   288 E SMD     : DCD OFF
,08-30 16:00:56.189  1455  1455 D PersonaManager: isKioskContainerExistOnDevice
,08-30 16:00:56.189  1020  1020 D RCPManagerService: PackageReceiver onReceive()
,08-30 16:00:56.189  1020  1020 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-30 16:00:56.199  1455  1455 D RegisteredServicesCache: empty dynamic service
,08-30 16:00:56.199  1020  1020 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,08-30 16:00:56.199  1020  1020 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,08-30 16:00:56.199  1020  1020 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-30 16:00:56.219  1455  1455 D RegisteredComponentCache: Collect Tech packages for Knox
,08-30 16:00:56.219  1455  1455 D PersonaManager: isKioskContainerExistOnDevice
,08-30 16:00:56.229  1020  1126 V NetworkStats: removeUidsLocked() for UIDs [10170]
,08-30 16:00:56.229  1020  1126 V NetworkStats: performPollLocked(flags=0x3)
08-30 16:00:56.229  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:56.229  1020  1044 D EnterpriseDeviceManagerService: Package has changed for user 0
08-30 16:00:56.229  1020  1044 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-30 16:00:56.229  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 16:00:56.229  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 16:00:56.229  1020  1020 I OTPFW   : ProvisionData::getAllEntries Enter
,08-30 16:00:56.239  1020  1020 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-30 16:00:56.239  1020  1044 W TextServicesManagerService: no available spell checker services found
,08-30 16:00:56.239  1020  1126 V NetworkStats: performPollLocked() took 11ms
,08-30 16:00:56.239  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:56.249  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:56.249  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 16:00:56.259  7984  7984 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-30 16:00:56.259  7984  7984 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-30 16:00:56.259  7984  7984 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-30 16:00:56.279  7984  7984 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-30 16:00:56.279  7984  7984 I PCWCLIENTTRACE_PushUtil: sales region : global
08-30 16:00:56.279  7984  7984 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,08-30 16:00:56.279  7984  7984 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:00:56.289  1020  1220 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
08-30 16:00:56.289  1020  1220 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-30 16:00:56.289  1020  1220 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-30 16:00:56.289  1020  1220 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-30 16:00:56.289  1020  1220 I ActivityManager: Killing 7473:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-30 16:00:56.289  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 16:00:56.309  1020  1359 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-30 16:00:56.309  1020  1359 D SecContentProvider2: mCursor = null
,08-30 16:00:56.309  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 16:00:56.329  1020  1060 I art     : Explicit concurrent mark sweep GC freed 67395(4MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 3.440ms total 233.969ms
,08-30 16:00:56.329  1020  1030 I art     : WaitForGcToComplete blocked for 186.683ms for cause HeapTrim
,08-30 16:00:56.359  1020  1060 D PackageManager: delete codoeFile: 
,08-30 16:00:56.379  1020  1060 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
08-30 16:00:56.379  1020  1060 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,08-30 16:00:56.379  1020  1060 D PackageManager: result of delete: 1{982880213}
,08-30 16:00:56.379  7969  7969 D AndroidRuntime: Shutting down VM
,08-30 16:00:56.379  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 16:00:56.379  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 16:00:56.469  1020  1044 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-30 16:00:56.479  1020  1131 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
08-30 16:00:56.479  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 16:00:56.479  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 16:00:56.489  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 16:00:56.499  1020  1044 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 16:00:56.499  1020  1044 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 16:00:56.499  1020  1044 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 16:00:56.499  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 16:00:56.509  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 16:00:56.509  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 16:00:56.509  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 16:00:56.509  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-30 16:00:56.519  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 16:00:56.519  1020  1020 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-30 16:00:56.519  1020  1020 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 16:00:56.519  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 16:00:56.519  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-30 16:00:56.519  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-30 16:00:56.519  1020  1020 V EnterpriseBillingPolicy: uID is 10170
,08-30 16:00:56.519  1020  1020 V EnterpriseBillingPolicy: Removed Packageuid is0
08-30 16:00:56.519  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-30 16:00:56.519  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,08-30 16:00:56.519  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-30 16:00:56.519  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-30 16:00:56.519  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-30 16:00:56.529  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-30 16:00:56.529  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 16:00:56.529  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-30 16:00:56.529  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 16:00:56.529  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-30 16:00:56.529  1020  1165 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,08-30 16:00:56.529  1020  3422 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-30 16:00:56.529  1020  1044 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-30 16:00:56.529  1020  1044 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-30 16:00:56.529  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,08-30 16:00:56.539  1020  1020 V EnterpriseBillingPolicy: uID is 10170
08-30 16:00:56.539  1020  1020 V EnterpriseBillingPolicy: Removed Packageuid is0
08-30 16:00:56.539  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-30 16:00:56.539  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-30 16:00:56.539  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-30 16:00:56.539  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-30 16:00:56.539  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-30 16:00:56.539  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-30 16:00:56.539  1020  1020 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,08-30 16:00:56.589  7969  7969 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-30 16:00:56.589  1020  1060 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-30 16:00:56.589  1020  1060 D PackageManager: userId{-1}
08-30 16:00:56.589  1020  1060 D PackageManager: andCode{true}
,08-30 16:00:56.599  1020  1060 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0,
08-30 16:00:56.599  1020  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:56.599  1020  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:56.599  1020  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:56.599  1020  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:56.609  8001  8001 E Zygote  : MountEmulatedStorage(),
08-30 16:00:56.609  8001  8001 E Zygote  : v2
08-30 16:00:56.609  8001  8001 I libpersona: KNOX_SDCARD checking this for 10003
08-30 16:00:56.609  8001  8001 I libpersona: KNOX_SDCARD not a persona
,08-30 16:00:56.609  8001  8001 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-30 16:00:56.609  1020  1060 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8001 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a,
,08-30 16:00:56.609  8001  8001 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 16:00:56.619  8001  8001 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 16:00:56.629  1020  1020 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-30 16:00:56.629  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-30 16:00:56.629  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:56.629  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-30 16:00:56.629  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:56.649  1020  1020 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=8017 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-30 16:00:56.649  8017  8017 E Zygote  : MountEmulatedStorage()
08-30 16:00:56.649  8017  8017 E Zygote  : v2
,08-30 16:00:56.649  8017  8017 I libpersona: KNOX_SDCARD checking this for 10001
08-30 16:00:56.649  8017  8017 I libpersona: KNOX_SDCARD not a persona
,08-30 16:00:56.649  8017  8017 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 16:00:56.649  8017  8017 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 16:00:56.649  8017  8017 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 16:00:56.659  8001  8001 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 16:00:56.659  8001  8001 D ActivityThread: Added TimaKeyStore provider
,08-30 16:00:56.679  8017  8017 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 16:00:56.679  8017  8017 D ActivityThread: Added TimaKeyStore provider
,08-30 16:00:56.709  1020  1032 I ActivityManager: Killing 7491:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,08-30 16:00:56.729  1020  1507 I ActivityManager: Killing 7506:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-30 16:00:56.729  1020  1507 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-30 16:00:56.729  1020  1507 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.sec.android.diagmonagent/com.sec.android.diagmonagent.DiagMonRegistrationReceiver}
08-30 16:00:56.729  1020  1507 W BroadcastQueue: android.os.TransactionTooLargeException
08-30 16:00:56.729  1020  1507 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 16:00:56.729  1020  1507 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 16:00:56.729  1020  1507 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-30 16:00:56.729  1020  1507 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-30 16:00:56.729  1020  1507 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-30 16:00:56.729  1020  1507 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-30 16:00:56.729  1020  1507 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-30 16:00:56.729  1020  1507 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-30 16:00:56.729  1020  1507 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
08-30 16:00:56.729  1020  1507 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-30 16:00:56.729  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:56.729  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:56.729  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 16:00:56.729  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 16:00:56.749  8035  8035 E Zygote  : MountEmulatedStorage(),
08-30 16:00:56.749  8035  8035 E Zygote  : v2
08-30 16:00:56.749  8035  8035 I libpersona: KNOX_SDCARD checking this for 1000,
08-30 16:00:56.749  8035  8035 I libpersona: KNOX_SDCARD not a persona
,08-30 16:00:56.749  8035  8035 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-30 16:00:56.749  8035  8035 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 16:00:56.759  1020  1507 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=8035 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-30 16:00:56.759  8035  8035 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-30 16:00:56.769   304   304 I art     : Explicit concurrent mark sweep GC freed 8715(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 608us total 21.930ms

```
